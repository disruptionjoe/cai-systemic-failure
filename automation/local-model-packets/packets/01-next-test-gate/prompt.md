# Draft a relied-on source-revision identity pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `assumption_source_context` field must name the reused assumption and the
source revision, version, date, or evidence basis relied on. Refuse a field
that does not tie the assumption to identifiable source context.
</evidence>

<synthetic_fixture id="RSI-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Report title `REPORT-Q` has admitted revisions `R1` and `R2`.
- `R1` explicitly supports old assumption `A-old`; `R2` is a later metadata-
  only revision that neither withdraws nor contradicts `A-old`.
- Draft `D-title` cites only `REPORT-Q` and does not identify the relied-on
  revision. Draft `D-revision` cites `REPORT-Q@R1` as the relied-on support.
- Do not invent supersession, contradiction, retirement, outcome, or remedy.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-RSI-0001-relied-on-source-revision-identity.md` with exactly:

1. YAML frontmatter: `test_id: SF-RSI-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_source_revision_identity_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF RSI 0001 - Relied-On Source Revision Identity`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-supersession invention,
   no-contradiction invention, no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Revision Identity Ledger` copying these records literally:

   `draft: D-title | report: REPORT-Q | revisions_admitted: R1,R2 | relied_revision: UNSPECIFIED | R1_assumption_support: YES | R2_effect: METADATA_ONLY | later_contradiction: NONE | verified_result: FAIL | qualification: REFUSE | uncertainty: relied revision unidentified`

   `draft: D-revision | report: REPORT-Q | revisions_admitted: R1,R2 | relied_revision: R1 | R1_assumption_support: YES | R2_effect: METADATA_ONLY | later_contradiction: NONE | verified_result: PASS | qualification: CONTINUE_GATE_CHECKS | uncertainty: none added`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: FAIL — D-title names REPORT-Q but not the relied-on revision`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing report-title identity,
   revision identity, relied-on support, later metadata change, contradiction,
   qualification, uncertainty, outcome, and remedy. State whether current
   source-context wording already refuses `D-title`.
8. `## Verdict`: choose exactly `ALREADY HANDLED — A REPORT TITLE WITHOUT THE
   RELIED-ON REVISION DOES NOT SATISFY SOURCE CONTEXT` or `PROPOSE SF-RSI-0001
   — A REPORT TITLE ALONE IDENTIFIES THE RELIED-ON SOURCE REVISION`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   ASSUMPTION-SOURCE-CONTEXT WORDING ALREADY REQUIRES RELIED-ON REVISION
   IDENTITY`; for propose, exactly `PROPOSE CLARIFYING
   assumption_source_context TO REQUIRE RELIED-ON REVISION IDENTITY`.
10. `## Frontier Verification` listing only exact fixture facts, the nine gate
    results, verdict/effect coherence, and boundary checks.

Return only the finished artifact. Emit raw Markdown. The first line must be `---`.
Use one concise row or bullet per item, do not repeat evidence, and stay under
900 words.
