# Draft a multi-condition validation-coverage pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `changed_condition` field identifies the change that alters the validation
burden. The `validation_burden` field states what adequate revalidation would
need to address and what source-backed evidence shows as unmet, disputed,
fragmented, or unresolved. Refuse a burden inferred only from hindsight.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#qualification-gate">
Positive qualification requires an old assumption reused under a changed
condition and a validation burden that admitted evidence shows as unmet,
disputed, fragmented, or not owner-visible enough. Other supplied gates do not
erase a failed validation-burden field.
</evidence>

<synthetic_fixture id="MVC-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Old assumption `A-old` is reused for bounded system `S-bounded` after two
  admitted changed conditions become jointly operative: load change `C-load`
  and interface change `C-interface`.
- Burden statement `B-joint` says adequate revalidation must address
  `C-load`, `C-interface`, and their interaction `X-joint` for `S-bounded`.
- Completed test `V-load` addresses `C-load` and passes. It does not address
  `C-interface` or `X-joint`.
- Summary `SUM-complete` truthfully says `V-load` completed and passed, but
  supplies no other test, analysis, dispute resolution, or owner-visible
  evidence for `C-interface` or `X-joint`.
- Draft `D-aggregate` claims `validation_burden` `PASS` because a completed
  validation exists. Draft `D-covered` preserves the same facts and marks the
  field `FAIL` because two named parts of `B-joint` remain unresolved.
- Do not infer that `V-load` is defective, that either change caused an
  outcome, that another validation occurred, or that a remedy is required.
  This tests completed partial validation versus coverage of the admitted
  burden, not domain adequacy.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-MVC-0001-multi-condition-validation-coverage.md` with exactly:

1. YAML frontmatter: `test_id: SF-MVC-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_coverage_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF MVC 0001 - Multi-Condition Validation Coverage`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-test-defect inference, no-causal or outcome inference, no-unobserved-
   validation inference, no-adequacy conclusion, and no-action status.
4. `## Synthetic Fixture` separating `A-old`, `S-bounded`, `C-load`,
   `C-interface`, `B-joint`, `X-joint`, `V-load`, `SUM-complete`,
   `D-aggregate`, and `D-covered`; never turn completion of `V-load` into
   coverage of the other named burden components.
5. `## Validation Coverage Ledger` with exactly two rows, one per draft, and
   columns for draft, assumption, system, changed-condition set, burden,
   completed validation, covered component, uncovered component, uncovered
   interaction, completion statement, draft-claimed target result,
   verified target result, qualification result, and uncertainty. Use the
   same supplied facts in both rows; vary only each draft's interpretation and
   claimed result. The verified result is `FAIL` for both rows.
6. `## Candidate Gate Trace` with these nine rows in order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each non-target row `PASS` / `supplied premise`; give
   `validation_burden` `FAIL` / `completed V-load covers C-load but admitted
   burden B-joint still lacks C-interface and X-joint coverage`. Infer no
   other failed gate.
7. `## Nearby-Control Comparison` keeping validation existence, completion,
   result, burden definition, component coverage, interaction coverage,
   domain adequacy, qualification, uncertainty, causation, and remedy
   distinct. State whether current wording already requires addressing the
   admitted validation burden rather than merely completing some validation.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-MVC-0001 — ANY COMPLETED VALIDATION SATISFIES A MULTI-CONDITION BURDEN`
     only if `D-aggregate` can pass; or
   - `ALREADY HANDLED — COMPLETION DOES NOT ESTABLISH COVERAGE OF THE ADMITTED VALIDATION BURDEN`
     when current wording already requires burden-relevant coverage.
9. `## Candidate Effect`: exactly `PROPOSE CLARIFYING validation_burden TO
   REQUIRE COVERAGE OF EVERY NAMED BURDEN COMPONENT` for `PROPOSE`, or exactly
   `NONE — CURRENT CONTROL ALREADY REQUIRES THE RECORD TO STATE WHAT ADEQUATE
   REVALIDATION MUST ADDRESS AND WHAT REMAINS UNRESOLVED` for already handled.
   Propose no test design, remedy, acceptance rule, annotation, or new field.
10. `## Frontier Verification` listing only exact evidence, identifiers,
    changed-condition set, burden components, completed-test scope, uncovered
    scope, supplied premises, qualification, wording, and boundary checks.

Return only the finished artifact. Emit raw Markdown without a code fence; the
first line must be `---` and frontmatter must end with a second `---` before
the title. Use one concise row or bullet per required item, do not repeat
evidence, and keep the finished artifact under 1,300 words.
