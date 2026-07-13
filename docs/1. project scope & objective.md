# Project Scope and Objectives Document


## 1. Executive Summary

DUT lab administrators receive complex utility data and system logs all in English. While tech-savvy, they lack electrical engineering training and, as non-native English speakers, struggle to interpret billing data and technical logs. This language-technical skills gap has led to **undetected energy waste** and **unnecessarily high electricity costs**.

This project proposes a **sovereign AI solution** that detects carbon footprint hotspots in KZN computer labs and delivers actionable alerts in **isiZulu** and other South African indigenous languages, empowering lab administrators to make data-driven decisions about energy consumption.

**Total Annual Production Cost:** R12,000
**Estimated Annual Savings:** R50,000 - R80,000
**Payback Period:** Less than 3 months

---

## 2. Project Background

### 2.1 The Real-World Problem

| Element | Description |
|---------|-------------|
| **Who is affected?** | DUT lab administrators, ICT/IS Department, students, Green Campus Initiative |
| **What is the problem?** | Complex utility data in English creates a language-technical gap |
| **Why does it matter?** | Undetected energy waste leads to high costs and unnecessary carbon emissions |
| **Current solutions** | NovaVue, Entronix EMP, GreenX - monitor only buildings/circuits, no language support |
| **Gap identified** | No per-computer granularity, no indigenous language interfaces |

### 2.2 Stakeholder Feedback

> *"We get the utility data. It's all in English. But the technical words—wattage, idle draw, carbon intensity—we struggle to interpret them."*
> — DUT Lab Staff Member

Based on discussions with two DUT lab staff members, this is a **real, validated need** affecting daily operations and institutional sustainability goals.

---

## 3. Project Objectives

### 3.1 Primary Objectives

| # | Objective | Success Criteria |
|---|-----------|------------------|
| 1 | **Detect** energy waste hotspots at per-computer level | System identifies idle computers with 95%+ accuracy |
| 2 | **Translate** technical energy data into isiZulu | Lab administrators can understand alerts without technical training |
| 3 | **Alert** users via accessible channels (WhatsApp) | Alerts delivered within 1 minute of detection |
| 4 | **Ensure** data sovereignty and POPIA compliance | 100% local hosting, zero data leakage |
| 5 | **Empower** lab administrators to reduce energy waste | Measurable reduction in electricity consumption |

### 3.2 SMART Objectives

| Objective | Specific | Measurable | Achievable | Relevant | Time-bound |
|-----------|----------|------------|------------|----------|------------|
| **O1** | Deploy Eco2AI telemetry on 1 DUT lab | Capture CPU/GPU wattage, process IDs | ✓ Free, open-source | Directly addresses waste detection | Week 4-6 |
| **O2** | Integrate Vulavula API for isiZulu | Translate alerts into isiZulu | ✓ Built by African researchers | Addresses language barrier | Week 6-8 |
| **O3** | Deliver WhatsApp alerts to lab managers | Messages sent within 1 minute | ✓ WhatsApp Business API | Actionable, accessible | Week 8-10 |
| **O4** | Host all data on Cloud Africa | 100% POPIA compliance | ✓ South African servers | Data sovereignty | Week 10-12 |
| **O5** | Demonstrate energy savings | 10% reduction in lab energy usage | ✓ Based on idle computer detection | Institutional sustainability | Week 12+ |

---

## 4. Project Scope

### 4.1 In-Scope

| Category | Items |
|----------|-------|
| **Systems** | DUT computer labs (starting with 1 pilot lab) |
| **Data** | CPU/GPU wattage, active process IDs, runtime durations, estimated carbon mass |
| **Languages** | isiZulu (primary), English (fallback), expandable to other SA languages |
| **Tools** | Eco2AI, Vulavula API, WhatsApp Business API, Cloud Africa |
| **Compliance** | POPIA (Protection of Personal Information Act) |
| **Users** | Lab administrators, ICT/IS Department, Green Campus Initiative |

### 4.2 Out-of-Scope

| Category | Items |
|----------|-------|
| **Hardware** | No new hardware procurement required |
| **Buildings** | No building-level monitoring (existing tools cover this) |
| **Other languages** | Initially isiZulu only (expandable) |
| **Student-facing app** | Initial focus on lab managers (future phase) |
| **Other campuses** | DUT only initially (expandable) |

### 4.3 Key Constraints

| Constraint | Impact | Mitigation |
|------------|--------|------------|
| **Time** | Hackathon deadline: Indigenous Languages Innovation Week | Prioritize MVP features, delay enhancements |
| **Budget** | R12,000 annual (prototype R0) | Use free tools for prototype, seek grants |
| **Data access** | Real DUT data needed | Partner with ICT/IS Department |
| **Language API** | Vulavula API cost after trial | Budgeted R3,500/year |
| **Compliance** | POPIA strict requirements | Local hosting via Cloud Africa |

---

## 5. Deliverables

### 5.1 Phase 1: Planning (Week 1)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D1.1 | Project Scope Document | Siyabonga |
| D1.2 | GitHub Repository Setup | Meluleki |
| D1.3 | Stakeholder Communication Plan | Siyabonga |
| D1.4 | Development Environment | Meluleki |

### 5.2 Phase 2: Analysis (Week 2-3)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D2.1 | Requirements Document | Both |
| D2.2 | Data Flow Diagram | Meluleki |
| D2.3 | User Personas | Siyabonga |
| D2.4 | Compliance Assessment (POPIA) | Both |

### 5.3 Phase 3: Design (Week 4-5)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D3.1 | System Architecture Diagram | Meluleki |
| D3.2 | Database Schema | Meluleki |
| D3.3 | UI/UX Mockups | Siyabonga |
| D3.4 | API Integration Specifications | Both |

### 5.4 Phase 4: Development (Week 6-9)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D4.1 | Eco2AI Telemetry Module | Meluleki |
| D4.2 | Vulavula Translation Module | Siyabonga |
| D4.3 | WhatsApp Alert Module | Siyabonga |
| D4.4 | Database & API Backend | Meluleki |
| D4.5 | "Vala/Sula" Privacy Module | Both |

### 5.5 Phase 5: Testing (Week 10-11)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D5.1 | Test Results Report | Both |
| D5.2 | User Acceptance Testing Report | Both |
| D5.3 | Bug Fixes & Enhancements | Both |

### 5.6 Phase 6: Deployment (Week 12)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D6.1 | Live Production System | Both |
| D6.2 | User Manual & Training | Both |
| D6.3 | Go-Live Certificate | Both |

### 5.7 Phase 7: Maintenance (Ongoing)

| Deliverable | Description | Owner |
|-------------|-------------|-------|
| D7.1 | Open-Source Code on GitHub | Both |
| D7.2 | SADiLaR Language Data Contribution | Both |
| D7.3 | Grant Applications (TIA, DSI) | Both |

---

## 6. Success Metrics & KPIs

| Metric | Target | Measurement Method |
|--------|--------|-------------------|
| **Energy savings** | 10-20% reduction in lab electricity | Compare monthly bills pre/post |
| **User satisfaction** | 85%+ lab manager satisfaction | Post-implementation survey |
| **Alert accuracy** | 95%+ accurate hotspot detection | Telemetry validation |
| **Translation quality** | 90%+ isiZulu accuracy | User review and feedback |
| **System uptime** | 99%+ | Cloud monitoring |
| **Cost savings** | R50,000 - R80,000/year | Electricity bill analysis |

---

## 7. Budget Summary

### 7.1 Prototype Phase (R0)

| Item | Cost |
|------|------|
| Eco2AI (Open-Source) | R0 |
| Python Environment | R0 |
| Test Computer (Existing) | R0 |
| Vulavula Sandbox | R0 |
| WhatsApp Sandbox | R0 |
| Contingency | R500 |
| **Total Prototype** | **R500** |

### 7.2 Production Phase (Annual)

| Item | Cost |
|------|------|
| Cloud Africa Hosting | R3,000 |
| Vulavula API (Commercial) | R3,500 |
| WhatsApp API | R3,500 |
| Maintenance Contingency | R2,000 |
| **Total Annual Production** | **R12,000** |

### 7.3 Return on Investment

| Metric | Value |
|--------|-------|
| Annual Investment | R12,000 |
| Estimated Annual Savings | R50,000 - R80,000 |
| **Payback Period** | **Less than 3 months** |
| **5-Year ROI** | **1,500%+** |

---

## 8. Risks & Mitigation

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| Vulavula API costs increase | Low | Medium | Lock in pricing, seek grants |
| POPIA compliance delays | Medium | High | Early legal consultation |
| Lab staff adoption resistance | Medium | Medium | Training, user-centered design |
| Technical issues with Eco2AI | Low | Medium | Open-source community support |
| Data access restrictions | Medium | High | Early ICT/IS Department partnership |
| Budget constraints | Low | Low | Low-cost model, multiple funding sources |

---

## 9. Stakeholder Engagement

| Stakeholder | Engagement Strategy | Frequency |
|-------------|---------------------|-----------|
| DUT Lab Administrators | Interviews, UAT sessions, feedback loops | Weekly |
| ICT/IS Department | Steering committee, progress updates | Bi-weekly |
| Green Campus Initiative | Sustainability reporting, data sharing | Monthly |
| Students | Awareness campaigns, educational materials | Quarterly |
| DSI / TIA | Grant reporting, progress showcases | As needed |

---

## 10. Timeline Summary

| Phase | Duration | Key Milestone | Date |
|-------|----------|---------------|------|
| Phase 1: Planning | 1 week | Project scope approved |  |
| Phase 2: Analysis | 2 weeks | Requirements finalized | |
| Phase 3: Design | 2 weeks | Architecture approved |  |
| Phase 4: Development | 4 weeks | MVP completed |  |
| Phase 5: Testing | 2 weeks | UAT signed off |  |
| Phase 6: Deployment | 1 week | Go-live |  |
| Phase 7: Maintenance | Ongoing | Open-source launch | |

---

## 11. Success Stories & Impact

### 11.1 Environmental Impact

| Metric | Year 1 Target | Year 5 Target |
|--------|---------------|---------------|
| CO₂ reduction | 2-3 tons | 15-20 tons |
| Electricity saved | 5,000 kWh | 25,000+ kWh |
| Labs covered | 1 | 10+ |

### 11.2 Social Impact

| Impact Area | Description |
|-------------|-------------|
| **Language Inclusion** | Indigenous language speakers can now understand energy data |
| **Empowerment** | Lab administrators gain data-driven decision-making power |
| **Education** | Students learn about energy consumption in their own language |
| **Public Service** | Better resource management in public institutions |

### 11.3 Innovation Impact

| Area | Contribution |
|------|--------------|
| **African AI** | Using locally-built tools (Vulavula, Cloud Africa) |
| **Open Source** | Codebase shared with Masakhane, SADiLaR |
| **Replicability** | Blueprint for other universities across Africa |

---

## 12. Appendices

### Appendix A: Glossary

| Term | Definition |
|------|------------|
| **Eco2AI** | Open-source Python framework for energy consumption monitoring |
| **Vulavula API** | African-built language API for isiZulu translation |
| **POPIA** | Protection of Personal Information Act (South Africa) |
| **"Vala/Sula"** | Close/Delete - hard data deletion command |
| **Telemetry** | Automatic measurement and transmission of data |
| **Carbon Footprint** | Total greenhouse gas emissions caused by activity |

### Appendix B: References

1. **Loghub** - System log datasets (GitHub)
2. **IEEE DataPort** - Energy consumption datasets
3. **Lelapa AI** - Vulavula API documentation
4. **Eco2AI** - GitHub repository
5. **POPIA Act** - South African data protection legislation

---

**Document Approved By:**

| Name | Signature | Date |
|------|-----------|------|
| Siyabonga Mkhize | ___________ | 07/07/2026 |
| Meluleki Shandu  | ___________ | 07/07/2026 |

---

**A Sovereign AI Blueprint for Carbon Footprint Hotspot Detection** | **Public Services & Inclusion** | **Siyabonga Mkhize & Meluleki Shandu**