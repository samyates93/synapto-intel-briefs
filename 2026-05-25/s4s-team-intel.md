# S4S Team

**PRQ: Green** (Medium) · ICP B · **Operational wedge** · s4steam.com

> Sheffield-based locum dental nurse and hygienist staffing agency placing across 30+ North and Midlands towns on PAYE and guaranteed-hours contracts with same-day booking SLA, mobile app for shift management, and a client-facing booking portal.

---

## At a glance

**🟢 Strengths**

7+ years in locum dental staffing. Mobile app (iOS/Android) for nurses: shift booking, availability scheduling, timesheets, document uploads. Client Shift Manager Portal for dental practices. CQC-compliant documentation generated 'within minutes'. REC corporate member. Same-day booking availability. PAYE and guaranteed-hours contracts - both employment models. S4S Dental Laboratory group connection (Matt Everatt) opens dental lab network as warm referral channel. Two apprentice recruiter hires in 2024-25 indicate active scaling.

**🔴 Weaknesses & pain points**

Neil Bullement director departure Feb 2025 - recent governance change. [DEPARTURE SIGNAL - third founding director left after 7 years; reason unknown]. Financial data not available (total-exemption-full, no P&L). Revenue est. ~£3.2m - moderate scale. PRQ confidence Medium: PAYE confirmed but dual-status model needs T&C verification. No Trustpilot data found.

**🟡 Payment posture**

Dental practices pay on invoice terms via Client Portal. Nurses paid PAYE or guaranteed-hours weekly. Mobile app manages shift acceptance and timesheet submission - payroll step is manual downstream of app. The Operational gap is between app-confirmed timesheets and same-day BACS disbursement.

**🟡 PRQ / PayFac signal**

PRQ: Green (Medium confidence). Website explicitly states PAYE model and guaranteed-hours contracts. SIC 78109/78200 (employment placement and temp agency). Employer-side compliance (DBS, GDC, indemnity managed). Dual employment model (PAYE + guaranteed hours) should be confirmed in T&C review before commercial engagement.

---

## Revenue & funding

| Metric | Value | Note |
|---|---|---|
| Revenue | Est. ~£3.2m [INFERENCE - third-party source ($4m); treat as unreliable. No P&L filed (total-exemption-full accounts).] | inferred |
| Total raised | Not disclosed (SYMCA grant/skills support received, amount not stated) | |
| Last round | No external funding. SYMCA South Yorkshire Combined Authority skills support received (grant/training subsidy). Bootstrapped. Revenue est. ~£3.2m (third-party). | |
| Cash on hand | Not available (total-exemption-full accounts; document access not attempted for most recent filing) |  |
| Runway | Not determinable from available data | estimated |
| Accumulated losses | Not available | |
| Trade creditors | Not available |  |

## Leadership

| Name | Role | Status | Outreach priority |
|---|---|---|---|
| Ryan Scott | Managing Director | active | Primary door - operational and commercial lead |
| Matthew Everatt | Co-founder Director | active | Secondary - group-level, S4S Dental Lab connection |
| Neil Bullement | Former Co-founder Director | Departed 2025-02-19 | Departed [DEPARTURE SIGNAL] |

## Synapto product fit

| Product | Fit | Rationale |
|---|---|---|
| Synapto Collect | ⚫ | B2B invoice terms via client portal - card acquiring not applicable. |
| Synapto Flow | 🟢 | Mobile app already manages timesheets and shift sign-off. Synapto Flow API sits between app and payroll - replacing manual BACS with same-day disbursement at timesheet approval. Both PAYE and guaranteed-hours models can be automated. Client portal provides invoice data for float calculation. Strong Operational fit. |
| Synapto Advance | 🟡 | Client portal implies structured invoice flow from dental practices. Advance against verified practice invoices is viable. Scale (~£3.2m est.) is moderate. Secondary conversation to Flow. |
| Synapto Recover | ⚫ | No evidence of material invoice recovery challenge at this stage. |

## Payment flow

**Dental Practice (NHS / Private)** (Invoice terms via Client Shift Manager Portal) → **S4S Team + Synapto** → **Locum Dental Nurse / Hygienist** (Weekly PAYE or guaranteed-hours payroll)

- Pays in: B2B
- Beneficiary type: PAYE-employed and guaranteed-hours locum dental nurses and hygienists across 30+ locations
- Float window: Invoice terms (14-30 days) vs weekly PAYE payroll. App timesheets are the data source; payroll execution is manual downstream.

## Companies House timeline

| Year | Cash | Trade creditors | Trade debtors | Net assets | Signal |
|---|---|---|---|---|---|
| Mar 2026 (most recent filed) | Not available (document not retrieved) | Not available | Not available | Not available | Total-exemption-full accounts filed; no P&L. Neil Bullement departed Feb 2025 between last two filing periods. |

## Director & corporate activity

- **2025-02-19** 🟡 Neil Bullement resigned as director [DEPARTURE SIGNAL] - founding director departed after 7 years; reason unknown. Possible buyout, retirement, or strategic disagreement.
- **2021-01-22** 🟡 Hannah Stuchfield resigned as director - second founding director departure
- **2018-11-20** 🟢 Ryan Scott appointed director as MD - operational leadership formalised
- **2018-01-26** 🟢 S4S Team Limited incorporated by Matt Everatt and Neil Bullement; Hannah Stuchfield also founding director

## PRQ preliminary findings

**PAYE and guaranteed-hours employer model - Green (Medium confidence)**

Website explicitly states PAYE basis and guaranteed-hours contracts. SIC 78109/78200. Employer-side compliance (DBS, GDC, indemnity all managed by S4S). Full T&C review required to confirm dual-status treatment before commercial engagement.

**App infrastructure with no embedded payment - Operational gap**

Mobile app (iOS/Android) for shift booking, scheduling, timesheets. Client Shift Manager Portal for practice bookings. No embedded payment or payout step mentioned in either platform - payroll runs manually after app-based timesheet approval.

**No charges registered**

Companies House confirms has_charges: false. Clean security position.

_Preliminary posture only. Full PRQ required before commercial engagement._

## Marketing vs reality

| Claim | Evidence | Severity |
|---|---|---|
| Trusted and reliable for 7 years | Two of four founding directors have departed (Stuchfield 2021, Bullement Feb 2025) - internal governance changes over life of business | Minor - departures may be natural evolution; Ryan Scott remains as MD |

## Competitive landscape

| Competitor | Trustpilot | Position | Note |
|---|---|---|---|
| Cavity Dental Staff | n/a | National 30+ region; similar coverage | Direct geographic overlap in North and Midlands |
| Crowns Recruitment | n/a | Yorkshire/NE/Midlands/Manchester - near-identical footprint | Closest geographic competitor |
| First Agency Direct | n/a | Nationwide vs S4S's North/Midlands focus | Broader geography but less regional depth |

## Outreach angles

### Primary, Ryan Scott, MD

**The app does the timesheet, the BACS is still manual**

Hi Ryan,

Your app handles shift booking and timesheet submission. The BACS payroll run is still a separate step after that. We build the API that closes that gap - timesheet approved in app, nurse paid the same day, no manual batch.

Several dental agencies with booking technology are using it to reduce Friday payroll admin and offer same-day pay as a nurse retention differentiator across 30+ locations.

Worth 20 minutes to see how the API sits behind what you have already built?

Best,
[Name]

### Secondary, Ryan Scott, MD

**Scaling without scaling the finance team**

Hi Ryan,

You have taken on two apprentice recruiters to scale the placement side. The payroll overhead per placement tends to scale too unless the back office is automated.

We work with locum dental agencies to automate the payment step between timesheet and BACS - so more placements does not mean more Friday payroll admin.

Happy to show you the setup in 20 minutes.

Best,
[Name]

### Tertiary, Matthew Everatt, Director (S4S group)

**The S4S group payment infrastructure**

Hi Matt,

With S4S Dental Lab and S4S Team both running payroll operations across the North, there is a question about whether the payment infrastructure scales efficiently as both businesses grow.

We work with staffing and services businesses that have built strong operational platforms but still run BACS manually behind the scenes. The infrastructure that closes that gap is the same in both contexts.

Worth 20 minutes to explore?

Best,
[Name]

---

_Synapto Intel · 2026-05-25 · Confidential. Full PRQ verdict required before commercial engagement._

_Source JSON: s4s-team-intel.json (in this folder)._