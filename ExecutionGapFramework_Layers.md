# The Execution Gap Framework™ — 8 Operational Layers
**Concept360 · Biljana Obradović · © 2026**

Applied to RWA tokenization and regulated fintech delivery programs.

Every regulated program — regardless of technology stack, jurisdiction, or scale — must address eight operational layers, L0 to L7. The sequence matters. Skipping a layer doesn't remove it; it relocates the problem to a later, more expensive stage.

---

## Layer Overview

| Layer | RWA Tokenization | Regulated Fintech / Core Banking |
|---|---|---|
| **L0 — Strategy & Value Definition** | Business case, board approval, governance, RACI, OKR framework, budget management, custody model selection | Business case, wave structure, country sequencing, governance, RACI, OKR framework, budget management |
| **L1 — Regulatory & Business Foundation** | MiCA/CASP, DORA, eWpG, BaFin/NCA licensing, MLRO appointment, AML program, multi-jurisdiction mapping, SPV incorporation, legal opinion, token classification | PSD2, per-country regulatory mapping, local banking law, DORA, AML program, MLRO |
| **L2 — Solution Architecture** | SC design, oracle selection, custody architecture, chain configuration, API governance, vendor MSA, SLA framework, decision tracking | Core system design, middleware strategy, API architecture, vendor contracts, SLA framework, integration agreements, decision tracking, assumption log |
| **L3 — Build & Integration** | SC development, KYC/KYT integration, SAST, platform and custody integration build | Core build, per-country integration across core banking system and middleware, KYC/AML pipeline, vendor governance |
| **L4 — Validation & Control** | SC audit #1 and #2, pen test, DAST, DORA ICT third-party register, ISO 27001 gap, end-to-end testing, settlement, PoR baseline, UAT | Pen test, DORA ICT, security audit, UAT per wave, end-to-end integration |
| **L5 — Readiness & Transition** | Rollback plan, gate sign-off, G-OPS gate, go-live readiness evidence | Gate sign-off, rollback plan, regulatory test filing, wave readiness |
| **L6 — Operational Execution** | Hypercare, KPI/KRI monitoring, change & incident management, DORA monitoring, regulatory reporting | Wave activation, hypercare, BAU transition, KPI/KRI monitoring, change & incident management |
| **L7 — Continuous Governance** | Vendor SLA management, regulatory reporting calendar, audit schedule, incident & change management, new project initiation from operations | Ongoing vendor governance, regulatory reporting, audit calendar, incident management, operational continuity planning |

---

## Key Principles

**L0 is never optional.**
The foundation — business case, operating model, RACI, OKR framework, and budget management — must be defined before any technical work begins. Most programs fail here, not at L4. A weak L0 means every subsequent layer inherits its structural problems.

**Layers overlap by design.**
Architecture work starts before regulatory and legal work is complete, and testing starts before build is complete. L6 operations begins at go-live per wave — not after the last wave closes. Compliance is embedded as a delivery dependency at each layer, not treated as an external requirement that arrives late.

**Compliance is a delivery task, not a dependency.**
MiCA, DORA, and per-country regulatory requirements are gate criteria — not external dependencies. Missing a compliance gate criterion blocks the gate. It does not simply delay it.

**Vendor governance runs across all layers.**
Multi-vendor coordination, SLA management, escalation ownership, and third-party risk tracking are not L2 or L3 tasks — they are continuous from L0 through L7. Vendor escalation fragmentation is one of the most common causes of operational drift in regulated programs.

**Change and incident management starts at L0.**
A change management process that does not exist at L0 cannot be retrofitted at L5. Incident classification, escalation paths, and regulatory notification obligations must be defined before go-live — not after the first incident.

**L7 — Continuous Governance. It is not the end. It is the operating state.**
Post-launch stability does not manage itself. L7 begins at go-live — not after the delivery team exits. Vendor SLA enforcement, regulatory reporting cadence, audit calendar, and the capacity to initiate new programs from a stable operational base require the same governance discipline as every layer that preceded it.

---

> For the full framework — [Start the conversation](https://biljanaobradovic-delivery.github.io/execution-gap-framework/#contact)

---
*Biljana Obradović · Concept360 · 2026*
