# 11 — Pilot Subject Protocol (Standard Operating Procedure)

## SOP — Conduct of Phase 0 Interventions on the Principal

**Document classification:** Privileged — for CMO, treating physicians, Principal, GC only.
**Effective:** Upon CMO countersignature + Ethics Council approval.
**Review cadence:** Bi-monthly during Phase 0.

---

## 11.1 Subject Definition

The Principal is:
- An adult, mentally competent individual
- The funder of and primary subject of Project PROMETHEUS
- Recipient of all interventions described herein
- The sole party with veto authority over any procedure on their own body

The Principal has been informed, in writing and via independent counsel, of:
- The investigational nature of all Phase 0 interventions
- The off-label nature of pharmacological combinations
- The right to withdraw at any time without penalty
- The possibility of adverse events including death, although low-probability

## 11.2 The Treating Team

The Principal's care is delivered by a defined team. No other party may administer any program-related intervention.

| Role | Function | Backup |
|---|---|---|
| **CMO (lead)** | Authority on all care; signs all orders | Associate CMO #1 |
| **Internist** | Day-to-day clinical; on-call 24/7 | Internist #2 |
| **Cardiologist** | Cardiac monitoring; clearance for any cardiovascular-relevant intervention | External consultant |
| **Endocrinologist** | Hormone protocols | External consultant |
| **Pharmacist (clinical)** | Drug dispensing; drug interaction review | Backup pharmacist |
| **Nurse practitioners (2)** | Bedside care; phlebotomy; vital signs | n/a |
| **Phlebotomist** | Blood draws | Backup |
| **Anesthesiologist (on-call)** | Any sedated procedure | External center |
| **Medical concierge** | Coordination, Principal liaison | n/a |

24/7/365 coverage required during any active intervention cycle. No solo coverage of the Principal during 48 hours post any novel intervention.

## 11.3 Consent Process

### Master Consent (signed once per phase)

- Plain-language description of phase objectives
- All anticipated interventions listed with citations
- Right to withdraw at any time
- Independent counsel signature certifying explanation

### Procedure-Specific Consent (signed pre-each intervention)

- Specific intervention name, dose, route
- Citations to evidence base
- Specific risks, with quantified probabilities where known
- Specific alternatives, including "do nothing"
- 14-day cooling-off period from signing to administration for any first-time intervention
- 24-hour cooling-off for repeat interventions

### Data Use Consent (annual)

- Authorizes use of Principal's de-identified data for spinout commercial purposes
- Authorizes use of identified data only for medical care + Board-approved purposes

### Advance Directive (updated quarterly)

- Care preferences in event of incapacitation
- Specific authorization (or refusal) for program to continue procedures if Principal cognitively impaired
- Designated medical proxy
- Cryopreservation / posthumous data use directives

## 11.4 Intervention Approval Workflow

For **any** intervention performed on the Principal, the following workflow is mandatory:

```
1. PI proposes intervention to CSO + CMO (written protocol)
2. CMO + CSO review for safety and scientific merit
3. If new intervention class: Ethics Council review (≤30 days)
4. If approved: Procedure-Specific Consent drafted by GC + CMO
5. Principal reviews with independent counsel
6. Cooling-off period (14 days first-time; 24 hours repeat)
7. Day-of-procedure: pre-procedure medical clearance
8. Procedure performed by named treating team
9. Post-procedure monitoring per protocol (minimum 24 hours observed)
10. Data captured to EMR + program database
11. Adverse event monitoring per CTCAE v5
12. Follow-up labs + clinical at 24h, 72h, 1 wk, 4 wk minimum
```

No step may be skipped or compressed without written CMO + GC + Principal sign-off.

## 11.5 Stop Rules

The Principal's intervention is **immediately halted**, and the CMO convenes an emergency review, if **any** of the following occur:

### Hard Stops (irreversible halt pending full review)

- **Death or imminent life threat** (any cause; obvious)
- **Grade 4 adverse event** (CTCAE v5: life-threatening, urgent intervention indicated)
- **New diagnosis of malignancy** (any stage, any tissue)
- **Cardiac arrest, MI, stroke, or significant arrhythmia**
- **Liver failure** (ALT/AST >10× ULN OR INR >2 OR clinical jaundice with bilirubin >3 mg/dL)
- **Acute kidney injury** (creatinine >2× baseline OR oliguria <0.5 mL/kg/hr × 6h)
- **Anaphylaxis or severe allergic reaction**
- **Principal request to stop** (for any reason; no override)

### Soft Stops (pause + 72-hour review)

- **Grade 3 adverse event** (severe but not life-threatening)
- **Hematocrit >55%** sustained (erythrocytosis risk)
- **Liver enzymes 3–10× ULN**
- **Creatinine 1.5–2× baseline**
- **New cardiac structural change on imaging**
- **New persistent symptom** (headache >1 week, fatigue >2 weeks, mood change, etc.)
- **Principal's subjective severe distress** (no override; Principal's call)
- **CMO clinical concern** (no override)

### Procedural Stops (re-confirm before continuing)

- **Any unplanned hospitalization**
- **Any new prescription medication**
- **Any new diagnosis (non-cancer, non-organ-failure)**
- **Significant life event affecting Principal's adherence capacity**

### Restart Criteria

After a hard stop: full external SAB review + Ethics Council re-approval + Principal re-consent + 30-day cooling-off minimum.

After a soft stop: CMO + CSO review + Principal re-consent + 7-day cooling-off minimum.

After a procedural stop: CMO + Principal review only.

## 11.6 Monitoring Schedule

### Daily (during active intervention cycles)

- Wearable data review (HRV, sleep, glucose, activity)
- Subjective rating scales (mood, energy, libido, sleep, soreness — 1–10 scale)
- Any new symptoms reported

### Weekly

- Targeted bloods (CBC, BMP, liver, lipid; ESR/CRP if relevant)
- Clinical visit (in-person or telehealth)
- Treating team huddle

### Biweekly

- Comprehensive metabolic panel; hormones (T, GH/IGF-1, T3/T4/TSH, cortisol)
- Pharmacokinetic samples for novel drugs

### Monthly

- Full Olink panel
- Methylation age (subset of clocks)
- Cardiac monitoring (ECG; echo Q3M)
- Mental status (PHQ-9, GAD-7)
- Performance benchmarks (subset of K1–K8)

### Quarterly

- Full multi-omic re-run (~$300K each)
- Comprehensive imaging (whole-body MRI + cardiac)
- Full neuropsych
- Body composition (DEXA + ADP)
- Performance benchmarks (full K1–K8)
- Muscle biopsy (if any AAV / mitochondrial intervention active)

### Annually

- Full physical
- Cancer screening (low-dose CT chest, colonoscopy if age ≥45, derm, MRI prostate)
- Refreshed advance directive
- Independent SAB review

## 11.7 Data Capture

Every clinical interaction generates:
- EMR entry (timestamped, locked, audit-trailed)
- Program database entry (linked to EMR)
- Lab data automatically ingested via HL7 / FHIR
- Wearable data ingested via vendor APIs (encrypted at rest)

Data quality control: PMO audits randomly selected records monthly.

## 11.8 Adverse Event Reporting

Per CTCAE v5 grading. Reporting hierarchy:

- **Grade 1 (mild):** Documented; reviewed at weekly treating team huddle
- **Grade 2 (moderate):** Documented; reviewed at CMO daily standup; CSO informed
- **Grade 3 (severe):** Soft stop activated; CMO + CSO + GC notified within 1 hour; Board within 24 hours
- **Grade 4 (life-threatening):** Hard stop; CMO + CEO + Principal + Board within 1 hour; crisis comms activated; external regulatory counsel notified
- **Grade 5 (death):** Hard stop; full crisis protocol

All Grade 2+ events trigger an Adverse Event Report due to Ethics Council within 7 days. Cumulative reports issued quarterly.

## 11.9 Drug-Specific SOPs (Tier 1–2 Examples)

### Senolytic — Dasatinib + Quercetin

**Indication:** Senolytic cycling per Kirkland protocol
**Dose:** Dasatinib 100mg + Quercetin 1000mg PO × 3 consecutive days
**Frequency:** Initial: monthly × 3. Maintenance: Q3M.
**Pre-administration:**
- CBC, BMP, liver panel within 7 days
- Cardiac assessment (ECG; echo if any concern)
- Hold if QTc >450 ms, platelets <100K, ANC <1500
**During administration:**
- Vital signs Q4h
- Symptom monitoring
**Post-administration:**
- Repeat CBC + BMP + liver at 48h, 7d
- Senescence-associated biomarker panel at 14d (β-gal, p16, SASP cytokines)
**Adverse event surveillance:**
- Thrombocytopenia (Grade 1: continue; Grade 2: hold next dose; Grade 3+: hard stop dasatinib)
- Pleural effusion (any: hold)
- QTc prolongation (>500 ms: hold)

### Therapeutic Plasma Exchange

**Indication:** Plasma factor dilution per Conboy / Mehdipour rationale
**Procedure:** 1.0 plasma volume exchange with 5% albumin replacement
**Frequency:** Initial: weekly × 4. Maintenance: Q6M.
**Pre-procedure:**
- CBC, BMP, calcium, magnesium within 24h
- IgG level (replace if dropping)
- Central line placement (if not in place)
**During procedure:**
- Continuous cardiac monitoring
- Citrate symptom monitoring (replace calcium PRN)
- 1:1 nursing
**Post-procedure:**
- 4h observation
- Same-day discharge from clinical suite
**Adverse event surveillance:**
- Citrate toxicity (paresthesia, perioral numbness): treat with IV calcium
- Allergic reaction to albumin (rare): treat per anaphylaxis protocol
- Hypotension: IV fluid, monitor

### Hyperbaric Oxygen Therapy

**Indication:** Cognitive + recovery enhancement per Hachmo protocol
**Procedure:** 90 min @ 2.0 ATA, 100% O₂ via mask
**Frequency:** 5×/week × 8 weeks
**Pre-protocol:**
- Pulmonary function test (rule out trapped gas)
- ENT clearance (Eustachian function)
- Ophthalmology (rule out refractive change risk awareness)
**During:**
- Vital signs continuous via in-chamber monitoring
- Communication via intercom
**Adverse event surveillance:**
- Otic barotrauma (most common; ENT review if persistent)
- Refractive change (transient; informed consent)
- Pulmonary O₂ toxicity (rare at 2.0 ATA; monitor)
- Seizure (extremely rare at 2.0 ATA)

(Complete SOPs for all 12 GREEN-bucket interventions in `appendices/A2_drug_sops/`.)

## 11.10 Emergency Protocols

### On-Site Code Blue

- Crash cart at Próspera clinical suite; in-suite 24/7 during active intervention
- ACLS-certified personnel on-site 24/7 during active intervention
- AED + defibrillator
- Intubation tray; emergency drugs
- Direct line to local ICU (Próspera has tertiary care contract)

### Medical Evacuation

- Pre-arranged medevac to Roatán hospital + onward to Miami if needed
- 24/7 dispatch contact at concierge
- Insurance pre-cleared
- Principal's medical records portable via encrypted device

### Mental Health Emergency

- On-call psychiatrist available within 4 hours
- Hospital-level psychiatric care available off-island; medevac contract covers

### Security Emergency (parallel to medical)

- CSecO co-located during high-risk interventions
- Secure transport prearranged
- Backup secure location identified

## 11.11 Documentation Requirements

Every encounter, every procedure, every decision documented:
- Time stamp
- Personnel present
- Procedure details (drug, dose, route, technique)
- Vital signs (continuous where applicable)
- Adverse events (any grade)
- Principal subjective report
- Plan + follow-up

Documents reviewed monthly by external auditor (independent of program staff). Discrepancies investigated.

## 11.12 Annual Independent Audit

An external auditor (qualified MD-MPH or equivalent, not affiliated with program) reviews annually:
- Adverse event tracking
- Consent documentation
- Stop rule adherence
- Protocol deviations
- Outcomes vs documented protocols

Audit findings reported to Board + Ethics Council. Findings of Material Deviation trigger Board review of the CMO.

---

**Status:** Phase 0 SOP v1.0 — to be countersigned by inbound CMO and approved by Ethics Council before any intervention administered.

**Critical commitment:** No deviation from this SOP, however well-intentioned, is acceptable. The integrity of the program depends on it.
