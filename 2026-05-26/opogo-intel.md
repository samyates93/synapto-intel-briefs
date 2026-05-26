# Opogo

**PRQ: Green** (Very High) · ICP B · **Liquidity wedge** · opogo.com

> UK app-based school staffing platform (London + Manchester) supplying invigilators, supply teachers and cover staff as an employment business; schools pay net-15 invoices, workers paid per assignment.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | ~£37m annualised [INFERENCE: debtor-days method, trade debtors £3.1m x 12] | inferred |
| Total raised | Venture debt from Investec (amounts undisclosed) | |
| Last round | Two outstanding Investec Capital Solutions venture debt charges (2019 and 2021). Parent: Digital Network Assembly Limited (100% owner). No new equity rounds identified. Corporate restructure underway: two new subsidiaries created January 2026 (Opogo Education Ltd, Opogo Services Ltd). | |
| Cash on hand | £15,925 (Dec 2024 - effectively zero) |  |
| Runway | Critical constraint. £15k cash vs £1.1m non-current liabilities (Investec). Advance against school receivables is not optional - it is the operating model. | estimated |
| Accumulated losses | (£185,063) net liabilities - technically insolvent balance sheet | |
| Trade creditors | Current liabilities £2,226,489 (Dec 2024) - breakdown not filed | 79% YoY |
| Employees | 30 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Justyn Randall | CEO and Founder | active | Primary door |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟡 | B2B invoice collections from schools/MATs at net-15 terms. Automating remittance reconciliation would help but is secondary to the cash constraint. |
| Synapto Flow | 🟢 | Per-assignment payouts to supply teachers, invigilators and cover staff. Synapto Flow replaces manual payout cycle, provides real-time visibility for workers, and integrates with the Opogo app booking layer. Two new subsidiaries (Opogo Education, Opogo Services) created Jan 2026 suggest the payout function may be separating from the booking function - this is exactly the architecture where a clean payout rail adds value. |
| Synapto Advance | 🟢 | Effectively critical. Opogo has £16k cash on hand against £3.1m trade debtors and £2.2m current liabilities. The business is operationally solvent (growing debtors, 30 staff) but structurally cash-constrained. Advancing against school net-15 invoices (school = high credit quality) would fund worker payroll, reduce Investec dependency, and support the restructure into separate operating entities. This is the highest-urgency Advance opportunity in the current run. |
| Synapto Recover | 🟡 | Net-15 school invoices with £3.1m debtors and near-zero cash means any late-paying school is a cash-flow event. Automated chasing is a direct operational benefit. |

## Payment flow

**Payer** () → **Opogo + Synapto** → **Beneficiary** ()

- Pays in: B2B
- Beneficiary type: Self-employed supply teachers, invigilators, cover staff
- Float window: Schools invoice at net-15 working days. Workers paid per assignment. With £3.1m trade debtors (Dec 2024, up 83% YoY), Opogo is funding a growing worker payroll from a near-zero cash position. The working-capital gap is structural and growing - the debtors book has almost doubled in 16 months while cash has fallen from £33k to £16k.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| 2023 (Aug YE) | £33,286 | included in current liabilities £1,242,579 | £1,696,973 | (£302,785) net liabilities | Already cash-constrained; debtors £1.7m, cash £33k. |
| 2024 (Dec YE, 16-month period) | £15,925 | included in current liabilities £2,226,489 | £3,108,512 | (£184,963) net liabilities | Debtors up 83% (growth). Cash down 52% (squeeze). Non-current liabilities up to £1.13m (Investec). Net liabilities improved slightly (£185k vs £303k) suggesting improved operating performance but structural cash constraint unresolved. |

## Director & corporate activity

- **2019-09-05** 🟡 First Investec venture debt charge registered
- **2021-10-11** 🟡 Second Investec venture debt charge registered - series extended
- **2024-05-01** 🟢 Company extended accounting period from Aug to Dec year-end - restructure preparation
- **2026-01-21** 🟢 Two new subsidiaries created: Opogo Education Limited (16979347) and Opogo Services Limited (16979349) - corporate restructure underway

## PRQ preliminary findings

**Employment-business MoR confirmed**

T&Cs Cl.3: 'Opogo, acting as an employment business'. Assignment fee paid by client school to Opogo. Cl.17: net-15 settlement terms.

**Net-15 school invoicing confirmed**

Cl.17: 'settle all invoices within 15 working days'. This is a short payment term relative to LA-funded IFAs (net-30/45) but school network is broad.

**No marketplace/facilitator language found**

Discovery row confirms T&C review. No Stripe Connect or PayFac signals identified.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Opogo is the transparent, ethical alternative to traditional supply agencies (opogo.com) | Net-liabilities balance sheet and £16k cash suggest the business model is operationally tight. Growing debtors without proportional cash growth = working-capital dependence on informal or Investec credit lines. | Minor |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Supply Desk / Hays Education | n/a | ahead | Incumbent supply teaching agency. Larger, established. Opogo pitches as tech-first alternative. |
| Zen Educate | n/a | par | VC-backed direct-hire platform. Similar tech-first proposition. May have cleaner funding. |
| Connex Education | n/a | par | Also in this run. Employment-business model, South West focus. Different geography. |

## Outreach angles

### Primary, CEO and Founder

**Primary**

Justyn,

Building a staffing platform where the schools pay net-15 and the teachers expect to be paid per booking creates a pretty specific cash-flow shape - you're effectively funding a payroll from a debtors book that's growing faster than the cash comes in.

We've built a product for exactly that: advance against confirmed school invoices at a rate that makes the working-capital cycle self-funding rather than something you have to manage around. Schools as debtors are high credit quality, so the cost is materially lower than standard debt.

We also have a payout rail that sits inside apps like yours - worker gets paid per booking, you get one reconciled view. Given the restructure you're running, the timing feels right.

Worth 20 minutes?

### Secondary, CEO and Founder

**Secondary**

Justyn,

You're building a platform that separates itself from traditional supply agencies on teacher experience - and one of the biggest things teachers care about is getting paid correctly and quickly after each booking.

We power the payout side of this for several staffing platforms: per-assignment, automated, real-time visibility for the worker in-app. It's the infrastructure piece that turns 'we pay faster than the big agencies' from a claim into a feature.

With Opogo Education and Opogo Services now running as separate entities, having one clean payout layer across both makes the ops simpler, not harder.

Happy to show you what this looks like in practice. 20 minutes?

### Tertiary, CEO and Founder (tech angle)

**Tertiary**

Justyn,

The Opogo app is a well-built product - the booking and compliance layer is clearly working given the growth in placements. The part that's harder to build natively is the money movement: paying teachers per booking, reconciling across schools, advancing against invoice to smooth the cash cycle.

That's exactly what we've built as an embedded layer for platforms like yours. API-first, sits behind your existing UI, handles the messy parts (payroll, deductions, bank-grade compliance) so you don't have to.

Would 20 minutes to walk through the integration pattern be useful?

---

_Synapto Intel · 2026-05-26 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: opogo-intel.json (in this folder)._