# 10 — Technical Roadmap (v1.1, Post-SAB Review)

**Pre-read:** [DEFINITIONS.md](./DEFINITIONS.md) — operational target.

## 10.1 Overview

This document defines the **scientific and engineering work** per phase. Each item is tagged with bucket (GREEN/YELLOW/ORANGE), owner, dependencies, deliverable, failure mode.

**v1.1 revisions:** (a) mAb-first replaces AAV-first for myostatin work; (b) mRNA-LNP OSK replaces AAV-OSK as first-line reprogramming; (c) NHP cohort added (Charles River) — canine reserved for chronic small-molecule + TPE only; (d) Klotho fragment KL1 sub-Q replaces full-length AAV-Klotho; (e) acarbose, canagliflozin, weekly low-dose rapamycin, microdose tirzepatide added to GREEN; (f) HBOT de-escalated to 3×/wk @ 1.5 ATA; (g) D+Q senolytic gated to single-cycle first with pleural ultrasound; (h) NMN dropped, NR substituted.

---

## 10.2 Phase 0: Foundation (Months 0–18)

### Workstream 0.1 — Comprehensive Baselining

**Bucket:** GREEN
**Owner:** CMO
**Dependencies:** Principal availability, lab capacity
**Deliverable:** Most thoroughly characterized human phenotype in published history; ~50 TB structured data; locked dataset for KPI pre/post.

Sub-tasks (v1.0 list plus):
- **Sperm cryopreservation** (mandatory pre-Phase-0 before gonadotoxic interventions)
- **Anti-AAV neutralizing antibody panel** (multi-serotype, gates Phase 1)
- **Baseline vaccine challenge** (Tdap + zoster — establishes K9 immune trajectory)
- **Baseline OGTT + Matsuda + 14-day CGM under structured exercise** (K10)
- **In-home PSG 7 nights** (K11)
- **Baseline IIEF + structured psychiatric battery** (SCID-5, Y-BOCS, AUDIT, hypomania, MLQ)

**Failure mode:** Logistics complexity delays baseline beyond M5. Mitigation: pre-arrange all vendors during M0–M2 (per A3 with deposit-funded slot reservations); PMO tracks on critical path.

### Workstream 0.2 — Tier 1 Interventional Protocol (Lifestyle + Pharma, GREEN)

**Bucket:** GREEN
**Owner:** CMO + PI-Performance
**Dependencies:** Baseline complete; EEC + Ethics Council + S&S Cmte approval
**Deliverable:** Documented 12-week Tier 1 with biomarker delta vs baseline.

Components (per doc 02 v1.1 GREEN bucket):
- Polarized training (Seiler protocol; 80/20 Z2/Z5)
- Heat acclimation (sauna)
- Intermittent hypoxia training (altitude tent + FiO₂ 0.13 sessions)
- Periodized diet
- Cyclic FMD (Longo, 5 days every 3 months)
- Sleep optimization (CBT-i + light/temp/CO₂ control)
- **Supplement stack: creatine, urolithin A, NR (not NMN), MitoQ, omega-3, vit D, mag glycinate, glycine, melatonin micro-dose**
- **Acarbose 100mg TID** (per SAB — ITP-positive, decades of safety data)
- **Canagliflozin 100mg daily** (per SAB — CV mortality benefit, non-diabetics)
- **Weekly low-dose rapamycin** (PEARL protocol; immune rejuvenation)
- Endocrine: physiological-range TRT only if clinically indicated
- **Microdose tirzepatide** (sub-anti-obesity dose, muscle-sparing with resistance training pair)

**Failure mode:** Principal cannot adhere. Mitigation: concierge medical model; protocol adapted; minimum effective dose first.

### Workstream 0.3 — Tier 2 (Senolytic single-cycle + capped TPE, GREEN — gated)

**Bucket:** GREEN with gates
**Owner:** CMO + PI-Reprogramming + S&S Committee (binding pre-clearance)
**Deliverable:** Senolytic single-cycle + 4 TPE sessions; biomarker response measured.

Components (revised per SAB):
- **D+Q single cycle** (100mg dasatinib + 1000mg quercetin × 3 consecutive days) — NOT monthly. **Pleural ultrasound at 14 days** before any further cycle consideration. 90-day washout minimum.
- **Fisetin single cycle** (1500mg × 2 consecutive days) alternating after washout
- **TPE: 4 sessions total in Phase 0** (was weekly × 4 + maintenance Q6M; capped per SAB feedback). Pre-cycle: IgG, B-cell repertoire baseline. Post: 4h observation per session.
- Post-each-cycle biomarker panel (full Olink + Metabolon + senescence-associated panel β-gal, p16, SASP)

**Failure mode:** Grade 2+ AE — hard stop per recalibrated rules. Mitigation: SOP stop rules (doc 11); dose-reduction NOT available without re-approval cycle; halt Tier 2 only, continue Tier 1.

### Workstream 0.4 — Tier 3 (Microbiome + Mitochondrial Substrate, GREEN)

**Bucket:** GREEN
**Owner:** PI-Performance + CMO + S&S
**Deliverable:** FMT engraftment confirmed; mitochondrial substrate optimization quantified.

Components: per v1.0, plus
- **³¹P-MRS in vivo for PCr recovery kinetics** as non-invasive functional mitochondrial readout

### Workstream 0.5 — Tier 4 (Cognitive + Recovery, GREEN)

**Bucket:** GREEN
**Owner:** CMO + S&S
**Deliverable:** Cognitive z-score improvement; HBOT course completed.

Components (revised per SAB):
- Daily tDCS (anodal F3, 2mA × 20 min + cognitive training pair)
- TMR during sleep
- **HBOT 3×/wk × 8wk @ 1.5 ATA** (de-escalated from 5×/wk @ 2.0 ATA; pulmonary function panels weeks 0/4/8)
- Photobiomodulation full-body

### Workstream 0.6 — Shadow NHP + Canine Cohorts

**Bucket:** GREEN (animal work, IACUC framework doc 16)
**Owner:** PI-Reprogramming + contracted CRO
**Dependencies:** Lab operational M6; IACUC charter executed M5; CRO contract M4
**Deliverable:**
- **NHP cohort (Charles River, BIOQUAL, or Bioneeds India) — 6 cynomolgus minimum** for AAV gene-therapy IND-enabling work (per SAB; canine was inadequate)
- **Canine cohort (n=12)** for chronic small-molecule + TPE PK/safety only

Note: NHP cohort is **prerequisite** for any AAV vector Principal administration in Phase 1. Cost: ~$400K Phase 0 down payment + $14M Phase 1 full IND-enabling.

**Failure mode:** Adverse signal in NHPs not predicted from prior literature. Mitigation: this is exactly why we run the cohort; halt Principal escalation if NHPs show issue.

### Workstream 0.7 — Phase 1 R&D Prep (mRNA-LNP + mAb characterization)

**Bucket:** YELLOW prep
**Owner:** CSO interim + PI-Reprogramming (to be augmented by PI-Gene Therapy Phase 1)
**Deliverable:**
- mRNA-LNP OSK characterization in cell culture and dose-finding NHP
- **Bimagrumab/garetosmab characterization** + license discussions with Versanis (or successor)
- Klotho fragment KL1 production characterization

### Workstream 0.8 — Computational Infrastructure

**Bucket:** GREEN
**Owner:** CSO + Head of Biostat + PMO
**Deliverable:** Data pipeline ingesting Principal data (wearables, labs, imaging) into unified data model; ML training environment; secure analyst access.

**Critical per SAB:** Data Management Plan (doc 14) is foundational. Tier-Red enclave architecture (doc 07 §7.6) physically separates Principal-identifiable data.

### Workstream 0.9 — Spinout Formation

**Bucket:** GREEN (operational)
**Owner:** CFO + GC
**Deliverable:** 8 spinouts incorporated (per doc 09 v1.1 expanded portfolio); at least one with Series A term sheet by M16, closed by M18.

---

## 10.3 Phase 1: Foundation Build (Months 18–36)

### Workstream 1.1 — Myostatin/ActRII Modulation (mAb-First, AAV Escalation)

**Bucket:** YELLOW (mAb), AAV demoted to escalation path
**Owner:** PI-Gene Therapy (hired M18) + PI-Performance
**Dependencies:** NHP 24-month safety data; Phase 0 success on relevant KPIs

**v1.1 critical change per SAB:**
- **Bimagrumab (anti-ActRII mAb) administered first** — reversible, Phase 2/3 safety data exists (Rooks 2020). 12 months of bimagrumab to characterize Principal response.
- **Garetosmab (anti-activin A mAb)** as adjunct if bimagrumab alone insufficient.
- **AAV-FS344 or AAV-MSTN only escalated to** if mAb fails AND NHP 24-month data clean AND EEC binding pre-approval.

Risks: erythrocytosis (manageable), cardiac hypertrophy (quarterly cardiac MRI), tendon stiffening (Mendias 2008 — known myostatin pathway risk). Doses calibrated to sub-Bhasin-1996 equivalent on first administration.

### Workstream 1.2 — Partial Reprogramming (mRNA-LNP First)

**Bucket:** YELLOW
**Owner:** PI-Reprogramming
**Dependencies:** External human Phase 1 readout (Altos/Retro/NewLimit) OR program NHP 24-month data

**v1.1 critical change per SAB:**
- **mRNA-LNP OSK (Cao 2024) is first-line.** Transient delivery, no integration, dose-tunable, stoppable.
- **AAV-OSK with Tet-off system demoted to escalation path** — only if mRNA-LNP shows insufficient signal.

Multiple cycles over 6-month window. Tissue-restricted initially (skeletal muscle, skin).

**Failure mode:** No methylation reset at tolerable doses. Mitigation: pivot to alternative factor cocktail (e.g., 7F from Sebastiano) or chemical reprogramming (Yang 2023).

### Workstream 1.3 — Mitochondrial Transplantation (Autologous)

**Bucket:** YELLOW
**Owner:** PI-Bioenergetics
**Dependencies:** Autologous source tissue harvested; GMP-equivalent enrichment

**v1.1 falsification plan strengthened per SAB:**
- Pre-specified ≥3 biopsy sites (mitochondrial heterogeneity within vastus lateralis is large)
- **mtDNA heteroplasmy tracking** via deliberate isotope labeling (¹⁵N pulse-chase or MitoTracker-stable analog) — distinguishes engraftment from paracrine
- Respirometry on **permeabilized fibers (Pesta/Gnaiger protocol)** with explicit OXPHOS coupling control ratios — NOT isolated mito
- **³¹P-MRS in vivo** for PCr recovery kinetics

Without these, "transplantation success" cannot be distinguished from "expensive growth factor injection."

### Workstream 1.4 — Senex Phase 2 Equivalent

**Bucket:** GREEN, scaled
**Owner:** PI-Reprogramming + CMO
**Deliverable:** Senex runs Phase 2 in healthy aging cohort (n=30–50); program licenses protocol and reciprocally provides Principal data.

### Workstream 1.5 — Klotho Fragment KL1 (Sub-Q peptide)

**Bucket:** YELLOW
**Owner:** PI-Bioenergetics
**Dependencies:** External Phase 1 readout

**v1.1 change per SAB:** Castner 2023 *Nat Aging* KL1 fragment sub-Q replaces full-length AAV-Klotho. Avoids phosphate-handling risks (vascular calcification) of full-length.

Cognitive outcome + CSF klotho measurement. Conservative dose. Reversible.

### Workstream 1.6 — Augmentation Suite Build (Phase 2 Prep)

**Bucket:** ORANGE (build Phase 1, operate Phase 2)
**Owner:** COO + Engineering team
**Deliverable:** 5 m short-arm human centrifuge ordered; hypobaric chamber site prepared; BCI lab build begun.

### Workstream 1.7 — Plasma Fraction E5 / PPF (NEW)

**Bucket:** YELLOW
**Owner:** CMO + PI-Reprogramming
**Dependencies:** Grifols Phase 2 readout
**Deliverable:** Plasma fraction E5 (Alkahest/Grifols approach, more targeted than full TPE) integrated as Principal protocol if Phase 2 cleanly readouts.

---

## 10.4 Phase 2: Integration (Months 36–60)

| Workstream | Topic | Bucket |
|---|---|---|
| 2.1 | Augmentation Suite operations (2–3G centrifuge chronic + 5–10G pulses; intermittent hypobaric; BCI integration) | ORANGE |
| 2.2 | Commercial BCI implantation (Neuralink, Synchron, or successor) — Principal travels to cleared jurisdiction | YELLOW |
| 2.3 | Iterative reprogramming optimization (chronic low-dose mRNA-LNP OSK Q3M) | YELLOW |
| 2.4 | Mitochondrial density escalation (multiple rounds autologous mito + 3D microscopy of biopsies) | YELLOW |
| 2.5 | Bioelectric field optimization (Phase 3 prep via Levin lab collaboration) | ORANGE |
| 2.6 | Tardigrade Dsup pilot (animal only — Phase 1 mouse, Phase 2 primate); Principal candidacy gated on EEC and clean mouse+primate data | YELLOW |
| 2.7 | Plasma fraction chronic | YELLOW |

---

## 10.5 Phase 3: Extension (Years 5–10)

Major capital deployment. Subject to separate Board + EEC reauthorization at Phase 2 gate.

| WS | Topic | Bucket | EEC binding-veto pre-approval required |
|---|---|---|---|
| 3.1 | Subdermal dermal mesh (graphene + spider silk) | ORANGE | Yes |
| 3.2 | Engineered limb regeneration (BioDome scaled to mammalian primate; Levin) | ORANGE | Yes |
| 3.3 | Subdermal electric organ (eel electroplaque) — animal first, then maybe Principal | ORANGE | Yes |
| 3.4 | Cybernetic reflex augmentation (epidural spinal stim) | ORANGE | Yes |
| 3.5 | Xenotransplantation if specific organ indication (FDA-cleared US center) | YELLOW now | Yes |
| 3.6 | Dsup transgene in Principal — only if mouse + primate data clean | ORANGE | Yes |
| 3.7 | Subdermal RTG power source — engineering R&D only (not yet implanted) | ORANGE | Yes when implant |
| 3.8 | Directed energy emitter — wearable first, subdermal much later | ORANGE | Yes when subdermal |
| 3.9 | Compact fusion research investment | ORANGE/RED | N/A (research only) |

---

## 10.6 Phase 4: Frontier (Years 10–15)

Subject to extensive Phase 3 review.

Plausibly:
- Subdermal nuclear power (if regulatory + supply path opens — Pu-238 acquisition is foreign-policy problem per doc 07)
- Subdermal directed energy emitter (if power available)
- Engineered HMM-HA transgene (cancer resistance) — only if all prior cancer-pathway safety data clean
- Substantial cybernetic substitution (if clinically indicated or strongly preferred)
- Bioelectric morphogenetic field engineering (if Levin program matures)
- Vehicle-mounted directed energy (defense partnership via Atlas-Defense spinout)

OR Phase 4 may be cancelled if Phase 3 outcomes don't justify further escalation.

---

## 10.7 Cross-Phase Dependencies

```
Phase 0 KPI hit ≥6/11  ──►  Phase 1 authorization
Phase 1 success          ──►  Phase 2 authorization (5× on at least 3 KPIs revised threshold)
Phase 2 success          ──►  Phase 3 authorization (separate Board + EEC vote; external bioethics panel)
Phase 3 success          ──►  Phase 4 authorization (unanimous Board + 8/9 SAB + EEC + ext. bioethics + Principal medical counsel)
```

---

## 10.8 Research Topics Monitored But Not Funded (RED + Frontier)

Quarterly literature review by CSO + 1 SAB member + 1 EEC member:

- Casimir / DCE engineering
- Schwinger pair production feasibility
- LENR replication attempts (post-Berlinguette 2019)
- Macroscopic quantum coherence (Bandyopadhyay, Reimers continuations)
- Antimatter production cost trajectory
- Compact fusion progress (Helion, SPARC, TAE)
- Whole-brain emulation roadmap
- ASC vitrification outcomes
- Heterologous mito ethics (likely permanent RED)

If any become engineering-ready, SAB convenes within 30 days to consider program incorporation. EEC binding veto applies to any inclusion.

---

## 10.9 Decision Authority Per Workstream

CSO: day-to-day technical direction within phase. **S&S Committee: binding pre-clearance on first-in-Principal interventions and Tier 2+ initiations.** EEC: binding veto on enumerated list. SAB: cross-phase pivots advisory. Board: phase transitions. **Principal: anything done to Principal's body.**

Detailed RACI in doc 01.

---

**Status:** Roadmap v1.1 (post-SAB) — phase-gated re-baselining each transition.
