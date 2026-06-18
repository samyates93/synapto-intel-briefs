# Xupes

**PRQ: Green** (High) · ICP 1 · **Margin wedge** · xupes.com

> Hertfordshire-based preloved luxury specialist (handbags, jewellery, watches via Chrono24 JV) operating since 2009 via showroom and global online, with outright buy and consignment models.

---

## At a glance

**🟢 Strengths**

Fifteen-year established brand with 5-star Trustpilot rating (1,560 reviews). Specialises in authenticated luxury handbags, jewellery, and accessories. 17th-century converted barn showroom in Hertfordshire plus 'Xupes at Sandersons' London presence. Strategic partnership with Chrono24 (global watch marketplace) separates the watch category and sharpens the handbag/jewellery focus. Strong authentication reputation from long-standing team (Reece Morgan and Debra Willis both deeply experienced in luxury retail).

**🔴 Weaknesses & pain points**

Cash fell 55% in 2024 (£791k to £356k). Retained earnings turned negative for the first time (-£47k, after +£333k in 2023). Share capital reduced by £100k in July 2024 (capital redemption - a shareholder exited). No finance director identified on Companies House. Small absolute scale for Adyen's typical enterprise tier. Stock declining (£932k to £824k) suggesting slower inventory cycle.

**🟡 Payment posture**

Dual model: outright purchase (Xupes is MoR, no payout to seller) and consignment (Xupes holds sale proceeds post-sale, pays consignor after returns window). Adyen named explicitly as PSP in T&Cs ('our secure online payment system provided by Adyen'). No Stripe Connect. Consumer payments flow to Xupes as MoR; consignor payouts are a scheduled float payout after returns window closes.

**🟡 PRQ / PayFac signal**

PRQ: Green (confirmed at discovery). Adyen named as PSP - Xupes is the acquiring merchant. No marketplace/facilitator language. Consignment flow: consumer pays Xupes, Xupes pays consignor post-returns-window - Xupes retains legal title to the inbound payment throughout. Full PRQ completed at discovery.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | £2m-£5m (inferred, not filed) | inferred |
| Total raised | Not publicly disclosed | |
| Last round | No external funding identified. Strategic JV with Chrono24 (German global watch marketplace, Chrono24 UK Ltd at same address) signed Oct 2021 for watches division. Long-term creditors £669k (Dec 2024) likely a shareholder or facility loan. | |
| Cash on hand | £355,805 | 2024-12-31 |
| Runway | Moderate; cash fell 55% year-on-year (£791k to £356k), retained earnings turned negative in 2024 (loss year after profitable 2023) | estimated |
| Accumulated losses | -£46,950 (Dec 2024; was +£333,007 in Dec 2023 - turned negative in 2024) | |
| Trade creditors | £228,330 total current liabilities (trade creditors not separately broken out) | -42.4% YoY |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Reece Morgan | Director, Handbags & Jewellery | active | Primary door - Director since Sept 2022, previously Head of Operations and Head of Handbags & Accessories since 2014. Commercial lead. |
| Debra Willis | Director, Handbags and Jewellery / Head of Jewellery & Accessories | active | Secondary door - Director since Sept 2022; ex-QVC jewellery buyer. Customer-facing (mentioned by name in Trustpilot reviews). |
| Mark Williams | Company Secretary | active | Secretary since Aug 2016; administrative contact only |
| Joseph Anthony McKenzie | Co-founder / Former Director | Departed 2022-01-21 | DEPARTED - Co-founder since 2009, resigned Jan 2022. Likely exited as part of Chrono24 JV transition. |
| Frank Edward McKenzie | Co-founder / Former Director | Departed 2022-09-08 | DEPARTED - Director since 2013, resigned Sept 2022. McKenzie family exit completed. |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟢 | Adyen named as PSP in T&Cs. High luxury ticket (handbags £500-£20k, jewellery £200-£5k) means card processing costs are a board-level line item. Interchange-plus acquiring from Synapto vs current Adyen blended rate is a direct per-transaction saving. Cash falling 55% YoY makes cost discipline relevant. |
| Synapto Flow | 🟡 | Consignment model creates a real payout flow: Xupes holds Adyen proceeds post-sale, pays consignors after returns window. Synapto Flow could automate this scheduled consignor payout and provide an embedded float account. Scale is boutique (est. £2m-£5m revenue) so volume may be at the lower end of Synapto's threshold - needs confirmation. |
| Synapto Advance | 🟡 | Cash down 55% in 2024 and retained earnings negative for the first time. Working capital advance against the consignor float (consumer card proceeds held pre-payout) or debtors book could address the liquidity squeeze. Dependent on confirmation of trading volume. |
| Synapto Recover | ⚫ | B2C retail with no evidence of B2B invoice terms. No debtors recovery application identified. |

## Payment flow

**Consumer / Online buyer** (B2C card payment via Adyen) → **Xupes + Synapto** → **Consignor** (Individual seller; paid post-sale after returns window (manual BACS assumed))

- Pays in: B2C
- Payouts: Yes - consignment model: consignors paid post-sale after returns window closes
- Beneficiary type: Consignors - individuals selling luxury items on a consignment basis
- Float window: Float exists between consumer card payment to Xupes (Adyen) and consignor payout post-returns-window. Returns window typical for luxury items is 7-14 days. Synapto Flow could automate these consignor payouts on a scheduled basis.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| 2023 | £791,390 | n/a (total curr liabs: £396,463) | £131,103 (debtors total) | £978,558 | Profitable year; retained earnings £333k positive; stock £932k; goodwill £48k on balance sheet |
| 2024 | £355,805 | n/a (total curr liabs: £228,330) | £94,916 (debtors total) | £498,601 | Loss year; retained earnings turned negative (-£47k); cash down 55%; share capital reduced £100k (capital redemption July 2024 - shareholder exit); stock declining |

_Total exemption full accounts (unaudited), year ending Dec 2024. P&L not filed (Section 444(5A) exemption). No employee count disclosed. Figures are for Xupes Handbags & Jewellery Ltd entity only; Chrono24 UK Ltd (watches) is a separate entity at same address._

## Director & corporate activity

- **2009-09-07** 🟢 Xupes incorporated. Joseph McKenzie and Frank McKenzie as founding directors.
- **2021-10-01** 🟢 Strategic JV signed with Chrono24 (MPN Marketplace Networks GmbH) for watches division. Chrono24 UK Ltd incorporated at same address. Watches business rebranded/transferred; Xupes retains handbags and jewellery.
- **2022-01-21** 🟡 Joseph McKenzie (co-founder) resigned as director. McKenzie family exit beginning.
- **2022-09-08** 🟡 Frank McKenzie resigned as director. Full McKenzie family exit complete.
- **2022-09-15** 🟢 Reece Morgan and Debra Willis appointed as directors. Post-JV management team formalised.
- **2024-07-03** 🟡 Capital redemption (SH02 filed): share capital reduced from £645,530 to £545,530. A shareholder (possibly Chrono24 or a McKenzie) exited via £100k capital redemption.
- **2025-09-18** · Total exemption full accounts for year ending Dec 2024 filed, showing first loss year since McKenzie exit.

## PRQ preliminary findings

**Adyen named as PSP - MoR confirmed**

T&Cs explicitly state 'our secure online payment system provided by Adyen'. Xupes is the merchant of record; consumer pays Xupes directly via Adyen. No Stripe Connect, no marketplace facilitation.

**Consignment payout flow - float exists**

Consignors are paid post-sale after returns window closes. Xupes holds inbound Adyen proceeds during the returns window. This is a legitimate non-regulated payout flow (Xupes retains title to inbound payment throughout).

**No marketplace or facilitator language**

PRQ confirmed no marketplace/facilitator signals. Outright purchase model and consignment model both route through Xupes as MoR. Full PRQ completed at discovery.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Strong established luxury brand (15 years, 5-star Trustpilot) | 2024 was a loss year for the first time since McKenzie exit. Cash down 55%. A shareholder exited via capital redemption in July 2024. Growth appears to have stalled post-Chrono24 JV transition. | Minor |
| Global online luxury destination | Debtors of £94k and stock of £824k suggest boutique scale, not the large-volume operation the brand positioning implies. Revenue est. £2m-£5m is at the low end of Adyen's typical enterprise tier. | Minor |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Vestiaire Collective | 4.2 (114000 reviews) | ahead | Global marketplace; vastly larger scale. VC is a marketplace (out of Synapto scope); Xupes is an outright buyer and consignor (in scope). |
| Designer Exchange | 4.3 (6000 reviews) | ahead | UK's largest preloved luxury retailer (also in today's brief queue). Six stores vs Xupes' one showroom. Similar Margin wedge profile. |
| Sellier Knightsbridge | n/a | par | Knightsbridge boutique; higher price points and tighter curation. Similar boutique positioning to Xupes. |
| Chrono24 | n/a | par | JV partner not a competitor for handbags/jewellery. Chrono24 UK operates the watch business from same address. |
| Bagista | n/a | behind | Knightsbridge handbag specialist; also in today's brief queue. Smaller footprint, hybrid consignment model. |

## Outreach angles

### Primary, Director (Reece Morgan)

**Primary**

Reece,

Fifteen years building a luxury preloved business from a converted barn in Hertfordshire into a brand people trust globally - and the Chrono24 partnership to bring in the watches expertise - that is a well-thought-through structure.

I'm Matt, founder of Synapto. We work with UK luxury retailers on the cost of taking card payments on high-ticket items, and the thing that comes up most with businesses your shape is the gap between what Adyen or your current provider charges as a blended rate and what an interchange-plus structure on a £5,000 Hermes bag actually looks like.

Would you be open to a 20-minute call to compare notes?

Matt

### Secondary, Director (Debra Willis)

**Secondary**

Debra,

Building a jewellery and handbag business where customers feel comfortable spending £5,000 with someone they have never met is not easy - the Trustpilot reviews suggest you have figured out the trust piece.

I'm Matt, founder of Synapto. We work with UK luxury retailers on two connected problems: the cost of accepting card payments on high-ticket items, and the mechanics of paying consignors after the returns window closes. The two tend to be more connected than they first look.

Would you be open to 20 minutes? Happy to share what we have seen working for similar boutique luxury businesses.

Matt

### Tertiary, Director (Reece Morgan) - operational follow-up

**Tertiary**

Reece,

A quick follow-up to my earlier note. The specific question I wanted to raise is around the consignor payout side - the gap between when the sale goes through and when the original owner gets paid. A few businesses we work with in luxury resale run that manually today, and automating it tends to remove a surprising amount of admin from the finance team each month.

Happy to walk through the mechanics in 20 minutes if that is useful.

Matt

---

_Synapto Intel · 2026-06-18 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: xupes-intel.json (in this folder)._