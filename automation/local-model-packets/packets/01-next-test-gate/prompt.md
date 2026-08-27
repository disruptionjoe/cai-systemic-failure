# Draft a completed-revalidation versus adequate-revalidation pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
A qualifying record must show an old assumption reused under a changed
condition or changed evidence context, and the changed condition must create a
validation burden shown as unmet, disputed, fragmented, or not owner-visible
enough.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `validation_burden` field must state what adequate revalidation would need
to address and what source-backed evidence shows as unmet, disputed,
fragmented, or unresolved. Refuse if the record supplies no source-backed
burden beyond hindsight.
</evidence>

<evidence path="ROADMAP.md">
Keep the candidate provisional and add another bounded test only if a new
public or synthetic case creates material pressure on a core field, refusal
note, annotation, source gate, or correction-route gate.
</evidence>

<synthetic_fixture id="VCA-FIXTURE-01">
- One bounded synthetic packet supplies old assumption `A-old`, a
  validation-relevant changed condition `C-edge`, and every non-target core
  gate as `PASS` for this exact logic test.
- Review procedure `R-complete` was performed and recorded after `C-edge`.
  Its completion is admitted and is not disputed.
- The same admitted packet states that adequate revalidation must test edge
  condition `Q-edge`, but `R-complete` tested only the prior nominal range and
  did not address `Q-edge`.
- The packet therefore preserves a source-backed dispute about adequacy even
  though a review procedure was completed. It does not claim the review was
  absent, fraudulent, or a remedy failure.
- Draft `D-completion` marks `validation_burden` `FAIL` solely because some
  revalidation was completed. Draft `D-adequacy` marks the field `PASS`
  because the completed procedure did not address the admitted adequate-
  revalidation question under `C-edge`.
- The supplied non-target grades are not real findings, a new positive record,
  or schema acceptance.
- All names and facts are synthetic. No real source, system, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-VCA-0001-validation-completion-and-adequacy.md` with exactly these
sections:

1. YAML frontmatter containing `test_id: SF-VCA-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_completion_adequacy_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF VCA 0001 - Validation Completion And Adequacy`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, no-new-record,
   and no-action status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-edge`,
   `R-complete`, `Q-edge`, `D-completion`, and `D-adequacy`. Do not treat
   procedure completion as proof that the admitted adequate-revalidation
   question was addressed.
5. `## Completion And Adequacy Ledger` comparing procedure completion,
   admitted adequate-revalidation question, tested range, changed-condition
   coverage, adequacy dispute, target-field result, and uncertainty for both
   drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give every non-target row `PASS` with the literal reason `supplied premise`.
   Give `validation_burden` `PASS` because the admitted packet shows that
   completed procedure `R-complete` did not address `Q-edge` under `C-edge`,
   leaving adequacy disputed. Do not infer failure of any other gate.
7. `## Nearby-Control Comparison` keeping review presence, review completion,
   adequate-revalidation scope, changed-condition coverage, disputed adequacy,
   and overall qualification distinct. State whether current wording already
   judges adequacy rather than mere completion.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-VCA-0001` only if current controls treat any completed review
     as proof that the validation burden is met; or
   - `ALREADY HANDLED — COMPLETED REVALIDATION DOES NOT ESTABLISH ADEQUATE REVALIDATION`
     when current wording already requires the completed review to address the
     admitted adequate-revalidation question.
9. `## Candidate Effect` containing exactly `NONE — CURRENT CONTROL ALREADY
   REQUIRES REVALIDATION TO ADDRESS THE STATED ADEQUACY QUESTION` when the
   verdict is already handled. Do not propose a review score, remedy,
   procedure, or new acceptance rule.
10. `## Frontier Verification` listing only exact evidence, procedure-
    completion, adequate-question, tested-range, changed-condition-coverage,
    dispute, supplied-premise, qualification, wording, and boundary checks
    needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---` and the frontmatter must end with a second `---` before the title.
