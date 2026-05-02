# Builders Merchants Federation

**PRQ: Green** (Medium) · ICP D · **Operational wedge** · bmf.org.uk

> UK building materials trade federation collecting member subscriptions and training fees in its own name across 1,020 merchant, supplier and service companies; 44% membership growth since 2020.

---

## At a glance

**🟢 Strengths**

Only UK trade body representing builders' merchants and their suppliers; dominant position with no sector competitor. 1,020 members across UK and Ireland; 44% membership growth since 2020. Well-regarded sector authority: Construction Leadership Council representation, Government engagement (Downing Street, parliamentary briefings). Uses iMIS AMS for membership management. BMF's own 'Branch of the Future' research identifies Payments and Pricing as a top-7 critical improvement area for the sector.

**🔴 Weaknesses & pain points**

CEO leadership gap from October 2026: John Newcomb moves to Executive Chairman, new CEO not yet appointed as of May 2026. Small operational team (~25-32 staff) handling 1,020 member billing relationships, training administration and event logistics - process intensity is high relative to headcount. Registered society structure means accounts are not publicly accessible at Companies House, reducing commercial intelligence.

**🟡 Payment posture**

Collects member subscription dues in own name. Additional revenue streams: training course bookings (BMF Campus from GBP 165/month), professional certification fees (IoBM annual membership), event registrations. Payment infrastructure runs through iMIS AMS - a specialist association management platform whose native payment processing capabilities are typically legacy card-gateway integrations, not optimised acquiring. No Stripe Connect or marketplace architecture. Direct Debit likely for annual subscription renewals.

**🟡 PRQ / PayFac signal**

Green (Medium confidence). Principal MoR confirmed for membership fee collection. No PayFac architecture. No Stripe Connect. No central-billing or rebate-distribution flow (unlike buying groups). Registered society structure is consistent with unregulated MoR. Affinity partner schemes (insurance, legal) are introducer-routed - not in own flow of funds.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | not-available | not-available |
| Total raised | N/A - member-funded | |
| Last round | Member-owned registered society; no external fundraising | |
| Cash on hand | not-available |  |
| Runway | N/A - member-owned, ongoing subscription income | estimated |
| Accumulated losses | not-available | |
| Trade creditors | not-available |  |
| Employees | 28 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| John Newcomb | Chief Executive | active | Primary door - CEO transitioning to Executive Chairman Oct 2026; ideal legacy-project window now |
| Richard Hill | Chairman | active | Board only - non-executive Chairman; term ends 30 Sep 2026 |
| New Chief Executive (TBC) | Chief Executive (incoming) | active | Future door - recruitment underway Q1 2026; target once appointed for operational excellence brief |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟡 | BMF collects subscription dues, training fees, CPD registrations and event bookings from 1,020 B2B member companies via iMIS AMS. iMIS typically runs on a legacy card-gateway integration (not modern acquiring); as membership has grown 44% since 2020 the fee income base has scaled but the payment infrastructure likely has not. Acquiring cost diagnostic is the opening question. Amber rather than Green because fund flows are modest scale and the organisation is small. |
| Synapto Flow | ⚫ | No outbound payout obligations to external beneficiaries. BMF pays internal staff via payroll and purchases services commercially - standard business banking, no split-payout architecture. Embedded accounts not immediately relevant. |
| Synapto Advance | ⚫ | Subscription income is collected upfront (annual renewals) or near-term (course bookings). No invoice book to advance. No working capital strain visible from public data. |
| Synapto Recover | 🟡 | 1,020 member companies on annual subscription renewal cycle. Even modest late-payment rates across a base of this size create meaningful manual chasing work for a ~25-person team. iMIS has basic dunning capability but automated recovery via Synapto Recover could reduce renewal failure and admin overhead. Amber because no explicit late-payment signal found in public sources. |

## Payment flow

**Member Companies** (1,020 merchants, suppliers, service companies) → **Builders Merchants Federation + Synapto** → **N/A** (N/A)

- Pays in: B2B
- Payouts: None - subscription income funds internal operations (staff, events, research, policy)
- Beneficiary type: N/A - trade federation; no downstream payout beneficiaries
- Float window: No float window: trade body collects subscriptions as principal and directs funds to internal operations. No split-payout or delayed settlement obligation.

## Director & corporate activity

- **2026-Q1** 🟡 BMF announces leadership transition: John Newcomb to become Executive Chairman from 1 Oct 2026; new CEO recruitment commenced February 2026
- **2026-10-01** 🟡 John Newcomb transitions to Executive Chairman; Richard Hill's chairmanship ends; new CEO takes operational charge
- **2025** 🟢 Membership reaches 1,020 companies - 37-year high and 44% growth since 2020
- **2025** 🟢 BMF All Industry Conference Barcelona; 'Branch of the Future' report published identifying Payments and Pricing as top-7 critical improvement area

## PRQ preliminary findings

**P1 - Entity is contracting principal**

BUILDERS MERCHANTS FEDERATION LIMITED registered as Co-operative and Community Benefit Society (No. 31516R). Member-owned mutual with limited liability. Entity structure consistent with collecting membership dues in own name as principal.

**P2 - Membership T&Cs imply own-name collection**

Membership T&Cs referenced in site footer. Pages not directly fetchable (403 on public user-agent). Verdict relies on entity structure and sector precedent rather than verbatim T&C extract. Confidence: Medium.

**Scale - 1,020 member companies**

1,020 merchant, supplier and service companies as at January 2025. GBP 52bn combined member turnover. 208,825 employees (members' employees, not BMF staff). Fund flows from BMF membership fees likely in GBP 1m-10m range [INFERENCE - no filed accounts available].

**No PayFac / Stripe Connect**

No marketplace language, no Stripe Connect reference, no third-party payout platform identified. iMIS AMS is the stated technology platform for membership management.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Membership T&Cs accessible on website | Footer references Membership T&Cs but pages return 403 on standard user-agents; content not verifiable | Minor |
| BMF represents all building materials businesses | Accurate: BMF describes itself as the 'only organisation' representing builders' merchants and suppliers in UK and Ireland; no direct sector competitor identified | None |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Federation of Master Builders (FMB) | n/a | par | Represents small building contractors, not merchants or suppliers; adjacent sector, not direct competitor |
| National Federation of Roofing Contractors (NFRC) | n/a | behind | Specialist roofing contractor federation; smaller scope; some member overlap with BMF supplier base |
| Builders Merchants Building Index (BMBI) | n/a | behind | BMF-sponsored data service reporting on sector sales trends; complementary to BMF, not a competitor |

## Outreach angles

### Primary, Chief Executive

**CEO transition legacy window**

John - you have five months before the operational handover. One thing that tends to get left to a new CEO rather than sorted beforehand: the payment infrastructure beneath the membership billing stack. 1,020 member renewals through iMIS, plus Campus subscriptions, events and CPD bookings - if the acquiring layer hasn't been reviewed since the last system upgrade, you're likely sitting on a meaningful cost and a non-trivial renewal failure rate. We've done this diagnostic with similar-size federations in 30 minutes. Worth a call before October?

### Secondary, Finance Director / Head of Operations

**Subscription billing automation**

BMF now has 1,020 member companies on annual subscription cycles, plus training and CPD streams through iMIS. As the billing base has grown 44% since 2020, the admin load scales linearly unless the payment infrastructure keeps pace. Synapto Collect optimises the acquiring layer beneath any AMS, reducing card failure rates and manual renewal chasing. One diagnostic call to surface your current failure rate and card cost - no commitment. Worth 20 minutes?

### Tertiary, Incoming Chief Executive (once appointed)

**Operational excellence on day one**

As the incoming BMF CEO, your brief explicitly covers financial stewardship and operational excellence for 1,020 member companies. The subscription billing infrastructure is one of the first things worth reviewing: iMIS handles the logic, but the payment rails beneath it may not have been optimised for the current scale. We work with comparable membership bodies. A 30-minute diagnostic before your first board meeting would give you a clear picture of where billing efficiency sits. Happy to arrange.

---

_Synapto Intel · 2026-05-02 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: builders-merchants-federation-intel.json (in this folder)._