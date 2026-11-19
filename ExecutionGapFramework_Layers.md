# The Execution Gap Framework™ — 8 Operational Layers
**Concept360 · Biljana Obradović · © 2026**

Applied to RWA tokenization and regulated fintech delivery programs.

Every regulated program — regardless of technology stack, jurisdiction, or scale — must address eight operational layers, L0 to L7. The sequence matters. Skipping a layer doesn't remove it; it relocates the problem to a later, more expensive stage.

---

## Layer Overview

| Layer | Core objective | Scope — RWA tokenization | Scope — regulated fintech / core banking |
|---|---|---|---|
| **L0 — Strategy & Value Definition** | Decide whether the program should exist. | Business case · mandate · governance · RACI · budget · custody principle | Business case · wave structure · country sequencing · governance · RACI · budget |
| **L1 — Regulatory & Business Foundation** | Ensure the program can legally exist. | Regulatory pathway · MLRO · AML · licensing · classification · banking | PSD2 · per-country regulatory mapping · local banking law · DORA · AML program · MLRO |
| **L2 — Solution Architecture** | Design before commitments become expensive. | Token · custody · vendors · SPV · IAM · data · economics · reconciliation · time | Core system design · middleware · API architecture · vendor contracts and SLAs · integration agreements · decision tracking |
| **L3 — Build & Integration** | Build and integrate with controlled execution. | Smart contracts · integrations · KYC/AML · custody · IAM · keys · reconciliation | Core build · per-country integration across core banking and middleware · KYC/AML pipeline |
| **L4 — Validation & Control** | Validate that controls operate in practice. | Validation types · security audit · penetration test · DORA · audit trail · independent sign-off | Penetration test · DORA ICT · security audit · end-to-end integration validation |
| **L5 — Readiness & Transition** | Authorize and prepare for production. | UAT · Proof of Reserves · key ceremony · rollback · go-live sign-offs · market readiness | UAT per wave · go-live sign-offs · rollback plan · regulatory test filing · wave readiness |
| **L6 — Operational Execution** | Stabilize under real production conditions. | G-OPS Gate · hypercare · KPI/KRI · incident management · BAU handover | Wave activation · hypercare · KPI/KRI monitoring · incident management · BAU handover |
| **L7 — Continuous Governance** | Govern, improve, and sustain. | Audit calendar · vendor management · regulatory reporting · drift monitoring · liquidity review | Ongoing vendor governance · regulatory reporting · audit calendar · incident management · operational continuity |

Each layer closes with a named decision gate that requires documented evidence, not verbal confirmation. Ranges and scopes are illustrative, not exhaustive: specific evidence requirements and gate criteria depend on program type, jurisdiction, and regulatory classification.

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
