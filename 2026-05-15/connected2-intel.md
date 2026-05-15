# Connected2

**PRQ: Green** (Medium) · ICP B · **Liquidity wedge** · connected2.io

> UK HGV contract driver staffing platform; Clarity Pay in-house arm runs PAYE and Ltd driver payroll on a £0.80/hr operator fee, bridging the weekly payroll-to-invoice gap via a Sonovate invoice finance facility.

---

## At a glance

**🟢 Strengths**

Established 2018; niche focus on HGV contract driver supply with built-in compliance (Clarity Pay handles PAYE and Ltd payroll). App-based shift allocation reduces manual overhead for operators. £0.80/hr fee model is simple and predictable. Has survived 7 years in a specialist market.

**🔴 Weaknesses & pain points**

Net liabilities £436k (growing from £414k prior year) on a tiny asset base of £49k — structurally balance-sheet insolvent. Entirely reliant on Sonovate invoice finance to fund weekly driver payroll. Zero employees filed (all operations via contractor/outsource structure). Website returning 503 during research — potential operational instability. Three co-founders all resigned simultaneously June 2025; single Dutch director now sole officer.

**🟡 Payment posture**

B2B invoice model: operators receive a consolidated invoice from Connected2 for driver hours. Connected2/Clarity Pay disburses driver wages every Friday (PAYE or Ltd). Sonovate floating charge covers all assets and advances against the operator debtor book to bridge the payroll-to-collection gap. Sonovate is effectively the working capital engine of the business.

**🟡 PRQ / PayFac signal**

Full PRQ completed in discovery routine: Green (Medium confidence). Connected2 is the clear MoR: operator invoices go to Connected2, driver payments come from Connected2/Clarity Pay. No Stripe Connect signals. No marketplace pass-through. SIC 78109: Other employment placement agency activities.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | Not available | not-available |
| Total raised | Not applicable — no equity funding identified | |
| Last round | No equity rounds identified. Sonovate invoice finance charge (floating and fixed, all assets) registered June 2020 and outstanding — invoice finance is the primary working capital instrument. | |
| Cash on hand | Not disclosed (micro-entity accounts) | 31 March 2025 |
| Runway | Unknown; net liabilities £436k on a £49k asset base indicate structural reliance on Sonovate facility for solvency | estimated |
| Accumulated losses | Net liabilities £435,943 (FY2025); no retained earnings, capital and reserves in deficit | |
| Trade creditors | Not separately disclosed (micro-entity); current liabilities £479,848 (FY2025) |  |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Steven Zwinkels | Director (Managing Director) | active | Primary door. Dutch national (born 1985). Appointed 26 June 2025 when all three founders resigned simultaneously. Also founder of Hummingbird Logistics Services (Sep 2020). New management — inherited Sonovate relationship and all supplier contracts. |
| Simon Alexander Crick | Co-founder and CEO (departed) | Departed 2025-06-26 | Departed. Former CEO per blog post July 2020. Director from company incorporation July 2018. Resigned 26 June 2025. |
| James Baldwin | Co-founder and Director (departed) | Departed 2025-06-26 | Departed. Director from August 2018. Resigned 26 June 2025. |
| James Lomas | Co-founder and Director (departed) | Departed 2025-06-26 | Departed. Director from August 2018 (Isle of Man address). Resigned 26 June 2025. |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | ⚫ | Purely B2B invoice model; operators pay via bank transfer against consolidated invoice. No card acquiring requirement. No Synapto Collect opportunity identified. |
| Synapto Flow | 🟢 | Clarity Pay disburses weekly wages to PAYE and Ltd-company HGV drivers every Friday. Synapto Flow would replace or enhance this rail with automated per-shift payment triggers and embedded accounts for driver earnings. Embedded accounts dimension: a platform-level float account (Griffin-powered) could replace reliance on Sonovate-advanced cash to fund Friday payroll, giving Connected2 direct control of the float. |
| Synapto Advance | 🟢 | Sonovate holds a live floating and fixed charge (all assets) as invoice finance provider since June 2020. Triver (Synapto Advance) is a direct same-function replacement. New management (Steven Zwinkels, June 2025) has inherited this facility and may review it. Net liabilities of £436k on a £49k asset base mean finance cost reduction is operationally material. |
| Synapto Recover | 🟡 | B2B invoice book with operator clients who have 14-30 day terms. Sonovate's facility partially substitutes for debtors management, but if operator payment disputes or late payment occur, there is a debtors recovery need. Amber pending confirmation of operator invoice dispute frequency. |

## Payment flow

**Transport Operator** (consolidated weekly invoice from Connected2 for driver hours) → **Connected2 + Synapto** → **HGV Driver** (PAYE or Ltd-company contractor, paid weekly on Friday via Clarity Pay)

- Pays in: B2B
- Payouts: Yes — Clarity Pay (in-house arm) disburses weekly driver wages every Friday
- Beneficiary type: HGV Contract Drivers (PAYE or Ltd company)
- Float window: Driver wages paid every Friday for prior week; operator invoices likely on 14-30 day terms. Sonovate bridges the gap by advancing against the debtor book. Float window estimated 7-21 days.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| FY2025 (Mar 2025) | Not disclosed | Not separately disclosed; current liabilities £479,848 | Not separately disclosed; current assets £13,515 | Net liabilities (£435,943) | Net liabilities growing (£414k to £436k). Assets shrinking. Fixed assets amortising (£61k to £36k). Zero employees. Structurally reliant on Sonovate. |
| FY2024 (Mar 2024) | Not disclosed | Not separately disclosed; current liabilities £483,023 | Not separately disclosed; current assets £23,902 | Net liabilities (£414,568) | Similar structure. Large current liabilities dominated by Sonovate facility. Micro-entity exemption: no P&L filed, no cash line separately disclosed. |

_Micro-entity accounts filed (both FY2024 and FY2025). No P&L filed — small company exemption. Revenue not available: balance sheet inference unreliable because Sonovate invoice finance means the debtor book is effectively held by Sonovate, not on Connected2's balance sheet. Current assets of £13,515 likely represent residual debtors not yet factored plus minimal cash. No self-reported revenue figures found in press or founder interviews. Revenue classified as not-available. Third-party database estimates not used._

## Director & corporate activity

- **2025-06-26** 🔴 All three co-founders (Simon Crick, James Baldwin, James Lomas) resign simultaneously. Steven Zwinkels (Dutch, Hummingbird Logistics) appointed sole director. Complete management transition in one day — significant instability signal.
- **2020-07-02** 🟡 Sonovate Limited registers floating and fixed charge over all assets of Connected2. Invoice finance facility established as primary working capital mechanism.
- **2020-10** 🟢 Nick Hay (ex-Fowler Welch CEO, 10 years) joins Connected2 board as non-executive. Industry credibility hire. [Note: Hay not registered as CH director; board/advisory role.]
- **2018-08-10** · James Baldwin and James Lomas appointed as directors. Simon Crick (CEO) already director from incorporation.
- **2018-07-11** 🟢 Connected2 Limited incorporated. Simon Crick as founding director.

## PRQ preliminary findings

**MoR confirmed: operators invoice Connected2, not drivers**

Operator-facing pages: 'consolidated invoice from Connected2 detailing all drivers hours' confirms Connected2 is the sole invoice counterparty for operators. No pass-through to individual drivers. Classic employment agency MoR architecture.

**Clarity Pay handles driver contracting and payroll**

'Clarity Pay is the contracting and payroll function for Connected2. Clarity Pay runs the compliance checks, manages the contracting and makes payments to the drivers.' Connected2 is the legal employer/contractor; drivers are not paying parties. Full PRQ completed by discovery routine: Green (Medium confidence).

**Uber analogy used in market descriptions**

Third-party sources describe Connected2 as an 'Uber-style agency platform.' However, Connected2 itself uses 'direct sourcing platform' language, not Uber analogy. Employment agency model (Conduct Regs 2003) confirmed by Clarity Pay payroll function. Uber analogy is market commentary, not structural indicator.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Innovative digital-first platform transforming HGV driver supply | Website returning 503 Service Unavailable during research (May 2026). For a digital-first platform, website downtime is a reputational and operational risk signal. | Minor |
| Stable and growing platform for operators and drivers | Net liabilities £436k (growing), all three co-founders resigned simultaneously June 2025. Balance sheet and governance signals suggest significant underlying pressure despite outward marketing. | Material |
| Zero employees (filed accounts) | Micro-entity accounts show zero employees in both FY2024 and FY2025. Platform that manages driver payroll and compliance for multiple operators operates with no directly employed staff — raises questions about operational resilience and whether Clarity Pay staff are employed via a separate entity not researched here. | Minor |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Avail Logistics | n/a | par | Direct UK HGV driver staffing competitor (Hull-based). 3300+ shifts/month. £7.50/driver/day flat fee vs Connected2's £0.80/hr. Also today's Synapto prospect. |
| Driver Require | n/a | ahead | Established UK HGV recruitment agency with digital job board. Broader market reach, longer trading history. |
| HGV Driver Hub | n/a | par | App-based HGV compliance and staffing platform. Similar tech-first approach to driver-operator matching. |
| UGO Hub (canugo.co.uk) | n/a | par | Driver worker app for recruitment agencies. Targets the same compliance-and-pay workflow. |

## Outreach angles

### Primary, MD (Steven Zwinkels)

**Sonovate displacement — Triver advance at better economics**

Steven, when you took over Connected2 in June you inherited a Sonovate invoice finance facility that has been running since 2020. It funds the Friday Clarity Pay payroll run by advancing against your operator receivables — effective, but Sonovate's pricing is a standing drag on a balance sheet that is already net-liabilities negative. Triver (via Synapto Advance) advances against the same receivable book, typically at meaningfully better economics for staffing-sector volumes. Worth a 15-minute comparison before the facility auto-renews?

### Secondary, MD (Steven Zwinkels)

**Collapse Sonovate and Clarity Pay into one automated stack**

Connected2's weekly cash cycle has two moving parts: a Sonovate draw-down to fund payroll, then a Clarity Pay disbursement run to driver accounts on Friday. Synapto Flow handles both in one: automated per-driver payment on shift confirmation, with an embedded float account replacing the Sonovate advance. New management typically reviews inherited operational complexity — is the Sonovate/Clarity Pay architecture on your list?

### Tertiary, Tech lead or Head of Operations

**Automate the Friday payroll trigger from shift confirmation**

Connected2's app confirms driver shift completion automatically. The payment step is still manual: a Sonovate draw-down, then a Clarity Pay batch run. Synapto Flow's API fires a direct payment per driver the moment the shift is marked complete in your system — PAYE or Ltd, real-time, no separate reconciliation step. Is replacing the manual Friday batch a tech priority for the new management team?

---

_Synapto Intel · 2026-05-15 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: connected2-intel.json (in this folder)._