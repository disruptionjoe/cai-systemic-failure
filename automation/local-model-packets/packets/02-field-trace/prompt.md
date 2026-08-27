# Draft a retrospective-evidence versus observation-environment pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
A positive record requires source-backed assumption reuse under a changed
condition, a validation burden, explicit affected standing, material review
paths, a narrower countermodel, and an owner-visible correction route.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `observation_environment` field preserves how the relevant evidence was
made visible, missed, normalized, routed, or disputed without importing a
domain conclusion. Refuse when the field becomes a domain-specific remedy or
expertise claim.
</evidence>

<evidence path="topology/SF-SQA-0001-source-quality-falsifier.md#verdict">
Source-thin or hindsight-built pattern matches cannot qualify without durable
source material that carries the assumption context, changed condition,
validation burden, review owner, and correction route.
</evidence>

<synthetic_fixture id="ROE-FIXTURE-01">
- One bounded synthetic packet concerns reuse of `A-old` under `C-new` at
  decision time `T2`.
- The packet explicitly says no relevant observation, measurement, log,
  request, or other evidence existed or was available to the review chain at
  `T2`; nothing was then visible, missed, normalized, routed, or disputed.
- At `T3`, after the bounded decision, reconstruction `E-post` creates new
  synthetic evidence about conditions at `T2`. The packet distinguishes this
  later-created evidence from evidence that existed but was overlooked or
  blocked during the earlier review.
- Draft `D-retro-pass` marks `observation_environment` passed because
  `E-post` is visible now. Draft `D-environment-bound` preserves `E-post` as
  retrospective evidence but marks the field unresolved for the tested review
  because the admitted packet supplies no relevant evidence environment at
  `T2`.
- Every non-observation core gate is supplied only as a synthetic premise for
  this exact test. The fixture does not dispute those premises or use the
  target observation result to regrade them.
- All names and facts are synthetic. No real system, measurement, source,
  person, organization, remedy, domain conclusion, or external action is
  represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-ROE-0001-retrospective-evidence-observation-environment.md` with exactly
these sections:

1. YAML frontmatter containing `test_id: SF-ROE-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_retrospective_observation_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF ROE 0001 - Retrospective Evidence And Observation Environment`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, and no-action
   status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-new`, `T2`,
   `T3`, `E-post`, `D-retro-pass`, and `D-environment-bound`. Do not relabel
   later-created evidence as evidence that was present but missed at `T2`.
5. `## Evidence Timing Ledger` comparing evidence existence at `T2`, later
   creation at `T3`, visibility, missed-or-routed status, field result, and
   uncertainty for both drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each row `PASS`, `FAIL`, or `UNRESOLVED` plus one fixture-local reason.
   For every non-target row, copy the supplied grade `PASS` and use the literal
   reason `supplied premise`; do not infer or regrade it from observation-
   timing facts. Grade only `observation_environment` from whether relevant
   evidence existed within the tested review environment, not from later
   reconstruction alone.
7. `## Nearby-Control Comparison` keeping later source availability, evidence
   creation, prior observation environment, and hindsight reconstruction
   distinct. State whether current wording plus the source-quality refusal
   already prevents retrospective evidence from masquerading as prior
   visibility, missed evidence, normalization, routing, or dispute.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-ROE-0001` only if current controls let evidence created after
     the decision supply the observation environment of the earlier review; or
   - `ALREADY HANDLED — LATER-CREATED EVIDENCE DOES NOT SUPPLY A PRIOR OBSERVATION ENVIRONMENT`
     when current wording already preserves that distinction.
9. `## Candidate Effect` stating whether any narrow wording change is
   justified. Do not add a core field, erase retrospective evidence, invent
   prior visibility, prescribe observation or a remedy, accept the schema, or
   create a control hierarchy.
10. `## Frontier Verification` listing only exact evidence, evidence timing,
    creation versus visibility, hindsight, supplied-premise, qualification,
    wording, and boundary checks needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---`.
