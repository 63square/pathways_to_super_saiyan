# 15 — Quality Management System (QMS) Framework

**Owner:** Head of Quality (QA)
**Effective:** eQMS deployment Month 3 (interim QA lead from Big-4 covers M3–M6); full handoff to Head of QA M6
**Review cadence:** Annual internal audit; annual external audit

## Purpose

v1.0 of the program asserted "GMP-equivalent SOPs" without underlying QMS architecture. This document closes that gap.

The QMS is the institutional discipline that distinguishes Project PROMETHEUS from an n=1 vanity protocol. Without it, every spinout has to rebuild data lineage at Series A diligence, and a single Form-483-equivalent finding against Senex (the senolytic+TPE spinout) torpedoes the $20M raise that gates Phase 1.

Aligned with: **ICH Q10**, **ISO 13485**, **GxP convergence**, **21 CFR Part 11** (electronic records).

---

## 15.1 QMS Scope

Covers all program activities producing:
- Clinical protocols and SOPs
- Pharmaceutical product handling and dispensing (off-label and investigational)
- Cell therapy, biospecimen, and tissue handling (autologous mito, FMT, sperm cryo, biopsies)
- Gene therapy vector handling (Phase 1+)
- Animal welfare (canine + NHP cohorts; doc 16 IACUC)
- Data management (doc 14)
- IP capture and trade-secret discipline
- Vendor qualification
- Training

## 15.2 eQMS Platform

**Selected platform: Veeva Vault QMS** (default) OR **Greenlight Guru** (faster startup; recommended for Phase 0 lean operation).

**Deployed Month 3** by interim QA lead (Big-4 Life Sciences practice). Full migration and configuration handoff to Head of QA by Month 6.

Platform modules:
- Document Control
- CAPA (Corrective and Preventive Action)
- Deviation Management
- Change Control
- Training Management (LMS)
- Internal Audit
- Supplier Qualification
- Risk Management (ISO 14971-aligned for medical devices; ICH Q9 for clinical)
- Complaint Handling (Principal subjective reports, staff escalations)

## 15.3 Document Control Hierarchy

```
Level 0 — Quality Manual (this document)
Level 1 — Standard Operating Procedures (SOPs)
Level 2 — Work Instructions (WIs)
Level 3 — Forms, Templates, Logs
Level 4 — Records (completed forms, captured data)
```

- **Level 0–1 changes:** require Head of QA + relevant function head sign-off
- **Level 2–3 changes:** Head of QA approves
- **Level 4 records:** locked, audit-trailed, retention per doc 14
- **Effective dates** managed via eQMS
- **Periodic review:** Level 0–1 annually; Level 2–3 biennially

## 15.4 SOP System

**SOP-on-SOPs** (SOP-0001) defines:
- Template structure
- Authoring workflow (drafted by SME, reviewed by Head of QA + relevant function head + CMO if clinical, approved by signatures)
- Version control (semantic versioning: MAJOR.MINOR.PATCH)
- Effective date logic
- Training assignment trigger (any MAJOR or MINOR change → re-training)
- Periodic review cycle
- Obsolescence procedure

**Phase 0 SOP library** (drafted by CMO + Head of QA, M3–M6):
- SOP-0001: SOP-on-SOPs
- SOP-CL-001 through CL-016: each Phase 0 GREEN-bucket intervention (doc 02)
- SOP-CL-020: Master consent process
- SOP-CL-021: Procedure-specific consent
- SOP-CL-022: Stop-rule decision flow (doc 11 §11.5)
- SOP-CL-023: Adverse event reporting
- SOP-CL-024: Emergency protocols (code blue, medevac, mental health, security)
- SOP-CL-025: Two-physician refusal rule procedure
- SOP-LAB-xxx: Biospecimen handling
- SOP-IT-xxx: Tier-Red access procedure
- SOP-IP-001: Invention disclosure and provisional filing workflow
- SOP-HR-001: Onboarding incl. DEFINITIONS.md acknowledgment
- SOP-VEN-001: Vendor qualification per tier
- SOP-AN-001: Animal welfare (links to doc 16 IACUC)
- SOP-PHARM-001: Pharmaceutical handling and dispensing
- SOP-DATA-001: Data capture and review per doc 14

**Locked at M6.** No interventional procedure runs until relevant SOP locked.

## 15.5 CAPA (Corrective and Preventive Action)

CAPA triggers:
- Any deviation (Level 1, 2, 3)
- Any adverse event Grade 1+
- Any audit finding
- Any complaint
- Any near-miss

CAPA workflow:
1. Trigger logged in eQMS within 24 hours
2. Investigation assigned (Head of QA + relevant function head)
3. Root-cause analysis (5-Why, Fishbone, or formal RCA depending on severity)
4. Corrective action proposed
5. Preventive action proposed
6. Effectiveness check defined (timeline, metric)
7. Implementation
8. Effectiveness verification at defined timeline
9. Closure with sign-off

**Open CAPA aging tracked monthly.** Stale CAPAs >90 days escalate to LID.

## 15.6 Deviation Management

**Planned deviation:** Pre-approved variance from SOP (rare; requires Head of QA + CMO if clinical + S&S Committee if Principal-impacting). Documented in eQMS pre-occurrence.

**Unplanned deviation:** Logged within 24 hours. Categorized:
- **Critical:** Patient/Principal safety impact, data integrity, regulatory compliance — immediate CMO + CSO + GC notification; mandatory CAPA
- **Major:** Process integrity impact — CAPA required
- **Minor:** Documentation or procedure variation without integrity impact — root cause and trend analysis

**Deviation rate** is operational KPI (doc 08 §8.5: <0.5 per active intervention day).

## 15.7 Change Control

(See doc 17 BCP for crisis-mode change control; this is steady-state.)

Any change to:
- Approved SOPs / WIs
- Validated systems (eQMS, EDC, eCRF)
- Approved suppliers
- Personnel role definitions affecting QA-critical activities
- Facilities affecting Tier-Red enclave

...requires change request in eQMS with:
1. Change description and rationale
2. Risk assessment (ISO 14971 / ICH Q9)
3. Impact assessment (training, documents, vendor agreements, regulatory submissions)
4. Approval workflow (Head of QA + relevant function head; CMO if clinical; CEO if cross-functional; Board if affecting gate criteria; **EEC if affecting enumerated-list interventions**)
5. Implementation plan
6. Effectiveness check
7. Closure

**Protocol amendment process** (doc 11 SOP):
- Mid-pilot biomarker-driven amendment workflow defined here
- SOP author drafts amendment with rationale
- Statistical impact assessed by Head of Biostat (does it require SAP modification? EEP approval?)
- Safety impact assessed by CMO + Science & Safety Committee
- Ethical impact assessed (EEC if enumerated-list)
- Re-consent assessment (is procedure-specific consent still valid?)
- Pre-registration update on public registry
- Amendment versioned and traced back to original

## 15.8 Training Management

**Training matrix:** maps each role to required SOP / WI / awareness-level training.

**Day-1 onboarding:**
- DEFINITIONS.md acknowledgment (mandatory all Manager+)
- Quality Manual (Level 0)
- Relevant SOPs (Level 1) for role
- DTSA-compliant trade-secret training
- OFAC/EAR/BIS export-controls screening (relevant roles)
- Privacy and data classification
- Security awareness
- Counter-intelligence awareness (Tier-Red access roles)
- Whistleblower channel awareness

**Ongoing:**
- SOP change triggers re-training within 30 days
- Annual refresher on Quality Manual + Security + Privacy
- Biennial role-specific refresher

**Compliance tracking:** Operational KPI; target 100% with overdue flagging (doc 08 §8.5).

## 15.9 Internal Audit Program

**Internal audits performed by:**
- Head of QA + cross-functional auditor (rotation)
- External auditor annually (Big-4 Life Sciences)

**Audit schedule:**
- Quarterly: rolling SOP compliance + deviation trend review
- Semi-annual: CAPA effectiveness + supplier qualification
- Annual: full QMS audit + GxP convergence review
- Per gate (G1–G7): pre-gate audit prepares EEP report

**Findings categorized:**
- Critical (immediate action; LID notification)
- Major (CAPA within 30 days)
- Minor (CAPA within 90 days)
- Observation (no CAPA required; trend tracking)

**Audit findings KPI:** target <3 medium, 0 high per annual external audit (doc 08 §8.5).

## 15.10 Supplier Qualification

Per vendor tier (doc 14 §14.8):

| Tier | Qualification Requirements |
|---|---|
| V1 (no Principal data, no Tier-Red proximity) | Standard MNDA + basic compliance attestation |
| V2 (de-identified Principal data, clinical-adjacent) | SOC 2 Type II + supply-chain attestation + named-individual NDAs + annual on-site audit + Quality Agreement |
| V3 (identified Principal data or Tier-Red proximity) | Full personnel TS-equivalent vetting + FOCI review + contractual right of CI investigation + no subcontracting without written consent + on-site audit pre-approval and biennial |

Quality Agreements (QAs) executed pre-engagement for V2 and V3.

**Supplier Performance Reviews:** semi-annual; non-conformances tracked; corrective actions enforced.

## 15.11 Risk Management

**ISO 14971 / ICH Q9 risk framework** applied at:
- Product/protocol level (each intervention)
- Process level (clinical, lab, IT, manufacturing)
- System level (entire QMS)

Risk matrix: probability × severity × detectability.

Risk control hierarchy:
1. Inherent safety by design (eliminate hazard)
2. Protective measures (mitigate hazard)
3. Information for safety (warnings, training)

**Risk-benefit analysis** documented for every interventional protocol; reviewed by Science & Safety Committee for binding pre-clearance.

## 15.12 Complaint Handling

Sources:
- Principal subjective reports (daily SOP §11.6)
- Staff escalations (whistleblower channel doc 07 + line manager)
- External regulator inquiry
- Spinout customer complaints (where applicable)

Triage:
- Critical (Principal safety, regulatory violation, data integrity): immediate CMO + CSO + GC + LID
- Major (process integrity): CAPA workflow
- Minor: trend tracking

**Mandatory escalation per doc 06 §6.7 whistleblower categories:**
- Pressure to soften gate criteria
- Principal-care decision over CMO objection
- AE documentation delay/omission
- Conflict-of-interest violation
- Data integrity concern

## 15.13 Annual Management Review

Annually:
- Head of QA prepares Management Review package
- CEO + LID + CMO + CSO + relevant heads attend
- Review topics:
  - QMS effectiveness (audit findings, CAPA closure, deviation trends, complaint volume)
  - Customer/Principal satisfaction
  - Process performance and product conformity
  - Status of preventive and corrective actions
  - Follow-up from previous Management Reviews
  - Changes affecting QMS
  - Improvement recommendations

Output: documented improvement actions, resource allocations, QMS objectives for next year.

Annual Management Review report shared with EEC + EEP + Board.

## 15.14 Phase Transition QMS Implications

At each gate (G1–G7):
- QMS scope re-evaluated for next phase
- New SOPs authored for new interventions
- Existing SOPs reviewed against new context
- Training matrix updated
- Supplier list refreshed
- Internal audit performed pre-gate
- Management Review specific to gate

**Phase 0 → Phase 1 QMS expansion:** add GMP cell therapy SOPs (autologous mito), AAV vector handling, NHP cohort full IND-enabling QMS, mAb pharmaceutical handling (bimagrumab/garetosmab), mRNA-LNP handling (Cao 2024 protocol).

---

## 15.15 QMS Maturity Levels

The program targets:

- **Phase 0:** Level 2 (Defined) — SOPs documented and followed
- **Phase 1:** Level 3 (Managed) — Quantitative process management; data-driven CAPA
- **Phase 2:** Level 4 (Predictable) — Predictive risk management; supplier integration
- **Phase 3+:** Level 5 (Optimizing) — Continuous improvement institutionalized

Each maturity step is a precondition for the next phase's gate.

---

**Status:** QMS v1.0 — to be operationalized upon eQMS deployment (M3 interim, M6 full handoff to Head of QA).
