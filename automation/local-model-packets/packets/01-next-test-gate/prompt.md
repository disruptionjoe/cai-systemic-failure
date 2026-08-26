# Draft a validation-surrogate coverage pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
A positive record requires old-assumption reuse under a changed condition and
a validation burden that source-backed evidence shows as unmet, disputed,
fragmented, or not owner-visible enough. The candidate remains provisional.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The validation burden must state what adequate revalidation would need to
address and what source-backed evidence shows as unmet, disputed, fragmented,
or unresolved. Refuse a burden supplied only by hindsight.
</evidence>

<evidence path="topology/SF-TC-0001-temporal-coherence.md#verdict">
Same-system identity and chronology do not prove an old assumption remained
active or was reused during a changed condition. Temporal support must carry
the qualifying relationship.
</evidence>

<evidence path="topology/SF-SQA-0001-source-quality-falsifier.md#verdict">
A source-thin or hindsight-built pattern match cannot qualify without durable
material carrying assumption context, changed condition, validation burden,
review owner, and correction route.
</evidence>

<synthetic_fixture id="VSC-FIXTURE-01">
- T1: bounded system `S` uses old assumption `A-old`. Revision-labeled
  synthetic material names the assumption owner, accountable review owner,
  affected standing, review path, and a capable owner-visible correction route.
- At T1, validation procedure `V-base` tests `A-old` in environment `E-base`.
  Its admitted scope explicitly excludes condition class `C-new`. `V-base`
  passes every stated acceptance criterion inside `E-base`.
- T2: `C-new` occurs while `A-old` remains in use. The admitted packet states
  that `C-new` changes the operating coupling that creates the record's
  validation burden. It does not say `V-base` was defective or that its
  baseline result should be withdrawn.
- Before decision `D-reuse`, no admitted validation tests `A-old` under
  `C-new`, maps `V-base` coverage to `C-new`, or explains why the excluded
  condition is immaterial. The gap is visible to the review path.
- A traceable, graded countermodel says `V-base` is valid evidence for
  `E-base`; it does not claim that the baseline result covers `C-new`.
- A draft record marks `validation_burden` passed as adequately revalidated
  solely because `V-base` formally passed. It does not distinguish a valid
  baseline result from coverage of the changed condition.
- Every other apparent gate is supplied only as a synthetic premise for testing
  that validation decision. All names and facts are synthetic. No real system,
  measurement, person, organization, remedy, domain conclusion, or external
  action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-VSC-0001-validation-surrogate-coverage.md` with exactly these sections:

1. YAML frontmatter containing `test_id: SF-VSC-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_coverage_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF VSC 0001 - Validation Surrogate Coverage`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, and no-action
   status.
4. `## Synthetic Fixture` with a T1/T2/pre-decision table faithful to every
   fixture fact. Do not call `V-base` invalid or invent a test under `C-new`.
5. `## Coverage Ledger` separating what `V-base` actually tested, what it
   explicitly excluded, what `C-new` changes, and what coverage relationship
   remains unsupported. A passed baseline test is evidence inside its stated
   scope, not automatically evidence for every later condition.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each row `PASS`, `FAIL`, or `UNRESOLVED` plus one fixture-local reason.
   Treat the supplied non-validation premises as supplied; do not mark them
   unresolved merely because `V-base` does not establish them.
7. `## Nearby-Control Comparison` comparing validation-surrogate coverage with
   TC temporal coexistence and SQA source/hindsight sufficiency. State the
   different decision object for each. Do not convert coverage alignment into
   a demand for perfect validation or a domain-specific test.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-VSC-0001` if current validation-burden wording leaves material
     ambiguity about whether a passed test covers the changed condition it is
     used to revalidate; or
   - `DUPLICATE — CURRENT WORDING SUFFICIENT` if the existing requirement to
     state what adequate revalidation must address already requires this
     coverage distinction.
9. `## Candidate Effect` stating whether current owner wording is sufficient
   or needs one narrow coverage-alignment clarification. Do not add a core
   field, invalidate `V-base`, require certainty, or accept the schema.
10. `## Frontier Verification` listing only exact scope, condition, timing,
    nonduplication, wording, and boundary checks needed before integration.

Return only the finished artifact.
