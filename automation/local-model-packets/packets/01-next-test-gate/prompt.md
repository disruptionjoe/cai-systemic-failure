# Draft a post-event investigator versus accountable-review-owner pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
A positive record requires an old assumption reused under a changed condition,
a source-backed validation burden, explicit affected standing, material review
paths, a narrower countermodel, and a capable owner-visible correction route.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `accountable_review_owner` field must distinguish the assumption owner from
the owner who could review, stop, escalate, or revise its reuse. Refuse when
accountability is only a generic organization label.
</evidence>

<evidence path="topology/SF-CRA-0001-correction-route-authority.md#verdict">
A visible label is insufficient when the admitted packet shows that the named
route cannot receive, review, or carry the relevant correction to an
accountable owner. Capability, not guaranteed success, is the decision object.
</evidence>

<synthetic_fixture id="ART-FIXTURE-01">
- One bounded synthetic packet shows assumption `A-old` reused under changed
  condition `C-new` at decision time `T2`.
- The packet names `O-maint` as the assumption owner. At `T2`, it names only
  generic review group `G-review`; no admitted fact shows that `G-review` or
  any named party could review, stop, escalate, or revise the reuse.
- After the bounded decision, at `T3`, `I-post` is appointed to investigate
  what occurred. The packet explicitly says `I-post` had no authority over the
  reuse at `T2` and can only inspect and report retrospectively.
- Draft `D-retro-owner` marks `accountable_review_owner` passed because
  `I-post` is a named investigator. Draft `D-time-bound` preserves `I-post` as
  retrospective evidence but marks the owner field unresolved because the
  packet names no party with the required review authority for the tested
  reuse at `T2`.
- Every non-owner core gate is supplied only as a synthetic premise for this
  exact test. The fixture does not dispute those premises or use the target
  owner result to regrade them.
- All names and facts are synthetic. No real system, source, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-ART-0001-post-event-investigator-review-owner.md` with exactly these
sections:

1. YAML frontmatter containing `test_id: SF-ART-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_review_owner_timing_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF ART 0001 - Post-Event Investigator And Accountable Review Owner`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, and no-action
   status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-new`, `T2`,
   `T3`, `O-maint`, `G-review`, `I-post`, `D-retro-owner`, and
   `D-time-bound`.
5. `## Authority Timing Ledger` comparing named identity, authority at `T2`,
   retrospective role at `T3`, owner-field result, and uncertainty for both
   drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each row `PASS`, `FAIL`, or `UNRESOLVED` plus one fixture-local reason.
   For every non-target row, copy the supplied grade `PASS` and use the literal
   reason `supplied premise`; do not infer or regrade it from owner-timing
   facts. Grade only `accountable_review_owner` from admitted authority over
   the tested reuse, not from a title created after the decision.
7. `## Nearby-Control Comparison` keeping assumption ownership, accountable
   review authority, retrospective investigation, and correction-route
   capability distinct. State whether current wording already requires the
   named owner to be capable with respect to the relevant reuse.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-ART-0001` only if current wording lets retrospective
     investigator identity substitute for accountable authority over the
     relevant reuse; or
   - `ALREADY HANDLED — POST-EVENT INVESTIGATOR IDENTITY DOES NOT SUPPLY PRIOR REVIEW AUTHORITY`
     when current wording already requires relevant capability.
9. `## Candidate Effect` stating whether any narrow wording change is
   justified. Do not add a core field, erase retrospective evidence, prescribe
   governance, accept the schema, or create a control hierarchy.
10. `## Frontier Verification` listing only exact evidence, identity,
    authority timing, supplied-premise, qualification, wording, and boundary
    checks needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---`.
