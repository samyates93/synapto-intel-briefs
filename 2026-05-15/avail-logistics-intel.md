# Avail Logistics

**PRQ: Green** (Medium) · ICP B · **Liquidity wedge** · availlogistics.co.uk

> UK HGV driver staffing platform (phoenix entity March 2024); 3,300+ shifts/month across PAYE and Ltd driver contracts; operators pay a weekly consolidated invoice plus £7.50/driver/day platform fee; weekly Friday payroll funded by Sonovate invoice finance.

---

## At a glance

**🟢 Strengths**

Active platform with 3,300+ shifts/month, 30,000 registered drivers, 94% fill rate, 4.8-star rating. Efficient 4-person back office indicates high operational leverage. Partnership with Logistics UK lends credibility. Weekly invoicing model provides predictable cash flow. Manchester base with national HGV coverage.

**🔴 Weaknesses & pain points**

Phoenix entity: predecessor Avail Technologies went into administration July 2024 (dissolved October 2025) after receiving Mercia/NPIF funding. New entity already in net liabilities (£160k) with no fixed assets. Sonovate charge secured immediately (July 2024) — same working capital pressure repeating. Only 4 employees managing 3,300+ monthly shifts — operational stretch risk at scale. Discovery row listed Erin Short as CEO; she resigned from the original entity in June 2021 and is not connected to the new entity.

**🟡 Payment posture**

B2B weekly invoice from operators: consolidated invoice detailing driver hours. Avail pays drivers weekly on Friday (PAYE or Ltd structure). £7.50/driver/day Avail platform fee charged to operator. Sonovate provides invoice finance advancing against operator receivables to pre-fund the Friday payroll run. Float window: driver wages paid Friday, operator collection typically 7-14 days later.

**🟡 PRQ / PayFac signal**

MoR confirmed from Truck and Driver snippet: Avail issues consolidated operator invoices and pays all drivers directly. No Stripe Connect signals. No marketplace pass-through language. SIC 78200: Temporary employment agency activities. Full PRQ completed in discovery: Green (Medium confidence).

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | £4-6m gross billing [INFERENCE] | inferred |
| Total raised | Not applicable to new entity; predecessor raised £350k (NPIF-Mercia, 2019) | |
| Last round | No equity funding in new entity (Avail Logistics Limited, incorporated March 2024). Predecessor Avail Technologies Ltd received £350k from NPIF-Mercia Equity Finance in July 2019 before entering administration July 2024. Sonovate invoice finance charge registered July 2024 on new entity. | |
| Cash on hand | Not disclosed (micro-entity accounts) | 30 June 2025 |
| Runway | Net liabilities £160k; structurally reliant on Sonovate invoice finance to fund Friday payroll ahead of operator collection | estimated |
| Accumulated losses | Net liabilities £160,101 as at June 2025 | |
| Trade creditors | Creditors within one year £242,825 (dominated by Sonovate facility) |  |
| Employees | 4 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Christopher James Watt | Director (Managing Director) | active | Primary door. Sole director of Avail Logistics Limited from incorporation (March 2024). Was also director of predecessor Avail Technologies Ltd from October 2022. British, born September 1985. Likely family connection to Keverne Watt (Chairman of predecessor entity). Bootstrapped new entity post-administration. |
| Erin Short | Co-founder and CEO of predecessor Avail Technologies (departed) | Departed 2021-06-04 | Not involved in current entity. Resigned from Avail Technologies Ltd June 2021. Discovery row listed as primary contact — this is incorrect for the new entity. Do not contact Erin Short as the Avail Logistics decision-maker. |
| Keverne Thomas Watt | Former Chairman of Avail Technologies (departed) | Departed | Was director of predecessor Avail Technologies Ltd from August 2018. Not on new entity Companies House register. Likely investor/family backer of Christopher Watt in new entity. May be a background influence. |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | ⚫ | B2B weekly invoice model. Operators pay by bank transfer against consolidated invoice. No card acquiring opportunity. |
| Synapto Flow | 🟢 | 3,300+ driver shifts/month require weekly payroll disbursement to PAYE and Ltd drivers every Friday. Current mechanism requires a Sonovate draw-down then batch payment. Synapto Flow's per-shift API trigger would automate each payment as a shift completes, remove the manual batch step, and reduce Friday payroll concentration risk. Embedded accounts dimension: a Synapto-powered float account could replace the Sonovate advance as the pre-funding mechanism for driver payroll. |
| Synapto Advance | 🟢 | Sonovate charge registered on Avail Logistics Limited in July 2024 (immediately after new entity formed). Predecessor also used invoice finance and still entered administration. Triver/Synapto Advance advances against the same operator invoice receivables. Direct displacement opportunity. With net liabilities £160k on a 15-month-old entity, cost of finance is material. |
| Synapto Recover | 🟡 | Weekly B2B invoices to transport operators. If operators dispute hours or delay payment, Sonovate facility is exposed. Synapto Recover's automated late payment chasing would protect the receivables that underpin the Sonovate advance. Amber pending confirmation of operator dispute frequency. |

## Payment flow

**Transport Operator** (weekly consolidated invoice for driver hours plus £7.50/driver/day platform fee) → **Avail Logistics + Synapto** → **HGV Driver** (PAYE or Ltd-company, paid weekly on Friday for previous week's shifts)

- Pays in: B2B
- Payouts: Yes — weekly Friday payroll run to all PAYE and Ltd drivers for prior week
- Beneficiary type: HGV Contract Drivers (PAYE or Ltd company)
- Float window: Driver wages paid every Friday for prior week. Operator invoices collected 7-14 days after. Sonovate advances against invoice book to bridge the 7-14 day float gap.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| FY2025 (Mar 2024 - Jun 2025, first period) | Not disclosed (micro-entity) | Creditors within one year £242,825 (Sonovate facility + trade payables) | Prepayments and accrued income £82,723 (operator invoices accrued) | Net liabilities (£160,101) | New entity, 15-month first period. Structurally loss-making from day one. Sonovate charge secured July 2024 as primary working capital instrument. 4 employees. No P&L filed. |

_Micro-entity accounts (first period: 30 March 2024 to 30 June 2025). No P&L filed — micro-entity exemption. No cash separately disclosed; no fixed assets. Revenue inference: accrued income £82,723 at weekly invoicing cycle implies gross billing approx £4-4.3m/year [INFERENCE — accrued income x 52 weekly cycles; consistent with 3,300 shifts/month x estimated £130/shift average billing]. Net platform fee revenue (at £7.50/driver/day): approx £297k/year [INFERENCE — 3,300 shifts/month x £7.50 x 12]. Total billing vs fee revenue distinction: gross billing is used as revenue in staffing agency P&L. Third-party estimates not used. Predecessor entity Avail Technologies Ltd last filed accounts to June 2022 (before entering administration)._

## Director & corporate activity

- **2025-10-04** 🔴 Avail Technologies Ltd (predecessor, CH 11402909) formally dissolved after administration ended July 2025. Mercia/NPIF investment lost. Original HGV driver platform no longer exists as legal entity.
- **2024-07-10** 🔴 Sonovate Limited registers floating and fixed charge over all assets of new Avail Logistics Limited — invoice finance facility secured immediately to fund driver payroll.
- **2024-07-03** 🔴 Avail Technologies Ltd enters administration (administrators: Andrew Haslam and Antonya Allison, Newcastle). Administration period runs July 2024 to July 2025.
- **2024-03-30** 🟡 Avail Logistics Limited incorporated by Christopher James Watt (sole director). Phoenix entity formed 3 months before predecessor's administration. Manchester registered address.
- **2022-10-17** · Christopher James Watt appointed director of predecessor Avail Technologies Ltd. (Likely son/family of Keverne Watt, Chairman).
- **2021-06-04** 🟡 Erin Short (co-founder and CEO) resigns as director of Avail Technologies Ltd after 3 years.
- **2019-07** 🟢 Avail Technologies raises £350k from NPIF-Mercia Equity Finance (£300k) plus £50k from Chairman Keverne Watt. 1,600 drivers registered at this time.
- **2018-06-07** 🟢 Avail Technologies Ltd incorporated by Erin Short and Callum Clark. Hull-based. £7.50/driver/day fee model from launch.

## PRQ preliminary findings

**MoR confirmed: operators invoice Avail, not drivers**

Truck and Driver: 'Avail pays everyone a week in lieu, every Friday'. Operator-side: 'consolidated invoice from Avail detailing all driver hours' plus £7.50/driver/day platform fee. Avail issues invoices to operators and pays drivers directly. Classic employment agency MoR.

**PAYE and Ltd driver structure confirms employment agency model**

Avail offers both PAYE and Ltd driver options. Avail handles 'all the payroll, tax and national insurance' (Bdaily, 2019). This is consistent with Conduct of Employment Agencies and Employment Businesses Regulations 2003 employment business model.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| One of the UK's fastest-growing HGV recruitment agencies | Predecessor entity (Avail Technologies) went into administration July 2024 after raising £350k from Mercia/NPIF. New entity has net liabilities £160k in its first 15 months. Growth claim is marketing for a phoenix company navigating financial fragility. | Material |
| 30,000+ registered drivers nationwide | This figure likely carries over from the predecessor entity's database. The new entity (Avail Logistics Limited) has only been trading since March 2024. The active driver count in the new entity is unknown. 3,300+ monthly shifts implies a smaller active pool. | Minor |
| 24/7 dedicated account management with 4 employees | Micro-entity accounts show 4 average employees managing 3,300+ monthly shifts and (claimed) 30,000 driver relationships. Operational stretch at this scale is a real risk and a likely reason the original entity struggled. | Minor |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Connected2 | n/a | par | Direct UK HGV driver staffing competitor (Bognor Regis). £0.80/hr fee vs Avail's £7.50/day. Also a Sonovate customer. Also today's Synapto prospect. |
| Driver Require | n/a | ahead | Established UK HGV recruitment with digital platform. Longer trading history, broader client base. |
| HGV Driver Hub | n/a | par | App-based HGV compliance and shift management. Similar technology-first positioning. |
| Best Connection (transport staffing) | n/a | ahead | Established national transport and logistics staffing. Significantly larger, traditional agency model. |

## Outreach angles

### Primary, MD (Christopher James Watt)

**Triver advance: avoid repeating the predecessor's working capital failure**

Chris, Avail Logistics picked up a Sonovate invoice finance charge in July 2024 — the same month the predecessor Avail Technologies entered administration under similar working capital pressure. Your Friday driver payroll for 3,300+ shifts/month is funded by advancing against operator invoices; the cost of that facility is a direct drag on a net-liabilities balance sheet. Triver (via Synapto Advance) advances against the same receivables at staffing-sector economics that are often meaningfully lower than Sonovate's. Worth a comparison before you lock in for another year?

### Secondary, MD (Christopher James Watt)

**Collapse the Friday payroll batch into an automated per-shift trigger**

Every Friday, Avail Logistics runs a payroll batch for every driver who worked the prior week — funded by a Sonovate draw-down, then reconciled across PAYE and Ltd structures. For 3,300+ shifts, that is a significant manual event with a 4-person team. Synapto Flow fires a payment to each driver the moment their shift is confirmed, removes the batch reconciliation step, and the embedded float account replaces the Sonovate advance as the pre-funding mechanism. Is reducing Friday payroll risk a priority as you scale?

### Tertiary, Tech or Operations lead

**Per-shift payment API to remove Friday payroll concentration risk**

Avail's platform processes 3,300+ driver confirmations monthly. Every payment for those confirmations happens in one Friday batch funded by Sonovate. That concentrates all payment risk, reconciliation effort, and cash exposure into a single weekly event. Synapto Flow's API fires each driver payment individually as the shift closes in your system — distributed throughout the week, with no Friday bottleneck and a full per-shift audit trail. Worth seeing how the API fits your shift confirmation flow?

---

_Synapto Intel · 2026-05-15 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: avail-logistics-intel.json (in this folder)._