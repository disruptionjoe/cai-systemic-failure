# Draft a correction-route referential-integrity pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `correction_route_stop_condition` field must name an owner-visible route
and an admitted basis showing how it can receive or surface the relevant
contradiction to a party able to correct, escalate, stop, revise, or expose the
assumption. Refuse a route that is only a label or cannot carry the relevant
correction.
</evidence>

<evidence path="topology/SF-CRA-0001-correction-route-authority.md#verdict">
A route need not guarantee success, but it must make the relevant contradiction
available through an accountable path. Outcome remains graded uncertainty.
</evidence>

<synthetic_fixture id="RRI-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Old assumption `A-old` is reused under changed condition `C-new` for bounded
  system `S-bounded` before final decision `D-final`.
- Evidence packet `E-relevant` contains synthetic basis `SRC-relevant` and the
  relevant contradiction. Unrelated packet `E-other` contains neither.
- Route `R-mutable` sends notice `N-ref` with location label `REF-mutable` to
  capable recipient `O-capable` before `D-final`.
- At notice time `REF-mutable` resolves to `E-relevant`. Before `O-capable`
  retrieves it, the location is overwritten and resolves only to `E-other`.
  No immutable content identifier, retained copy, or alternate route preserves
  access to `E-relevant` before `D-final`.
- Receipt `REC-other` verifies that `O-capable` retrieved `E-other`; it does
  not verify access to `E-relevant` or `SRC-relevant`.
- Draft `D-label` marks `correction_route_stop_condition` `PASS` because the
  notice and location label remain visible. Draft `D-content` preserves the
  same facts and marks the field `FAIL` because the relevant contradiction is
  unavailable through the route at retrieval time.
- Do not infer bad faith, data loss outside this fixture, route redesign,
  recipient agreement, authority exercise, outcome, or remedy.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-RRI-0001-correction-route-referential-integrity.md` with exactly:

1. YAML frontmatter: `test_id: SF-RRI-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_route_integrity_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF RRI 0001 - Correction Route Referential Integrity`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, no-domain-expertise, uncertainty, no-new-record, no-bad-faith
   inference, no-retention-policy inference, no-route-redesign, no-authority-
   exercise or recipient-agreement inference, no-outcome inference, and
   no-action status.
4. `## Synthetic Fixture` separating every named object and never treating the
   stable location label or `REC-other` as proof that the relevant
   contradiction remained available.
5. `## Route Integrity Ledger` using exactly these two keyed records and keys
   in this order. Copy every supplied value literally; edit only
   `draft_claim` and `verified_result`:

   `draft: D-label | relevant_packet: E-relevant | relevant_basis: SRC-relevant | unrelated_packet: E-other | route: R-mutable | notice: N-ref | reference: REF-mutable | recipient: O-capable | notice_timing: before D-final | at_notice: E-relevant | at_retrieval: E-other only | immutable_id: NONE | retained_copy: NONE | receipt: REC-other | relevant_content_available: NO | draft_claim: PASS | verified_result: FAIL | qualification: REFUSE | uncertainty: outcome not inferred`

   `draft: D-content | relevant_packet: E-relevant | relevant_basis: SRC-relevant | unrelated_packet: E-other | route: R-mutable | notice: N-ref | reference: REF-mutable | recipient: O-capable | notice_timing: before D-final | at_notice: E-relevant | at_retrieval: E-other only | immutable_id: NONE | retained_copy: NONE | receipt: REC-other | relevant_content_available: NO | draft_claim: FAIL | verified_result: FAIL | qualification: REFUSE | uncertainty: outcome not inferred`
6. `## Candidate Gate Trace` with the nine candidate fields in current order.
   Give every non-target field `PASS — supplied premise`; give
   `correction_route_stop_condition` `FAIL — R-mutable cannot surface
   E-relevant or SRC-relevant to O-capable at retrieval time`. Infer no other
   failed gate.
7. `## Nearby-Control Comparison` keeping notice delivery, label stability,
   referential integrity, relevant-content availability, recipient
   capability, receipt identity, authority exercise, route outcome,
   qualification, uncertainty, and remedy distinct. State whether current
   relevant-contradiction carriage wording already refuses `D-label`.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-RRI-0001 — A VISIBLE LOCATION LABEL SATISFIES THE ROUTE AFTER ITS RELEVANT CONTENT CHANGES`; or
   - `ALREADY HANDLED — A ROUTE MUST STILL SURFACE THE RELEVANT CONTRADICTION, NOT MERELY ITS OLD LABEL`.
9. `## Candidate Effect`: exactly `PROPOSE CLARIFYING
   correction_route_stop_condition TO REQUIRE REFERENTIAL INTEGRITY` for
   `PROPOSE`, or exactly `NONE — CURRENT RELEVANT-CORRECTION CARRIAGE CONTROLS
   ALREADY REFUSE A LABEL THAT NO LONGER RESOLVES TO THE CONTRADICTION` for
   already handled. Propose no storage design, retention policy, route repair,
   remedy, acceptance rule, annotation, or new field.
10. `## Frontier Verification` listing only exact evidence, identifiers,
    resolution states and timing, receipt identity, relevant-content
    availability, supplied premises, qualification, wording, and boundaries.

Return only the finished artifact. Emit raw Markdown without a code fence; the
first line must be `---` and frontmatter must close before the title. Use one
concise row or bullet per required item, do not repeat evidence, and keep the
finished artifact under 1,100 words.
