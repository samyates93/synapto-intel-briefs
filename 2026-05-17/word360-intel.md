# Word360

**PRQ: Green** (Very High) · ICP B · **Liquidity wedge** · word360.co.uk

> Birmingham-based UK language services platform (est. 1991); 15,000 freelance interpreters across 450 languages; NHS SBS, CCS, LPP and ESPO framework supplier; collects from public-sector clients on 14-day invoice terms and pays subcontractor interpreters per booking.

---

## At a glance

**🟢 Strengths**

One of the UK's largest NHS interpreting and translation providers. Five major NHS procurement frameworks (NHS SBS, CCS, LPP, ESPO, Healthtrust Europe). Proprietary Wordskii tech platform. 15,000-strong freelancer network. 450 languages. 30%+ annual revenue growth (self-reported). Recently appointed PwC-trained CFO for investment phase. Strong founder continuity (Tiku and Kavita Chauhan since 2013).

**🔴 Weaknesses & pain points**

Balance sheet data unavailable (small company exemption, S3 environment limitation). Trustpilot reviews show interpreter dissatisfaction (low pay, limited suitable jobs, travel distances). HSBC all-assets charge suggests reliance on bank working capital facility. Jackie Hendley director departure Dec 2024 leaves the board as two-director only.

**🟡 Payment posture**

Word360 collects from NHS trusts and public-sector bodies on 14-day invoice terms (T&C-confirmed; NHS practice often 30-45 days). Pays 15,000 freelance interpreters per booking or periodic batch. Float gap is structural. HSBC all-assets charge indicates an existing working capital facility to bridge this gap. Exact payout mechanism not publicly disclosed.

**🟡 PRQ / PayFac signal**

Employment/principal model confirmed. Word360 acts as merchant-of-record collecting from clients and paying freelancers as subcontractors. AMBER: preliminary compatible with Synapto Advance and Flow. No marketplace or introduction-only language. No Stripe Connect signals. Full PRQ required before commercial engagement.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | £8m-£10m estimated [INFERENCE] | inferred |
| Total raised | Not disclosed (no equity rounds identified) | |
| Last round | No equity funding identified. HSBC Bank PLC all-assets charge (fixed and floating) outstanding since September 2017. Single debt instrument in place. | |
| Cash on hand | Not available — CH accounts S3 access blocked in this environment |  |
| Runway | Not available — P&L not filed (small company exemption); balance sheet inaccessible via environment | estimated |
| Accumulated losses | Not available | |
| Trade creditors | Not available |  |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Tiku Chauhan | CEO / Director | active | Primary door. Co-founder. Director since Aug 2013. Sole PSC. Acquired business 2013 and grew from £600k turnover. |
| Kavita Chauhan (formerly Parmar) | Chief Commercial Officer / Director / Company Secretary | active | Co-founder. Director since Mar 2017, Secretary since Apr 2014. Built Wordskii tech platform. Strong CCO profile. |
| Colin Strevens | Chief Financial Officer | active | Appointed April 2024. PwC-trained (11 years). Partner at Heligan Group prior. Brought in to accelerate growth with investment. Not yet a statutory director per CH. |
| Jackie Hendley | Director (resigned) | Departed 2024-12-29 | [DEPARTURE SIGNAL] Resigned 29 Dec 2024 after nearly 5 years as director. No replacement director appointed per current CH record. |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟡 | NHS and public-sector clients pay via BACS on invoice terms; no consumer card flow. Synapto Collect has limited fit in the current model but could improve payment capture speed if Word360 expands into private-sector or consumer-facing services. |
| Synapto Flow | 🟢 | Dual fit. Payout rails: 15,000 freelance interpreters across hundreds of NHS trusts and LAs require per-booking disbursement at high frequency — currently likely manual batch, a clear automation target. Embedded accounts: Word360 needs a float account to hold NHS invoice receipts before disbursing interpreter pay, a direct use case for Griffin-powered embedded accounts replacing the current bank facility draw-down gap. |
| Synapto Advance | 🟢 | Primary fit. 14-day stated invoice terms against NHS/public-sector clients (government-backed, very high credit quality). HSBC all-assets charge outstanding since Sept 2017 suggests an existing working capital facility — Triver can compete on rate against HSBC or offer an invoice-advance overlay. Freelancer payouts are frequent; Triver funding the float gap eliminates dependency on the HSBC facility. |
| Synapto Recover | 🟡 | NHS and public-sector clients are reliable but slow payers (often 30-45 days in practice vs. 14-day terms). Automated invoice chasing on overdue NHS invoices would shorten average collection period and reduce the draw on the HSBC working capital facility. |

## Payment flow

**NHS Trusts and Public-Sector Bodies** (B2B, 14-day invoice terms) → **Word360 + Synapto** → **Freelance Interpreters** (15,000 subcontractors, per-booking settlement)

- Pays in: B2B
- Payouts: Per-booking or periodic batch to 15,000 freelancers
- Beneficiary type: Freelance interpreters and translators (subcontractors)
- Float window: 14-day client invoice terms (T&C-confirmed) vs. per-booking or periodic freelancer payments to 15,000 subcontractors. NHS and public-sector payment cycles typically run 30-45 days in practice.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| FY2024 | Not available (S3 403) | Not available | Not available | Not available | Total-exemption-full accounts filed 27 Aug 2025. P&L not filed. Balance sheet inaccessible due to environment limitation. |
| FY2023 | Not available (S3 403) | Not available | Not available | Not available | Total-exemption-full accounts filed 21 Sep 2024. P&L not filed. Balance sheet inaccessible due to environment limitation. |

_Both FY2024 and FY2023 accounts are filed as total-exemption-full (small company, P&L not filed). The CH document API S3 redirect returns 403 Forbidden in this environment — a known environment limitation documented in the routine. Revenue inferred at £8m-£10m based on self-reported 30% annual growth from £600k base (2013), per LDC Top 50 2024 feature. HSBC all-assets charge outstanding since Sept 2017 indicates existing working capital facility. No further balance sheet data available without direct accounts access._

## Director & corporate activity

- **2005-07-04** · Express Interpreting and Translation Ltd incorporated. Ratilal Karson Chauhan and Usha Chauhan appointed as directors.
- **2013-08-15** 🟢 Tiku Chauhan appointed director. Ratilal Karson Chauhan resigned. Business acquired by current founding team at £600k turnover.
- **2014-01-31** · Usha Chauhan resigned as director. Kavita Chauhan appointed company secretary.
- **2016-02-05** · Company renamed from Express Interpreting and Translation Ltd to WORD360 LTD.
- **2017-03-28** 🟢 Kavita Chauhan appointed director (CCO). Co-founder formally joins board.
- **2017-09-25** 🟡 HSBC Bank PLC all-assets charge registered (fixed and floating, negative pledge). Outstanding as of May 2026. Sole active charge.
- **2020-03-09** · Jackie Hendley appointed director.
- **2024-04-26** 🟢 Colin Strevens appointed CFO (not a statutory CH director). PwC background; brought in to support growth and investment strategy.
- **2024-12-29** 🔴 [DEPARTURE SIGNAL] Jackie Hendley resigned as director. No replacement director appointed per current CH record.

## PRQ preliminary findings

**MoR principal model confirmed. AMBER: preliminary compatible.**

T&Cs verbatim (per PRQ discovery): 'Charges means the charges payable by the Client to Word360 for the provision of the Services'; 'Staff means the employees of Word360 or Sub-contractors.' Word360 acts as merchant-of-record, collecting from NHS/public-sector clients and paying freelance interpreters as subcontractors. Not a marketplace or introduction-only model. No Stripe Connect signals found.

**NHS and public-sector debtor base: premium credit quality.**

Framework supplier on NHS SBS, Crown Commercial Service, London Procurement Partnership, ESPO, and Healthtrust Europe. Named NHS trust clients include UHB, Birmingham Women's and Children's NHS FT, Nottinghamshire Healthcare NHS FT, Somerset NHS FT, and others. Government-backed payment obligations confirm premium collateral quality for Triver.

**14-day stated invoice terms confirmed in T&Cs.**

PRQ discovery verbatim confirms 14-day client payment terms. NHS practice often extends to 30-45 days. Float gap between invoice and freelancer payout is structural and persistent.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Professional and reliable language services provider | Trustpilot shows some interpreters reporting 'few suitable jobs available, offers far away for low pay.' Mixed experience for freelancers on the network, suggesting supply-side dissatisfaction may limit interpreter retention. | Minor |
| Tech-enabled languages services with digital transformation focus | No public disclosure of payout automation or digital interpreter payment rails. Payout mechanism unknown. If payments are still manual, this contradicts the tech-forward positioning. | Minor |
| Growing revenues by over 30% a year (2024 LDC feature) | 30% annual growth from a small base is credible but not independently verified. No filed P&L. Balance sheet unavailable. Growth claim is founder-stated and unaudited. | Minor (unverifiable, not necessarily false) |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| thebigword | 1.3 (56 reviews) | ahead | Major NHS and public-sector language services provider. Trusted by 80% of top global 100 brands. Very low Trustpilot score — likely reflects interpreter dissatisfaction, not client experience. Direct NHS framework competitor. |
| LanguageLine | 1.4 (53 reviews) | ahead | Major UK/US interpreting provider. NHS framework supplier. Low Trustpilot score. Word360 competes directly on NHS video/telephone interpreting. |
| Capita Translation and Interpreting | n/a | ahead | Major NHS competitor. Part of Capita group. Historically strong on NHS frameworks. Word360 positions itself as more tech-enabled alternative. |
| Pearl Linguistics | n/a | par | Owler-listed direct competitor. UK language services. Scale and NHS exposure smaller than Word360. |
| Language Empire | n/a | par | UK interpreting provider. NHS and public sector focus. Trustpilot present but limited data available. |

## Outreach angles

### Primary, CFO (Colin Strevens)

**Displace the HSBC facility with a specialist NHS-invoice advance**

Colin, Word360 holds 14-day invoice terms across NHS SBS, CCS, LPP and ESPO frameworks — government-backed receivables that banks rate as premium collateral. Yet the HSBC all-assets charge filed September 2017 suggests the working capital stack has not been refreshed since before the platform scaled to 15,000 interpreters. Triver (via Synapto Advance) advances against NHS framework receivables at staffing-sector economics. Worth a 20-minute comparison before you close FY2025 with the same HSBC economics?

### Secondary, CEO (Tiku Chauhan)

**Automate 15,000-interpreter payouts with Synapto Flow**

Tiku, at 15,000 freelance interpreters across 450 languages, your payout desk is one of the most complex disbursement problems in UK language services. Synapto Flow replaces manual per-booking bank transfers with automated API-driven settlement, embedded float accounts for NHS invoice receipts, and per-interpreter payment history for HMRC compliance. How much manual reconciliation time does the finance team spend on interpreter payouts each week?

### Tertiary, CTO / Head of Technology

**Embed payments natively into Wordskii**

Wordskii is Word360's proprietary booking platform — the right integration point for automated interpreter payment rails. Synapto Flow's API embeds directly into booking workflows: booking confirmed, interpreter paid on completion, NHS invoice auto-generated. Removes the post-booking payment step entirely. What does your current payout trigger look like — manual approval or automated off booking status?

---

_Synapto Intel · 2026-05-17 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: word360-intel.json (in this folder)._