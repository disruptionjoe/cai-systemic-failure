# Draft an affected-standing versus shared-owner-label pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `affected_system_and_standing` field must name the bounded affected system
and affected-party standing visible in sources. Refuse standing borrowed from
an unrelated system without a source-backed bridge.
</evidence>

<synthetic_fixture id="SOL-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Owner label `OWNER-X` administers bounded systems `S-alpha` and `S-beta`.
- Source `E-alpha` establishes group `P-alpha` as affected in `S-alpha` only.
- Source `E-beta` establishes the other required facts for `S-beta` but names
  no affected party. No admitted bridge connects `P-alpha` to `S-beta`.
- Draft `D-owner` transfers standing to `S-beta` because both systems share
  `OWNER-X`. Draft `D-bounded` preserves standing for `S-alpha` and marks
  standing in `S-beta` `UNRESOLVED`.
- Do not infer common population, impact, authority exercise, outcome, or remedy.
- All facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-SOL-0001-affected-standing-and-shared-owner-label.md` with exactly:

1. YAML frontmatter: `test_id: SF-SOL-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_affected_standing_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF SOL 0001 - Affected Standing And Shared Owner Label`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, uncertainty, no-new-record, no-population or impact identity
   inference, no-authority-exercise inference, no-outcome inference, and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Standing Scope Ledger` copying these records literally:

   `draft: D-owner | owner_label: OWNER-X | target_system: S-beta | target_source: E-beta | comparison_system: S-alpha | standing_source: E-alpha | affected_group: P-alpha | standing_in_comparison_system: YES | standing_in_target_system: UNRESOLVED | bridge_to_target_system: NONE | verified_result: FAIL | qualification: REFUSE | uncertainty: target standing unsupported`

   `draft: D-bounded | owner_label: OWNER-X | target_system: S-beta | target_source: E-beta | comparison_system: S-alpha | standing_source: E-alpha | affected_group: P-alpha | standing_in_comparison_system: YES | standing_in_target_system: UNRESOLVED | bridge_to_target_system: NONE | verified_result: FAIL | qualification: REFUSE | uncertainty: target standing unsupported`
6. `## Candidate Gate Trace` copying exactly these lines:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: FAIL — E-alpha supports P-alpha standing only for S-alpha and no admitted bridge connects that standing to S-beta`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` distinguishing owner-label identity, bounded-
   system identity, affected-group identity, source-backed standing, bridge,
   qualification, uncertainty, outcome, and remedy. State whether current
   affected-standing wording already refuses `D-owner`.
8. `## Verdict`: choose exactly `ALREADY HANDLED — A SHARED OWNER LABEL DOES
   NOT TRANSFER AFFECTED-PARTY STANDING BETWEEN BOUNDED SYSTEMS` or `PROPOSE
   SF-SOL-0001 — A SHARED OWNER LABEL TRANSFERS AFFECTED-PARTY STANDING`.
9. `## Candidate Effect`: for already handled, exactly `NONE — CURRENT
   AFFECTED-STANDING WORDING ALREADY REFUSES OWNER-LABEL-BASED TRANSFER`; for
   propose, exactly `PROPOSE CLARIFYING affected_system_and_standing TO
   REQUIRE A SYSTEM-SPECIFIC STANDING BRIDGE`.
10. `## Frontier Verification` listing only exact fixture facts, the nine gate
    results, verdict/effect coherence, and boundary checks.

Return only the finished artifact. Emit raw Markdown. The first line must be `---`.
Use one concise row or bullet per item, do not repeat evidence, and stay under
900 words.
