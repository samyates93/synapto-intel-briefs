# Breedr

**PRQ: Green** (High) · ICP 1 · **Liquidity wedge** · breedr.co

> UK livestock trading marketplace; ~4,000 registered farmers; flat 2% seller commission; Breedr holds buyer payment in its bank account and releases to seller within 72 hours of animal collection.

---

## At a glance

**🟢 Strengths**

Confirmed MoR collect-and-release payment model with verbatim evidence. Only online livestock marketplace with integrated animal data and payment holding. AHDB partnership adds institutional credibility. Ian Wheal is an active, publicly accessible founder.

**🔴 Weaknesses & pain points**

UK entity net assets negative (-£1.88m); cash position critically thin (£133k); relies entirely on US parent intercompany funding; employees shrinking (28 to 20 over two years); no CFO or finance function at director level in UK entity.

**🟡 Payment posture**

Breedr collects buyer payments into its own bank account, holds funds during collection, and releases to seller within 72 hours. Flat 2% seller commission, no buyer premium. Seller payment timing is a core part of the value proposition. Current payment infrastructure not publicly disclosed.

**🟡 PRQ / PayFac signal**

PRQ: Green (High confidence) from discovery. Direct language on marketplace page: 'buyer pays into the Breedr Bank Account' and 'we'll release the payment to the seller on collection'. Confirmed ISV/MoR pattern. Full PRQ required before commercial engagement.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | ~£300k-£750k commission (marketplace); total group revenue unclear | inferred |
| Total raised | ~£14m (Series A + crowdfunding + earlier seed rounds) | |
| Last round | Series A £12m (led by Investbridge Capital, with LocalGlobe and Forward Partners), Mar 2022; plus £2.2m via Crowdcube crowdfunding at same time | |
| Cash on hand | £133,748 | 2024-12-31 |
| Runway | Dependent on intercompany funding from US parent (Breedr Holdings Inc.); net intercompany debt to parent is £1.9m (£2.61m owed to group minus £0.71m owed by group); standalone UK cash runway is weeks without continued parent funding | estimated |
| Accumulated losses | -£11,320,712 (Dec 2024) | |
| Trade creditors | £51,880 (Dec 2024) | -66.1% YoY |
| Employees | 20 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Ian Geoffrey Wheal | Founder and CEO | active | Primary door - sole active director; founder; all decisions pass through him |
| Anthony Oliver Richard Hogg | Director (Investbridge Capital representative) | Departed 2025-05-30 | [DEPARTURE SIGNAL] Investor board rep - resigned May 2025 after 3.5 years; signals investor stepping back from active governance |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟢 | Breedr collects all buyer payments into its own bank account - this is the core of the collect-and-release model. Direct PSP displacement angle: replacing or optimising the inbound collection rail would reduce per-transaction cost and simplify reconciliation for a 20-person team. |
| Synapto Flow | 🟢 | Seller payments within 72h of collection are the core payout rail - Synapto Flow directly addresses this. Embedded float accounts via Griffin would also allow Breedr to manage the collect-and-release window more efficiently, potentially holding buyer funds in a dedicated sub-account per transaction before release. |
| Synapto Advance | 🟡 | Breedr already operates a £10m cashflow fund for farmer advances (animals-as-collateral lending product). Synapto Advance could underpin or replace this, or provide working capital for Breedr UK itself given its thin cash position (£133k at Dec 2024). Dependent on whether Breedr wants to grow or exit the lending product. |
| Synapto Recover | ⚫ | Collect-and-release model means buyers pay before collection - no significant invoice debtors management pain. B2B but settled at point of transaction. Recovery angle not applicable. |

## Payment flow

**Buyer (farmer)** (B2B livestock buyer, pays on offer acceptance) → **Breedr + Synapto** → **Seller (farmer)** (Paid within 72h of collection)

- Pays in: B2B
- Payouts: To seller-farmers within 72h of livestock collection
- Beneficiary type: Seller farmers (registered UK livestock producers)
- Float window: Buyer pays into 'the Breedr Bank Account' on offer acceptance. Funds held until animal is collected. Seller paid within 72 hours of collection. Typical float window: 3-14 days depending on buyer collection timing.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| 2022 | £577,589 | £84,281 | £20,025 | -£722,870 | Cash healthy post-Series A (£12m raised Mar 2022); low trade debtors suggests limited marketplace activity at that point |
| 2023 | £93,478 | £152,979 | £26,634 | -£650,801 | Cash burned down sharply from £577k to £93k; trade creditors rose (vendor obligations); near break-even on P&L (~£72k improvement in accumulated losses) |
| 2024 | £133,748 | £51,880 | £145,918 | -£1,879,594 | Net loss of ~£1.23m; funded via £937k additional intercompany borrowing from US parent; trade debtors up 448% (marketplace growth signal); trade creditors down 66% (vendor debts cleared); UK employees down to 20 from 26 |

## Director & corporate activity

- **2018-02-27** 🟢 BREEDR LIMITED incorporated; Ian Geoffrey Wheal appointed director
- **2021-12-21** 🟢 Anthony Oliver Richard Hogg (Investbridge Capital) appointed director - marks Series A completion
- **2022-03** 🟢 Series A £12m closed (led by Investbridge Capital, plus £2.2m Crowdcube crowdfunding)
- **2022-02-08** · Charge 112272000003 created (debt instrument - likely venture debt or lending facility alongside Series A)
- **2023-08-14** 🟢 Charge 112272000002 fully satisfied - all debt instruments now cleared; company has_charges = false
- **2023-11-10** · Ian Wheal ceases as PSC; Breedr Holdings Inc. (US) notified as new PSC - US parent holdco structure created for international expansion
- **2023-02-02** · Registered office moved from Chichester to Tangmere (West Sussex) - operational address change
- **2025-02** 🟢 Full Circle Beef brand launched - supply chain traceability product connecting beef supply chain from ranch to retail
- **2025-05-30** 🟡 [DEPARTURE SIGNAL] Anthony Hogg (Investbridge Capital board rep) resigned as director - investor stepping back from active board governance after 3.5 years; Ian Wheal now sole active director of UK entity

## PRQ preliminary findings

**Verbatim MoR collect-and-release language on public marketplace page**

Breedr livestock market page states: 'Upon acceptance, the buyer receives notification via app and email, then makes payment to the Breedr Bank Account. The platform holds funds until collection is complete, then releases payment to the seller.' This is explicit ISV/merchant-of-record language. Breedr is the payment intermediary, not a facilitator.

**Float window confirmed - buyer-to-seller settlement gap is 3-14 days**

Buyer pays on offer acceptance; seller paid within 72 hours of animal collection. Buyer organises collection timing. Typical livestock collection lag: 3-14 days. Breedr holds float during this window.

**No buyer's premium - all monetisation via 2% seller commission**

Marketplace page confirmed: 'Breedr charges 2% commission on the sale to sellers. There is no buyer's premium.' Simple single-sided fee model. Synapto Collect would reduce the per-transaction cost of acquiring buyer payments.

**UK entity has no outstanding charges and relies on intercompany funding**

Companies House: has_charges = false. Previous charges all satisfied by Aug 2023. Current funding via £2.6m intercompany owed to Breedr Holdings Inc. (US parent). UK entity cash of £133k is insufficient for standalone operations.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Free to use livestock management app | Breedr app is free; marketplace commission only on completed transactions. No contradiction. | None |
| 4,000 British farmers on platform | Unverified; not in filed accounts. Self-reported marketing figure. Consistent with growth from 1,100 farms at Series A (March 2022). | Minor - unverified marketing claim, consistent with trajectory |
| Sellers paid within 72 hours of collection | Float window risk: if buyer delays collection, seller waits longer. 72 hours starts from collection date, not offer acceptance. Gap between offer and collection not capped. | Minor - timing risk borne by sellers if buyers delay collection |
| £10m cashflow fund for farmers | Self-reported; not independently verified. No evidence in UK Companies House accounts of this as a balance sheet item - may be funded via US parent or separate SPV. | Minor - funding source of the £10m not transparent |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| SellMyLivestock | n/a | behind | UK online livestock classifieds marketplace; appears to operate as an ad-listing model (buyer pays seller directly), not a payment intermediary. No data-driven animal profiles. Breedr leads on data and trust. |
| Traditional livestock auctions (Aberdeen and Northern Marts, Hexham, etc.) | n/a | ahead | Physical auctions remain dominant for cattle trading. Regulated, established trust, immediate settlement. Breedr competes on data, convenience and lower commission vs typical 4-6% auction fees. |
| FarmAds / Farming Ads | n/a | behind | UK livestock classified ad platforms. Buyer-to-seller payment direct, no intermediary. No data layer. Behind Breedr on trust and data. |
| AgriWebb | n/a | par | Australian-founded livestock farm management platform; strong on data and records but focused on management software rather than trading marketplace. Different segment to Breedr marketplace. |

## Outreach angles

### Primary, Founder/CEO

**PSP displacement - the collect-and-release rail**

Ian,

Building a livestock marketplace that farmers trust with their money takes real conviction. The collect-upfront, release-on-collection model is the kind of thing that works when the payment side holds up under it. The thing we hear most often from platforms with that same shape is that the back office handling the money movement takes more time than it should, particularly as transaction volume grows.

I'm Matt, founder of Synapto. We work with UK platforms that have a similar collect-and-release shape to Breedr. Would you be open to a 20-minute call? Happy to share what we've seen working in your space, and either way I'd value the conversation.

Congrats on the Full Circle Beef launch - the provenance-plus-trading combination is a genuinely interesting direction.

Matt

### Secondary, Founder/CEO

**International expansion - payment complexity at scale**

Ian,

Running a livestock trading platform across the UK, US and Australia - with the same collect-and-release model underpinning each market - creates a coordination question that grows with you. The operations piece that works at UK scale needs more thought when it's moving money in multiple markets. I'm Matt, founder of Synapto. We work with UK-based platforms that have a similar multi-market shape. The question we keep hearing come up is how to keep the payment back office lean as the platform scales. Would you be open to a 30-minute call to compare notes?

Matt

### Tertiary, Founder/CEO (technical background)

**App-native platform - payments as the natural next layer**

Ian,

The Breedr app solving the data layer for livestock - weight, medicine records, provenance, genetics - is the kind of vertical integration that takes years to build right. The next piece that tends to come up for a platform with that level of data is what the payment layer looks like. When you're already the trusted record of the animal's life, being the trusted handler of the money alongside it is a natural next step. I'm Matt, founder of Synapto. Would you be open to a 20-minute call? Either way I'd value the conversation.

Matt

---

_Synapto Intel · 2026-06-14 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: breedr-intel.json (in this folder)._