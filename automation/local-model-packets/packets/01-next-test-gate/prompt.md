# Draft a named-reviewer versus accountable-review-authority pressure test

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
Delegation, review, or request paths must be material to the contradiction, and
the changed condition must create a validation burden shown as unmet,
disputed, fragmented, or not owner-visible enough.
</evidence>

<synthetic_fixture id="NRA-FIXTURE-01">
- One bounded synthetic packet supplies every non-target core gate as `PASS`
  for this exact logic test.
- Old assumption `A-old` is reused under changed condition `C-new` before
  decision `D-final`.
- Meeting record `M-attend` names reviewer `R-observer`, records that
  `R-observer` received the contradiction packet, and permits comment.
- The same admitted packet explicitly says `R-observer` cannot stop,
  escalate, approve, reject, or revise reuse of `A-old`.
- Authority charter `C-authority` names `O-control` as the owner who can review,
  stop, escalate, or revise that reuse. `O-control` receives the contradiction
  packet before `D-final`.
- Draft `D-name` marks `accountable_review_owner` `PASS` by naming
  `R-observer`. Draft `D-authority` marks `R-observer` non-accountable for this
  field and identifies `O-control` as the accountable review owner.
- The fixture does not infer that `O-control` reviewed adequately, exercised
  authority, made a safe decision, accepted the contradiction, or supplied a
  remedy. It tests only named review presence versus accountable authority.
- The supplied non-target grades are not real findings, a new positive record,
  or schema acceptance.
- All names and facts are synthetic. No real source, system, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-NRA-0001-named-reviewer-and-accountable-authority.md` with exactly these
sections:

1. YAML frontmatter containing `test_id: SF-NRA-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_review_authority_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF NRA 0001 - Named Reviewer And Accountable Authority`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-adequacy-inference, no-exercise-of-authority inference, and no-action
   status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-new`, `D-final`,
   `M-attend`, `R-observer`, `C-authority`, `O-control`, `D-name`, and
   `D-authority`. Do not convert attendance, receipt, or permission to comment
   into stop, escalation, approval, rejection, or revision authority.
5. `## Reviewer And Authority Ledger` comparing named reviewer, packet
   receipt, comment permission, stop authority, escalation authority, approval
   or rejection authority, revision authority, authority source, accountable
   owner result, qualification result, and uncertainty for both drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give every non-target row `PASS` with the literal reason `supplied premise`.
   Give `accountable_review_owner` `PASS` with the literal reason `owner with
   review, stop, escalation, and revision authority is identified`. Do not
   infer adequacy, authority exercise, acceptance, or failure of another gate.
7. `## Nearby-Control Comparison` keeping reviewer identity, attendance,
   packet receipt, comment permission, assumption ownership, accountable
   review authority, authority source, authority exercise, review adequacy,
   and overall qualification distinct. State whether current wording already
   requires an owner able to review, stop, escalate, or revise reuse rather
   than a merely named reviewer.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-NRA-0001` only if current controls let a named reviewer without
     the relevant authority satisfy `accountable_review_owner`; or
   - `ALREADY HANDLED — NAMED REVIEW PRESENCE DOES NOT ESTABLISH ACCOUNTABLE REVIEW AUTHORITY`
     when current wording already requires the relevant review, stop,
     escalation, or revision authority.
9. `## Candidate Effect` containing exactly `NONE — CURRENT CONTROL ALREADY
   DISTINGUISHES NAMED REVIEW PRESENCE FROM ACCOUNTABLE REVIEW AUTHORITY` when
   the verdict is already handled. Do not propose an organization design,
   delegation rule, remedy, adequacy finding, acceptance rule, or new field.
10. `## Frontier Verification` listing only exact evidence, reviewer-identity,
    attendance, packet-receipt, comment-permission, stop-authority,
    escalation-authority, approval-or-rejection-authority, revision-authority,
    authority-source, supplied-premise, qualification, wording, and boundary
    checks needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---` and the frontmatter must end with a second `---` before the title.
