# CSD London

**PRQ: Green** (High) · ICP 1 · **Operational wedge** · csd.shop

> Manual consignor payout process breaking at scale - Trustpilot shows multiple sellers waiting months for payment, and a fresh October 2025 capital raise creates the window to fix it now.

---

## At a glance

**🟢 Strengths**

Two premium London locations (Notting Hill, Marylebone) with strong buyer-side Trustpilot reputation. October 2025 raised c.£1.57m in fresh share capital, giving runway. Staff headcount growing (23 to 27 in 2024). Significant CapEx (£150k in 2024) signals active expansion. Gamal Marwan is a committed founder-operator who navigated a full ownership transition in 2023-24.

**🔴 Weaknesses & pain points**

Net liabilities of £970k (Dec 2024) and accumulated losses of £2.72m signal a business still burning cash. Long-term creditors jumped from £79k to £1.38m in 2024 - likely director/investor loans, not disclosed in abridged accounts. Cash was £4k at year-end 2023 (crisis-level) before recovering to £83k. Trustpilot seller-side reviews consistently report payment delays of 7+ months - a reputational and operational time-bomb.

**🟡 Payment posture**

Accepts card payments (Klarna confirmed from T&C page). Pays consignors monthly batch BACS (per discovery source) or 2-4 business days after 14-day returns window (per website terms) - either way the actual execution is failing, per Trustpilot. No evidence of a modern payout API or automated settlement engine.

**🟡 PRQ / PayFac signal**

Green/High. CSD is seller of record on all consumer transactions. Consignors are disbursement recipients, not co-merchants. Payment terms and pricing set unilaterally by CSD. This is a clean principal-model consignment chain, not a regulated marketplace. No PI licence or FCA registration found.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | c.£4.3m GMV implied | Debtor triangulation: £362k debtors x 12 = c.£4.3m GMV. CSD net commission (15-35%) implies c.£650k-£1.5m net revenue. P&L not filed (abridged accounts). |
| Total raised | c.£1.57m (October 2025 share allotment) | |
| Last round | October 2025: share allotment lifted total capital from £1,750,000 to £3,323,600 - c.£1.57m injected. Replacement SH01 filed November 2025 to correct capital figure. Earlier Dec 2023 and Oct 2023 allotments brought paid-in capital to £1.75m after 2023 ownership transition. | |
| Cash on hand | £82,627 | Dec 2024 |
| Runway | Post-October 2025 raise (£1.57m) provides meaningful runway from a low base | estimated |
| Accumulated losses | £2,720,286 | |
| Trade creditors | £413,681 (due <1yr) + £1,380,928 (due >1yr) |  |
| Employees | 27 | average |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Gamal Marwan | CEO / Founder / Director | active | PRIMARY - decision-maker, PSC, sole beneficial owner |
| Giorgio Ammirabile | Director | active | Secondary - operational director |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | 🟡 | CSD already accepts card and Klarna. Switching acquirer at c.£4m GMV would save material processing cost but is secondary to the payout pain. Amber until volume/rate confirmed. |
| Synapto Flow | 🟢 | Primary fit. CSD needs automated per-sale consignor payouts triggered at returns-window close (14 days post-sale). Manual batch BACS is visibly failing - Trustpilot confirms 7+ month payment delays. Synapto Flow replaces the batch with event-driven settlement to consignor UK bank accounts. |
| Synapto Advance | 🟡 | CSD holds consignor inventory and has working capital stress (net liabilities £970k). Advance against receivables could ease cash pressure, but consignor obligations make the collateral structure complex. Secondary conversation. |
| Synapto Recover | ⚫ | B2C model - customers pay upfront or via Klarna. No meaningful B2B invoice receivables to chase. Not applicable. |

## Payment flow

**Consumer buyers** (card / Klarna) → **CSD London + Synapto** → **Consignors** (luxury fashion sellers, UK individuals/dealers)

- Pays in: Card (Visa, Mastercard, Amex probable), Klarna BNPL
- Payouts: Monthly batch BACS to consignors (current, manual, failing per Trustpilot). Website states 2-4 business days after 14-day returns window - execution is not matching this SLA.
- Beneficiary type: UK private individuals and small dealers
- Float window: 14-day returns window per sale before consignor can receive payment. CSD holds float during window and batch-pays at month-end.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| Dec 2023 | £4,009 | £343,576 | £220,036 | £46,290 | Crisis-level cash. Ownership transition complete. |
| Dec 2024 | £82,627 | £413,681 (<1yr) + £1,380,928 (>1yr) | £362,343 | -£970,286 | Cash recovered but net liabilities £970k. Long-term creditor jump (director loans) funds operations. Loss c.£1m in 2024. |

_Abridged accounts only; P&L not filed. Accumulated losses widened from £1.70m to £2.72m implying c.£1.0m operating loss in 2024. Long-term creditors jumped from £79k to £1.38m - almost certainly director or investor loans. Cash recovered from crisis levels (£4k Dec 2023) to £83k Dec 2024, suggesting a mid-year injection. Revenue not disclosed; debtor triangulation (£362k x 12) implies c.£4.3m GMV. October 2025 share allotment lifted total paid-in capital from £1.75m to £3.32m, injecting c.£1.57m of fresh capital post year-end._

## Director & corporate activity

- **Nov 2020** 🟢 Company incorporated. Gamal Marwan founding director.
- **Sep 2023** 🟡 Gamal Marwan removed as director (ownership/investor restructure).
- **Oct 2023** 🟡 Share allotment - capital £1,645,000. New investor capital.
- **Dec 2023** 🟢 Gamal Marwan re-appointed as director. Share allotment - capital £1,750,000.
- **Feb 2024** 🟡 Mohammad Shapan removed as director.
- **Mar 2024** 🟢 PSC statement withdrawn. Gamal Marwan formally registered as PSC (sole beneficial owner).
- **Jul 2024** 🟢 Giorgio Ammirabile appointed as Director.
- **Jul 2025** 🟡 Registered office moved Covent Garden to Ruislip. Mintplus Services Ltd appointed corporate secretary. PSC address update for Gamal Marwan.
- **Sep 2025** 🟡 Unaudited abridged accounts filed for year ended Dec 2024 - showing net liabilities £970k.
- **Oct 2025** 🟢 Share allotment filed - capital raised from £1,750,000 to £3,323,600 (~£1.57m injected). WHY NOW anchor.
- **May 2026** 🟢 Confirmation statement with updates. Gamal Marwan director address change.

## PRQ preliminary findings

**Seller-of-record confirmed**

CSD T&Cs confirm CSD sets all prices and acts as merchant on consumer sales. Consignors grant CSD authority to price and sell. Consumer purchase contract is with CSD, not the consignor. This is a principal consignment model, not an agent or marketplace model.

**Payout is a disbursement, not a regulated split**

Consignors receive 65-85% of CSD sale price, net of commission. CSD collects full consumer payment in its own name and disburses to consignors. No evidence of Stripe Connect, sub-acquiring, or client money segregation. Monthly batch BACS / per-sale settlement to UK bank accounts.

**No FCA registration or PI licence**

Companies House shows no FCA register reference. SIC codes 47799 and 47910 (mail order/internet retail) - retail not financial services. Confirmed non-regulated posture for current model.

**Returns window creates float**

14-day returns window per sale before payout is triggered. CSD holds float during this window. This is standard retail practice, not regulated activity.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Website: consignors paid 2-4 business days after 14-day returns window | Multiple Trustpilot reviews (seller-side) report waiting 7+ months for payment. Accounts team criticised in multiple reviews. Website SLA is not being met at current scale. | High |
| Company operating as a going concern | Net liabilities £970k at Dec 2024. Accumulated losses £2.72m. Long-term creditors jumped £1.3m (director loans funding operations). Business is technically insolvent without ongoing shareholder support. | High |
| Three London flagship stores (Notting Hill, Marylebone, possible third) | Two verified trading addresses (56 Ledbury Road W11, 70-72 Marylebone Lane W1U). Third store unconfirmed. Registered office is a Ruislip corporate secretary address, not a trading location. | Low |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Vestiaire Collective | 4.2 (c.20,000 reviews) | Global peer-to-peer luxury resale platform. Far larger scale. | Operates as marketplace (buyers/sellers transact directly) - different model to CSD's merchant model. |
| Hardly Ever Worn It (HEWI) | n/a | UK luxury consignment, online-only | Direct competitor for consignors and buyers. Online-only, no physical stores. |
| Sellier Knightsbridge | n/a | Knightsbridge luxury resale boutique | Adjacent discovery source. Single-store Hermes/luxury specialist. Similar affluent London demographic. |
| The RealReal | n/a | US luxury consignment giant | US-focused, recently expanded Europe. Known for payout delays and consignor complaints - same pain CSD has. |

## Outreach angles

### Primary, CEO / Founder

**Operational: consignor payout delays are a reputational risk you can fix now**

Hi Gamal - your buyer reviews on Trustpilot are excellent, which makes the seller-side complaints stand out sharply. Multiple consignors are publicly reporting waits of 6-7+ months for payment after sales complete. That kind of friction costs you consignor supply at exactly the moment you are expanding.

Synapto can replace your current batch payout process with event-driven settlement: the 14-day returns window closes, the payout fires automatically to the consignor's bank account. No manual BACS runs, no accounts-team bottleneck. Takes days to plug in.

Given the October capital raise, this is the right moment to fix the operational plumbing before you scale the store count further. Happy to show you how three other consignment businesses have done it.

### Secondary, CEO / Founder

**Margin: card processing cost at £4m+ GMV is worth reviewing**

Hi Gamal - CSD is processing meaningful card and Klarna volume across two premium stores and online. At your scale, the blended processing rate you pay to your current acquirer is likely 1.5-2.5%. Synapto's Collect product typically cuts that by 0.5-1pp for merchant-model retailers in your volume band.

On £4m GMV that is £20-40k per year that stays in the business. Worth a 20-minute conversation to check the numbers.

### Tertiary, CEO / Founder

**Timing: fresh capital - right moment to upgrade payment infrastructure**

Hi Gamal - congratulations on the October raise. Growing the store count is the right move and the timing for the operational infrastructure upgrade is now, while you have the capital and before the payout process becomes a bigger constraint on consignor supply.

Synapto works with consignment and managed-service businesses at this stage to automate the payout layer and bring card costs down. It is a one-week integration, not a project. Happy to share a short overview.

---

_Synapto Intel · 2026-06-18 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: csd-london-intel.json (in this folder)._