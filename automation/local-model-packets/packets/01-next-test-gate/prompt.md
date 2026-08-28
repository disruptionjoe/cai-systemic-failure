# Draft an explicit stop condition versus discretionary review pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `correction_route_stop_condition` field requires an owner-visible route
that can carry the relevant contradiction to a capable party and an admitted
source- or synthetic-backed condition that keeps qualification stopped or
unresolved while that contradiction remains unresolved. Route capability does
not substitute for the condition, and the repository does not prescribe the
remedy.
</evidence>

<synthetic_fixture id="DSR-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Route `R-capable` can carry contradiction `K-two` to accountable owner
  `O-capable`, who has the supplied relevant authority.
- Draft `D-review` says `O-capable` may review the matter if concerns arise,
  but supplies no condition tied to unresolved `K-two`, no decision checkpoint,
  and no qualification consequence.
- Draft `D-stop` preserves the route and supplies condition `C-two`: if
  `K-two` remains unresolved at checkpoint `T-two`, qualification stops and
  remains unresolved.
- The fixture does not say that review occurred, that `C-two` is a remedy, or
  that an outcome followed. All facts are synthetic; this is not a new record
  or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-DSR-0001-discretionary-review-explicit-stop-condition.md` with exactly:

1. Begin with this literal raw frontmatter block, including both `---` lines:

   `---`

   `test_id: SF-DSR-0001`

   `candidate: SF-SCHEMA-CANDIDATE-0001`

   `status: synthetic_stop_condition_proposal`

   `source_material: synthetic`

   `external_action: none`

   `---`
2. `# SF DSR 0001 - Discretionary Review And Explicit Stop Condition`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-authority-exercise inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Condition Ledger` copying these records literally:

   `draft: D-review | route: R-capable | contradiction: K-two | recipient: O-capable | route_capability: PASS | backed_condition: NONE | checkpoint: NONE | qualification_effect: NONE | verified_result: FAIL | uncertainty: discretionary review is not a stop condition`

   `draft: D-stop | route: R-capable | contradiction: K-two | recipient: O-capable | route_capability: PASS | backed_condition: C-two | checkpoint: T-two | qualification_effect: STOP_AND_UNRESOLVED_IF_K-two_UNRESOLVED | verified_result: PASS | uncertainty: condition is synthetic and not a remedy`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: FAIL — D-review supplies route capability but no contradiction-tied backed condition, checkpoint, or qualification consequence`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing route capability,
   discretionary review, contradiction-tied condition, checkpoint,
   qualification consequence, uncertainty, authority exercise, outcome, and
   remedy. State whether current wording already refuses `D-review`.
8. `## Verdict`: choose exactly `ALREADY HANDLED — DISCRETIONARY REVIEW DOES
   NOT SUBSTITUTE FOR AN EXPLICIT STOP CONDITION` or `PROPOSE SF-DSR-0001 —
   CURRENT WORDING ALLOWS DISCRETIONARY REVIEW TO SUBSTITUTE FOR A STOP
   CONDITION`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   correction_route_stop_condition WORDING REQUIRES A BACKED CONDITION AND
   QUALIFICATION CONSEQUENCE`; for propose, exactly `PROPOSE A
   CONTRADICTION-TIED CONDITION, CHECKPOINT, AND QUALIFICATION CONSEQUENCE`.
10. `## Frontier Verification` listing only exact fixture facts, all nine gate
    results, verdict/effect coherence, raw-frontmatter validity, and boundary
    checks.

Return only the finished artifact. Emit raw Markdown, not a code fence. The
first line and the line after `external_action: none` must both be `---`. Copy
all five YAML fields. Use one concise row or bullet per item, do not repeat
evidence, and stay under 900 words.
