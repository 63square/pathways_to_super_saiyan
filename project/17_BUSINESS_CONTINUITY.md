# 17 — Business Continuity Plan (BCP)

**Owner:** CSecO + COO (joint)
**Effective:** Month 6 (full plan); core protocols Month 3
**Review cadence:** Annual full review; quarterly tabletop exercises

## Purpose

Doc 07 §7.7 covers **legal** crisis playbooks (C1–C10). This document covers **operational** continuity — facility loss, CMO incapacitation during active intervention, cold-chain failure, ransomware, key-person kidnap, supply-chain breakdown.

The 90-day jurisdictional relocation contingency from doc 07 §7.2 is asserted but lacks an operational runbook. This document provides it.

---

## 17.1 BCP Scope

| Threat | Plan |
|---|---|
| Facility loss (Próspera fire / hurricane / political seizure) | §17.4 Site Loss Playbook |
| Facility loss (UAE / El Salvador) | §17.4 (jurisdictional variant) |
| CMO sudden incapacitation during active intervention | §17.5 Clinical Continuity |
| Key-person incapacitation (other C-suite) | §17.5 |
| Cold-chain failure (AAV vectors, mRNA-LNP, biospecimens) | §17.6 |
| Ransomware on Tier-Amber clinical systems | §17.7 Cyber Incident Response |
| Ransomware on Tier-Red (low probability given air-gap) | §17.7 |
| Banking-rail loss | §17.8 |
| Key-person kidnap or ransom (R-NEW-13) | §17.9 |
| Supply-chain breakdown (single-source critical input) | §17.10 |
| Mass-casualty event affecting staff | §17.11 |
| Pandemic / public health emergency | §17.12 |
| Wholesale jurisdictional collapse (Próspera ZEDE revoked) | §17.13 |
| Catastrophic AE on Principal | §17.14 |
| Program wind-down (orderly) | §17.15 Kill Switch Playbook |
| Posture Black activation (hostile press exposure of Principal identity) | §17.16 |

---

## 17.2 Recovery Time / Recovery Point Objectives (RTO/RPO)

| Function | RTO | RPO |
|---|---|---|
| Clinical operations on Principal (active intervention) | 4 hours | 0 (continuous backup) |
| Tier-Red enclave operations | 24 hours | 24 hours |
| Tier-Amber clinical IT | 4 hours | 4 hours |
| eQMS / document control | 24 hours | 24 hours |
| Spinout operations | 1 week | 24 hours |
| Banking rails | 48 hours | n/a |
| Research-only functions | 1 week | 1 week |
| Facility relocation (jurisdictional) | 90 days | n/a |

---

## 17.3 BCP Governance

- **CSecO + COO** are joint plan owners
- **Quarterly tabletop exercise** rotating scenario from §17.1 list
- **Annual full BCP exercise** (full-scale, includes Principal where appropriate)
- **Annual external auditor review** of BCP
- **BCP plan stored in three jurisdictions** (Próspera, UAE, Cayman trustee escrow)
- **Activation authority:** CSecO + GC + CMO any two can activate; CEO confirms; LID notified

---

## 17.4 Site Loss Playbook

### Próspera HQ Loss

**0–4 hours:**
- Personnel accountability (all staff check-in via secure app within 1 hour)
- CSecO secures site perimeter (or confirms loss)
- Tier-Red enclave status confirmed (intact, compromised, lost)
- Principal status confirmed; if on-site during incident, evacuated per medical/protective plan
- Active intervention cycles assessed; if any in progress, transferred to backup clinical capability (Próspera alternate or UAE clinical)

**4–24 hours:**
- Insurance notification (Bermuda captive)
- Initial damage assessment
- Alternative facility activated (Próspera alternate location pre-leased; UAE Mediclinic standby)
- Data continuity confirmed (Tier-Red enclave operations resumed if data intact; if compromised, restore from Cayman trustee escrow)
- Communications: staff, Board, EEC, SAB, key vendors

**24 hours – 7 days:**
- Damage / forensic investigation
- Insurance claim documentation
- Decision: rebuild on-site OR relocate to co-primary
- If political seizure: GC activates jurisdictional contingency

**7–90 days:**
- Full operations relocated as needed
- New build-out if rebuild
- Lessons-learned review

### UAE / El Salvador Loss

Same template; "alternative facility" is the other two of the triad.

---

## 17.5 Clinical Continuity (CMO / Key Person Incapacitation)

### Shadow CMO Activation

If CMO incapacitated (sudden illness, arrest, voluntary resignation, death) during active intervention cycle:

**0–4 hours:**
- Shadow CMO (on retainer from Day 7, doc 06 §6.3.2) activated
- Associate CMOs (M12+) take operational coverage
- Active intervention cycles paused if in critical window
- All Principal-care decisions deferred to Shadow CMO + Science & Safety Committee until full CMO replacement

**4–48 hours:**
- LID notified; Board called
- External legal review of any non-compete or covenant issues with departing CMO
- Communications to staff (carefully scoped)

**2 weeks – 6 months:**
- New CMO search via pre-staged Spencer Stuart/Korn Ferry pipeline
- Shadow CMO operates with full Science & Safety Committee pre-clearance binding
- Principal continues maintenance protocol only; no new interventional cycles
- New CMO onboarded per doc 06 §6.3.2 structure

### Other Key Persons

- **CSO:** Deputy assumes (M12+); pause Phase 1 R&D escalation; SAB advisory
- **GC:** Wilson Sonsini partner-on-call assumes interim; ongoing regulatory matters paused if non-trivial
- **CFO:** FLG Partners or equivalent interim assumes
- **CSecO:** Deputy assumes; counterintel posture defaults to heightened
- **CEO:** Deputy or LID assumes interim; emergency Board convenes within 72 hours
- **Principal:** Medical proxy chain (doc 06 §6.8); program operations continue under advance directive

---

## 17.6 Cold-Chain Failure

### Detection
- Cryostorage temperature monitoring with alarm escalation (24/7)
- Threshold: any excursion >2°C from setpoint for >15 minutes triggers Tier-1 alert

### Response
**0–1 hour:**
- On-call vet/lab tech investigates
- Backup freezer activated; samples transferred if needed
- Loss assessment initiated

**1–24 hours:**
- Affected samples categorized:
  - Critical (Principal biospecimens, sperm cryo, autologous mitochondrial isolate)
  - Important (AAV/LNP/mAb stocks, screened FMT donor stool)
  - Routine (research samples)
- Critical: notification to CMO + CSO + Principal; replacement/re-collection plan
- Important: notification to CSO + CMO; replacement sourcing
- Insurance documentation initiated

### Prevention
- Redundant freezers (N+1 for Tier-Red biospecimens)
- Dual power (grid + UPS + generator)
- Two geographies for irreplaceable samples (Próspera + UAE)
- Monthly inventory audit
- Sperm cryo specifically: 3 separate freezers, 2 geographies

---

## 17.7 Cyber Incident Response

### Tier-Red Compromise (suspected)
**Immediate:**
- CSecO activates Crisis Cyber Team within 1 hour
- Tier-Red enclave physically isolated (already air-gapped; confirm no covert exfiltration)
- Threshold cryptography key shares verified
- External forensics (Mandiant or NCC Group APT team) engaged
- FBI/Interpol notification if external attribution likely
- Principal notified within 4 hours

### Tier-Amber Ransomware
**Immediate:**
- Network segmentation isolates Tier-Amber from Tier-Green
- Restore from backups (RPO 4 hours)
- Forensics + ransom decision per crisis legal playbook C5
- Clinical operations on Principal continue using paper SOPs and manual workflows for ≤72 hours if necessary

### Tier-Green / Tier-Open Incident
- Standard enterprise incident response
- Notification per GDPR/state breach laws

### Insider Threat Indication
- UEBA alert investigated by CI Officer + CSecO
- Subject access suspended pending investigation
- Forensic imaging of devices
- HR + GC engaged

---

## 17.8 Banking-Rail Loss

If primary banking jurisdiction (Cayman) loses correspondent banking or imposes restrictions:

- Operating reserves at UAE + Cayman + Bermuda captive
- 6-month operating runway in stable instruments outside any single banking system
- **Cryptocurrency operating reserves** (~5% of cash) provide further independence (per doc 07 §7.7 C6)
- Multi-sig wallets in 3 jurisdictions

---

## 17.9 Key-Person Kidnap / Ransom (R-NEW-13)

Per doc 05 risk register R-NEW-13 P3×S5=15.

- **K&R insurance** included in Bermuda captive tower
- **Crisis response retainer** with specialized firm (Control Risks, Pinkerton, Olive Group)
- **No-ransom-payment policy** as default; case-by-case Board+Principal+GC decision under counsel
- **Pre-staged response plan** in three jurisdictions
- **Family communications protocol** activated if family member targeted
- **Travel security protocols** prevent predictable patterns (per doc 11 §11.10)

---

## 17.10 Supply-Chain Breakdown

Per R-NEW-2 (single-source critical inputs):

- **4-box mapping** of every Tier-1 input: single-source × long-lead
- Board-level escalation for any single-source AND >90-day lead item
- **6-month inventory buffer** for irreplaceable inputs (AAV vectors, custom peptides, specialized reagents)
- Dual-source agreements where feasible
- In-house manufacturing migration in Phase 2 (per doc 04)

---

## 17.11 Mass-Casualty Event

Earthquake, mass-shooting, plane crash, etc. affecting program staff:

- Staff accountability protocol (secure app check-in)
- Family notification protocol
- Operations continuity per role-criticality (clinical highest; corporate lowest)
- Insurance + bereavement support
- External executive coaching for surviving staff

---

## 17.12 Pandemic / Public Health Emergency

Lessons from COVID-19:
- Remote-work capable for 60%+ of roles
- Clinical operations on Principal can pause without permanent loss
- 6-month medical supply buffer at Próspera + UAE
- Cross-trained backup personnel
- Pre-arranged PPE supply

---

## 17.13 Wholesale Jurisdictional Collapse

If Próspera ZEDE adversely revoked AND UAE policy shifts AND El Salvador fails simultaneously (very low probability; combined Scenario "Regulatory Pincer" per doc 05 §5.4):

**0–7 days:**
- Triad collapse confirmed
- Cayman + St. Kitts tertiary engaged
- Personnel + equipment relocation begun
- Principal clinical pause if any cycle active (cannot relocate mid-cycle safely)

**1 week – 90 days:**
- Tertiary jurisdiction stood up operationally
- Equipment shipped (already dual-located so partial inventory in place)
- Personnel relocate (visa support pre-arranged)
- Vendor MSAs migrate

**90 days – 18 months:**
- Full operations resumed at new jurisdiction
- Lessons documented
- Quadruple-jurisdiction architecture explored

Cost estimate: $100–200M relocation + 12–18 month delay. Per doc 05 R3, P=3, S=5.

---

## 17.14 Catastrophic AE on Principal

Per doc 11 §11.5 hard stop rules + doc 12 EG2.

**0–4 hours:**
- Medical response per SOP §11.10
- CMO + CEO + Principal medical proxy + LID + EEC chair notified
- Crisis comms team activated (no statements yet)

**4–24 hours:**
- Full Board + SAB + EEC convened
- Independent autopsy pre-contracted academic pathology activated if death
- Insurance notification (Bermuda captive + reinsurance)
- External regulatory counsel engaged
- Forensic medical review of intervention

**24–72 hours:**
- Communications strategy decided
- Principal family / NOK notification
- Spinout boards alerted per reputational contagion map (doc 05 §5.6)
- Program-wide pause activated

**72 hours – 30 days:**
- Investigation completed
- Lessons learned + CAPA (doc 15)
- Decision: resume with protocol changes, restructure, or wind down (EG2)

---

## 17.15 Kill Switch — Orderly Wind-Down Playbook

### 7-Day Wind-Down (Catastrophic Trigger)

Triggers: catastrophic AE Grade 4-5, criminal indictment, regulatory shutdown order.

**Day 1:**
- All interventional activity halted immediately
- Principal medical maintenance continues (chronic medications, monitoring)
- Press posture Black activated
- Communications: staff (mandatory), Board, EEC, SAB, regulators (per legal)

**Days 2–7:**
- Tier-Red data secured (offline backup; legal hold)
- Biological samples secured per advance directive
- Active animal cohorts: humane endpoint or transfer to academic partner
- Spinouts: separate operational; protected from parent fallout
- Personnel: retention package for critical, severance for non-critical

### 30-Day Wind-Down (Major Trigger)

Triggers: Gate G4 hard fail, Próspera collapse without failover, sustained adverse press cascade.

**Days 1–7:**
- Decision committee (Principal + Board + EEC + LID) confirms wind-down
- Communications plan executed in sequence: staff → Board → SAB → regulators → spinouts → press (last)
- Principal medical maintenance protocol locked

**Days 7–30:**
- Spinouts: continuity capital ensured; new boards if needed; license amendments
- Personnel: outplacement; recruiting partners notified
- Facilities: lease termination per terms
- IP: rolled to Holdco maintenance entity
- Data: 50-year retention escrow activated

### 90-Day Wind-Down (Standard Trigger)

Triggers: Phase 1 or later gate fail with Principal+Board+EEC concurrence, no clearer crisis.

Per doc 12 §12.13 "Honest Failure Pathway":
- Months 1–2: Spinouts retained, half scientific staff retained, lessons documented
- Month 3+: Holdco transitions to investment / royalty vehicle

### Asset Preservation Sequence

| Asset | Disposition |
|---|---|
| Tier-Red Principal data | Retained 50 years per consent + advance directive |
| Tier-Amber research data | Retained per IP value; archived after spinout exits |
| Biological samples | Per advance directive; sperm cryo retained Principal lifetime + estate disposition |
| Patents | Maintained where commercially valuable; abandoned otherwise (Holdco continues) |
| Trade secrets | Locked in escrow; access only on Holdco governance vote |
| Spinout equity | Retained in Holdco; managed for orderly exit |
| Insurance | Run-off coverage activated |
| Real estate / leases | Terminated per terms |
| Animal cohorts | Adopted (canines per §16.13) or sanctuary (NHPs where appropriate) |

---

## 17.16 Posture Black — Hostile Press Exposure of Principal Identity

Per doc 06 §6.3.6 identity-lifecycle planning.

**Trigger:** investigative journalist or hostile actor publishes Principal's identity tied to program in a hostile framing, OR confirmed leak imminent.

**0–4 hours:**
- CSecO confirms exposure
- Principal moved to pre-prepared alternate residence in second jurisdiction within 72 hours
- Alternate identity activated for non-program life (legally obtained second passport)
- Family relocation plan executed
- Pre-positioned schools, banks, medical, vehicle access activated under alternate ID

**4 hours – 7 days:**
- Crisis comms firm executes pre-drafted statements (12 scenario library)
- Defamation/right-of-publicity counsel engaged
- Legal action assessed against source if knowingly false
- Family communications protocol activated
- Spinout boards alerted

**7+ days:**
- Long-term Posture management
- Controlled disclosure on Principal's timeline (Posture White) if recoverable
- Permanent posture White if exposure cannot be reversed

**Annual rehearsal** of Posture Black activation (without execution). Year-round maintenance of parallel "cold" identity infrastructure: ~$800K/yr (covered in security budget doc 04).

---

## 17.17 Exercise & Maintenance Schedule

| Activity | Frequency |
|---|---|
| Tabletop exercise (rotating scenario) | Quarterly |
| Full-scale BCP exercise | Annual |
| Posture Black rehearsal (no execution) | Annual |
| External BCP audit | Annual |
| BCP plan update / lessons fold-in | Quarterly |
| Disaster drill (facility-specific) | Semi-annual |
| Hurricane preparedness drill (Próspera) | Pre-hurricane-season annually |
| Cybersecurity red team (full-scope) | Annual |
| Insider threat tabletop | Annual |

---

**Status:** BCP v1.0 — core protocols operational Month 3; full plan operational Month 6.
