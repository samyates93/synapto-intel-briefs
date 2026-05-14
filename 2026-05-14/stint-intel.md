# Stint

**PRQ: Green** (High) · ICP B · **Operational wedge** · stint.co

> UK on-demand hospitality shift platform matching student workers to restaurants and venues for 2-3 hour shifts; Stint acts as employment business, auto-debits businesses weekly on Mondays, pays workers on Fridays.

---

## At a glance

**🟢 Strengths**

Employment business MoR model confirmed via T&Cs and Companies House. No marketplace or facilitator language. 100,000+ Stinters registered. Serves GAIL's, PizzaExpress, Pret A Manger, Mitchells & Butlers and SSP Group. Losses more than halved from £8m (FY2023) to £3.3m (FY2025). AI workforce management platform in active development.

**🔴 Weaknesses & pain points**

Only £674k cash at March 2025 against £3.3m annual burn — extremely tight without ongoing equity injections. Headcount slashed from 112 (FY2023) to 47 (FY2025). Trade creditors up 108% YoY. Tax and social security liabilities up 167% YoY — cash stress signal. Glassdoor complaints about pay disputes and shift cancellations. Third-party dependency on ONSI for next-day pay.

**🟡 Payment posture**

B2B invoicing: businesses pay Stint via direct debit every Monday for prior week stints plus VAT. Stint pays Stinters on Fridays, using ONSI for next-day pay option. Businesses explicitly forbidden from paying workers directly. Float window: payroll pre-funded 3 days before collection.

**🟡 PRQ / PayFac signal**

PRQ: GREEN confirmed. Stint is employment business under Conduct Regs 2003. No facilitator or marketplace language in T&Cs. Businesses pay Stint, not workers. Introduction fee clause (£1,500) if businesses hire Stinters directly. Direct debit collection, no Stripe Connect evidence found.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | £4.8m–£10.3m | inferred |
| Total raised | ~£37m equity invested (share premium £37,079,725 at FY2025) | |
| Last round | Continuous rolling share allotments through 2026; £12.7m convertible loans converted to equity in FY2024; Graham Edwards (Edinv/Telereal Trillium) investor director since Dec 2021; WPGSS Ltd and HSBC Holdings PLC as PSCs from Nov 2022 | |
| Cash on hand | £673,567 | 2025-03-31 |
| Runway | ~2.5 months from Mar 2025 balance sheet; extended by ongoing rolling equity raises through 2026 | estimated |
| Accumulated losses | £35,689,176 | |
| Trade creditors | £132,135 | 108% YoY |
| Employees | 47 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Samuel Schlagman | Co-founder / CEO | active | Primary door — co-founder, operational CEO, director since Oct 2017 |
| Nicola Bowley | Director (likely CFO / Finance lead) | active | Secondary door — appointed Nov 2023 when Solomon stepped back; likely owns financial operations |
| Giovanni Ciuccio | Director (CTO / CPO) | active | Secondary door — likely tech and product decision-maker; director since Oct 2019 |
| Kaysan Nikkhah | Director (COO) | active | Secondary door — operations; director since Oct 2019 |
| Graham Edwards | Director / Investor (Edinv / Telereal Trillium family office) | active | Board only — investor director; confirmed via Startups Magazine interview; director since Dec 2021 |
| Solomon Schlagman | Company Secretary (co-founder) | active | Step-down signal — moved from director to Secretary role Nov 2023; co-founder operationally less prominent |
| Benjamin Schlagman | Former Director | Departed 2024-08-08 | [DEPARTURE SIGNAL] Resigned Aug 2024 — co-founder family member, born 2001, appointed Dec 2021 |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟡 | Businesses already pay via direct debit/standing order — collection is largely automated. Synapto Collect could improve payment intelligence and reduce failed debits but is not the primary pain point. |
| Synapto Flow | 🟢 | Stint pays 100,000+ Stinters weekly via third-party ONSI (EWA provider). Synapto Flow real-time payout rails and Griffin-powered earnings wallets could replace ONSI entirely, internalise the payout stack, and enable same-day pay — turning a third-party cost into a competitive moat vs Indeed Flex. Strong fit on both dimensions: payout rails and embedded Stinter earnings accounts. |
| Synapto Advance | 🟢 | Stint pre-funds Stinter payroll (Friday) before collecting from businesses (Monday), creating a structural weekly working capital gap. With only £674k cash vs £3.3m annual burn, Synapto Advance converting the weekly debtor book (£398k trade debtors) into same-day liquidity would reduce cash risk and enable same-day pay without balance sheet strain. |
| Synapto Recover | 🟡 | Stint invoices businesses weekly with VAT and charges 8% late interest for overdue payments — suggesting late payment is an acknowledged issue. The 167% surge in tax and social security liabilities (FY2025) may indicate collection pressure. However, weekly direct debit automates most collection, so Synapto Recover adds value at the margin (disputes and failed debits). |

## Payment flow

**Businesses** (weekly Monday direct debit for prior week stints + VAT) → **Stint + Synapto** → **Stinters** (weekly Friday payroll; next-day pay via ONSI (third-party EWA))

- Pays in: B2B
- Payouts: Weekly Friday payroll to 100,000+ Stinters; optional next-day pay via ONSI (third-party EWA provider — displacement target)
- Beneficiary type: Gig/shift workers (student Stinters)
- Float window: Stint pre-funds Stinter payroll on Fridays before collecting from businesses on Mondays — structural 3-day weekly float gap scaled across full weekly payroll volume; creates recurring working capital deficit

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| FY2023 (Mar 2023) | £1,235,456 | £12,582 | £308,744 | -£9,570,638 | Net liabilities due to £12.7m convertible loans on balance sheet; loss £8m; 112 employees at peak |
| FY2024 (Mar 2024) | £578,636 | £63,377 | £343,968 | £1,532,818 | Convertible loans converted to equity (balance sheet turned positive); headcount halved to 55; loss halved to £3.6m; trade creditors up 5x YoY |
| FY2025 (Mar 2025) | £673,567 | £132,135 | £397,834 | £1,391,099 | Trade creditors +108% YoY; tax and social security +167% YoY (£881k); loss £3.3m; headcount 47; cash critically tight at ~2.5 months runway without new equity |

_P&L not filed — small company exemption elected by directors. Revenue inferred from trade debtors (range £4.8m–£10.3m depending on DSO assumption; see revenue_note). Convertible loans of £12.7m converted to equity in FY2024, driving share premium from £19.1m to £33.9m. Ongoing rolling share allotments continue through 2026._

## Director & corporate activity

- **2017-10-19** 🟢 STINT LTD incorporated (as SKEEM LTD, renamed Jan 2018). Samuel and Solomon Schlagman founding directors.
- **2019-10-29** 🟢 Giovanni Ciuccio and Kaysan Nikkhah appointed directors — core leadership team formalised.
- **2021-12-08** 🟢 Graham Edwards (Edinv / Telereal Trillium family office) appointed investor director. Benjamin Schlagman also appointed.
- **2022-11-03** · Capital restructure: share cancellation and buyback filed. WPGSS Limited and HSBC Holdings PLC registered as PSCs (significant shareholders).
- **2023-11-01** 🟡 Solomon Schlagman steps down as director (moves to Company Secretary). Nicola Bowley appointed director — likely CFO or Finance Director hire to professionalise finance function.
- **2024-08-08** 🔴 [DEPARTURE SIGNAL] Benjamin Schlagman (co-founder family member, born 2001, appointed Dec 2021) resigns as director.
- **2025-03-31** 🟡 FY2025 accounts (filed Dec 2025): trade creditors +108% YoY, tax and social security +167%, cash £674k vs £3.3m annual burn. Rolling share allotments continue monthly through 2026.

## PRQ preliminary findings

**Employment business MoR model confirmed**

T&Cs state: 'Stint Ltd operates as an employment business.' Contract is between Stint Ltd and the Business. Contract for services between Stint Ltd and Stinters. Businesses 'not permitted to pay any sums directly to any Stinters directly for Stints.' Confirmed under Conduct of Employment Agencies and Employment Businesses Regulations 2003.

**VAT invoicing to businesses confirms billing principal status**

T&Cs: 'Stint Ltd shall charge VAT to the Business on top of the Stint Charges, at the prevailing rate. Stint Ltd shall provide the Business with a VAT invoice for all Stint Charges.' Stint is the billing entity, not a facilitator.

**Introduction fee clause confirms MoR not marketplace**

If businesses hire Stinters directly within the Relevant Period, they owe Stint Ltd a £1,500 introduction fee. Confirms Stint's proprietary relationship with workers and employment business positioning.

**No marketplace or facilitator language; no Stripe Connect evidence**

T&Cs use 'employment business' language throughout. No 'connects', 'introduces', 'facilitates', 'marketplace' or Uber-analogy language found. Payment method references direct debit and standing order only. No Stripe Connect evidence found.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Next Day Pay available for Stinters (homepage feature) | Next-day pay is delivered via ONSI (third-party EWA provider), not Stint's own infrastructure. Stint does not own this capability and pays ONSI fees. | Minor — third-party dependency, not a customer-facing deception; but creates a switching opportunity |
| 100,000+ flexible workers in the network | Glassdoor and Trustpilot reviews show workers complaining: 'too many people after very few shifts' and 'Stints don't show up — only available for old users.' Supply significantly exceeds demand for available shifts. | Material — supply-demand imbalance undermines Stinter satisfaction, retention and monetisation |
| AI-powered workforce management platform with fully optimised decisions | Glassdoor reviews (3.8/5, 208 reviews) note 'app doesn't work properly' and complaints about management direction. Employee reviews describe poor internal organisation. | Minor / Reputational risk |
| Reliable flexible pay for Stinters | Glassdoor reviews cite: 'lied about pay, constantly cancel work last minute without agreed compensation being paid.' Some workers report unpaid cancellation compensation. | Material — pay dispute and cancellation risk indicates payment operations strain; direct Synapto hook |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Indeed Flex (formerly Syft) | n/a | ahead | Acquired by Indeed/Recruit Holdings. Largest UK hospitality temp platform by scale. Has early payment options. Significant scale advantage over Stint. |
| Limber | n/a | behind | UK hospitality temp app, smaller scale than Stint. Similar flexible shift model. |
| Redwigwam | n/a | behind | UK flexible staffing platform with broader sector coverage but smaller hospitality footprint. |
| Qwick | n/a | behind | US-focused hospitality staffing; limited UK presence. |
| Crowdskills | n/a | behind | UK temp staffing app, smaller scale and sector footprint. |

## Outreach angles

### Primary, CFO / Finance lead (Nicola Bowley)

**Worker payout infrastructure: own it, don't outsource it**

Stint routes next-day pay for 100,000+ Stinters through ONSI, a third-party EWA provider. Synapto Flow replaces that dependency: real-time Friday payroll direct to Stinter earnings wallets (Griffin-powered), same-day rather than next-day, with the payout margin staying inside Stint rather than ONSI. Trade creditors are up 108% and your weekly float gap between Stinter payroll (Friday) and business collection (Monday) is a structural working capital drain. Are you reviewing your payout stack this year?

### Secondary, CEO / Co-founder (Samuel Schlagman)

**Turn your weekly float gap into a financial product**

Stint pre-funds Stinter payroll on Fridays and collects from businesses the following Monday. That structural 3-day float, across your weekly payroll volume, is real working capital tied up in the cycle. Synapto Advance converts your debtor book into same-day liquidity, letting you extend Stinter pay to same-day without a cash drag. At around £670k cash against £3.3m annual burn, tightening the working capital cycle matters. Worth 20 minutes?

### Tertiary, CTO / Tech lead (Giovanni Ciuccio)

**Embed payout intelligence into Stint AI**

Stint AI manages the staffing workflow. It cannot currently trigger instant payout on shift completion via its own rails. Synapto Flow's API fires a payment the moment a Stinter clocks out, replacing the ONSI dependency with a native Stint capability. Griffin embedded accounts give each Stinter an earnings wallet visible in the app. For a platform positioning on AI-powered workforce management, owning the pay layer is the next logical step. Is this on your tech roadmap?

---

_Synapto Intel · 2026-05-14 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: stint-intel.json (in this folder)._