# Draft an exact-assumption support versus adjacent citation pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `assumption_source_context` field must name the reused assumption and the
source revision, version, date, or evidence basis relied on, tying that exact
assumption to identifiable source context. A source label alone does not pass.
</evidence>

<synthetic_fixture id="ASR-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Report `REPORT-M@V3` contains separate admitted sections `P-alpha` and
  `P-beta`. `P-alpha` supports assumption `A-alpha`; `P-beta` supports
  assumption `A-beta`.
- The record under review claims reuse of `A-beta`.
- Draft `D-adjacent` cites `REPORT-M@V3#P-alpha` for `A-beta` because the page
  is in the same report. Draft `D-exact` cites `REPORT-M@V3#P-beta`.
- No later revision, contradiction, retirement, or bridge between `A-alpha`
  and `A-beta` is admitted.
- Do not invent shared meaning, source supersession, contradiction, authority
  exercise, outcome, or remedy.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-ASR-0001-exact-assumption-source-support.md` with exactly:

1. YAML frontmatter: `test_id: SF-ASR-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_exact_assumption_support_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF ASR 0001 - Exact Assumption Support Versus Adjacent Citation`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-shared-meaning invention,
   no-supersession or contradiction invention, no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Assumption Support Ledger` copying these records literally:

   `draft: D-adjacent | claimed_assumption: A-beta | cited_source: REPORT-M@V3#P-alpha | source_supports: A-alpha | exact_support_for_claim: NO | admitted_bridge: NONE | later_revision: NONE | material_contradiction: NONE | verified_result: FAIL | qualification: REFUSE | uncertainty: adjacent support substituted`

   `draft: D-exact | claimed_assumption: A-beta | cited_source: REPORT-M@V3#P-beta | source_supports: A-beta | exact_support_for_claim: YES | admitted_bridge: NOT_NEEDED | later_revision: NONE | material_contradiction: NONE | verified_result: PASS | qualification: CONTINUE_GATE_CHECKS | uncertainty: none added`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: FAIL — D-adjacent cites support for A-alpha rather than the claimed reused assumption A-beta`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing report identity, revision
   identity, section identity, exact assumption support, adjacent support,
   bridge, qualification, uncertainty, outcome, and remedy. State whether
   current source-context wording already refuses `D-adjacent`.
8. `## Verdict`: choose exactly `ALREADY HANDLED — A CITATION FOR AN ADJACENT
   ASSUMPTION DOES NOT SUPPORT THE CLAIMED REUSED ASSUMPTION` or `PROPOSE
   SF-ASR-0001 — ANY SECTION OF THE SAME REPORT SUPPORTS THE CLAIMED ASSUMPTION`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   ASSUMPTION-SOURCE-CONTEXT WORDING ALREADY REQUIRES SUPPORT FOR THE EXACT
   REUSED ASSUMPTION`; for propose, exactly `PROPOSE ALLOWING SAME-REPORT
   ADJACENT SUPPORT IN assumption_source_context`.
10. `## Frontier Verification` listing only exact fixture facts, the nine gate
    results, verdict/effect coherence, and boundary checks.

Return only the finished artifact. Emit raw Markdown. The first line must be `---`.
Use one concise row or bullet per item, do not repeat evidence, and stay under
900 words.
