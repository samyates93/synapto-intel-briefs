# Horticultural Trades Association (HTA)

**PRQ: Green** (Medium) · ICP D · **Operational wedge** · hta.org.uk

> UK garden industry trade body (1,400 members, est. 1899) that issues and manages the National Garden Gift Card closed-loop voucher scheme, processing ~£32.5m in card sales annually across 1,000+ redemption locations.

---

## At a glance

**🟢 Strengths**

UK's largest gardening gift card scheme (est. 1962), £32.5m annual throughput, 1,000+ redemption locations. Strong membership base of 1,359 garden centres and growers. Filed full accounts (not small company exemption), indicating financial transparency. Interest income of £412k suggests significant cash/investment reserves. Scheme is PSR-exempt (closed-loop issuer).

**🔴 Weaknesses & pain points**

Running an operating loss (£804k in 2024, £1.1m in 2023). Membership count slipping (1,380 to 1,359 YoY). Balance sheet not accessible due to filing retrieval limitation. No finance or payments roles currently being recruited - suggests back-office processes absorbed into existing team.

**🟡 Payment posture**

HTA issues and manages the National Garden Gift Card. ePay processes POS transactions at member garden centres. HTA holds funds from card sale until garden centre redemption. HTA retains 3% commission on each redemption. Settlement flow to 1,000+ members requires reconciliation of which card value belongs to which member and commission calculation. Float window up to 30 months (card validity).

**🟡 PRQ / PayFac signal**

Closed-loop voucher; HTA is the issuer; explicitly PSR-exempt. Full PRQ already completed - verdict Green. ISV pathway viable.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | £6,602,784 | filed |
| Total raised | N/A (trade body) | |
| Last round | No external funding; non-profit trade body; funded by membership subscriptions | |
| Cash on hand | Not extracted (balance sheet truncated in filing retrieval) | 31 Dec 2024 |
| Runway | Non-profit; membership-funded; not applicable | estimated |
| Accumulated losses | Not extracted (balance sheet truncated) | |
| Trade creditors | Not extracted (balance sheet truncated) |  |
| Employees | 80 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Fran Barnes | Chief Executive Officer | active | Primary door - CEO, strategy and operations owner |
| Stan Owen (James Stanhope Owen) | Chief Financial Officer | active | Secondary door - new CFO, appointed April 2025; will be reviewing back-office costs |
| Jon Dixon | Director of Gifting Sales | active | Tertiary door - owns the gift card scheme operations end to end |
| Will Armitage | HTA President | active | Board only - not primary outreach |
| Timothy Barnes | Director (former) | Departed 2025-09-25 | Departed - Sept 2025 board rotation |
| Matthew Bent | Director (former) | Departed 2025-09-25 | Departed - Sept 2025 board rotation |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | ⚫ | ePay handles POS card acquisition and consumer-facing payments. HTA's inbound payment infrastructure is ePay's problem, not obviously a Synapto Collect opportunity at this stage. |
| Synapto Flow | 🟢 | Core opportunity. HTA needs to settle 1,000+ member accounts per redemption cycle, netting off the 3% commission correctly for each member. Synapto Flow's payout rails could automate this settlement entirely. Embedded float account dimension also relevant - HTA holds £8-15m [INFERENCE] in unredeemed card value at any time; a Griffin-powered embedded account for this float would provide visibility and potential yield. Both payout-rails and embedded-accounts dimensions apply. |
| Synapto Advance | 🟡 | HTA holds a significant pre-redemption float and earns £412k in interest income - it is already putting cash to work. Synapto Advance for working capital conversion is not an obvious pain point. Amber because float visibility tools may still be relevant. |
| Synapto Recover | ⚫ | HTA is a membership body, not primarily a B2B invoicing operation. Membership subscription invoicing is likely low-volume and managed internally. No evidence of debtors pain. |

## Payment flow

**Consumers / Corporates** (Buy gift cards online and in-store via ePay) → **Horticultural Trades Association (HTA) + Synapto** → **Member garden centres (1,000+)** (Receive face value less 3% HTA commission on each redemption)

- Pays in: Both
- Payouts: Yes - net settlement to 1,000+ member accounts per redemption cycle
- Beneficiary type: Member garden centres (1,000+)
- Float window: Up to 30 months (maximum card validity); HTA holds all card face value from sale date until garden centre redemption; with £32.5m annual GMV the outstanding float at any point is likely £8-15m [INFERENCE based on typical gift card redemption curve]

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| 2024 | Not extracted | Not extracted | Not extracted | ~£2.2m | Operating loss £804k, narrowing from £1.1m in 2023. Interest income £412k suggests substantial cash/investments held. |
| 2023 | Not extracted | Not extracted | Not extracted | ~£2.7m (estimated from loss trajectory) | Operating loss £1.1m. Gift card GMV £32.0m. Turnover £5.2m. |

_Full accounts filed (P&L included). Balance sheet figures not extracted due to iXBRL document truncation in filing retrieval. Gift cards sold (£32.5m) is scheme GMV, not HTA revenue._

## Director & corporate activity

- **2025-09-25** 🟡 Board rotation: Brett Avery, Jacqui Prior, Martin Rowe appointed; Timothy Barnes, Matthew Bent, Brian Fraser resigned. Normal governance cycle.
- **2025-04-17** 🟢 James Stanhope Owen (Stan Owen) appointed as CFO - first dedicated CFO appointment visible in recent records.
- **2024-09-25** · Michael Burks appointed to board.
- **2024-06-13** · Mark Pitman appointed to board.
- **2023-03-22** 🟢 Frances (Fran) Barnes appointed as CEO/director.
- **2022-05-12** · William Armitage (President) and Alan Down appointed to board.

## PRQ preliminary findings

**Closed-loop issuer, PSR-exempt**

HTA issues and manages the National Garden Gift Card under its own name. Funds flow from consumer to HTA (issuer) and from HTA to member garden centres (settlement). This is a closed-loop instrument where HTA is the economic principal, not a payment facilitator. Closed-loop gift card schemes are explicitly exempt from PSR regulation. PRQ verdict: Green (from discovery PRQ).

**HTA holds funds pre-redemption**

Verbatim from discovery PRQ: 'HTA holds funds pre-redemption'. Card validity up to 30 months. HTA earns interest on the float (£412k interest receivable in 2024 accounts). This confirms HTA is the holder of the float, not ePay.

**ePay processes transactions**

Join-gift-card page confirms participants 'Actively sell and redeem the epay gift cards'. ePay is the POS processor. HTA is the issuer and settlement manager.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| UK's largest gardening promotion since 1962 - generating 2 million visits annually | Membership actually declined slightly (1,380 to 1,359 members YoY) and HTA is running an operating loss of £804k. The scheme is large but HTA is not generating a surplus from it. | Minor |
| Not-for-profit, reinvests subscription revenue into services | HTA does run a loss (net loss £453k in 2024), consistent with reinvestment. However, interest income of £412k on held funds suggests meaningful financial assets. No dissonance - minor framing only. | Minor |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| RHS Gift Card | n/a | behind | Royal Horticultural Society gift card is narrower (RHS gardens only); NGGC covers 1,000+ independent centres - much broader network. |
| Garden Centre Group gift vouchers | n/a | behind | Single-chain vouchers (Dobbies, Strikes, etc.) serve their own estate only; NGGC is cross-retailer and open. |
| One4all Gift Card (multi-retailer) | 3.9 | behind | Generic multi-retailer card; no gardening specialism; lower perceived gifting value for the category. |
| Love2shop | 3.8 | behind | Generic multi-retailer; does not specialise in garden retail. |

## Outreach angles

### Primary, CEO - Fran Barnes

**Primary**

Fran,

Running a gift card scheme that covers a thousand-plus independent garden centres - not a handful, a thousand - is a genuinely unusual operational achievement, especially as a membership body rather than a funded tech company.

I'm Matt, founder of Synapto. We work with UK organisations that collect money centrally and then need to pay it out correctly across a large network of independent businesses. The thing we hear most often from finance teams in that situation is that the reconciliation - calculating what each member is owed after the commission is netted off, then getting the money to them without errors - takes more time than it should.

Would you be open to a 20-minute call? Happy to share what we have seen working in similar setups, and either way the conversation would be useful.

Matt

### Secondary, CFO - Stan Owen

**Secondary**

Stan,

Congratulations on joining HTA. One of the first things a new CFO in a membership body typically lands on is the gift card settlement - specifically, how the reconciliation and the member payouts actually work, and what it costs the team to run it correctly each cycle.

I'm Matt, founder of Synapto. We work with organisations running payment flows across large networks of independent members or partners - where the challenge is getting the right net amount to each member, reliably, without the finance team having to touch it individually.

With the National Garden Gift Card scheme processing well over a thousand redemption points, that reconciliation piece is a natural place to look. Would a 20-minute call be worth putting in the diary?

Matt

### Tertiary, Director of Gifting Sales - Jon Dixon

**Tertiary**

Jon,

The gift card scheme you run - £30-plus million in annual sales, accepted at over a thousand garden centres, operating since 1962 - is not something many membership bodies have built and kept running at that scale. Credit to the team.

I'm Matt, founder of Synapto. The part of the scheme we tend to look at is the back end: once a card is redeemed in a garden centre, how does the settlement get calculated and paid out to that member, net of the commission? At the volumes you're running, that reconciliation step is where most of the operational time tends to sit.

Would 20 minutes to compare notes be useful? No agenda beyond seeing whether what we do fits.

Matt

---

_Synapto Intel · 2026-06-28 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: horticultural-trades-association-hta-intel.json (in this folder)._