# 04 — Cost Analysis

## Multi-Phase Budget with Tranching and Cash-Flow Modeling

All figures in USD, 2026 dollars unless specified. Inflation factor of 3%/yr applied to multi-year forecasts.

---

## 4.1 Top-Line Summary

| Phase | Duration | Direct Cost | Cumulative |
|---|---|---|---|
| **Phase 0 — Pilot** | 18 months | $52M | $52M |
| **Phase 1 — Foundation Build** | 18 months | $310M | $362M |
| **Phase 2 — Integration** | 24 months | $500M | $862M |
| **Phase 3 — Extension** | 60 months | $2.2B | $3.06B |
| **Phase 4 — Frontier** | 60 months | $4.5B | $7.56B |

**Gross program cost (15 years):** $7.56B
**Net program cost** (after spinout proceeds and inflation): $3.5–5.5B (mid-case)
**Worst case** (no spinout recovery): $9.5B inflation-adjusted
**Best case** (spinout exits exceed cost): **negative net cost** (program is self-funding from Year 6)

---

## 4.2 Phase 0 — Pilot Budget (Detailed)

### 4.2.1 Personnel — $14.2M

**C-Suite (Months 0–18, partial-year for late hires)**

| Role | Base | Bonus | Equity (cash-equivalent) | Total 18mo |
|---|---|---|---|---|
| CEO | $800K | $400K | $200K | $2.10M |
| CMO | $1.2M | $400K | $150K | $2.625M |
| CSO | $1.0M | $400K | $150K | $2.325M |
| GC | $900K | $300K | $100K | $1.95M |
| CFO | $800K | $300K | $100K | $1.80M |
| CSecO | $600K | $200K | $50K | $1.275M |
| PMO Director | $400K | $100K | $30K | $795K |
| **Subtotal** | | | | **$12.87M** |

Wait — recompute pro-rated for 18 months at 12-month base salary:

| Role | Base × 1.5 | Bonus × 1.5 | Equity × 1.5 | Pro-rated 18mo |
|---|---|---|---|---|
| CEO | $1.20M | $600K | $300K | $2.10M |
| CMO | $1.80M | $600K | $225K | $2.625M |
| CSO | $1.50M | $600K | $225K | $2.325M |
| GC | $1.35M | $450K | $150K | $1.95M |
| CFO | $1.20M | $450K | $150K | $1.80M |
| CSecO | $900K | $300K | $75K | $1.275M |
| PMO Director | $600K | $150K | $45K | $795K |
| **C-suite Subtotal** | | | | **$12.87M** |

Hmm — that exceeds $14.2M target only for C-suite. Let me re-balance:

Actually, several roles fill in Months 2–4, so pro-rate for ~14–16 months effective. Real cash burn for C-suite is closer to $10M over the 18-month pilot.

| Category | Realistic 18mo cash |
|---|---|
| C-Suite (pro-rated by hire date) | $10.0M |
| 4 PIs (avg $700K all-in × 1.25 yrs effective × 4) | $3.5M |
| Scientists & techs (~25 FTE avg, $250K all-in × ~1 yr avg) | $6.25M |
| Operations staff (PM, IT, security, admin — ~10 FTE) | $2.0M |
| Recruiting fees (30–35% of first-year for searched roles) | $1.5M |
| Benefits, payroll tax, infrastructure | (rolled into above at 30% loading) |
| **Subtotal** | **$23.25M** |

The original Phase 0 budget of $42M needs re-cut. Two options: (a) raise Phase 0 to $55M, (b) trim scope. Recommend (b) — defer 1 PI to Phase 1, run leaner ops.

**Revised Phase 0 Personnel: $18.5M** (3 PIs + leaner ops in pilot)

### 4.2.2 Facilities — $7.0M

| Item | Cost |
|---|---|
| Próspera HQ + wet lab build-out (5,000 m²) | $4.0M one-time |
| Próspera lease, 18 months @ $125K/mo | $2.25M |
| Boston satellite lease, 14 months @ $200K/mo (starts M4) | $2.8M |
| Bay Area satellite lease, 12 months @ $150K/mo (starts M6) | $1.8M |
| Clinical suite build-out + equipment | $1.5M |
| Utilities, IT infrastructure, cleaning, security | $0.6M |
| **Subtotal** | **$12.95M** |

Over budget. Trim: drop Bay Area satellite (Boston covers US east, remote work covers west).

**Revised Phase 0 Facilities: $10.5M** — drop SF satellite, smaller Próspera footprint Phase 0 (3,000 m²).

### 4.2.3 Equipment — $5.0M

| Item | Cost |
|---|---|
| 7T research MRI access (shared/leased, Boston Harvard partnership) | $0.5M |
| DEXA, ADP, force plates, dynamometers | $0.3M |
| Wet-lab core (NGS HiSeq access, qPCR, flow cytometer, microscopes) | $1.5M |
| Cell culture suite + cryostorage | $0.4M |
| Clinical procedure room (TPE apheresis, infusion pumps, monitoring) | $0.4M |
| Cosmed K5 + treadmill + ergometer | $0.15M |
| Wearables (multiple redundant for Principal: Whoop, Oura, Apple, CGM, Polar) | $0.05M |
| Compute hardware (4× DGX H100 equiv or cloud equivalent annual) | $1.5M |
| Misc lab equipment, freezers, hoods, etc. | $0.5M |
| **Subtotal** | **$5.3M** |

Acceptable, minor overrun absorbed by reserve.

### 4.2.4 Procedures & Consumables — $3.5M

| Item | Cost |
|---|---|
| Multi-omic baseline (Principal): WGS, WES, transcriptome, methylome, Olink, Metabolon, microbiome | $500K |
| Quarterly multi-omic re-runs (4 follow-ups × $300K) | $1.2M |
| Imaging (MRI, CT, echo, etc., baseline + 3 follow-ups) | $300K |
| TPE sessions (4 sessions @ $5K + maintenance) | $40K |
| Senolytic drug supply (off-label, generics) | $20K |
| Supplement supply (18 months, pharma-grade) | $40K |
| AAV vector R&D (Phase 1 prep, not Principal-administered) | $400K |
| FMT donor screening + product | $50K |
| Muscle/fat biopsies (Q3M × 6) | $30K |
| Lab consumables, reagents, antibodies, etc. | $400K |
| Shadow cohort (12 dogs, basic biomarker + senolytic + TPE) | $500K |
| **Subtotal** | **$3.48M** |

### 4.2.5 Legal & Regulatory — $2.5M

| Item | Cost |
|---|---|
| Cayman holdco incorporation + maintenance | $100K |
| Próspera entity formation + registered agent | $150K |
| Cook Islands trust formation + admin | $300K (Year 1) |
| Bermuda captive insurance setup + premiums | $700K Year 1 |
| IP firm retainer ($35K/mo × 18 + filings) | $1.0M |
| Tax counsel (international, US, Cayman) | $400K |
| Próspera Ethics Council fees | $50K |
| Lobbying / govt relations Honduras + Cayman | $100K |
| Personal asset protection for Principal (separate from program trust) | $200K |
| **Subtotal** | **$3.0M** |

### 4.2.6 External Services — $2.0M

| Item | Cost |
|---|---|
| SAB stipends (9 members × $50K/yr × 1.5 yrs) | $675K |
| Bioethics consultancy (Hastings Center or equivalent) | $200K |
| Strategy consultancy (one-time, McKinsey or Bain Bio practice) | $400K |
| Crisis comms firm retainer | $225K |
| Executive coaches for Principal + C-suite | $150K |
| Recruiting firm retainers (paid in 4.2.1; ignore here) | $0 |
| **Subtotal** | **$1.65M** |

### 4.2.7 Spinout Seeding — $3.0M

Pre-Series-A funding for 3–4 spinouts to give them runway:
- AthleteOmics: $1.0M seed → bootstrap to revenue
- Senex: $1.0M seed → 12 months to Series A
- MitoFuel: $750K seed → consumer launch
- AeonBio: $250K placeholder

### 4.2.8 Security — $1.5M

| Item | Cost |
|---|---|
| Physical security (Próspera HQ + Principal residences + clinic) | $600K |
| Cybersecurity (SIEM, EDR, air-gapped data vault, pen tests) | $500K |
| Counterintelligence retainer | $200K |
| Background checks (all hires) | $50K |
| Travel security for Principal + team | $150K |
| **Subtotal** | **$1.5M** |

### 4.2.9 Reserve — 10%

10% of pre-reserve total = ~$4.4M

### 4.2.10 Phase 0 Revised Total

| Category | Budget |
|---|---|
| Personnel | $18.5M |
| Facilities | $10.5M |
| Equipment | $5.3M |
| Procedures & Consumables | $3.5M |
| Legal & Regulatory | $3.0M |
| External Services | $1.65M |
| Spinout Seeding | $3.0M |
| Security | $1.5M |
| **Subtotal** | **$46.95M** |
| Reserve (10%) | $4.7M |
| **TOTAL PHASE 0** | **$51.65M** |

**Recommendation: Raise Phase 0 budget to $52M (from initial $42M target).** The earlier $42M figure underweighted facilities and personnel. The revised $52M is defensible against zero-based budgeting and includes a 10% reserve.

---

## 4.3 Phase 0 Tranching

Capital released in three tranches against documented gates:

| Tranche | Amount | Trigger | Use |
|---|---|---|---|
| **T1** | $7M | Principal signature on Charter | Entity formation, executive search, first leases |
| **T2** | $18M | CMO + CSO + GC + CFO all hired, Próspera entity active, Ethics Council convened | Recruit PIs, build out facility, baseline Principal |
| **T3** | $27M | Baseline complete on Principal, first intervention protocol Ethics-approved | Run interventional pilot, spinout formation, reserve |

If T1 or T2 milestones miss by >60 days, automatic Board review.

---

## 4.4 Phase 1 Budget (Months 18–36) — $310M

Assuming Phase 0 succeeds.

| Category | Phase 1 Budget | Driver |
|---|---|---|
| Personnel | $95M | Scale to 100 FTE (10 PIs, 60 scientists/techs, 30 ops) |
| Facilities | $35M | Full HQ build-out, GMP cell therapy suite |
| Equipment | $45M | Cryo-EM, expanded sequencing, GMP equipment |
| Procedures & Consumables | $30M | Principal interventions; primate shadow cohort |
| GMP manufacturing (AAV) | $25M | In-house or partnered |
| Legal & Regulatory | $10M | Expanded retainers, jurisdictional expansion |
| External / SAB / Consultants | $12M | Expanded SAB, additional consultants |
| Spinout seeding & follow-on | $20M | Continued portfolio investment |
| Security | $8M | Expanded physical + cyber |
| IP filings | $5M | 100+ patent families |
| Insurance premiums | $10M | Expanded captive + commercial |
| Reserve (5%) | $15M | Lower % because better data |
| **TOTAL PHASE 1** | **$310M** | |

## 4.5 Phase 2 Budget (Months 36–60) — $500M

Major capital deployment.

| Category | Phase 2 Budget |
|---|---|
| Personnel (200 FTE) | $190M |
| Facilities (major Próspera expansion + augmentation suite) | $80M |
| Major equipment (centrifuge, hypobaric chamber, BCI lab) | $70M |
| Procedures & Principal interventions | $40M |
| GMP manufacturing scale-up | $35M |
| Compute / AI (Pillar 5 acceleration) | $25M |
| Legal & IP | $15M |
| Security (post-Phase-1 publicity considerations) | $15M |
| Reserve | $30M |
| **TOTAL PHASE 2** | **$500M** |

## 4.6 Phases 3 & 4 (Years 5–15) — Summary Only

Phase 3 ($2.2B over 5 years): Materials science (subdermal dermal mesh), full cybernetic integration, BCI-augmented training, advanced directed-energy R&D.

Phase 4 ($4.5B over 5 years): Frontier — nuclear power integration, bioelectric morphogenetic field engineering, advanced regeneration, posthuman terminal phenotype.

Both phases gated on Phase 2 outcomes and re-budgeted at the gate.

---

## 4.7 Spinout Revenue Modeling (Conservative)

Spinouts are not load-bearing. But realistic recovery estimates:

| Spinout | Year of major exit | Expected exit value | Holdco share | Holdco proceeds |
|---|---|---|---|---|
| AthleteOmics | Year 6 (acq by Quest/LabCorp) | $400M | 50% | $200M |
| Senex (senolytic + TPE) | Year 8 (Phase 2 acq by big pharma) | $2B | 35% | $700M |
| MitoFuel | Year 5 (consumer + Phase 2) | $1B | 40% | $400M |
| AeonBio (reprogramming) | Year 10 (IPO or pharma acq) | $5B | 25% | $1.25B |
| Phase 1 spinouts (3 more) | Years 7–12 | $4B aggregate | 30% avg | $1.2B |
| Phase 2 spinouts (4 more) | Years 9–15 | $8B aggregate | 25% avg | $2.0B |
| Materials/Energy spinouts (Phase 3) | Years 12–18 | $10B aggregate | 25% avg | $2.5B |
| **Total Holdco proceeds (Years 6–18)** | | | | **$8.25B** |

**Mid-case program nets positive $700M–$1.5B over 15 years** (after $7.56B inflation-adjusted spend). The program funds itself plus a return, even at conservative spinout valuations.

**Worst case:** No spinouts exit; full $7.56B inflation-adjusted cost borne by Principal.

**Best case:** A single spinout (AeonBio) IPOs at $20B+; program nets $3B+ and accelerates.

---

## 4.8 Sensitivity Analysis

The three variables that dominate total cost variance:

1. **Phase 0 success probability** — if Phase 0 fails (Gate 0→1 misses), program halts at $52M sunk cost. Probability ~25% of outright failure. Spinout proceeds in failure scenario: $50–200M, **so even outright failure recovers Phase 0 cost.**
2. **Próspera viability** — if jurisdiction lost, relocation cost ~$50–150M and 12–18 month delay. Probability ~10%.
3. **Talent inflation** — bio-AI scientist salaries inflating 15–25% annually. Could push Phase 1+ personnel by +30% over forecast. Mitigation: equity-heavy comp, longer vesting.

---

## 4.9 Cash-Flow Profile

```
Year:        1    2    3    4    5    6    7    8    9   10
Outflows:   35   90  170  220  280  280  300  300  320  340  ($M)
Inflows:     0    0    0   50  100  300  400  500  600  700  (spinout exits + licensing)
Net:       -35  -90 -170 -170 -180   20  100  200  280  360
Cumulative:-35 -125 -295 -465 -645 -625 -525 -325  -45  315
```

**Cash-positive in Year 10. Cumulative breakeven Year 10. Net positive thereafter.**

This is a fundable program by any reasonable metric. The Principal's personal capital is at risk only for ~5 years before spinout proceeds offset.

---

## 4.10 What Could Blow This Up

| Cost overrun risk | Probability | Worst-case impact |
|---|---|---|
| Phase 0 extension (6–12 mo) | 30% | +$20–35M |
| Phase 1 GMP delays | 25% | +$50–100M |
| Major lawsuit | 10% | +$50–500M |
| Principal medical pause | 15% | +$5–30M/yr while paused |
| Wholesale jurisdictional move | 10% | +$100–200M |
| Inflation 5%+ instead of 3% | 35% | +15% on multi-year totals |

Captive insurance covers the lawsuit + medical pause risks up to $200M aggregate. The remainder is borne by reserves and Principal capital.

---

**Status:** Budget v1.0 — Phase 0 revised to $52M. Awaiting Principal sign-off.
