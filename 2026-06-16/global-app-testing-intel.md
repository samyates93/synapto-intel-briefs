# Global App Testing

**PRQ: Green** (Very High) · ICP B · **Operational wedge** · globalapptesting.com

> Enterprise crowdtesting and GenAI evaluation platform paying 145,000 vetted testers across 190 countries per-project on behalf of enterprise software clients.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | ~$18m USD (annualised) [INFERENCE] | inferred |
| Total raised | £10.6m | |
| Last round | BGF + FPE Capital, total approx. £10.6m, last known tranche linked to 2022 Santander charge event | |
| Cash on hand | $981,011 USD (31 Dec 2024) | 2024-12-31 |
| Runway | Cash declining ($1.25m to $981k YoY). Going concern reliant on majority investor backing per directors note. Real burn funded in part by intercompany credit facility at 10% p.a. | estimated |
| Accumulated losses | ($16,866,765) USD | |
| Trade creditors | $421,236 USD (2024) | 235% YoY |
| Employees | 22 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Nick Viney | Chief Executive Officer | active | Primary door - new CEO Nov 2024. Ex-Microsoft, Google, McAfee, Sycurio. Driving GAT AI GroundTruth GenAI pivot launched MWC March 2026. |
| Iqram Damiel | Director | active | Secondary door - appointed 2025-02-25. Role not confirmed publicly but likely COO or CFO. Owns operational/financial function. |
| Ronald Cummings-John | Co-founder (departed) | Departed 2025-01-24 | [DEPARTURE SIGNAL] Co-founder, 14 years. Resigned 2025-01-24 alongside Owais Peer. Now board observer per FPE Capital announcement. |
| Owais Peer | Co-founder / Finance Director (departed) | Departed 2025-01-24 | [DEPARTURE SIGNAL] Co-founder and finance function lead. Resigned 2025-01-24 same day as Cummings-John. Note: discovery row listed as CFO outreach target but role now vacant. |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟡 | B2B enterprise invoicing on Order Forms. Potential to streamline card or direct-debit collection on Monthly Plan clients. Not the primary pain point. |
| Synapto Flow | 🟢 | 145,000 testers across 190 countries need per-project disbursements. Trade creditors surged 235% YoY ($126k to $421k) signalling growing tester payout obligations outpacing cash. Synapto Flow rails directly address the cross-border tester payout problem. Embedded sub-accounts for tester earnings wallets also relevant at this scale. |
| Synapto Advance | 🟢 | Enterprise clients on 30-60 day terms, tester payouts required post-project. Cash declining ($981k) with going concern note. Advance against confirmed enterprise receivables (trade debtors $1.5m) would fund same-project or next-project tester payouts without relying on intercompany credit at 10% p.a. |
| Synapto Recover | 🟡 | Trade debtors $1.5m from enterprise clients. B2B Order Form model likely includes some overdue invoices. Corp tax recoverable $211k also outstanding. Invoice chasing automation relevant but not the primary wedge. |

## Payment flow

**Payer** () → **Global App Testing + Synapto** → **Beneficiary** ()

- Pays in: B2B
- Beneficiary type: Global crowd testers (freelance individuals, 145k vetted, 190 countries)
- Float window: Enterprise clients pay GAT per Order Form (30-60 day terms typical for B2B). Testers paid post-project completion. Float window estimated at 30-60 days, creating working capital demand as tester payout volume grows.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| 2024 | $981,011 | $421,236 | $1,496,701 | ($3,875,454) | Cash declining, trade creditors +235% YoY, net liabilities worsening. Going concern note: reliant on majority investor backing. |
| 2023 | $1,248,369 | $125,619 | $1,261,228 | ($2,935,370) | Net liabilities position established. Creditor base lower, cash healthier. |

## Director & corporate activity

- **2011-04-18** 🟢 SPA Worldwide Ltd incorporated. Ronald Cummings-John and Owais Peer appointed co-founders.
- **2017-12-22** 🟢 Simon Calver (BGF) appointed to board - BGF investment confirmed.
- **2021-03-16** · Ian Downing (BGF, Birmingham) appointed.
- **2022-08-16** 🟡 Ian Downing, Christopher Mathias, and Simon Murdoch all resigned same day. Santander charge registered. Likely refinancing/investor restructure event.
- **2024-11-26** 🟡 Nick Viney announced as new CEO (per FPE Capital press release). Co-founders stepping back from day-to-day operations.
- **2025-01-24** 🔴 [DEPARTURE SIGNAL] Ronald Cummings-John and Owais Peer both resigned as directors on same day. 14-year founders out. Finance function leadership gap created.
- **2025-02-03** 🟢 Nick Viney formally appointed as director on Companies House.
- **2025-02-25** · Iqram Damiel appointed as director. Likely COO or CFO to replace Owais Peer.
- **2026-03-23** 🟢 GAT AI GroundTruth launched at MWC Barcelona. New human-centred GenAI evaluation product across 120k evaluators in 190 countries. Major strategic pivot under Viney.

## PRQ preliminary findings

**Clean MoR structure confirmed**

T&Cs s2.1: Client pays GAT per Order Form. s8.3: testers described as subcontractors of GAT. Stripe confirmed as PSP (not Stripe Connect). GAT is the merchant of record for client payments and the principal disbursing to testers. Full PRQ returned Green (Very High confidence).

**Payment flow: enterprise B2B inbound, crowd outbound**

Enterprise clients on Monthly Plan or Bulk Buy Order Forms. Testers paid per completed project. Cross-border disbursement to 190 countries via unconfirmed but non-Connect payment rail.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Platform serves enterprise clients including Facebook, Microsoft, OpenAI, YouTube | Confirmed from website and press. G2 rating 4.7/5. Gartner Peer Insights listed. ISO 27001 certified. | Minor |
| 152 staff (from discovery row, likely 2022 figure) | CH accounts show average 22 employees in 2024, down from 32 in 2023. Discovery row figure significantly outdated. Team has been substantially reduced. | Material |
| 2-48 hour test turnaround | Advertised prominently. G2 reviewers generally confirm. Some reviews note generic reports requiring re-briefing. | Minor |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Applause (uTest) | n/a | ahead | Largest crowdtesting provider, 800k+ testers, 200+ countries. Subscription model. GAT positioned as faster and more enterprise-focused on AI evaluation. |
| Testlio | n/a | par | Integrated platform + freelance network. Originator of networked testing concept. Strong enterprise positioning. |
| Testbirds | n/a | par | Munich-based, 700k+ testers, enterprise crowdtesting. Strong European presence. |

## Outreach angles

### Primary, CEO

**Primary**

Nick,

Bootstrapped your way to OpenAI and YouTube as clients, then launched a new product category at MWC in the same month - not the usual trajectory for a company at your stage.

I'm Matt, founder of Synapto. We work with UK platforms that have a similar shape: enterprise clients on one side, a large distributed crowd to pay on the other, and a small core team holding it all together. The thing we hear most often from companies like yours is that moving money to the crowd takes more back-office time than it should, particularly when the product is expanding and every operational constraint shows up faster.

Would you be open to a 30-minute call? Happy to share what we've seen working in your space.

Matt

P.S. 'Think less testing, more evaluation' - solid reframe for GroundTruth. Curious how the reception landed at Barcelona.

### Secondary, Director (Operations/Finance)

**Secondary**

Iqram,

I'm Matt, founder of Synapto. We work with platforms that manage large distributed payments - typically a lean core team paying a global crowd per job - and the operational infrastructure question comes up in almost every conversation we have at the stage you're at.

GAT has just completed a significant leadership transition and launched a new product line in the same window. Both are high-signal moments for getting the financial plumbing right before the next growth phase makes it harder to change.

Would a 30-minute conversation be useful? Happy to show you what we have built and leave the decision with you.

Matt

### Tertiary, CEO (GroundTruth product angle)

**Tertiary**

Nick,

GroundTruth is a genuinely different play - real evaluators, real markets, executive-ready reports. The infrastructure to pay 120,000 evaluators across 190 countries per evaluation cycle is the part that determines how fast you can actually scale it commercially.

I'm Matt at Synapto. We have built the financial rail that lets platforms like yours consolidate client money in and crowd money out into a single operation. Worth 30 minutes to see if there is a fit?

Matt

---

_Synapto Intel · 2026-06-16 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: global-app-testing-intel.json (in this folder)._