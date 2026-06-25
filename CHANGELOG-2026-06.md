# Data Refresh — Change Log (June 25, 2026)

Verification pass against **ClinicalTrials.gov API v2** and authoritative drug references (Wikipedia/FDA label citations). Only changes confirmed by a live source are listed; entries verified as still-accurate are not enumerated.

## Status changes (existing entries corrected)

| Entry | Field | Was | Now | Source |
|---|---|---|---|---|
| Aficamten (Cytokinetics, HCM) | Phase + Drug name | Phase 3 / "Aficamten" | **Commercial / "Myqorzo (aficamten)"** | FDA approval Dec 2025; Phase 4 transition trial NCT07600177 recruiting |
| Nipocalimab (J&J, gMG) | Phase + Drug name | Phase 3 / "Nipocalimab" | **Commercial / "Imaavy (nipocalimab)"** | FDA approved (brand Imaavy) |
| Tremfya/guselkumab (J&J, Crohn's) | Phase | Phase 3 | **Commercial** | Approved for Crohn's/UC; Phase 4 real-world studies (NCT07616687) |
| Cobenfy (schizophrenia) | Company | Karuna Therapeutics | **Bristol-Myers Squibb** | BMS acquired Karuna; trials now list "Karuna…a Bristol Myers Squibb company" |
| VERVE-101 (FH) | Company | Verve Therapeutics | **Verve Therapeutics (Eli Lilly)** | Lilly acquisition of Verve |
| Recall: MYH7/MYBPC3 HCM | Lead companies | "Cytokinetics (Aficamten)" | "Cytokinetics (Myqorzo/aficamten — FDA approved Dec 2025)" | as above |

## New entries added

**Main opportunities (DATA) — 6 added:**

1. **Muvalaplin** (Eli Lilly) — Lp(a), *oral* small-molecule — Phase 3 (IMPACT, NCT07157774)
2. **Lepodisiran** (Eli Lilly) — Lp(a) siRNA — Phase 3 (ACCLAIM-Lp(a), NCT06292013)
3. **VERVE-102** (Verve/Eli Lilly) — PCSK9 base editing, lead successor to VERVE-101 — Phase 1/2 (NCT06164730)
4. **AMT-130** (uniQure) — Huntington's disease, HTT-lowering AAV gene therapy — Phase 1/2 (NCT04120493)
5. **Sibeprenlimab** (Otsuka) — IgA nephropathy, anti-APRIL — Phase 3 (VISIONARY, NCT05248646)
6. **Vanrafia (atrasentan)** (Novartis) — IgA nephropathy, endothelin antagonist — Commercial

**Recall by genotype (RECALL_DATA) — 1 added:**

7. **HTT (CAG repeat)** — Huntington's Disease — Genetics-First Enrollment, Phase 1/2 (uniQure AMT-130 + ASO programs)

## Verified unchanged (spot-checked, no edit needed)

- Lp(a) injectables **Pelacarsen** (Novartis, Ph3), **Olpasiran** (Amgen, Ph3), **Zerlasiran** (Silence, Ph2) — still trial-stage, none approved.
- **Inaxaplin/VX-147** (Vertex, APOL1) — pivotal study is a Phase 2/3 adaptive trial (NCT05312879, recruiting); "Phase 3" retained.
- **CagriSema**, **Survodutide**, **Fazirsiran** — confirmed Phase 3.
- **Vutrisiran/Amvuttra** — ATTR-CM indication confirmed approved (Mar 2025); already listed Commercial.
- **Tezspire/tezepelumab** — COPD still Phase 3 (not yet approved for COPD); asthma approval basis for "Commercial" retained.

## Notes / flagged for your judgment

- **BIIB122/DNL151** (LRRK2 PD): one Phase 3 (NCT05418673) was terminated in 2023, but a Phase 2 (NCT06602193) is active. Left as "Phase 2/3" — confirm whether you want to reclassify to "Phase 2."
- **BBP-631** (CAH gene therapy): some CT.gov records now list **Adrenas Therapeutics** rather than BridgeBio — possible program transfer. Not changed pending your confirmation.

## Data integrity
- DATA: 93 → **99** rows; RECALL_DATA: 31 → **32**; RECALL_PRECLINICAL_DATA: 17 (unchanged).
- All three arrays validated as syntactically correct JavaScript after edits.
