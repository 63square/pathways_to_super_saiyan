# 02 — Feasibility Analysis

**Pre-read:** [DEFINITIONS.md](./DEFINITIONS.md) — what the program is trying to achieve.

## Purpose

To partition every intervention proposed in Volumes I and II of the white paper into four buckets:

- **GREEN — In Pilot (Phase 0):** Published in humans, safe profile, deliverable now
- **YELLOW — In Foundation (Phase 1–2):** Demonstrated in primates/humans for related indications, requires protocol development
- **ORANGE — In Extension (Phase 3+):** Plausible but requires substantial engineering and regulatory work, deferred
- **RED — Cut from program:** Speculative, unfalsifiable, or violates physical law; remains research curiosity only

This is the central document. Every other document derives from this triage.

**Version note:** This document is v1.1 post-SAB-style external review. Material revisions from v1.0: (a) D+Q senolytic demoted from GREEN to early-YELLOW with single-cycle gate; (b) NMN dropped, NR substituted; (c) AAV-myostatin Y1/Y2 replaced with **bimagrumab/garetosmab mAb first** (reversible, established safety); (d) AAV-OSK Y3 replaced with **mRNA-LNP OSK**; (e) acarbose, canagliflozin, weekly low-dose rapamycin added to GREEN; (f) multiplicative-stacking thesis (§2.3) recalibrated from 12–80× to realistic 2–4× envelope.

---

## 2.1 The Triage

### GREEN — Phase 0 Pilot (Months 0–18)

| # | Intervention | Evidence Base | Why it qualifies |
|---|---|---|---|
| G1 | Comprehensive multi-omic baselining | Standard CRO offering | Establishes metrics |
| G2 | Senolytic single-cycle (dasatinib + quercetin, fisetin) — **gated**, see note | Kirkland Mayo Phase 1/2; Hickson 2019 *EBioMedicine* | Approved drugs off-label; first cycle only with 90-day washout + pleural ultrasound before any monthly cadence |
| G3 | Therapeutic plasma exchange — **capped at 4 sessions/yr in Phase 0** | FDA-approved many indications; Mehdipour 2020 | Standard procedure; chronic schedule novel — capped per SAB feedback |
| G4 | Cyclic prolonged fasting + autophagy (FMD) | Longo lab; Mattson reviews | Lifestyle, zero pharmaceutical risk |
| G5 | Microbiome optimization (FMT from athlete donors) | Scheiman 2019 *Nature Med* | FDA-regulated routine |
| G6 | Mitochondrial substrate optimization (urolithin A, **NR** [not NMN], MitoQ) | Andreux 2019; Liu 2022 *JAMA Netw Open*; Mills 2016 | UA + NR have stronger pharmacokinetic + functional data than NMN |
| G7 | HBOT — **3×/wk × 8wk @ 1.5 ATA** with pulmonary function monitoring | Hachmo 2020 (unreplicated) | De-escalated from 5×/wk @ 2.0 ATA per SAB feedback |
| G8 | Polarized training + heat acclimation | Sports science literature | Zero medical risk |
| G9 | Targeted endocrine optimization (physiological-range TRT, GH only if indicated) | Standard endocrinology | Mainstream clinical practice |
| G10 | Cognitive training + tDCS + sleep optimization | Walker lab; Reato et al. | Non-invasive |
| G11 | Continuous biometric monitoring | Consumer + clinical wearables | Pure data |
| G12 | Pre-registered RCT-style N=1 design + public protocol registry | SCRIBE, SPIRIT guidelines | Methodology |
| **G13** | **Weekly low-dose rapamycin** (PEARL trial, Konopka, Mannick 2024) | Phase 2 readouts in healthy adults | Immune rejuvenation, manageable AE profile — added per SAB feedback |
| **G14** | **Acarbose** | ITP-positive both sexes; decades of anti-diabetic human safety data | Stronger evidence base than NMN for healthspan |
| **G15** | **Canagliflozin or empagliflozin** | EMPA-KIDNEY 2023, EMPEROR-Preserved; ITP-positive males | CV mortality benefit even in non-diabetics |
| **G16** | **Microdose GLP-1 / GIP co-agonist** (tirzepatide low dose for healthspan; ApoB/hsCRP/visceral fat reduction) | SELECT trial Lincoff 2023 *NEJM* | Body composition + CV signal at sub-anti-obesity dose; muscle-sparing protocol with resistance training paired |

**Total Phase 0 interventional surface area: 16 protocols (expanded from 12 per SAB).**

### YELLOW — Phase 1 & 2 Foundation (Months 18–60)

**Major v1.1 revision:** AAV gene therapies replaced with monoclonal antibody (mAb) first-line approach where the underlying biology has an mAb option. Gene therapy is escalation, not first move.

| # | Intervention | Evidence Base | Gate before deployment |
|---|---|---|---|
| **Y1** | **Bimagrumab (anti-ActRII mAb) — replaces AAV-MSTN as first line** | Rooks 2020 (sarcopenia Phase 2): ~7% lean mass gain | Reversible mAb data accrues 12 mo before any gene therapy considered |
| **Y2** | **Garetosmab (anti-activin A mAb)** | Regeneron Phase 2/3 in FOP | Adjunct to Y1 if needed |
| Y2-AAV | AAV-FS344 follistatin gene therapy — **only if Y1+Y2 mAb fail** | Mendell 2015 (no clinical benefit, low expression) + Kota 2009 primate | Demoted to escalation path; not first-line |
| **Y3** | **mRNA-LNP OSK partial reprogramming — replaces AAV-OSK** | Ocampo 2016; Browder 2022; Yang 2023; **Cao 2024** (transient mRNA, no integration) | mRNA-LNP route is safer than AAV-OSK for first-in-human |
| Y3-AAV | AAV-OSK with Tet-off — **only if mRNA-LNP fails** | Browder 2022 | Demoted to escalation path |
| Y4 | Autologous mitochondrial transplantation | McCully 2017 *JTCS* (FDA Breakthrough, pediatric cardiac) | FDA precedent confirms safety; requires ³¹P-MRS + heteroplasmy tracking (see doc 10) |
| **Y5** | **Klotho fragment KL1 (sub-Q peptide) — replaces full-length AAV-Klotho as first line** | Castner 2023 *Nat Aging* NHP | Avoids phosphate-handling risks (vascular calcification) of full-length |
| Y6 | TPE chronic schedule (extended) | Standard procedure | 12-month chronic safety data + immune repertoire monitoring required |
| Y7 | Senolytic + reprogramming combined cycling | No published combined data | In-house NHP model required (not canine) |
| Y8 | TERT mRNA telomere maintenance | Bär 2014 *Nat Commun* | Phase 1 readout from any sponsor |
| Y9 | Mitochondrial uncoupling (CRMP liver-targeted) | Goedeke 2019 *Cell Metab* | Liver-targeted only; whole-body deferred to ORANGE |
| Y10 | BCI for skill acquisition (commercial Neuralink/Synchron) | First human implants 2024+ | Commercial availability + 24-month track record |
| Y11 | Wearable bioelectric stimulation | Galvani, SetPoint (vagus only) | Levin lab partnership for protocols |
| Y12 | Tardigrade Dsup protein transgene (animals only Phase 1) | Hashimoto 2016 in vitro | Mouse 24-mo + primate before any Principal consideration |
| Y13 | Cetacean/avian mitochondrial donor sourcing | None — speculative | EEC binding veto; ethical review + alternative (synthetic) preferred — likely never approved |
| Y14 | Engineered chromaffin cell grafts (iPSC autologous) | Adrenal autograft precedent (1980s) | iPSC source, autologous |
| Y15 | Naked-mole-rat HMM hyaluronan transgene | Tian 2013 (mice only) | Mouse safety + primate before subject |
| **Y16** | **Plasma fraction E5 / PPF (Grifols)** | Horowitz/Wyss-Coray 2020 *Nature* | Phase 2 readout pending; more targeted than full TPE |

### ORANGE — Phase 3+ Extension (Year 5+)

| # | Intervention | Earliest start | Critical prerequisite |
|---|---|---|---|
| O1 | Subdermal graphene-spider silk dermal mesh | Year 8 | Material at scale + 5-year primate data |
| O2 | Subdermal RTG power source | Year 10 | Pu-238 supply + medical isotope license |
| O3 | Subdermal directed-energy emitter | Year 12 | Power source first |
| O4 | Subdermal electric organ (eel-derived electroplaque) | Year 10 | Schroeder protocol scaled |
| O5 | Engineered limb regeneration (BioDome scaled) | Year 7 | Levin lab + mammalian primate data |
| O6 | Engineered tail (vestigial reactivation) | Year 12 | Aesthetic-only; deprioritize |
| O7 | High-G centrifuge chronic training | Year 5 | Phase 2 spinout pays for it |
| O8 | Pseudo-HTC torpor + accelerated VR training | Year 8 | Mark Roth H2S protocol scaled to humans |
| O9 | Cybernetic reflex augmentation (epidural stim) | Year 9 | Courtine clinical translation matures |
| O10 | Subdermal Cherenkov aura emitter | Year 12 | Cosmetic, post-functional gains |

### RED — Cut from Program (No Capital, Quarterly Literature Monitoring Only)

| # | Intervention | Why cut |
|---|---|---|
| R1 | Casimir vacuum energy extraction | No path from physics to engineering |
| R2 | Schwinger pair production as personal weapon | Requires ELI-class facility |
| R3 | Unruh radiation harvesting | Self-destroying accelerations |
| R4 | LENR / cold fusion | Awaiting replication of Berlinguette/Google |
| R5 | Alcubierre/Lentz warp drive | Civilization-scale capabilities |
| R6 | Whole-brain emulation / upload | Destroys Principal; posthumous-only with separate consent |
| R7 | Germline modification | Criminalized; bright-line |
| R8 | Antimatter power | Supply problem multi-century |
| R9 | Schwinger biological field amplifier | Speculative beyond horizon |
| R10 | Macroscopic Fröhlich condensate ki substrate | Monitor literature; not interventional |
| R11 | "International waters research vessel" intervention site | Ethically indefensible per SAB review — **removed entirely** |

---

## 2.2 Why the Cuts Matter

The original two-volume white paper conflated three categories. A serious program keeps them separate:

1. **Things deliverable now with biomarker-grade human evidence.** (GREEN)
2. **Things developable within a 5–10 year program.** (YELLOW + ORANGE)
3. **Things that may be possible if frontier physics or biology cooperates.** (RED — monitor, do not fund)

Treating all three as deliverables is the failure mode of every prior posthuman program. **Project PROMETHEUS operates only on categories 1 and 2 with capital. Category 3 is monitored as research, not pursued as engineering.**

## 2.3 Multiplicative Realism Check — HONEST RECALIBRATION

**v1.0 of this document claimed 12–80× over baseline elite human. Per SAB-style external review, this is biophysically indefensible.** Independent reviewers identified that the v1.0 product:

- Double-counted interventions acting on the same physiological axis (e.g., mitochondrial transplant + HBOT + microbiome + AAV-myostatin all multiplied into a single VO₂max number, when the VO₂max ceiling is the **minimum** of O₂ delivery and O₂ extraction, not the product)
- Treated antagonistic interactions as independent (senolytics + reprogramming may **antagonize** because senescent cells are required intermediates in tissue regeneration; Ritschka 2017)
- Ignored that AAV-myostatin **reduces** capillary-to-fiber ratio (Amthor 2007), reducing the oxidative-capacity contribution it was multiplied with

### Revised Honest Envelope

Replace the multiplicative product with **physiologically-grounded ceilings per metric**, modeled with the Fick equation for VO₂max, the Hill equation for strength, etc.:

| Axis | Realistic terminal envelope (Phase 2) | Source of ceiling |
|---|---|---|
| VO₂max | 1.5–2.2× elite baseline | Mitochondrial volume fraction (~2× max biological), Hb mass, capillary density |
| Peak power | 1.5–2× elite baseline | Fiber cross-sectional area × specific tension |
| Lean mass | 1.4–1.8× | Myostatin path saturation |
| Recovery rate | 2–4× | Stem cell biology + reprogramming |
| Biological age delta (DNAm) | 15–25 years younger than chronological | Reprogramming + senolytic literature ceiling |
| Cognitive composite | 1.2–1.5× baseline z-score | Brain plasticity ceilings |
| Reaction time | 3–5× (with BCI) | Hardware-limited, not biology-limited |
| Impact tolerance | 5–20× (with subdermal mesh, Phase 3+) | Material science ceiling |
| Projected energy (Phase 3+) | 100–10,000× (wearable directed energy) | Battery + emitter engineering |

**Multi-axis terminal envelope (Phase 2 only, biological):** **3–5× elite baseline** on best axes, not 12–80×.

**Multi-axis terminal envelope (Phase 4, including materials + cybernetics + directed energy):** **30–200× on selected axes** — but this includes hardware contributions, not pure biology.

This recalibration is reflected in the revised Phase 2 KPI targets (doc 01 §1.3 objective 10: 5× on 3+ KPIs, down from 10×) and the DEFINITIONS.md operational criteria. It does **not** preclude the program from achieving the operational Super Saiyan definition (DEFINITIONS §2.2), because that definition is calibrated against this realistic envelope — not against an inflated naive product.

## 2.4 What "Feasibility" Means Here

For GREEN and YELLOW items, we require:
1. ≥1 peer-reviewed publication demonstrating the intervention in humans or in a translational mammalian model (NHP, dog, pig)
2. ≥1 currently-active commercial or academic program working on the same intervention
3. Clear path to GMP-equivalent manufacturing
4. Clear path to regulatory authorization (Próspera Ethics Council, UAE DHA, FDA, EMA, or compassionate use)
5. Documented safety profile with quantified AE rates from prior trials

For ORANGE: plausible engineering path, no physical-law violations, identifiable critical-path technology on development trajectory.

For RED: quarterly literature review by CSO + 1 SAB member. No capital allocated.

## 2.5 Falsifiability

Every GREEN and YELLOW intervention has at least one quantitative biomarker that can fail. Phase 0 KPIs (doc 08) are pre-registered with numeric thresholds. Failed interventions are **defunded** at the Phase 0–1 gate, not iterated indefinitely.

This is the discipline that distinguishes Project PROMETHEUS from a vanity project. **Every assertion has a failure condition.**

---

**Status:** Triage v1.1 (post-SAB review) — to be re-reviewed at each phase gate by SAB and EEC.
