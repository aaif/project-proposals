*Operating procedure for the Agentic AI Foundation, aligned to the AAIF
Project Lifecycle Policy effective March 18, 2026.*

> This document defines how projects are proposed to the Agentic AI
> Foundation (AAIF), screened for completeness and fit, reviewed by the
> Technical Committee (TC), approved by the Governing Board (GB), and
> onboarded into the Foundation. It also explains how AAIF assigns an
> initial lifecycle stage---typically Growth or Impact---consistent with
> the AAIF Project Lifecycle Policy.

# 1. Purpose

This procedure sets out how projects are proposed, reviewed, approved,
and onboarded into the Agentic AI Foundation. It converts the AAIF
Project Lifecycle Policy into an operating workflow covering intake,
screening, technical review, voting, approval, contribution of project
assets, and onboarding.

# 2. Governing References

This procedure should be read together with the AAIF project proposals
repository and the AAIF Project Lifecycle Policy. Where this procedure
adds operating detail, the lifecycle policy remains the governing
authority for lifecycle stages, acceptance criteria, and annual review
expectations.

# 3. Core Policy Alignment

- Projects are submitted through the AAIF project proposals GitHub
  repository using the established submission process.

- Each proposal must include the information required by the AAIF
  Project Lifecycle Policy, including project description, mission
  alignment, license, repository location, governance details,
  maintainership, communication channels, website, social accounts,
  dependencies, and infrastructure needs.

- Projects are expected to present their proposal at a Technical
  Committee meeting arranged by the project's TC sponsor.

- Projects admitted into AAIF are assigned an initial lifecycle stage,
  normally Growth or Impact, based on the lifecycle policy criteria.

- Technical Committee approval is by absolute majority vote of all TC
  members, and accepted projects are then referred to the Governing
  Board for approval.

- Admission is contingent on completion of the Linux Foundation
  contribution process, including governance finalization and
  transfer of required project assets. No public announcement is
  made before that work is complete.

# 4. Roles and Responsibilities

| **Role** | **Primary responsibilities** |
|---|---|
| Project submitter | Prepares and files the GitHub issue, supplies supporting information, responds to feedback, presents to the TC, and completes required corrective actions and contribution steps. |
| AAIF staff | Coordinates intake, provides draft governance documents and project contribution agreement materials, tracks process status, and coordinates with LF Legal and other operational teams. |
| CTO / VP of Technology or PMs | Perform the initial completeness and minimum-criteria screening where applicable in AAIF's operating model, determine whether a submission is ready to move forward, and communicate deficiencies. |
| TC sponsor | Mentors the project, helps prepare it for review, and arranges the project's presentation to the Technical Committee. |
| Technical Committee | Reviews the proposal, conducts due diligence, evaluates fit and lifecycle stage, requests changes if needed, and votes on admission and stage recommendation. |
| Governing Board | Approves projects referred by the Technical Committee and approves any cost-bearing commitments or infrastructure support requiring board authorization. |
| LF Legal / operations | Finalize contribution documentation, transfer of project trademarks and assets, governance documentation, and other onboarding prerequisites. |
| LF IT | Assumes repository ownership and executes technical onboarding into Linux Foundation-controlled systems, including GitHub administration. |

# 5. Proposal Intake Requirements

A project enters the process when its owners submit a proposal through
the GitHub issue workflow in the AAIF project proposals repository. At
minimum, the issue should contain or link to the information required by
the lifecycle policy.

- Project name, description, origin, and history.

- Statement of alignment with the AAIF mission and relationship to
  existing AAIF projects.

- Examples of use cases, adoption evidence, and external dependencies.

- OSI-approved permissive license, public repository location, issue
  tracker, release methodology, and public-facing validation or
  delivery processes.

- Leadership structure, decision-making process, maintainers,
  governance materials such as GOVERNANCE.md, and contribution
  materials where available. Ideally implementing OpenMVG.

- Official communication channels, website, social media accounts,
  financial sponsorship details if any, and infrastructure needs or
  requests.

- Preferred lifecycle stage, if the submitter seeks admission as
  Growth or Impact.

# 6. End-to-End Process

## 6.1 Submission and logging

The GitHub issue is opened in the AAIF project proposals repository and
serves as the official record for the submission. AAIF staff acknowledge
receipt, confirm that the proposal is in scope for AAIF, and begin
intake tracking.

## 6.2 Initial screening for completeness and minimum criteria

The CTO or VP of Technology, if such a role exists, or otherwise the
PMs, review the submission for completeness, baseline readiness, and
compliance with the minimum proposal requirements. The screening is
intended to avoid sending materially incomplete proposals into formal
committee review.

## 6.3 Rejection at intake, with feedback

If the proposal does not meet the minimum criteria, it is rejected at
intake. The GitHub issue is updated with clear feedback identifying the
missing, insufficient, or misaligned elements. The issue is then closed
unless AAIF staff determine that a short clarification cycle is
appropriate.

## 6.4 Move to In Review

If the proposal satisfies the intake threshold, the issue is moved to In
Review. This marks the proposal as sufficiently complete for formal AAIF
technical review.

## 6.5 Assignment or confirmation of a TC sponsor

Where possible, a Technical Committee sponsor is identified to help
mentor the project, coordinate the review path, and arrange the
committee presentation. A sponsor is particularly important for projects
seeking admission at the Growth stage.

## 6.6 Preparation of the project brief

AAIF staff and the reviewers compile a concise project brief for the
Technical Committee. The brief should summarize the project's purpose,
ecosystem relevance, mission alignment, repository and licensing
posture, governance and maintainership, evidence of adoption,
dependencies, lifecycle stage requested, and any notable risks or open
questions.

## 6.7 Asynchronous Technical Committee pre-read

The project brief is shared with the Technical Committee asynchronously
before the meeting. TC members review the materials, identify areas
requiring due diligence, and note any questions to be addressed during
the presentation.

## 6.8 Technical Committee presentation

The project owners are invited to the next Technical Committee meeting
to present the proposal. The standard format is a 10-minute presentation
followed by 10 to 15 minutes of committee questions. The purpose is to
validate fit, readiness, governance maturity, community health, and the
proposed lifecycle stage.

## 6.9 Technical Committee due diligence

Following the presentation, the TC is expected to perform reasonable due
diligence during the voting window. Members may consult internally
within their companies if needed and should assess the project against
the AAIF lifecycle policy, including whether Growth or Impact entry
criteria are met.

## 6.10 Seven-day asynchronous TC vote in LFX

The Technical Committee votes asynchronously over a seven-day period
using LFX voting. Admission requires an absolute majority vote of all TC
members. The TC's approval should also include a recommendation on the
project's initial lifecycle stage.

## 6.11 Technical Committee outcome

The Technical Committee may reject the proposal, request changes before
progression, conditionally approve the proposal subject to specific
corrective actions, or approve the proposal for referral to the
Governing Board. If the project is not ready for AAIF, the GitHub issue
is updated with the reason and the issue is closed.

## 6.12 Governing Board approval

Projects that receive the required TC vote are referred to the Governing
Board for approval. Governing Board review confirms organizational
readiness, any resource implications, and the Foundation's willingness
to accept the project under the proposed terms and lifecycle stage.

## 6.13 Contribution, governance finalization, and asset transfer

Any approval remains contingent on completion of the Linux Foundation
contribution process. AAIF staff provide draft governance documents and
the contribution agreement for transferred assets. The project host must
execute and deliver the contribution agreement, adopt an approved
technical charter, and transfer the required project trademarks and
other project assets to the Linux Foundation.

## 6.14 Technical onboarding and controls

Once legal contribution requirements are complete, the Linux Foundation
conducts a license scan and LF IT assumes repository ownership or
administrative control. Where appropriate, the repository may be moved
into Foundation-managed GitHub infrastructure, including an enterprise
account when applicable.

## 6.15 Final issue closure

After the project has formally joined AAIF and the onboarding
prerequisites are complete, the GitHub issue is closed with the status
Approved. No public announcement is made before contribution
documentation and governance finalization are complete.

# 7. Decision Rules and Outcome Paths

## 7.1 Rejection after review

If the TC or GB declines the project, the GitHub issue should record the
principal reason for the decision and be closed. The explanation should
be specific enough to guide future resubmission without disclosing
confidential deliberations.

## 7.2 Resubmission timing

Where a proposal is rejected because substantial improvements are
needed, the submitter may reapply after three months, provided those
improvements have been made. Examples include material governance
redesign, significant community development, clearer mission alignment,
or resolution of major licensing or ownership issues.

## 7.3 Conditional approval for minor gaps

If the project is fundamentally acceptable but has minor outstanding
items, such as adding governance documentation, clarifying a maintainer
process, or addressing small operational gaps, the TC may recommend
conditional approval. In that case, the missing items must be documented
in the GitHub issue and fully resolved before the project is treated as
finally admitted or publicly announced.

# 8. Initial Lifecycle Stage Assignment

Every admitted AAIF project must be assigned a lifecycle stage
consistent with the AAIF Project Lifecycle Policy. New projects may
enter as Growth or Impact, and the TC should state its recommended
initial stage as part of the approval package sent to the Governing
Board.

## 8.1 Growth stage entry

Growth stage is generally appropriate for projects that show strong
promise and meaningful use, but still need mentorship, governance
maturation, contributor growth, or a clearer growth plan before they can
be considered mature top-level projects.

## 8.2 Impact stage entry

Impact stage is generally appropriate only for projects that already
demonstrate substantial industry adoption, durable governance, diverse
maintainership, public roadmap and release practices, and the broader
characteristics required by the lifecycle policy.

## 8.3 Future transitions and annual review

After admission, the project remains subject to the lifecycle policy's
annual review process. The Technical Committee may recommend that the
project remain in its current stage, take corrective actions, or
transition to a different stage based on health, adoption,
maintainership, release cadence, and progress against stated goals.

# 9. Contribution and Onboarding Requirements

| **Requirement** | **What must be completed** | **Owner** |
|---|---|---|
| Contribution agreement | Project host executes and delivers the project contribution agreement to the Linux Foundation. | Submitter / LF Legal |
| Governance package | Draft governance documents are reviewed and finalized, including an approved technical charter. | LF Legal / Submitter |
| Trademark and project assets | Required trademarks and community assets are transferred to the Linux Foundation. | LF Legal / Submitter |
| Repository and admin control | GitHub organization, repositories, and administrative access are transferred or reconfigured for LF control. | Submitter / LF IT |
| Community channels and web properties | Website ownership or admin access, social media accounts, and other official community properties are transferred as required. | Submitter / Marketing |
| License scan | The Linux Foundation performs a license scan as part of onboarding. | LF operations |
| Announcement hold | No public announcement is made until the contribution process and governance finalization are complete. | AAIF staff |

# 10. GitHub Actions and Cost Review

If the project repository has working CI that uses GitHub Actions, AAIF
should assess the operating cost that would be assumed by the Foundation
after onboarding. Because this can create a recurring financial
obligation, Governing Board approval is generally required before AAIF
accepts responsibility for those costs. This cost review should be
completed before final onboarding commitments are made.

# 11. Operating Standards for the GitHub Issue Record

- The GitHub issue should serve as the primary written record of the
  process from intake through closure.

- Status changes should be reflected in the issue, including intake
  rejection, In Review, conditional approval requirements, referral
  to the Governing Board, and final approval or rejection.

- Feedback to submitters should be clear, actionable, and tied to
  policy or process requirements where possible.

- Final closure should indicate whether the project was rejected,
  conditionally approved and completed, or approved and admitted to
  AAIF.

# 12. Recommended Standard Timing

| **Stage** | **Typical timing** |
|---|---|
| Initial completeness screening | As soon as practical after the GitHub issue is submitted. |
| Project brief and TC pre-read | Completed after the proposal is moved to In Review and before the next suitable TC meeting. |
| TC presentation | 10-minute presentation plus 10–15 minutes of questions at the next TC meeting. |
| LFX voting period | Seven days from the start of the asynchronous TC vote. |
| Resubmission after substantive rejection | Eligible after three months, provided meaningful improvements have been made. |

# 13. Summary of the Approval Gate

A project is not fully admitted to AAIF merely because it passed
technical review. Formal admission requires: (1) a complete proposal,
(2) successful TC review and absolute-majority approval, (3) Governing
Board approval, (4) completion of the Linux Foundation contribution and
governance process, and (5) transfer of the required project assets
before any public announcement.

# 14. Project Proposal and Onboarding Timeline

The following table provides a comprehensive timeline covering all
stages of the AAIF project proposal process, from initial submission
through technical review, governing board approval, and final
onboarding. Timeframes run concurrently where noted. All business day
references exclude weekends and recognized Linux Foundation holidays.

| **Phase** | **Activity and Description** | **Timeframe** | **Owner** |
|---|---|---|---|
| **Submission Review** | AAIF staff and designated reviewers conduct an initial completeness and minimum-criteria screening of the submitted GitHub issue. The submitter receives a written response indicating whether the proposal is accepted into formal review, requires additional information, or is rejected at intake with specific feedback. | 5–10 business days from submission | AAIF Staff / CTO or PMs |
| **TC Submission Brief** | AAIF staff compile and distribute a project brief to all Technical Committee members. The brief summarizes mission alignment, licensing, governance, adoption evidence, proposed lifecycle stage, and any notable risks. TC members review the materials asynchronously before the scheduled presentation meeting. | Within 5 days of submission | AAIF Staff / TC Sponsor |
| **TC Meeting Presentation** | The project submitter presents the proposal to the Technical Committee at the next scheduled TC meeting. The standard format is a 10-minute presentation followed by 10–15 minutes of committee questions covering fit, governance maturity, community health, and the proposed lifecycle stage. | Next scheduled TC meeting after brief distribution | Project Submitter / TC Sponsor |
| **TC Async Vote** | Following the presentation, the TC conducts an asynchronous vote via LFX. Admission requires an absolute majority of all TC members. At the close of the voting period, the TC issues a formal response to the submitter with one of three outcomes: (1) approval for referral to the Governing Board, (2) conditional approval identifying specific issues to resolve, or (3) outright rejection with a documented rationale and guidance on resubmission. | 7 calendar days from TC meeting | Technical Committee |
| **Governing Board Async Vote** | Projects that receive TC approval are referred to the Governing Board for an asynchronous vote. The GB confirms organizational readiness, resource implications, and the Foundation's willingness to accept the project under the proposed terms and lifecycle stage. Final approval or rejection is issued at the close of the voting period. | 7 calendar days from TC approval | Governing Board / AAIF Staff |
| **Project Formation with LF Legal** *(concurrent)* | In tandem with the TC and GB review and voting stages, AAIF staff engage LF Legal to initiate the project formation process. This includes preparation of the contribution agreement, technical charter, trademark and asset transfer documentation, and any other legal prerequisites. Upon GB approval, the submitter must execute the required paperwork to formalize the contribution. | 5–15 days (concurrent with TC/GB stages); paperwork signed upon GB approval | LF Legal / AAIF Staff / Submitter |
| **Technical Onboarding and Asset Transfer** | Following GB approval and execution of the contribution agreement, the submitter completes the following within 4 weeks: (1) implement the approved governance structure in the project repository (e.g., GOVERNANCE.md and technical charter - ideally OpenMVG); (2) transfer GitHub repository ownership to the Linux Foundation or grant LF IT administrative control, enabling the Foundation to move the repository to LF-managed infrastructure if required; and (3) provide credentials and administrative access for all official social media accounts and the project website to LF IT. No public announcement is made until all onboarding steps are complete. | 4 weeks from GB approval and contribution agreement execution | Submitter / LF IT / AAIF Staff |
