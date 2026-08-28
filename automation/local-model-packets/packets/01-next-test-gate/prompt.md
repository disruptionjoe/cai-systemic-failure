# Draft archive custody versus operative assumption support pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `assumption_source_context` field must name the reused assumption and the
source, revision, decision context, or evidence basis relied on for the
synthesis. Repository custody, citation metadata, or access to a revision does
not by itself show that the revision supports the named assumption or that the
assumption informed the reuse decision.
</evidence>

<synthetic_fixture id="ADC-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Archive `A-store` contains revision `R-cited`, and team `T-review` has read
  access to the archive.
- Draft `D-custody` cites `R-cited` and the archive path, but the admitted
  fixture supplies no statement in `R-cited` supporting assumption `A-old`
  and no trace connecting `A-old` to reuse decision `T-reuse`.
- Draft `D-use` preserves the same custody metadata and supplies synthetic
  statement `S-assumption` in `R-cited` plus trace `TR-use` connecting
  `A-old`, `R-cited`, and `T-reuse`.
- The fixture does not say archive access was exercised, that either draft is
  a real record, or that an outcome followed. All facts are synthetic.
</synthetic_fixture>

## Work now

Draft `SF-ADC-0001-archive-custody-operative-assumption-support.md` with exactly:

1. Begin with this literal raw frontmatter block, including both `---` lines:

   `---`

   `test_id: SF-ADC-0001`

   `candidate: SF-SCHEMA-CANDIDATE-0001`

   `status: synthetic_assumption_support_proposal`

   `source_material: synthetic`

   `external_action: none`

   `---`
2. `# SF ADC 0001 - Archive Custody And Operative Assumption Support`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-access-exercise inference,
   no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Support Ledger` copying these records literally:

   `draft: D-custody | archive: A-store | revision: R-cited | access: PRESENT | assumption_statement: NONE | reuse_trace: NONE | verified_result: FAIL | uncertainty: custody and access do not establish operative support`

   `draft: D-use | archive: A-store | revision: R-cited | access: PRESENT | assumption_statement: S-assumption | reuse_trace: TR-use | verified_result: PASS | uncertainty: synthetic support is not a real-world claim`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: FAIL — D-custody names custody and revision metadata but supplies no assumption support or reuse-decision trace`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing archive custody, access,
   revision identity, assumption support, reuse-decision trace, uncertainty,
   access exercise, outcome, and remedy. State whether current wording already
   refuses `D-custody` and permits `D-use` to continue gate checks.
8. `## Verdict`: choose exactly `ALREADY HANDLED — ARCHIVE CUSTODY DOES NOT
   SUBSTITUTE FOR OPERATIVE ASSUMPTION SUPPORT` or `PROPOSE SF-ADC-0001 —
   CURRENT WORDING ALLOWS CUSTODY METADATA TO SUBSTITUTE FOR ASSUMPTION
   SUPPORT`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   assumption_source_context WORDING REQUIRES ASSUMPTION SUPPORT AND A
   REUSE-DECISION TRACE`; for propose, exactly `PROPOSE CLAIM-LEVEL SUPPORT AND
   REUSE-TRACE HANDLING`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; all
    nine gate results; verdict/effect coherence; raw-frontmatter validity; and
    boundary checks.

Return only the finished artifact. Emit raw Markdown, not a code fence. The
first line and the line after `external_action: none` must both be `---`. Copy
all five YAML fields. Use one concise row or bullet per item, do not repeat
evidence, and stay under 850 words.
