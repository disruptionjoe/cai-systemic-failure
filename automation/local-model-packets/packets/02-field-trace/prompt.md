# Draft validation-burden timing pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
An old assumption must be reused under a changed condition, and the changed
condition must create a validation burden that admitted evidence shows as
unmet, disputed, fragmented, or not owner-visible enough.
</evidence>

<synthetic_fixture id="VBT-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Reuse decision `T-reuse` occurred at `T0` under changed condition `C-new`.
- Validation burden `VB-new` existed at `T0` because `C-new` required
  revalidation of the reused assumption before the decision could count as
  adequately validated.
- Draft `D-backdated` supplies no completed validation, dispute resolution, or
  owner-visible validation result before `T0`. It marks `validation_burden`
  passed only because validation event `V-late` completed at `T1`, after
  `T-reuse` was final, and then backdates that result to `T0`.
- Draft `D-timely` supplies validation event `V-pre`, completed and made
  owner-visible at `T-1`, whose admitted synthetic scope covers `VB-new` before
  `T-reuse` at `T0`.
- The fixture does not say either validation is real, adequate outside its
  supplied scope, exercised by an authority, causally effective, a duty, a
  remedy, or evidence of an outcome.
</synthetic_fixture>

## Work now

Draft `SF-VBT-0001-validation-burden-timing.md` with exactly:

1. Begin with this literal raw frontmatter block, including both `---` lines:

   `---`

   `test_id: SF-VBT-0001`

   `candidate: SF-SCHEMA-CANDIDATE-0001`

   `status: synthetic_validation_burden_timing_proposal`

   `source_material: synthetic`

   `external_action: none`

   `---`
2. `# SF VBT 0001 - Validation-Burden Timing`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, uncertainty,
   no-remedy, no-promotion, no-new-record, no-authority-exercise inference,
   no-duty inference, no-causal inference, no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Timing Ledger` copying these records literally:

   `draft: D-backdated | reuse_decision: T-reuse | decision_time: T0 | changed_condition: C-new | validation_burden: VB-new | validation_event: V-late | validation_completed: T1 | owner_visible_before_decision: NO | backdated_to_decision: YES | verified_result: FAIL | uncertainty: later validation does not establish decision-time satisfaction`

   `draft: D-timely | reuse_decision: T-reuse | decision_time: T0 | changed_condition: C-new | validation_burden: VB-new | validation_event: V-pre | validation_completed: T-1 | owner_visible_before_decision: YES | backdated_to_decision: NO | verified_result: PASS | uncertainty: synthetic scope coverage does not prove real-world adequacy or outcome`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: FAIL — D-backdated substitutes post-decision validation at T1 for decision-time satisfaction at T0`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   `Infer no other failed gate.`
7. `## Nearby-Control Comparison` distinguishing burden existence, burden
   scope, validation event, completion time, owner visibility time, decision
   time, backdating, adequacy, authority exercise, duty, outcome, and remedy.
   State whether current wording already refuses `D-backdated` and permits
   `D-timely` to continue gate checks.
8. `## Verdict`: choose exactly `ALREADY HANDLED — POST-DECISION VALIDATION
   CANNOT BE BACKDATED TO SATISFY A DECISION-TIME VALIDATION BURDEN` or
   `PROPOSE SF-VBT-0001 — CURRENT WORDING ALLOWS POST-DECISION VALIDATION TO
   SATISFY A DECISION-TIME VALIDATION BURDEN`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   QUALIFICATION AND validation_burden WORDING REQUIRE THE BURDEN TO REMAIN
   UNMET, DISPUTED, FRAGMENTED, OR NOT OWNER-VISIBLE ENOUGH AT THE RELEVANT
   DECISION`; for propose, exactly `PROPOSE VALIDATION-BURDEN TIMING HANDLING`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; all
    nine gate results; verdict/effect coherence; raw-frontmatter validity; and
    boundary checks.

Return only the finished artifact. Emit raw Markdown, not a code fence. The
first line and the line after `external_action: none` must both be `---`. Copy
all five YAML fields, both ledger records, and the literal `Infer no other
failed gate.` line. Stay under 900 words.
