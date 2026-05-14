# 10 — Technical Roadmap

## 10.1 Overview

This document defines the **scientific and engineering work** to be performed in each phase. Each item is tagged with:
- **Bucket** (GREEN / YELLOW / ORANGE) from doc 02
- **Owner** (PI or function)
- **Dependencies** (what must come first)
- **Deliverable** (what success looks like)
- **Failure mode** (how it dies and what we do then)

---

## 10.2 Phase 0: Foundation (Months 0–18)

### Workstream 0.1 — Comprehensive Baselining

**Bucket:** GREEN
**Owner:** CMO
**Dependencies:** Principal availability, lab capacity
**Deliverable:** The most thoroughly characterized human phenotype in published history; ~50 TB of structured data; locked dataset for KPI pre/post comparison.

Sub-tasks:
- WGS 30× (germline + somatic) — vendors: Illumina NovaSeq via Veritas or BGI
- Whole exome on multiple tissues — vendor: Twist or Agilent capture, sequenced in-house Phase 1+
- Methylome (450K + targeted) — vendor: TruDiagnostic + custom Twist panel
- Proteome (Olink Explore 3072) — vendor: Olink
- Metabolome (Metabolon HD4) + Lipidome — vendor: Metabolon
- Microbiome shotgun (gut, oral, skin) — vendor: uBiome successor (Microba, etc.)
- Whole-body MRI 7T — partner: Harvard MRI center or Stanford
- Cardiac MRI + stress + echo — partner: Mass General or equivalent
- Brain MRI (multimodal) — same partner as above
- DEXA, ADP, CT bone — vendor: standard radiology
- VO₂max, Wingate, isokinetic — in-house clinical suite
- Continuous monitoring: Whoop, Oura, Apple Watch, Polar, Levels (CGM) — redundant
- Neuropsych battery — vendor: Cogstate, CANTAB
- Sleep PSG — in-home

**Failure mode:** Logistics complexity delays baseline beyond M5. Mitigation: pre-arrange all vendors during M1–M2; PMO tracks each test on critical path.

### Workstream 0.2 — Tier 1 Interventional Protocol (Lifestyle + Pharma)

**Bucket:** GREEN
**Owner:** CMO + PI-Performance
**Dependencies:** Baseline complete; Ethics Council approval
**Deliverable:** Documented 12-week Tier 1 intervention with biomarker delta vs baseline.

Components:
- Polarized training program (Seiler protocol; 80/20 Z2/Z5)
- Heat acclimation (sauna protocol; Hannuksela & Ellahham reviews)
- Intermittent hypoxia (IHT; altitude tent + sessions at FiO₂ 0.13)
- Diet (periodized; target macros calibrated to training load)
- Cyclic FMD (Longo protocol; 5 days every 3 months)
- Sleep optimization (CBT-i + behavioral + environmental)
- Supplement stack (creatine, urolithin A, NMN, MitoQ, omega-3, vit D, mag glycinate, glycine, melatonin)
- Endocrine assessment + TRT only if clinically indicated and within physiological ranges

**Failure mode:** Principal cannot adhere due to schedule. Mitigation: concierge medical model; protocol adapted to schedule; minimum effective dose first.

### Workstream 0.3 — Tier 2 Interventional Protocol (Senolytic + TPE)

**Bucket:** GREEN
**Owner:** CMO + PI-Reprogramming
**Dependencies:** Tier 1 in stable execution; clean labs M0–M6
**Deliverable:** Senolytic cycles + 4 TPE sessions completed; biomarker response measured.

Components:
- D+Q dosing: 100mg dasatinib + 1000mg quercetin × 3 consecutive days, Q monthly × 3 then Q3M
- Fisetin: 1500mg × 2 consecutive days monthly (alternates with D+Q)
- TPE: 1.0 plasma volume × 4 sessions over 8 weeks, then Q6M maintenance
- Post-each-cycle biomarker panel (full Olink + Metabolon)

**Failure mode:** Adverse event (Grade ≥2). Mitigation: SOP stop rules (doc 11); dose-reduction available; halt to Tier 2 only, continue Tier 1.

### Workstream 0.4 — Tier 3 Interventional Protocol (Microbiome + Mitochondrial Substrate)

**Bucket:** GREEN
**Owner:** PI-Performance + CMO
**Dependencies:** Tier 2 stable; donor screening complete
**Deliverable:** FMT engraftment confirmed; mitochondrial substrate optimization quantified.

Components:
- Pre-FMT abx (Cipro + Metronidazole 7 days)
- FMT from screened athlete donor (3 doses oral capsule over 3 weeks)
- Veillonella + Akkermansia maintenance probiotics
- Ketogenic adaptation (8 weeks) + cyclic
- Exogenous ketone esters pre-key sessions

**Failure mode:** Poor FMT engraftment. Mitigation: repeat with different donor; backup donor pool pre-screened.

### Workstream 0.5 — Tier 4 Interventional Protocol (Cognitive + Recovery)

**Bucket:** GREEN
**Owner:** CMO
**Dependencies:** Tier 3 stable
**Deliverable:** Cognitive z-score improvement; HBOT course completed.

Components:
- tDCS daily (anodal F3, 2mA × 20 min, paired with cog training)
- TMR during sleep (audio cues + daytime learning)
- HBOT (90 min @ 2.0 ATA, 5×/wk × 8 wk; Hachmo protocol)
- Photobiomodulation full-body

**Failure mode:** No cognitive signal. Mitigation: this is exploratory; not a KPI-essential workstream.

### Workstream 0.6 — Shadow Canine Cohort

**Bucket:** GREEN (animal work, IACUC-equivalent in Próspera)
**Owner:** PI-Reprogramming
**Dependencies:** Lab operational M6; veterinary staff hired
**Deliverable:** 12-dog cohort run Tier 1+2+3 protocols 6 months ahead of Principal; provides safety signal generalization.

Note: Dogs were chosen as a model species because (a) longer lifespan = better aging signal, (b) similar microbiome diversity, (c) ethical-and-legal compared to NHPs, (d) Próspera-Roatán hosts a veterinary research facility. Co-housing with owners during non-procedure periods is allowed (Pampered Pets model).

**Failure mode:** Adverse signal in dogs that wasn't predicted from prior literature. Mitigation: this is exactly why we run the cohort; halt Principal escalation if dogs show issue.

### Workstream 0.7 — AAV R&D (Phase 1 Prep)

**Bucket:** YELLOW (R&D in Phase 0; administration in Phase 1)
**Owner:** PI-Gene Therapy (Phase 1 hire) + CSO interim
**Dependencies:** Lab build-out; AAV vector source
**Deliverable:** Optimized AAV-MSTN and AAV-FS344 vectors characterized in cell culture and dose-finding in canine cohort.

**Failure mode:** Vector immunogenicity profile incompatible with Principal's pre-existing AAV antibodies. Mitigation: pre-screen Principal for anti-AAV titers (multiple serotypes) at baseline; if positive, plan immunomodulation or alternate serotype.

### Workstream 0.8 — Computational Infrastructure

**Bucket:** GREEN
**Owner:** CSO + PMO
**Dependencies:** Cloud or on-prem decision; security architecture
**Deliverable:** Data pipeline ingesting all Principal data (wearables, labs, imaging) into a unified data model; ML model training environment; secure analyst access.

**Failure mode:** Data silos; analysts cannot link wearable to clinical to omic. Mitigation: enforce schema-first ingest; PMO audits monthly.

### Workstream 0.9 — Spinout Formation

**Bucket:** GREEN (operational)
**Owner:** CFO + GC
**Dependencies:** First Tier 1 + Tier 2 data; IP filings
**Deliverable:** 3–4 spinouts incorporated; at least one with Series A term sheet by Month 16, closed by Month 18.

---

## 10.3 Phase 1: Foundation Build (Months 18–36)

### Workstream 1.1 — AAV Myostatin / ActRII Modulation

**Bucket:** YELLOW
**Owner:** PI-Gene Therapy
**Dependencies:** Canine 24-month safety data; Phase 0 success on relevant KPIs
**Deliverable:** Single dose AAV-MSTN or AAV-FS344 administered intramuscularly to Principal at multiple muscle groups; muscle biopsy at 8 weeks, 6 months, 12 months; functional outcome measured.

Risks: erythrocytosis (manageable), cardiac hypertrophy (monitored by quarterly cardiac MRI), persistent neoantigen expression. Doses calibrated to be sub-Bhasin-1996 equivalent on the first administration.

### Workstream 1.2 — Partial Reprogramming (OSK)

**Bucket:** YELLOW
**Owner:** PI-Reprogramming
**Dependencies:** External human Phase 1 readout OR program canine 24-month data
**Deliverable:** Doxycycline-inducible AAV-OSK delivered tissue-selectively (initially: skeletal muscle, skin). Multiple cycles over 6-month window.

The key innovation: tissue-restricted, drug-inducible, c-Myc-excluded — substantially de-risked vs first-generation OSKM work.

**Failure mode:** No methylation reset signal at tolerable doses. Mitigation: pivot to different reprogramming factor cocktail (e.g., 7F from Sebastiano).

### Workstream 1.3 — Mitochondrial Transplantation

**Bucket:** YELLOW
**Owner:** PI-Bioenergetics
**Dependencies:** Autologous source tissue harvested; GMP-equivalent enrichment
**Deliverable:** Autologous mitochondria harvested from Principal's iliac crest fat, enriched in vitro, reinjected into specific skeletal muscle groups. Functional respirometry pre-post.

McCully's pediatric cardiac protocol generalizes to skeletal muscle indications. We are the first to attempt enhancement rather than rescue.

**Failure mode:** Low transplantation efficiency. Mitigation: optimize enrichment method; multiple administration routes.

### Workstream 1.4 — Senex Phase 2 Equivalent

**Bucket:** GREEN, scaled
**Owner:** PI-Reprogramming + CMO
**Dependencies:** Senex spinout operational
**Deliverable:** Senex runs Phase 2 trial in healthy aging cohort (n=30–50); program licenses protocol and reciprocally provides Principal data.

### Workstream 1.5 — Klotho mRNA

**Bucket:** YELLOW
**Owner:** PI-Bioenergetics
**Dependencies:** External Phase 1 readout
**Deliverable:** Klotho mRNA (LNP) administered to Principal at conservative dose; cognitive outcome + CSF klotho measurement.

### Workstream 1.6 — Augmentation Suite Build (Phase 2 Prep)

**Bucket:** ORANGE (build in Phase 1, operate in Phase 2)
**Owner:** COO + Engineering team
**Dependencies:** Phase 1 capital
**Deliverable:** 5 m short-arm human centrifuge specced and ordered; hypobaric chamber site prepared; BCI lab build-out begun.

---

## 10.4 Phase 2: Integration (Months 36–60)

### Workstream 2.1 — Augmentation Suite Operations

**Bucket:** ORANGE
**Owner:** PI-Performance + CMO
**Deliverable:** 2–3G chronic centrifuge training; intermittent hypobaric work; BCI integration.

### Workstream 2.2 — Commercial BCI Implantation

**Bucket:** YELLOW
**Owner:** CMO + outside partner (Neuralink, Synchron, or successor)
**Dependencies:** Commercial BCI available; Principal informed consent
**Deliverable:** Principal receives BCI in US under commercial protocol; subsequent care at Próspera.

Initial use: skill acceleration paired with high-bandwidth motor learning; cognitive bandwidth augmentation.

### Workstream 2.3 — Iterative Reprogramming Optimization

**Bucket:** YELLOW
**Owner:** PI-Reprogramming
**Deliverable:** Chronic, low-dose reprogramming protocol delivered Q3M; methylome age trajectory measured.

### Workstream 2.4 — Mitochondrial Density Escalation

**Bucket:** YELLOW
**Owner:** PI-Bioenergetics
**Deliverable:** Multiple rounds of mitochondrial transplantation; muscle mitochondrial volume fraction measured by 3D microscopy of biopsies.

### Workstream 2.5 — Bioelectric Field Optimization (Phase 3 Prep)

**Bucket:** ORANGE
**Owner:** Levin lab collaboration
**Deliverable:** Surface bioelectric mapping of Principal; first wearable bioelectric "pattern hold" device prototype.

### Workstream 2.6 — Tardigrade Dsup Pilot (Animal Only)

**Bucket:** YELLOW
**Owner:** PI-Reprogramming
**Deliverable:** Dsup transgene expressed in mouse muscle; radiation tolerance characterized. If positive: primate program.

---

## 10.5 Phase 3: Extension (Years 5–10)

Major capital deployment. Subject to separate Board reauthorization at Phase 2 gate. High-level workstreams:

| WS | Topic | Bucket |
|---|---|---|
| 3.1 | Subdermal dermal mesh (graphene + silk) | ORANGE |
| 3.2 | Engineered limb regeneration (BioDome scaled to mammalian primate) | ORANGE |
| 3.3 | Subdermal electric organ (eel electroplaque) — animal first, then maybe Principal | ORANGE |
| 3.4 | Cybernetic reflex augmentation (epidural spinal stim) | ORANGE |
| 3.5 | Xenotransplantation if specific indication (organ replacement) | YELLOW now / ORANGE for enhancement |
| 3.6 | Dsup transgene in Principal — only if mouse + primate data clean | ORANGE |
| 3.7 | Klotho chronic AAV (sustained expression) | YELLOW now / ORANGE if novel |
| 3.8 | Subdermal RTG power source — engineering R&D (not yet implanted) | ORANGE |
| 3.9 | Directed energy emitter — wearable first, subdermal much later | ORANGE |
| 3.10 | Compact fusion follow-on (research investment only) | ORANGE/RED |

---

## 10.6 Phase 4: Frontier (Years 10–15)

Subject to extensive Phase 3 review. Phase 4 is plausibly:
- Subdermal nuclear power (if regulatory + supply path opens)
- Subdermal directed energy emitter (if power available)
- Engineered HMM-HA transgene in Principal (cancer-resistance)
- Substantial cybernetic substitution (if clinically indicated or strongly preferred)
- Bioelectric morphogenetic field engineering (if Levin program matures)
- Possible engineered tail (Principal preference)
- Vehicle-mounted directed energy (defense partnership)

OR Phase 4 may be cancelled if Phase 3 outcomes do not justify further escalation.

---

## 10.7 Cross-Phase Dependencies

```
Phase 0 KPI hit  ──►  Phase 1 authorization
Phase 1 success  ──►  Phase 2 authorization
Phase 2 success  ──►  Phase 3 authorization (separate Board vote)
Phase 3 success  ──►  Phase 4 authorization (separate Board vote, supermajority)
```

Each gate is a real stop point. The program is designed so that at every gate, the Holdco retains operating value (spinouts, IP, infrastructure) independent of Principal outcome.

---

## 10.8 Research Topics Monitored But Not Funded (RED + Frontier)

Quarterly literature review by CSO + 1 SAB member:

- Casimir / DCE engineering applications
- Schwinger pair production feasibility
- LENR replication attempts
- Macroscopic quantum coherence in biology (Bandyopadhyay, Reimers continuations)
- Antimatter production cost trajectory
- Compact fusion progress (Helion, SPARC, TAE)
- Whole-brain emulation roadmap progress
- Aldehyde-stabilized cryopreservation outcomes

If any of these become engineering-ready (e.g., a LENR replication that survives peer review), the SAB convenes within 30 days to consider program incorporation.

---

## 10.9 Decision Authority Per Workstream

The CSO is the day-to-day authority on technical direction within phase. The SAB approves cross-phase pivots. The Board approves phase transitions. The Principal approves anything done to the Principal's body.

Detailed RACI in doc 01.

---

**Status:** Roadmap v1.0 — phase-gated re-baselining each transition.
