# Awesome Automated Revenue Recognition (ASC 606 & IFRS 15)

A curated list of automated revenue recognition platforms, tools, and compliance software engineered for ASC 606 and IFRS 15 accounting standards.

---

## Sector Overview & Market Dynamics

The global revenue recognition and automated revenue management software market is estimated at approximately **$4.8 billion**, projected to exceed **$11.6 billion** over the next decade at a CAGR of ~10.2%. The market structure is a **hybrid with moderate concentration at the top**: large multinational enterprise general ledgers and ERP suites (e.g., Oracle, SAP) dominate high-volume core financial infrastructure, while the mid-market and high-velocity SaaS/usage-based billing segment is **moderately fragmented** across specialized cloud point solutions and automated revenue subledgers (e.g., Zuora, Maxio, Chargebee).

---

## SaaS Revenue Recognition Platforms

| Platform | Company Scale (Valuation / Revenue) | Pricing | Free Tier / Trial Limits | Details & Compliance Scope |
|---|---|---|---|---|
| **Oracle Revenue Management (RMCS)** | **~$355B Market Cap** (~$71.8B Annual Revenue) | **From $300/user/month** (Enterprise quote based on Hosted Named User licenses) | **30-day trial with $300 cloud credits** via Oracle Cloud Infrastructure (OCI) Free Tier; no standalone production self-serve trial for RMCS | Enterprise-grade subledger module for Fusion Cloud ERP; manages automated multi-element arrangements, performance obligations, and ASC 606/IFRS 15 schedules. |
| **SAP Revenue Accounting and Reporting (RAR)** | **~$260B Market Cap** (~$44.6B Annual Revenue) | **From $50/user/month** (Cloud solutions base; S/4HANA RAR deployments typically run from $100K+/year up to multi-million dollar custom licensing) | **30-day free trial** available for SAP S/4HANA Cloud Public Edition (guided scenarios with pre-configured sample financial data; no standalone self-serve trial) | Embedded S/4HANA revenue engine automating the 5-step ASC 606/IFRS 15 framework, standalone selling price (SSP) allocation, and ERP GL postings. |
| **Chargebee RevRec** | **$3.5B Valuation** (~$202M Annual Revenue) | **From $5,000/year** (Starting tier for RevRec module on Performance plan; custom quote for Enterprise) | **Free Starter tier up to $250,000 lifetime billing** on core Chargebee Billing; RevRec add-on requires demo / sales-assisted onboarding | Standalone Selling Price (SSP) library, contract modification handling, and automated deferred revenue schedules integrated with billing and ERPs. |
| **BlackLine (RevRec & Financial Close)** | **~$1.95B Market Cap** (~$740M Annual Revenue) | **From $1,000/month** ($12,000–$25,000+/year benchmark baseline for mid-market packages; quote-only) | **No free trial or free tier** (Evaluation via tailored proof-of-concept environment and guided sales engineering walkthrough) | Enterprise financial close automation and balance-sheet reconciliation suite with contract-level revenue subledger capabilities. |
| **Zuora Revenue (formerly RevPro)** | **~$1.6B Acquisition Valuation** (~$450M Annual Revenue) | **From $100,000/year** (Enterprise quote-only; typical contract range $100K–$300K+/year) | **No free trial or free tier** (Evaluation via guided product demonstration and architectural consultation) | Enterprise automated revenue recognition engine purpose-built for complex subscription and usage-based contracts under ASC 606 & IFRS 15. |
| **FloQast** | **$1.6B Valuation** (~$200M ARR) | **From $999/month** (~$12,000/year entry baseline; median contracts ~$24,500/year) | **No free trial or free tier** (Requires scheduled live solution demo and sandbox walkthrough) | Accounting automation and close management platform with automated reconciliation (AutoRec) and ASC 606 compliance workflows. |
| **Maxio** | **~$50M+ ARR** (Battery Ventures-backed) | **From $599/month** (Grow plan; up to $100,000/month in billing volume; Scale plan quote-only) | **Build tier: Free sandbox for API/dev testing** (30-day trial sandbox with dummy payment gateway; live billing/RevRec disabled) | Complete B2B subscription billing and automated revenue recognition engine with ratable amortization and SaaS metrics (unlimited seats). |
| **Subscript** | **~$50M–$100M Valuation** (~$27M Venture Funded) | **From $500/month** ($6,000–$15,000/year entry; typical deployments ~$24,000/year) | **No free trial or free tier** (Assisted onboarding and guided demo only due to direct general ledger sync) | Real-time B2B SaaS billing analytics, revenue recognition schedules conforming to ASC 606/IFRS 15, and automated deferred revenue tracking. |
| **Leapfin** | **~$50M Valuation** (Acquired by Airwallex) | **From $1,000/month** ($12,000/year minimum annual commitment; Premium from $1,000+/mo) | **No free trial or free tier** (Provides a personalized sample transaction "test drive" demo with customer data) | Financial data engine that converts high-volume transactions into ASC 606-compliant GAAP journal entries and revenue waterfall reports. |
| **RightRev** | **~$5M–$7M ARR** (~$31M Venture Funded) | **From $1,516/month** (~$18,194–$24,000/year observed baseline via Vendr; quote-based) | **No free trial or free tier** (Evaluation via sales demo and custom proof-of-concept environment) | AI-powered automated revenue recognition and management engine designed for complex hybrid, evergreen, and consumption models. |

---

## Open-Source Software

| Project | License | Implementation & Architecture | Scope & Limitations |
|---|---|---|---|
| **[eRev](https://github.com/ishandutta2007)** | Open Source (Free-Tier Program) | Pure Python packaged application; local SQLite database; runs locally on Windows; EFS encryption; PowerBI/Tableau data connector | Handles ASC 606 / IFRS 15 five-step revenue allocation math, contract modifications, and variable consideration. Designed as a standalone desktop utility; does not include billing gateways, invoicing, or native ERP cloud syncing. |

---

## Pricing Models & Buyer Context

When evaluating automated revenue recognition platforms, consider the distinct pricing structures across the market:
* **Flat Monthly / Volume Capped:** (e.g., Maxio) Predictable baseline fees up to a predefined billing volume threshold.
* **Per-User / Named User Licensing:** (e.g., Oracle RMCS, SAP) Common in enterprise ERP suites where licenses depend on finance and accounting seat access.
* **Annual Base + Add-on Modules:** (e.g., Chargebee, Leapfin, FloQast, RightRev) Annual commitments with separate modules for core billing, reconciliations, or advanced RevRec.
* **Enterprise Custom Quotes:** (e.g., Zuora Revenue, SAP RAR, Oracle RMCS) Calibrated to total annual contract value (ACV), multi-entity legal structures, and ERP integrations.
