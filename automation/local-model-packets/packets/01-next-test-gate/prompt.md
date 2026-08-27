# Draft a later authority versus decision-time review authority pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `accountable_review_owner` field must distinguish the assumption owner
from the owner who could review, stop, escalate, or revise its reuse. Refuse if
accountability is only a generic organization label.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
An old assumption must be reused under a changed condition or evidence
context, and the changed condition must create a validation burden shown as
unmet, disputed, fragmented, or not owner-visible enough.
</evidence>

<synthetic_fixture id="DRA-FIXTURE-01">
- One bounded synthetic packet supplies every non-target core gate as `PASS`
  for this exact logic test.
- Old assumption `A-old` is reused under changed condition `C-new` at
  `T-reuse`, before decision `D-final` at `T-final`.
- Before and through `T-final`, reviewer `R-comment` may attend, receive the
  contradiction packet, and comment, but cannot review authoritatively, stop,
  escalate, approve, reject, or revise reuse of `A-old`.
- Charter revision `C-late` becomes operative only at `T-late`, after
  `T-final`. It gives owner `O-late` review, stop, escalation, approval or
  rejection, and revision authority for future reuse decisions.
- The admitted packet explicitly says `O-late` had none of that authority at
  `T-reuse` or before `D-final` and that no other accountable owner is shown
  during the relevant decision window.
- Draft `D-current` marks `accountable_review_owner` `PASS` because `O-late`
  holds the named authority when the draft is written. Draft `D-window` marks
  the field `FAIL` because the authority begins only after the reuse decision
  and cannot establish accountable review authority for that decision.
- The fixture does not infer that later authority is useless, that `O-late`
  exercised authority, that earlier review would have changed the outcome, or
  that any remedy is required. It tests later authority versus authority
  available during the reuse decision window.
- The supplied non-target grades are not real findings, a new positive record,
  or schema acceptance.
- All names and facts are synthetic. No real source, system, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-DRA-0001-later-authority-and-decision-time-authority.md` with exactly these
sections:

1. YAML frontmatter containing `test_id: SF-DRA-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_decision_time_authority_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF DRA 0001 - Later Authority And Decision-Time Authority`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-outcome-counterfactual, no-authority-exercise inference, and no-action
   status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-new`, `T-reuse`,
   `D-final`, `T-final`, `R-comment`, `C-late`, `T-late`, `O-late`,
   `D-current`, and `D-window`. Do not move `C-late` before `D-final`, convert
   attendance or comment permission into authority, or infer an outcome.
5. `## Authority Timeline Ledger` comparing authority source, effective time,
   review authority, stop authority, escalation authority, approval or
   rejection authority, revision authority, relation to `T-reuse`, relation to
   `D-final`, accountable-owner result, target-field result, qualification
   result, and uncertainty for both drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give every non-target row `PASS` with the literal reason `supplied premise`.
   Give `accountable_review_owner` `FAIL` with the literal reason `authority
   begins only after the reuse decision`. Do not infer authority exercise,
   outcome change, acceptance, or failure of another gate.
7. `## Nearby-Control Comparison` keeping named reviewer, attendance, packet
   receipt, comment permission, current charter existence, charter effective
   time, later authority, decision-time authority, authority exercise, review
   adequacy, correction-route timing, and overall qualification distinct.
   State whether current wording already requires the accountable owner to
   possess relevant authority during the reuse decision window rather than
   merely at the later artifact-writing time.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-DRA-0001 — DECISION-TIME REVIEW AUTHORITY IS NOT EXPLICIT`
     only if current controls allow authority acquired after `D-final` to
     satisfy `accountable_review_owner` for that earlier decision; or
   - `ALREADY HANDLED — LATER AUTHORITY DOES NOT ESTABLISH DECISION-TIME ACCOUNTABLE REVIEW AUTHORITY`
     when current wording already requires relevant authority for the reuse
     decision under review.
9. `## Candidate Effect` containing exactly `PROPOSE CLARIFYING
   accountable_review_owner TO REQUIRE RELEVANT AUTHORITY DURING THE REUSE
   DECISION WINDOW` when the verdict is `PROPOSE`, or exactly `NONE — CURRENT
   CONTROL ALREADY REQUIRES ACCOUNTABLE REVIEW AUTHORITY FOR THE REUSE
   DECISION UNDER REVIEW` when the verdict is already handled. Do not propose
   a remedy, organization design, retroactive authority rule, acceptance rule,
   or new field.
10. `## Frontier Verification` listing only exact evidence, timeline,
    reviewer-role, attendance, packet-receipt, comment-permission,
    charter-effective-time, review-authority, stop-authority,
    escalation-authority, approval-or-rejection-authority,
    revision-authority, decision-window, supplied-premise, qualification,
    wording, and boundary checks needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---` and the frontmatter must end with a second `---` before the title.
