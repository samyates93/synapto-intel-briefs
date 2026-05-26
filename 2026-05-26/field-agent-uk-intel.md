# Field Agent UK

**PRQ: Green** (High) · ICP B · **Liquidity wedge** · fieldagent.co.uk

> UK mobile retail audit and mystery-shopping platform dispatching 200k+ self-employed shoppers to FMCG brand and retailer clients on B2B invoice contracts, paying shoppers per completed task via Interact e-Transfer.

---

## At a glance

**🟢 Strengths**

200k+ vetted shopper network across UK - one of the largest crowdsourced retail audit populations in the market. Blue-chip FMCG client base: Mars, Sanofi, Johnson and Johnson, Sainsbury's, ASDA, Marks and Spencer. Mobile-native platform with real-time task dispatch and structured data capture. US parent ($17.5m Series B, Sep 2024) provides funding and technology backing. Agent Participation Agreement explicitly names Field Agent UK Limited as contracting and paying party - clean regulatory structure. Trustpilot 4 stars, 138 reviews.

**🔴 Weaknesses & pain points**

UK entity has just 1 employee (down from 3 in 2024) - extremely lean for a platform operating a 200k-shopper network. Micro-entity accounts filed - no P&L or detailed balance sheet; revenue entirely opaque. Trustpilot complaints include payment delays and dispute resolution failures: 'took over a week to reply', 'found excuses not to refund'. Creditors <1yr up 38% YoY, suggesting payout obligations growing. No dedicated finance or payments lead publicly visible.

**🟡 Payment posture**

FMCG brands and retailers pay Field Agent UK on B2B invoice terms (net-30 assumed standard). Field Agent UK pays shoppers per completed and approved task via Interact e-Transfer. The float window is the gap between brand invoice settlement and per-task shopper payout. With 200k+ active shoppers, the aggregate weekly payout obligation is material. Current mechanism (Interact e-Transfer, manually triggered or batch) creates both a Liquidity wedge (invoice advance vs FMCG debtors) and a Flow opportunity (automated per-task disbursement replacing current batch process).

**🟡 PRQ / PayFac signal**

PRQ: Green confirmed. Agent Participation Agreement explicitly names Field Agent UK Limited as contracting entity and payment processor for agents. B2B invoice clients pay Field Agent UK; Field Agent UK pays shoppers. No marketplace or facilitator language. No Stripe Connect identified. Preliminary posture: fully compatible with Synapto ISV pathway.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | Not available | not-available |
| Total raised | Not disclosed at UK entity level; US parent $17.5m Series B (Sep 2024) | |
| Last round | No external funding at UK entity level. UK entity is subsidiary of Field Agent Inc. (Fayetteville, Arkansas). US parent raised $17.5m Series B Growth Equity round Sep 2024. | |
| Cash on hand | Not disclosed (micro-entity accounts; cash not itemised separately from current assets of £122,780 at May 2025) | May 2025 |
| Runway | Not determinable - UK entity has 1 employee and is supported by US parent | estimated |
| Accumulated losses | Net assets £53,082 (May 2025); positive retained equity, no accumulated losses evident | |
| Trade creditors | £63,682 creditors due within 1 year (May 2025) | 38% YoY |
| Employees | 1 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Robin Shuker | Managing Director | active | Primary door - founded UK entity May 2017, operational authority |
| Gwenaelle Deloux | Director | active | Secondary - appointed Oct 2023, likely from US parent |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | ⚫ | Clients are FMCG brands and retailers paying on B2B invoice terms. Card acquiring is not relevant. Collect not a fit. |
| Synapto Flow | 🟢 | 200k+ shoppers receiving per-task Interact e-Transfer payouts. Automating disbursement via API at task approval - same-day, per-task, no batch run - directly solves the current payout friction evidenced by Trustpilot complaints. With only 1 UK employee, automation is structural necessity not a nice-to-have. Strong fit. Embedded accounts: float management account for the UK entity to hold received brand invoices before disbursement would also be viable. |
| Synapto Advance | 🟢 | B2B invoice receivables from FMCG brands and retailers (net-30 assumed) against a known weekly shopper payout obligation. Triver advance against verified brand invoices converts the float gap into available cash and removes the working capital constraint on taking on more brand campaigns. US parent Series B growth context makes this an acute need. |
| Synapto Recover | 🟡 | B2B invoice clients exist (FMCG, retailers). Invoice disputes are unlikely with blue-chip clients but slow settlement from large procurement systems is common. Recover is secondary to Flow and Advance but worth mentioning in a second conversation. |

## Payment flow

**FMCG Brand / Retailer** (B2B invoice terms (net-30 assumed)) → **Field Agent UK + Synapto** → **Self-employed Shopper** (Per-task Interact e-Transfer payout)

- Pays in: B2B
- Payouts: Interact e-Transfer per completed and approved task
- Beneficiary type: Self-employed shoppers (200k+ UK network)
- Float window: Float window exists between B2B client invoice settlement (net-30 assumed) and per-task shopper payout. With 200k+ shoppers completing tasks weekly, aggregate payout volume is material. Shopper Trustpilot complaints about payment delays confirm the current timing gap is a live shopper retention issue.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| May 2025 | Not separately disclosed | £63,682 (<1yr) + £10,926 (>1yr) | Not separately disclosed | £53,082 | Creditors <1yr up 38% YoY; employees down to 1; US parent growth round funding expansion |
| May 2024 | Not separately disclosed | £46,171 (<1yr) + £27,793 (>1yr) | Not separately disclosed | £43,370 | 3 employees; interco creditor high (£27,793 >1yr, likely US parent loan) |

_Micro-entity accounts filed annually; no P&L, no detailed balance sheet line items. Revenue not available. Current assets and creditor totals only. UK entity is a subsidiary of Field Agent Inc. (Fayetteville, Arkansas) which raised a $17.5m Series B Growth Equity round in Sep 2024. Revenue inference not possible from available balance sheet data._

## Director & corporate activity

- **2024-03-04** 🟡 Director details change (CH01), PSC change (PSC04), and registered office address change (AD01) filed on same date - potential UK entity restructure or PSC update following parent Series B preparations
- **2023-10-17** 🟡 Gwenaelle Deloux appointed director - new board appointment, likely from US parent following period of growth
- **2021-05-07** · Robin Shuker director details change and PSC update - routine administrative filing
- **2017-05-05** 🟢 Field Agent UK Limited incorporated; Robin Shuker appointed founding director

## PRQ preliminary findings

**Explicit MoR contract - Green**

Agent Participation Agreement: 'This Agreement is between you and Field Agent UK Limited' and 'Field Agent or its Affiliates will process all payments to Agents.' UK entity is confirmed as contractual counterparty for both brand clients and shopper payouts. No facilitator or marketplace language identified. Full PRQ completed by discovery routine - verdict Green, High confidence.

**No Stripe Connect identified**

Agent FAQ confirms Interact e-Transfer as payment mechanism. No third-party split-payment infrastructure visible. Field Agent UK processes payments directly, consistent with MoR structure.

**No charges registered**

Companies House confirms has_charges: false. Clean security position for Synapto Advance against brand debtor book.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Fast, accurate retail information and shopper insights | Trustpilot: some reviewers report tasks rejected after completion with no compensation for time, and payment disputes taking over a week to resolve | Minor - operational friction in shopper payment dispute process, not a brand client issue |
| 200k+ strong UK shopper network | Trustpilot reviewers complain about insufficient tasks in their area and inability to earn consistently - network size may mask low task density outside major cities | Minor - geographic coverage gap, not commercial |
| Reliable payouts and platform transparency | Trustpilot: 'took over a week to reply', 'found excuses not to refund', payment dispute resolution described as poor by multiple reviewers | Reputational risk - shopper retention signal; Synapto Flow automation would reduce dispute surface area |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Mystery Shoppers Ltd | n/a | behind | UK mystery shopping incumbent (1989); 350k shoppers but 28-day payment standard vs Field Agent's faster Interact payout |
| Roamler | n/a | par | Dutch crowdsourced retail audit; operates in UK; comparable crowdsourcing model |
| CPM Group | n/a | ahead | Full-service outsourced sales and merchandising; larger operation, employed field teams not gig workers |
| Sonata GBW | n/a | par | Global mystery shopping network, 100+ countries; traditional provider vs Field Agent's tech-native approach |
| Premise | n/a | par | US-based crowdsourced data collection; similar gig-worker model; competes in UK enterprise accounts |

## Outreach angles

### Primary, Robin Shuker, Managing Director

**The per-task payout at scale**

Robin,

Running payouts to 200k+ shoppers on a per-task basis is one of the more complex back-office problems in the UK platform market. Every approved job needs to trigger the right amount to the right person - and at your scale, the gap between a batch process and automatic same-day payment per task approval is a real operational difference.

We work with platforms like yours to close that gap. The payout fires at approval, no batch run, one UK employee's Friday afternoon back.

Worth a 20-minute call to see if the API sits neatly behind what you've already built?

Best,
[Name]

### Secondary, Robin Shuker / Finance lead

**The Series B growth moment**

Robin,

The US parent's growth round is designed to accelerate the platform - more brand clients, more campaigns, more shoppers active every week. That's the right problem to have.

The question that comes with it is whether the payment infrastructure scales with the volume or becomes the constraint on growth. Several crowdsourced platforms have found the payout batch process is the thing that breaks first when volume doubles.

We help platforms get the back office sorted before the growth arrives rather than after. Happy to show you what that looks like in 20 minutes.

Best,
[Name]

### Tertiary, Robin Shuker / Technical lead

**The approval-to-payment gap**

Robin,

Your platform handles task dispatch, structured data capture, quality control review, and approval - all in real time on mobile. The payment step after approval is the one place where the automation doesn't match the rest of the product.

We build the API that closes that gap - task approved in-app, shopper paid the same day, no separate batch. A few crowdsourced-task platforms are using it to remove the Friday payout run entirely and use same-day pay as a shopper retention differentiator.

Worth 20 minutes to see how it sits behind what you've already built?

Best,
[Name]

---

_Synapto Intel · 2026-05-26 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: field-agent-uk-intel.json (in this folder)._