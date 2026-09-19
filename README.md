# E-Commerce MVP Launch: "Green Home" (Project Management Case Study)

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Methodology](https://img.shields.io/badge/Methodology-Hybrid%20(CCPM%20%2B%20Kanban)-blue)
![Tools](https://img.shields.io/badge/Tools-ProjectLibre%20%7C%20Excel%20%7C%201C-orange)
![Role](https://img.shields.io/badge/Role-Project%20Manager-purple)

---

## 📌 Executive Summary

**"Green Home"** (*Зелёный дом*) is a retail brand specializing in eco-friendly cookware, cosmetics, and household products. Facing declining offline retail footfall (-15% YoY) and aggressive digital expansion by competitors, the company initiated a strategic digital transformation project: designing, developing, and launching an e-commerce platform MVP integrated with the legacy **1C ERP** system.

As **Project Manager**, I led the project through the full lifecycle — from initial charter formulation and financial feasibility modeling to critical chain scheduling, procurement, risk governance, acceptance testing, and post-project audit.

### Key Project Highlights & Results
* **Duration:** 4 months target baseline (executed in 95 working days vs. 70 days planned baseline).
* **Budget & Capex:** 3,000,000 RUB authorized budget (total cost 3.3M RUB with marketing scale-up).
* **Financial Return:** **NPV = 183,402 RUB** (@ 25% discount rate), **IRR = 74%**, **PI = 1.18**, Discounted Payback Period (**DPB**) = **5.8 months**.
* **Governance Model:** Hybrid framework combining **Critical Chain Project Management (CCPM)** for schedule buffer protection and **Kanban** (WIP limit = 2) for sprint execution.
* **Core Technical Outcomes:** 100% MVP scope delivered on 1C-Bitrix, bi-directional 1C catalog/order sync (<15 min latency), 0 critical release blockers, page load under 2 seconds.

---

## 🎯 Business Goals & Success Criteria

### Business Objectives (SMART)
1. **Sales Channel Diversification:** Launch a scalable online channel generating **2.5M RUB/month** in turnover within 6 months post-launch.
2. **Revenue Growth:** Deliver **+40% company-wide sales increase** within 6 months.
3. **ROI:** Achieve full investment payback within **12 months** post-release.

### Operational KPIs & Quality Gates
| Metric | Target Baseline | Final Result | Status |
|---|---|---|---|
| **Delivery Timeframe** | $\le$ 4 months | 95 working days (~4.5 mos) | Controlled variance via buffers |
| **Development Budget** | 3,000,000 RUB | 2,100,000 RUB (Dev) + 1.2M RUB (Ads) | Approved via Change Request |
| **MVP Scope Completion** | 100% Must-Have items | 100% delivered | Met |
| **Critical Defects at Launch** | 0 critical / blocking bugs | 0 (0% broken critical UI buttons) | Met |
| **Homepage & Catalog Speed** | $\le$ 2.0 sec (50 CCU) | 1.85 sec desktop / 2.3 sec mobile | Partially met (optimization queued) |
| **1C ERP Catalog Sync** | $\le$ 15 min update cycle | Real-time batch sync (< 10 min) | Met |
| **Payment Gateway Reliability**| Error rate < 1.0% | 0.2% transaction failure rate | Met |
| **Customer Satisfaction (CSAT)**| $\ge$ 4.5 / 5.0 | 4.6 / 5.0 | Met |

---

## 🏗️ Scope Management (MoSCoW Prioritization)

To safeguard launch timelines and budget boundaries, strict scope gating was enforced:

* **Must Have (MVP Baseline):**
  * Product catalog with multi-parameter filtering (category, price range, brand).
  * Product detail pages, shopping cart, checkout flow with integrated online acquiring.
  * User profile with order history and delivery tracking.
  * Bi-directional 1C integration (catalog items, stock balance sync, incoming order dispatch).
  * CMS administrative dashboard and mobile-responsive viewport.
  * Technical SEO foundation and core analytics integration.
* **Should Have (Phase 1.1):**
  * Content marketing blog section and promotional discounts engine.
* **Could Have (Backlog / Future Sprints):**
  * AI-driven personalized recommendations and multi-tier loyalty bonus system.
* **Won't Have (Out of Scope):**
  * Native iOS/Android apps, private courier logistics fleet, international multi-currency localization.

---

## 👥 Stakeholders & Team Structure

A hybrid resourcing strategy was deployed, pairing internal domain experts with dedicated outstaff development capacity:



---

## 📊 Financial Feasibility & Sensitivity Analysis

A dynamic cash flow projection model was constructed over a 6-period lifecycle:

* **Discount Rate (WACC):** 25.0%
* **Net Present Value (NPV):** 183,402 RUB
* **Internal Rate of Return (IRR):** 74%
* **Profitability Index (PI):** 1.18
* **Payback Period:** Simple = 5.68 periods | Discounted (DPB) = 5.77 periods

### Sensitivity Testing (NPV Impact)
* **Sales Volume / Price Drop:** The model tolerates up to a **10% decrease** in gross sales before NPV breaches negative territory (critical threshold: -15,564 RUB at -10% volume). This insight triggered immediate pre-launch marketing safeguards.
* **Fixed Cost Fluctuations:** Robust against fixed cost inflation (+35% increase still preserves +32,256 RUB positive NPV).

---

## ⏱️ Schedule & Buffer Management (CCPM)

To prevent *Student Syndrome* and *Parkinson's Law*, standard task estimates were stripped of hidden contingency reserves and consolidated into managed strategic buffers in **ProjectLibre**:



1. **Resource Buffer (2 days):** Placed prior to backend development to verify environment provisioning, 1C API readiness, and contractor onboarding.
2. **Project Buffer (5 days):** Appended immediately after final deployment to absorb critical chain delays without breaching stakeholder launch commitments.

---

## 🚦 Risk Governance & Response Strategy

Risks were quantitatively scored using a  	imes 5$ probability-impact matrix ( = P 	imes I$):

| # | Risk Event | P (%) | I (%) | Score | Classification | Primary Mitigation (Preventive & Contingent) |
|---|---|---|---|---|---|---|
| **R1** | **Low Conversion Rate (<0.5% vs 2.0%)** | 80% | 100% | **0.80** | **Critical** | Pre-launch usability testing; conversion funnel analytics; modular checkout redesign. |
| **R2** | **1-Month Development Slippage** | 80% | 80% | **0.64** | **Critical** | CCPM buffer deployment; sprint scope trimming; on-call reserve engineering bench. |
| **R3** | **Contextual Ad Inflation (+30%)** | 60% | 60% | **0.36** | **Moderate** | Multi-channel CAC monitoring; reallocation to organic SEO and direct social traffic. |
| **R4** | **Acquiring Gateway Outage under Load** | 40% | 80% | **0.32** | **Moderate** | Load testing up to 200 CCU; dual redundant payment provider failover setup. |
| **R5** | **1C Data Exchange Bottlenecks** | 60% | 40% | **0.24** | **Low-Mod** | Upfront API audit; dedicated **80,000 RUB contingency fund** for specialized 1C developer. |

### Continuous Risk Governance Workflow
* **Bi-weekly Risk Audits:** Formal reassessment of Top-5 threat trajectories.
* **Trigger Thresholds:** Automatic escalation to Sponsor if variance exceeds 10% of milestone timeline or budget.

---

## 🔄 Project Governance, Agile Cadence & Change Control

### Kanban Execution & WIP Constraints
* Workflow stages: Planned → In Progress → Review / QA → Done
* **WIP Limit:** Hard ceiling of **maximum 2 concurrent tasks in progress** to eliminate multitasking drag and cycle time inflation.

### Meeting Cadence
* **Daily Standup (15 min):** Blocker identification and daily commitment.
* **Weekly Demo (30 min):** Tangible milestone demo for Sponsor & Commercial Director.
* **Bi-weekly Retrospective (60 min):** Process optimization and impediment removal.

### Formal Change Management Procedure


---

## ✅ Quality Assurance, Acceptance & Handover

Formal acceptance was governed by strict verification protocols:
1. **Functional Integrity:** 100% pass on core checkout scenarios; 0% broken interactive elements.
2. **ERP Synchronization:** Newly created SKU in 1C automatically appears on storefront in $\le 15$ minutes.
3. **Performance Benchmarks:** Server response $<2$ seconds under concurrent load of 50 users.
4. **Operational Readiness:** Delivery of complete CMS Administrator Manual and training session conducted for store administrator Anna.

---

## 🔍 Post-Project Audit & Lessons Learned (Month +3)

A post-implementation audit was conducted 90 days after public release to compare baseline vs. actuals and institutionalize learnings:

| Dimension | Baseline Plan | Actual Outcome | Variance Analysis & Root Cause |
|---|---|---|---|
| **Labor Effort** | 70 working days | 95 working days | **+35% delay.** Primary driver: complex legacy 1C data schema requiring deeper data sanitization. |
| **Development Cost** | 2,100,000 RUB | 2,100,000 RUB | **0% variance.** Fixed outstaff contracts and strict scope gating prevented cost overruns. |
| **Marketing Spend** | 900,000 RUB | 1,200,000 RUB | **+33% investment.** Scaled customer acquisition budget to offset seasonal CPC increases. |
| **Mobile Performance**| $\le 2.0$ sec | 2.30 sec | Identified unoptimized WebP banner assets; CDN cache optimization scheduled. |

### Key Retrospective Takeaways (PM Lessons Learned)
1. **De-couple ERP Integration Early:** Legacy data cleansing in ERP systems takes 2x longer than anticipated. Future initiatives must run database audits during the Initiation phase before baseline freeze.
2. **Buffering Works:** Without the CCPM project buffer (5 days) and resource buffer (2 days), commercial launch would have missed the critical promotional window.
3. **WIP Constraints Reduced Cycle Time:** Enforcing WIP = 2 kept developer focus sharp, resulting in zero critical defects upon initial public release.

---

## 📂 Repository File Structure
```
green-home-study-project/
│
├── README.md                           
├── README.ru.md                        
│
├── docs/
│   ├── en/                             
│   │   ├── project-charter.md          
│   │   └── risk-management.md          
│   │
│   └── ru/                             
│       ├── 01-устав-проекта.docx       
│       ├── 02-риски-и-финансы.docx     
│       ├── 03-план-закупок.docx        
│       ├── 04-исполнение-и-ccpm.docx   
│       └── 05-приемка-и-аудит.docx     
│
└── artifacts/                          
    ├── Green_Home_Schedule_v1.pod      
    ├── Green_Home_Schedule_CCPM.pod    
    ├── Financial_Model.xlsm            
    └── Costing_and_Procurement.xlsx    
```
---

## 🛠️ Tools & Standards Applied
* **Frameworks:** PMBOK Guide 7th Ed., Theory of Constraints / CCPM, Agile Kanban, MoSCoW.
* **Software:** ProjectLibre, Microsoft Excel / Advanced Financial Modeling, 1C:Enterprise, 1C-Bitrix CMS.

---
*Created by Elina Musaeva — Project Manager*
*Contact: elllina.m@proton.me / https://www.linkedin.com/in/elina-musaeva / tg: @m_elllina*
