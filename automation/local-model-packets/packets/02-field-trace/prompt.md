# Draft an affected-standing versus shared-label pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `affected_system_and_standing` field must name the bounded affected system
and affected-party standing visible in the sources. When assembled from
multiple fragments, preserve the admitted bridge connecting that standing to
that system. Refuse standing borrowed from an unrelated system without a
source-backed bridge.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
The record must preserve affected standing and make review paths material to
the contradiction. Every non-target gate below is supplied as `PASS` for this
exact logic test.
</evidence>

<synthetic_fixture id="SSL-FIXTURE-01">
- Old assumption `A-old` is reused under changed condition `C-new` in bounded
  target system `S-target` before final decision `D-final`.
- Source `E-other` establishes that group `P-shared` has affected-party
  standing in different bounded system `S-other`.
- Both systems use the same program label `PROGRAM-Z`, but the packet supplies
  no source-backed bridge connecting `P-shared` or its standing to `S-target`.
- Source `E-target` establishes the other required facts for `S-target` but
  names no affected party. No alternate admitted source supplies that standing.
- Draft `D-label` marks `affected_system_and_standing` `PASS` because the shared
  program label appears in both systems. Draft `D-bounded` preserves
  `P-shared` as standing for `S-other` and marks standing for `S-target`
  `UNRESOLVED`.
- Do not infer that the systems, populations, impacts, or authorities are the
  same; do not infer that `P-shared` lacks standing outside this packet.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-SSL-0001-affected-standing-and-shared-label.md` with exactly:

1. YAML frontmatter: `test_id: SF-SSL-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_affected_standing_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF SSL 0001 - Affected Standing And Shared Label`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-system-identity inference, no-population or impact identity inference,
   no-authority inference, no-standing denial beyond this packet, no-causal
   or outcome inference, and no action.
4. `## Synthetic Fixture` separating every named object and never treating
   shared label `PROGRAM-Z` as a source-backed standing bridge.
5. `## Standing Scope Ledger` using exactly these two keyed records and keys in
   this order. Copy every supplied value literally; edit only `draft_claim`
   and `verified_result`:

   `draft: D-label | target_system: S-target | target_source: E-target | comparison_system: S-other | standing_source: E-other | affected_group: P-shared | shared_label: PROGRAM-Z | standing_in_comparison_system: YES | standing_in_target_system: UNRESOLVED | bridge_to_target_system: NONE | decision: D-final | draft_claim: PASS | verified_result: FAIL | qualification: REFUSE | uncertainty: target standing unsupported`

   `draft: D-bounded | target_system: S-target | target_source: E-target | comparison_system: S-other | standing_source: E-other | affected_group: P-shared | shared_label: PROGRAM-Z | standing_in_comparison_system: YES | standing_in_target_system: UNRESOLVED | bridge_to_target_system: NONE | decision: D-final | draft_claim: UNRESOLVED | verified_result: FAIL | qualification: REFUSE | uncertainty: target standing unsupported`
6. `## Candidate Gate Trace` copying exactly these nine lines in order:

   `assumption_source_context: PASS — supplied premise`

   `accountable_review_owner: PASS — supplied premise`

   `affected_system_and_standing: FAIL — E-other supports P-shared standing only for S-other and no admitted bridge connects that standing to S-target`

   `changed_condition: PASS — supplied premise`

   `validation_burden: PASS — supplied premise`

   `observation_environment: PASS — supplied premise`

   `delegation_visibility_gap: PASS — supplied premise`

   `absorber_or_counterevidence: PASS — supplied premise`

   `correction_route_stop_condition: PASS — supplied premise`

   Infer no other failed gate.
7. `## Nearby-Control Comparison` keeping program-label identity, bounded-
   system identity, affected-group identity, source-backed standing, bridge
   evidence, qualification, uncertainty, outcome, and remedy distinct. State
   whether current affected-standing wording already refuses `D-label`.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-SSL-0001 — A SHARED PROGRAM LABEL TRANSFERS AFFECTED-PARTY STANDING BETWEEN BOUNDED SYSTEMS`; or
   - `ALREADY HANDLED — A SHARED PROGRAM LABEL DOES NOT TRANSFER AFFECTED-PARTY STANDING WITHOUT A SOURCE-BACKED BRIDGE`.
9. `## Candidate Effect`: exactly `PROPOSE CLARIFYING
   affected_system_and_standing TO REQUIRE A SYSTEM-SPECIFIC STANDING BRIDGE`
   for `PROPOSE`, or exactly `NONE — CURRENT AFFECTED-STANDING CONTROL ALREADY
   REFUSES BORROWED STANDING FROM AN UNRELATED SYSTEM` for already handled.
   Propose no new standing, bridge, remedy, acceptance rule, annotation, or
   new field.
10. `## Frontier Verification` listing only exact evidence, identifiers,
    systems and sources, group and label, standing and bridge status, supplied
    premises, qualification, wording, and boundaries.

Return only the finished artifact. Emit raw Markdown without a code fence; the
first line must be `---` and frontmatter must close before the title. Use one
concise row or bullet per required item, do not repeat evidence, and keep the
finished artifact under 1,100 words.
