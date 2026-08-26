# Draft a correction-route continuity falsifier

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, recommend a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
The result is candidate material for Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
A positive record requires an old assumption reused under a changed condition,
an explicit affected system or affected-party standing, material delegation or
review paths, a source-backed validation burden, at least one narrower
countermodel, and an owner-visible correction route.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#correction-route-stop-condition">
The correction route must be shown capable of receiving or surfacing the
contradiction to a party able to correct, escalate, stop, revise, or expose the
assumption. A visible label or a route shown unable to carry the correction is
insufficient.
</evidence>

<evidence path="topology/SF-CRA-0001-correction-route-authority.md#current-control">
CRA refuses a fixture when a named visible route is incapable of receiving,
reviewing, or carrying the contradiction to an accountable owner.
</evidence>

<evidence path="topology/SF-TC-0001-temporal-coherence.md#current-control">
TC refuses a fixture when chronology or same-system identity is used instead
of evidence that the old assumption remained active or was reused during the
changed condition.
</evidence>

<synthetic_fixture id="CRH-FIXTURE-01">
- T1: `A-old` is active for bounded system `S`. Review owner `O-legacy` can
  receive contradictions through `R-legacy`; the route is capable at T1.
- T2: responsibility transfers from `O-legacy` to `O-current`. The transfer
  record removes `R-legacy` access and says it no longer forwards messages.
  No capable replacement route is documented before T4.
- T3: changed condition `C-new` occurs while `A-old` is still reused. A
  source-backed contradiction is sent to `R-legacy`, bounces, and never reaches
  `O-current` before the decision continues.
- The fixture explicitly establishes continued reuse of `A-old`, one bounded
  system, affected standing, a changed condition, and an unmet validation
  burden. Its contested question is whether a route that was capable earlier
  but lost continuity across owner transfer can satisfy the correction-route
  gate at T3.
- All names and facts are synthetic. No real system, person, organization,
  remedy, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-CRH-0001-correction-route-continuity.md` with exactly these sections:

1. YAML frontmatter containing `test_id: SF-CRH-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_falsifier_proposal`, `source_material: synthetic`,
   `external_action: none`.
2. `# SF CRH 0001 - Correction-Route Continuity`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, and no-action status.
4. `## Synthetic Fixture` with a T1/T2/T3 table faithful to every fixture
   fact.
5. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each row `PASS`, `FAIL`, or `UNRESOLVED` plus one fixture-local reason.
6. `## Nearby-Control Comparison` comparing the proposed continuity decision
   with CRA and TC. State the different decision object for each. Do not call
   the new test distinct merely because it has a new name.
7. `## Verdict` choosing exactly one:
   - `PROPOSE SF-CRH-0001` if owner-transfer continuity creates a decision not
     already made by CRA or TC; or
   - `DUPLICATE — DO NOT ADD` if CRA already fully decides it.
   Explain the choice from the embedded controls. In either case the fixture
   must refuse positive qualification at T3 because no capable correction
   route reaches `O-current`.
8. `## Candidate Effect` stating whether existing correction-route wording is
   sufficient or needs one narrow clarification. Do not add a core field.
9. `## Frontier Verification` listing only the exact control comparison and
   wording checks Frontier must perform before any integration.

Return only the finished artifact.
