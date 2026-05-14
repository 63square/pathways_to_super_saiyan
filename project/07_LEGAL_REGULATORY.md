# 07 — Legal & Regulatory Strategy

## 7.1 Core Legal Architecture

```
┌──────────────────────────────────────────────────────────┐
│      COOK ISLANDS ASSET PROTECTION TRUST (Principal)      │
│      ─ Owns the Cayman Holdco                             │
│      ─ Shields personal assets from program liability     │
└──────────────────────┬───────────────────────────────────┘
                       │ owns
                       ▼
┌──────────────────────────────────────────────────────────┐
│            CAYMAN HOLDCO (PROMETHEUS Ltd)                 │
│            ─ IP ownership                                 │
│            ─ Spinout equity                               │
│            ─ Financing entity                             │
└────────┬──────────────┬──────────────┬───────────────────┘
         │              │              │
         ▼              ▼              ▼
┌────────────┐  ┌──────────────┐  ┌──────────────────┐
│ PRÓSPERA   │  │ DELAWARE     │  │ SPINOUTS         │
│ OPERATING  │  │ US LLC       │  │ (each Delaware C │
│ SUBSIDIARY │  │ (employment, │  │  with own cap    │
│ (clinical, │  │  IP licensing)│ │  table)          │
│  research) │  │              │  │                  │
└────────────┘  └──────────────┘  └──────────────────┘
         │
         ▼
┌────────────────────────────────────────┐
│   BERMUDA CAPTIVE INSURANCE CO         │
│   Owned by Holdco                      │
│   Insures: med-mal, D&O, cyber, GL     │
└────────────────────────────────────────┘
```

### 7.1.1 Why Each Entity

**Cook Islands Trust:**
- Strongest debtor protection statute on Earth (creditors must re-litigate in Cook Islands; 2-year statute of limitations on fraudulent transfer claims)
- Shields Principal's personal assets if a program-related claim pierces all corporate veils
- Principal is the settlor + named discretionary beneficiary

**Cayman Holdco:**
- No corporate income tax
- Sophisticated financial sector with English-law commercial framework
- Standard vehicle for biotech IP holdings
- Spinout equity rolled up cleanly

**Próspera Operating Subsidiary:**
- Conducts the actual clinical and research activity
- Operates under Próspera's customized regulatory framework
- Workers are employees of this entity

**Delaware US LLC:**
- US employment of US-based staff (Boston satellite)
- Standard biotech IP licensing entity
- Allows Delaware-law contracts (most US biotech operates under)

**Bermuda Captive:**
- Self-insurance for medical malpractice, D&O, cyber
- Premium tax-efficient
- Reinsurance to commercial markets above $50M retention

**Each Spinout (Delaware C-corp):**
- Standard VC-fundable structure
- Cap table optimized for outside capital
- IP licensed from Holdco

---

## 7.2 Jurisdictional Strategy

### Primary: Próspera ZEDE, Honduras

**Status as of 2026:** Próspera operates under Honduras's Zone for Employment and Economic Development (ZEDE) framework. The Honduran government under Castro has moved to revoke ZEDE status; multiple international arbitration proceedings (ICSID) ongoing.

**Our exposure:**
- Próspera's legal framework allows customized regulatory regimes negotiated with the ZEDE Council
- The Próspera Health framework permits accelerated approval for therapies with established safety in other jurisdictions
- Several gene therapy / longevity companies have already operated there (Minicircle, etc.)

**Risk:** Honduras may successfully revoke ZEDE status before Phase 2. Probability: 20–40% by 2030.

**Mitigation:** All Próspera activity is dual-domiciled in Cayman. If Próspera regulatory framework collapses, operations relocate within 90 days. Specific contingency facilities pre-arranged in:
- Cayman (medical tourism infrastructure exists)
- St. Kitts (Caribbean stem cell tourism corridor)
- BVI

### Secondary: Cayman Islands

**Status:** Stable. Established financial sector. Reasonable medical regulatory environment.

**Use case:** Backup operating jurisdiction. Holdco domicile. Captive insurance secondary.

### Tertiary: International Research Vessel

**Status:** A medical research vessel flagged in Panama or Marshall Islands, operating in international waters beyond 12 nm of any coast, is subject only to flag-state law and the most permissive international treaties.

**Use case:** Worst-case fallback for procedures that become unlawful in all land jurisdictions. The vessel exists as a leased capability in Phase 0, owned outright by Phase 2.

**Cost:** ~$30–50M to acquire + outfit; $5–8M/yr to operate.

### Excluded: United States, EU, UK

The program **never** performs interventional procedures on the Principal in the US, EU, or UK. These jurisdictions have:
- Strict FDA/EMA/MHRA pre-approval requirements for novel therapeutics
- Aggressive enforcement of off-label use frameworks for novel combinations
- High litigation risk environment
- Press freedom that creates leak risk

Research, IP filings, employment of US/EU/UK staff in non-interventional roles is fine and necessary.

---

## 7.3 Specific Regulatory Considerations

### 7.3.1 Off-Label Use of Approved Drugs (Senolytics, TPE, TRT)

**Strategy:** All Tier 1 and Tier 2 Phase 0 interventions use **already-approved drugs** in off-label combinations. Off-label use is legal in most jurisdictions including Próspera; what is restricted is *marketing* off-label use, which we will not do (no patient recruitment, no advertising).

**Documentation:** Each protocol explicitly cites the published evidence base; the Principal signs informed consent acknowledging off-label use.

### 7.3.2 AAV Gene Therapy (Phase 1)

**Strategy:** Phase 1 introduces AAV vectors not yet FDA-approved. These will be:
- Manufactured under GMP in a Próspera-licensed facility (or contracted to a third-party GMP CMO)
- Administered under Próspera Health framework with documented Ethics Council approval
- Documented to a standard exceeding ICH-GCP

**The key risk:** an adverse event involving a non-FDA-approved AAV vector could attract attention if the Principal subsequently sought care in the US. Mitigation: medical records segregation, encrypted communication with treating physicians, optional alias for international medical records.

### 7.3.3 Partial Reprogramming (Yamanaka factors)

**Strategy:** OSK (not OSKM — c-Myc excluded due to oncogenic risk) delivered via AAV. This is approximately the Browder 2022 protocol. Several Altos and Retro programs are in pre-clinical primate work. Once *anyone* publishes Phase 1 human data on partial reprogramming, our regulatory environment improves dramatically.

**Timeline:** Realistically administered to the Principal in Phase 1 (Months 18–36). If no human data available by then, deferred to Phase 2.

### 7.3.4 Mitochondrial Transplantation

**Strategy:** Autologous mitochondrial transplantation has FDA Breakthrough designation (pediatric cardiac, McCully). For the Principal, autologous (own mitochondria from biopsy → enriched in vitro → reinjected) is the legally cleanest path.

**Heterologous (cetacean/avian) mitochondria are deferred to Phase 3+** and may never be done legally; remains an open question.

### 7.3.5 BCI Implantation

**Strategy:** When the Principal eventually receives a BCI (Phase 2 earliest), it will be a commercial device (Neuralink, Synchron, or successor) with regulatory clearance in at least one major jurisdiction. The Principal travels to the cleared jurisdiction for implantation; subsequent care at Próspera.

### 7.3.6 Germline Modification

**Absolute prohibition.** No germline edits at any phase. No embryo work of any kind. No exception. This is the bright line that distinguishes Project PROMETHEUS from a He-Jiankui-style scandal magnet.

If the Principal at some future point wishes to have heritable enhancements for offspring, that is a separate program requiring separate Board approval, fresh ethical review, and probably a different jurisdiction. Out of scope for this charter.

### 7.3.7 Xenotransplantation (Phase 3+)

**Strategy:** Pig-to-human xenotransplants are now in formal FDA-cleared trials (eGenesis, United Therapeutics). If the program reaches Phase 3, xenotransplant of specific organs (kidney, possibly heart) to the Principal would use FDA-cleared protocols at a US center.

---

## 7.4 Informed Consent Framework

The Principal signs:

1. **Master Consent** (per phase, refreshed each gate): Authorizes the program at conceptual level.
2. **Procedure-Specific Consent** (per intervention): Detailed risk/benefit, alternatives, right to withdraw.
3. **Data Use Consent** (annual): Authorizes use of Principal's data for spinout commercialization, anonymized where possible.
4. **Advance Directive** (one-time, updated quarterly): Specifies care preferences in event of incapacitation; specifies whether program continues with Principal's body if Principal is cognitively impaired.

All consent witnessed by GC + Principal's independent counsel (separate firm). Cooling-off period of 14 days between consent and procedure for any intervention not previously performed on Principal.

---

## 7.5 IP Strategy

### 7.5.1 Ownership

All inventions by employees during program work are owned by Holdco (employment agreements explicitly assign). Inventions by SAB members: program has right of first refusal at fair market rate.

### 7.5.2 Filing Strategy

- **Provisional patents:** filed within 30 days of any meaningful invention disclosure
- **PCT applications:** filed within 9 months of provisional
- **National phase entry:** US, EU, UK, China, Japan, Canada, Australia (rest of world by exception)
- **Trade secret protection:** for any process or formulation that cannot be reverse-engineered from a granted patent

### 7.5.3 Licensing & Spinouts

Each spinout receives a field-limited, exclusive license to specific IP from Holdco. Holdco retains:
- Reservation of rights for program (Principal's own care)
- Royalty stream (typically 3–8% of net sales)
- Right of first refusal on follow-on technology

### 7.5.4 Defensive Patenting

Some IP is filed defensively (to prevent competitors from blocking program directions) rather than commercially. The CSO + GC + IP counsel review quarterly.

---

## 7.6 Data Governance

### 7.6.1 Principal's Personal Data

The most sensitive data in the program. Stored in:
- Air-gapped vault at Próspera HQ
- Encrypted backup at Cayman
- Encrypted backup at Boston satellite (limited subset)

Access requires:
- Biometric + hardware key + 2-of-3 authorized parties (Principal + CMO + CEO, or CMO + GC + COO)
- All access logged immutably
- Quarterly access audit

The Principal's data is **never** transmitted across public internet in unencrypted form. Physical media transport for major datasets.

### 7.6.2 Research Data (Non-Principal)

Standard biotech data governance: GxP-compliant, electronic lab notebooks, audit trails, retention 25 years.

### 7.6.3 Right to Be Forgotten

Principal can demand destruction of any data at any time, with GC opinion on legal/insurance retention requirements. Default: data destruction on Principal request after retention statutes lapse.

---

## 7.7 Crisis Legal Playbook

Pre-drafted, on-retainer responses to:

**C1 — Major adverse event in Principal:**
- Immediate medical response under SOP
- GC notification within 1 hour
- CMO produces 6-hour incident report
- Crisis comms firm activates with pre-drafted statements
- Board emergency call within 24 hours
- Program pause pending review

**C2 — Press leak:**
- CSecO containment investigation
- GC reviews press claims for defamation potential
- Pre-drafted statements (selected from a library of 12 scenarios) deployed
- Principal does not engage personally without GC approval

**C3 — Regulatory inquiry (FDA, EMA, etc.):**
- GC sole point of contact
- No staff communication with regulators without GC presence
- Document preservation hold immediate
- External regulatory counsel (Hogan Lovells or similar) engaged

**C4 — Civil litigation:**
- GC selects defense counsel from pre-approved panel
- Captive insurance notification within 48 hours
- Discovery protocol activates (preserves attorney-client and work-product privileges)

**C5 — Criminal investigation (any jurisdiction):**
- Immediate program pause for relevant activity
- External white-collar criminal defense counsel engaged (Williams & Connolly tier)
- Staff individually represented (program funds their legal defense)
- GC personally retains separate counsel (to manage own exposure)

**C6 — Asset seizure / freeze:**
- Cook Islands trust structure activates protection
- Operating reserves at Cayman provide 12-month runway independent of US/EU banking
- Cryptocurrency operating reserves provide further independence

---

## 7.8 Public Disclosure Strategy

**Through end of Phase 1:** No public disclosure of the integration thesis. Spinout disclosures are component-specific and omit reference to a coordinated program.

**Phase 2 onwards:** Selective disclosure begins via peer-reviewed publication of individual components. Trade secrets retained where applicable.

**Phase 3+:** The Principal may begin to be publicly identified as a "longevity protocol participant" but never as a "Super Saiyan program subject" — phraseology matters for press and regulatory reception.

The Principal does not give media interviews about the program until program leadership and GC concur. Quarterly briefing to Principal on press posture.

---

## 7.9 Legal Budget (Phase 0)

| Item | Cost |
|---|---|
| Entity formation (Cayman, Próspera, Delaware) | $0.5M |
| Cook Islands trust setup + Year 1 admin | $0.4M |
| Bermuda captive setup + Year 1 premiums | $1.5M |
| IP firm retainer (18 months @ $35K/mo) | $0.6M |
| Tax counsel (international + US + Cayman) | $0.4M |
| Próspera regulatory counsel | $0.2M |
| Crisis comms retainer | $0.225M |
| Document automation + governance software | $0.1M |
| Reserve for unforeseen legal needs | $0.5M |
| **Subtotal Legal/Regulatory** | **$4.4M** |

(Above is detailed; rolled into doc 04's $3.0M legal line for Phase 0 with reserves covering overage.)

---

**Status:** Legal/Regulatory v1.0 — for review by inbound GC upon hire.
