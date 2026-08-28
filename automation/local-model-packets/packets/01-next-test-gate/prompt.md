# Draft a changed-evidence-context versus physical-change pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
Positive qualification requires an old assumption reused under a changed
condition or changed evidence context. The `changed_condition` field may name
an observed anomaly, source switch, evidence-context change, operating change,
or other change that alters the validation burden. Refuse reuse under
materially unchanged conditions.
</evidence>

<synthetic_fixture id="CEV-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- System `S-one` reuses old assumption `A-old` at decision `T-reuse`.
- Physical operating condition `O-one` is materially unchanged from the
  earlier decision window.
- Admitted source `E-old` supported `A-old`. Before `T-reuse`, admitted source
  `E-new` materially disputes that support and therefore changes the evidence
  context and validation burden. The conflict is preserved and graded.
- Draft `D-physical` marks `changed_condition` failed solely because `O-one`
  did not change. Draft `D-evidence` marks it passed because `E-new` changed
  the admitted evidence context before reuse.
- Do not invent a physical change, source supersession, authority exercise,
  outcome, remedy, or ungraded contradiction.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-CEV-0001-changed-evidence-context.md` with exactly:

1. YAML frontmatter: `test_id: SF-CEV-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_changed_evidence_context_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF CEV 0001 - Changed Evidence Context Without Physical Change`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-physical-change invention,
   no-authority-exercise inference, no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Change Context Ledger` copying these records literally:

   `draft: D-physical | system: S-one | reused_assumption: A-old | decision: T-reuse | physical_condition: O-one | physical_change: NONE | earlier_source: E-old | new_admitted_source: E-new | evidence_context_change: MATERIAL_DISPUTE | contradiction_grade: PRESERVED | changed_condition_result: FAIL | qualification: REFUSE | uncertainty: physical-change-only reading`

   `draft: D-evidence | system: S-one | reused_assumption: A-old | decision: T-reuse | physical_condition: O-one | physical_change: NONE | earlier_source: E-old | new_admitted_source: E-new | evidence_context_change: MATERIAL_DISPUTE | contradiction_grade: PRESERVED | changed_condition_result: PASS | qualification: CONTINUE_GATE_CHECKS | uncertainty: no physical change`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: PASS — supplied premise; E-old and E-new are admitted and the conflict is graded`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: PASS — supplied premise`

   `changed_condition: PASS — E-new materially changes the admitted evidence context and validation burden before T-reuse`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing physical-condition change,
   changed evidence context, material dispute, graded contradiction, reuse,
   qualification, uncertainty, outcome, and remedy. State whether current
   changed-condition wording already supports `D-evidence`.
8. `## Verdict`: choose exactly `ALREADY HANDLED — A MATERIAL EVIDENCE-CONTEXT
   CHANGE CAN ALTER THE VALIDATION BURDEN WITHOUT A PHYSICAL CHANGE` or
   `PROPOSE SF-CEV-0001 — ONLY A PHYSICAL CHANGE CAN SATISFY changed_condition`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   CHANGED-CONDITION WORDING ALREADY INCLUDES CHANGED EVIDENCE CONTEXT`; for
   propose, exactly `PROPOSE NARROWING changed_condition TO PHYSICAL CHANGES`.
10. `## Frontier Verification` listing only exact fixture facts, the nine gate
    results, verdict/effect coherence, and boundary checks.

Return only the finished artifact. Emit raw Markdown. The first line must be `---`.
Use one concise row or bullet per item, do not repeat evidence, and stay under
900 words.
