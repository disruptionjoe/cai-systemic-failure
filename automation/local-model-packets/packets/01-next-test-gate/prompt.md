# Draft decision-time review-authority scope pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `accountable_review_owner` field must distinguish the assumption owner from
the owner who held relevant authority during the reuse decision window and
could review, stop, escalate, approve or reject, or revise that reuse. A role
or authority at the right time does not satisfy the field when its matter scope
does not cover the reuse decision under review.
</evidence>

<synthetic_fixture id="RAS-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Reuse decision `T-reuse` for bounded system `S-target` occurred at `T0`.
- Owner `O-report` held a named review title at `T0`, but admitted charter
  `CH-report` limited that authority to receiving status reports for separate
  system `S-report`; it did not cover `T-reuse`, `S-target`, or the ability to
  review, stop, escalate, approve, reject, or revise that reuse.
- Draft `D-title` marks accountable review passed because `O-report` held a
  review title and some authority at `T0`.
- Draft `D-scoped` instead names owner `O-decision` and admitted charter
  `CH-decision`, operative at `T0`, whose matter scope covers `T-reuse` in
  `S-target` and the supplied review, stop, escalation, approval, rejection,
  and revision capabilities.
- The fixture does not say either owner is real, that either authority was
  exercised, that a duty or remedy exists, or that an outcome followed.
</synthetic_fixture>

## Work now

Draft `SF-RAS-0001-decision-time-review-authority-scope.md` with exactly:

1. Begin with this literal raw frontmatter block, including both `---` lines:

   `---`

   `test_id: SF-RAS-0001`

   `candidate: SF-SCHEMA-CANDIDATE-0001`

   `status: synthetic_review_authority_scope_proposal`

   `source_material: synthetic`

   `external_action: none`

   `---`
2. `# SF RAS 0001 - Decision-Time Review Authority Scope`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-authority-exercise inference,
   no-duty inference, no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Authority Scope Ledger` copying these records literally:

   `draft: D-title | decision: T-reuse | decision_time: T0 | target_system: S-target | named_owner: O-report | authority_source: CH-report | authority_time: T0 | authority_scope: S-report status receipt only | target_decision_scope: NONE | target_capability: NONE | verified_result: FAIL | uncertainty: same-time title and unrelated authority do not establish relevant authority`

   `draft: D-scoped | decision: T-reuse | decision_time: T0 | target_system: S-target | named_owner: O-decision | authority_source: CH-decision | authority_time: T0 | authority_scope: T-reuse in S-target | target_decision_scope: PRESENT | target_capability: REVIEW_STOP_ESCALATE_APPROVE_REJECT_REVISE | verified_result: PASS | uncertainty: authority is synthetic and exercise is not inferred`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: FAIL — D-title substitutes same-time title and unrelated authority for relevant authority over T-reuse in S-target`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   `Infer no other failed gate.`
7. `## Nearby-Control Comparison` distinguishing title, authority existence,
   authority time, authority matter scope, target decision, target system,
   capability, authority exercise, duty, outcome, and remedy. State whether
   current wording already refuses `D-title` and permits `D-scoped` to continue
   gate checks.
8. `## Verdict`: choose exactly `ALREADY HANDLED — SAME-TIME AUTHORITY OUTSIDE
   THE REUSE DECISION SCOPE IS NOT ACCOUNTABLE REVIEW AUTHORITY` or `PROPOSE
   SF-RAS-0001 — CURRENT WORDING ALLOWS UNRELATED SAME-TIME AUTHORITY TO
   SATISFY accountable_review_owner`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   accountable_review_owner WORDING REQUIRES RELEVANT AUTHORITY OVER THE REUSE
   DECISION`; for propose, exactly `PROPOSE REVIEW-AUTHORITY MATTER-SCOPE
   HANDLING`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; all
    nine gate results; verdict/effect coherence; raw-frontmatter validity; and
    boundary checks.

Return only the finished artifact. Emit raw Markdown, not a code fence. The
first line and the line after `external_action: none` must both be `---`. Copy
all five YAML fields and the literal `Infer no other failed gate.` line. Use
one concise row or bullet per item, do not repeat evidence, and stay under 850
words.
