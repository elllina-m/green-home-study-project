# Project Charter: "Green Home" E-Commerce MVP

## 1. General Project Information
* **Project Name:** "Green Home" (*Зелёный дом*)
* **Project Manager:** Project Manager
* **Project Sponsor:** Petr, Owner & CEO of "Green Home"
* **Date of Authorization:** January 01, 2026
* **Project Type:** Web Application / E-Commerce MVP Launch & ERP Integration

---

## 2. Executive Context & Business Case

### Background
"Green Home" is a retail company specializing in eco-friendly household goods, cookware, and cosmetics. For five years, sales relied almost exclusively on a physical brick-and-mortar storefront and social media inquiries. Over the preceding two quarters, offline retail footfall declined steadily. Concurrently, primary market competitors expanded aggressive digital retail channels, offering seamless online purchasing journeys.

### Project Concept & Strategic Intent
Design, develop, and launch a minimum viable product (MVP) e-commerce web platform for "Green Home". The platform creates a scalable direct-to-consumer (D2C) sales channel, automates inventory and order workflows via bi-directional integration with the legacy 1C ERP system, and provides customers with an intuitive, self-service shopping experience.

### Core Business Drivers
* Mitigate business dependency on offline footfall.
* Diversify revenue streams with an always-on online sales channel.
* Increase product catalog accessibility across geographic regions.
* Align with evolving consumer expectations regarding digital checkout convenience.
* Eliminate manual data entry and synchronization between warehouse inventory and customer orders.
* Improve operational efficiency by synchronizing web operations with 1C:Enterprise ERP.
* Establish a foundational platform for digital performance marketing, SEO, and retention campaigns.

---

## 3. Project Scope & Boundaries (MoSCoW)

### In-Scope (MVP Baseline)
* **Discovery & Requirements:** Elicitation, documentation, and stakeholder sign-off of business and technical requirements.
* **UI/UX Design:** Architecture mapping, information hierarchy, wireframes, and responsive high-fidelity design layouts.
* **Architecture & Development:** Frontend and backend development based on 1C-Bitrix CMS.
* **Catalog & Merchandising:** Multi-category catalog, faceted filtering (price range, category, brand), dynamic product cards with specifications and photo galleries.
* **Checkout Engine:** Shopping cart state persistence, multi-step checkout workflow, secure payment acquiring integration.
* **Customer Account (Cabinet):** User registration/login, profile data management, order history, real-time shipment status tracking.
* **Administration & Operations:** CMS administrative console, role-based access control, basic discount/promo engine.
* **1C ERP Integration:** Automated bi-directional data exchange for product SKUs, real-time stock balances, and order ingestion.
* **Marketing & SEO Foundation:** Clean URL routing, meta tags architecture, sitemap.xml, robots.txt, and a content blog module.
* **Quality Assurance:** Cross-browser, responsive mobile testing, end-to-end integration testing, zero-tolerance policy for critical/blocker defects.
* **Deployment & Handover:** Server provisioning, domain and SSL setup, administrator user guide delivery, staff training, and formal operational handover.

### Out of Scope (Explicit Exclusions)
* Native mobile applications (iOS / Android).
* Proprietary in-house delivery logistics fleet and real-time courier tracking.
* Advanced multi-tier loyalty point reward system.
* Multi-channel marketplace integrations (Ozon, Wildberries, Yandex Market).
* Multi-language / international currency localization.
* AI-driven personalized recommendation algorithms.
* Comprehensive accounting automation beyond order and inventory balance exchange.
* Post-launch feature iterations beyond agreed warranty support.

---

## 4. Project Objectives & Success Criteria

### Business Objectives
* Establish a functioning online sales channel generating **2.5M RUB/month** in gross merchandise value (GMV) within 6 months post-launch.
* Deliver an overall **40% increase in company-wide revenue** within 6 months post-launch.
* Achieve full capital investment payback within **12 months** of commercial launch.

### Technical & Execution Target (Iron Triangle)
* Complete end-to-end development, testing, and deployment within **4 months**.
* Maintain project expenditures strictly within the approved **3,000,000 RUB** budget cap.

### Target Performance Metrics & Quality Gates
| Metric | Baseline Target | Measurement Method / Tool |
|---|---|---|
| **Schedule Duration** | $\le$ 4 months | Calendar schedule (ProjectLibre) |
| **Budget Variance** | $\le$ 10% tolerance | Cash flow audit & expense logs |
| **MVP Requirement Fulfillment** | 100% Must-Have scope | Requirements traceability matrix |
| **Critical Defects at Launch** | 0 critical / blocking bugs | Bug tracking system (Jira/tracker) |
| **Homepage Performance** | $\le$ 2.0 seconds load time | Synthetic load testing (50 CCU) |
| **Payment Gateway Failure Rate** | < 1.0% failed transactions | Acquiring transaction logs |
| **1C ERP Integration Reliability** | 100% critical sync paths passing | Automated exchange protocol logs (<15 min cycle) |
| **Customer Satisfaction (CSAT)** | $\ge$ 4.5 / 5.0 at Month +1 | Stakeholder feedback survey |

---

## 5. Assumptions and Dependencies

| ID | Assumption | Potential Impact if Invalidated |
|---|---|---|
| **A1** | Existing 1C ERP configuration supports required API data exchange schemas. | Requires custom 1C configuration development, causing cost/schedule escalation. |
| **A2** | Designated internal subject matter experts will remain available as scheduled. | Workstream dependencies delayed, impacting milestone sign-offs. |
| **A3** | The 3,000,000 RUB budget is sufficient to cover outstaff development rates. | Work breakdown re-negotiation or scope deselect required. |
| **A4** | Master catalog data and high-res asset photography are ready prior to content ingestion. | Catalog ingestion milestone slippage, postponing final launch. |
| **A5** | The Project Sponsor reviews and approves deliverables within agreed turnaround times. | Schedule delays propagating through dependent critical path tasks. |
| **A6** | Merchant bank payment acquiring API is fully functional and sandbox-accessible. | Checkout flow testing delayed, requiring placeholder payment flows. |
| **A7** | Core business requirements remain baseline-frozen once development sprints begin. | Scope creep leading to rework, cost escalation, and deadline slippage. |

---

## 6. Project Stakeholders & Governance Structure

| Project Role | Name & Company Position | Core Responsibilities in Project |
|---|---|---|
| **Project Sponsor** | Petr, Owner & CEO | Defines strategic business objectives, authorizes budget and scope baseline, acts as ultimate escalation authority, formally accepts final outcome. |
| **Project Manager** | Project Manager (*Case Author*) | End-to-end project planning and execution, schedule and budget control, risk governance, stakeholder communications, conflict resolution, acceptance management. |
| **Technical Lead** | Alexey, Head of IT | Evaluates architectural patterns, oversees technical standards, coordinates developers, co-signs technical acceptance gates. |
| **Business Domain Lead** | Olga, Commercial Director | Owns business requirements and commercial workflow rules, validates discount and inventory policies, participates in acceptance testing. |
| **1C ERP Specialist** | Maria, Internal 1C Developer | Analyzes existing database schema, builds data exchange modules, monitors catalog/stock sync protocols. |
| **Digital Marketing Lead** | Ivan, Internal Marketing Manager | Establishes SEO technical requirements, content marketing architecture, prepares campaign launching assets. |
| **Web Backend Developer** | Outstaff External Specialist | Implements business logic, API integrations, CMS configuration, and database persistence. |
| **Frontend / UI Engineer** | Outstaff External Specialist | Builds responsive user interface, cross-device compatibility, accessibility standards. |
| **Quality Assurance (QA)** | Outstaff External Specialist | Develops test suites, executes functional/integration/regression testing, logs and validates defect resolution. |
| **Store Operations Rep** | Anna, Store Administrator | Validates administrative panel ergonomics, participates in user acceptance testing (UAT), assumes operational store management post-launch. |
