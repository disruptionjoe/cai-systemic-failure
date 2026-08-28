# Draft decision-time assumption-use trace pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `assumption_source_context` field must name the reused assumption and the
source, revision, decision context, or evidence basis relied on for the
synthesis. A later-written trace does not by itself show that the assumption
informed the earlier reuse decision.
</evidence>

<synthetic_fixture id="DTS-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Revision `R-support` contains synthetic statement `S-old` supporting reused
  assumption `A-old`.
- Reuse decision `T-reuse` occurred at `T0`.
- Draft `D-late` cites `R-support` and trace `TR-late`, but `TR-late` was first
  written at `T1`, after `T0`, and the admitted fixture supplies no evidence
  that `A-old` informed `T-reuse` at decision time.
- Draft `D-grounded` preserves the same source and later trace and also
  supplies synthetic decision record `E-use`, created at `T0`, linking
  `A-old`, `R-support`, and `T-reuse`.
- The fixture does not say either draft is real, that a later trace is always
  invalid, that authority was exercised, or that an outcome followed.
</synthetic_fixture>

## Work now

Draft `SF-DTS-0001-decision-time-assumption-support.md` with exactly:

1. Begin with this literal raw frontmatter block, including both `---` lines:

   `---`

   `test_id: SF-DTS-0001`

   `candidate: SF-SCHEMA-CANDIDATE-0001`

   `status: synthetic_assumption_timing_proposal`

   `source_material: synthetic`

   `external_action: none`

   `---`
2. `# SF DTS 0001 - Decision-Time Assumption Support`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-authority-exercise inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Support Ledger` copying these records literally:

   `draft: D-late | assumption: A-old | source: R-support | source_statement: S-old | decision: T-reuse | decision_time: T0 | trace: TR-late | trace_time: T1 | contemporaneous_use_record: NONE | verified_result: FAIL | uncertainty: later trace alone does not prove decision-time use`

   `draft: D-grounded | assumption: A-old | source: R-support | source_statement: S-old | decision: T-reuse | decision_time: T0 | trace: TR-late | trace_time: T1 | contemporaneous_use_record: E-use | verified_result: PASS | uncertainty: all support is synthetic`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: FAIL — D-late supplies source support and a later trace but no evidence that A-old informed T-reuse at T0`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing source support, source
   identity, decision timing, trace timing, contemporaneous use evidence,
   uncertainty, authority exercise, outcome, and remedy. State whether current
   wording already refuses `D-late` and permits `D-grounded` to continue gate
   checks.
8. `## Verdict`: choose exactly `ALREADY HANDLED — A LATER TRACE ALONE DOES
   NOT PROVE DECISION-TIME ASSUMPTION USE` or `PROPOSE SF-DTS-0001 — CURRENT
   WORDING ALLOWS A LATER TRACE TO SUBSTITUTE FOR DECISION-TIME USE EVIDENCE`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   assumption_source_context WORDING REQUIRES THE ASSUMPTION TO INFORM THE
   REUSE DECISION`; for propose, exactly `PROPOSE DECISION-TIME ASSUMPTION-USE
   HANDLING`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; all
    nine gate results; verdict/effect coherence; raw-frontmatter validity; and
    boundary checks.

Return only the finished artifact. Emit raw Markdown, not a code fence. The
first line and the line after `external_action: none` must both be `---`. Copy
all five YAML fields. Use one concise row or bullet per item, do not repeat
evidence, and stay under 850 words.
