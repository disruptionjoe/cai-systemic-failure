# Draft expired versus operative stop-condition pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `correction_route_stop_condition` field requires a capable owner-visible
route and an admitted source- or synthetic-backed condition that keeps
qualification stopped or unresolved while the relevant contradiction remains
unresolved. A historical condition that expired before the contradiction arose
does not remain operative merely because its text once existed.
</evidence>

<synthetic_fixture id="ESC-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Route `R-live` can carry contradiction `K-late` to accountable owner
  `O-live`, who has the supplied relevant authority.
- Condition `C-old` required qualification to stop while a contradiction was
  unresolved, but its admitted validity ended at `T-expire`.
- Contradiction `K-late` first arose at `T-late`, after `T-expire`.
- Draft `D-expired` relies only on `C-old`; draft `D-operative` supplies
  synthetic condition `C-live`, effective at `T-late` and remaining operative
  while `K-late` is unresolved.
- The fixture does not say either condition is a remedy, that authority was
  exercised, or that an outcome followed. All facts are synthetic.
</synthetic_fixture>

## Work now

Draft `SF-ESC-0001-expired-operative-stop-condition.md` with exactly:

1. Begin with this literal raw frontmatter block, including both `---` lines:

   `---`

   `test_id: SF-ESC-0001`

   `candidate: SF-SCHEMA-CANDIDATE-0001`

   `status: synthetic_stop_condition_timing_proposal`

   `source_material: synthetic`

   `external_action: none`

   `---`
2. `# SF ESC 0001 - Expired And Operative Stop Conditions`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-authority-exercise inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Condition Ledger` copying these records literally:

   `draft: D-expired | route: R-live | contradiction: K-late | recipient: O-live | condition: C-old | condition_end: T-expire | contradiction_start: T-late | operative_while_unresolved: NO | verified_result: FAIL | uncertainty: historical condition expired before contradiction`

   `draft: D-operative | route: R-live | contradiction: K-late | recipient: O-live | condition: C-live | condition_start: T-late | operative_while_unresolved: YES | verified_result: PASS | uncertainty: condition is synthetic and not a remedy`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: FAIL — D-expired relies on a condition that ended before K-late arose and was not operative while the contradiction remained unresolved`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing route capability,
   condition existence, condition validity window, contradiction timing,
   operative consequence, uncertainty, authority exercise, outcome, and
   remedy. State whether current wording already refuses `D-expired` and
   permits `D-operative` to continue gate checks.
8. `## Verdict`: choose exactly `ALREADY HANDLED — AN EXPIRED CONDITION DOES
   NOT REMAIN OPERATIVE FOR A LATER CONTRADICTION` or `PROPOSE SF-ESC-0001 —
   CURRENT WORDING ALLOWS AN EXPIRED CONDITION TO SATISFY THE STOP GATE`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   correction_route_stop_condition WORDING REQUIRES A CONDITION OPERATIVE
   WHILE THE CONTRADICTION REMAINS UNRESOLVED`; for propose, exactly `PROPOSE
   STOP-CONDITION VALIDITY-WINDOW HANDLING`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; all
    nine gate results; verdict/effect coherence; raw-frontmatter validity; and
    boundary checks.

Return only the finished artifact. Emit raw Markdown, not a code fence. The
first line and the line after `external_action: none` must both be `---`. Copy
all five YAML fields. Use one concise row or bullet per item, do not repeat
evidence, and stay under 850 words.
