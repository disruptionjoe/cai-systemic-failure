# Draft a dispute-presence versus validation-burden-relevance pressure test

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

<synthetic_fixture id="VDR-FIXTURE-01">
- One bounded synthetic packet supplies old assumption `A-old`, a
  validation-relevant changed condition `C-range`, and every non-target core
  gate as `PASS` for this exact logic test.
- The only admitted dispute `D-format` concerns capitalization in a display
  label. It does not address the accepted input range, the reuse of `A-old`,
  what adequate revalidation must test, or whether that revalidation is met,
  fragmented, unresolved, or owner-visible.
- Contrast `D-linked` would dispute whether the expanded input range was
  revalidated against `A-old`, but `D-linked` did not occur in the tested
  packet and cannot be borrowed as evidence.
- Draft `D-any` marks `validation_burden` `PASS` solely because some dispute
  exists. Draft `D-relevant` marks the field `FAIL` because the admitted
  dispute is unrelated to the validation burden and keeps `D-linked` only as
  a contrast.
- The supplied non-target grades are not real findings, a new positive record,
  or schema acceptance.
- All names and facts are synthetic. No real source, system, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-VDR-0001-validation-dispute-relevance.md` with exactly these sections:

1. YAML frontmatter containing `test_id: SF-VDR-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_dispute_relevance_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF VDR 0001 - Validation Dispute Relevance`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, no-new-record,
   and no-action status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-range`,
   `D-format`, `D-linked`, `D-any`, and `D-relevant`. Do not treat the mere
   presence of an unrelated dispute or the non-occurring contrast as evidence
   of an unmet validation burden.
5. `## Dispute Relevance Ledger` comparing admitted dispute, connection to
   the reused assumption, connection to the changed condition, adequate-
   revalidation question, burden effect, target-field result, and uncertainty
   for both drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give every non-target row `PASS` with the literal reason `supplied premise`.
   Give `validation_burden` `FAIL` because the only admitted dispute is
   unrelated to what adequate revalidation of `A-old` under `C-range` must
   address. Do not regrade any other gate from the target-field failure.
7. `## Nearby-Control Comparison` keeping dispute presence, dispute
   relevance, adequate-revalidation scope, hypothetical contrast, and overall
   qualification distinct. State whether current wording already requires the
   dispute to bear on the stated validation burden.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-VDR-0001` only if current controls treat any dispute as proof
     of a qualifying validation burden; or
   - `ALREADY HANDLED — DISPUTE PRESENCE DOES NOT ESTABLISH A VALIDATION-RELEVANT BURDEN`
     when current wording already ties disputed status to what adequate
     revalidation must address.
9. `## Candidate Effect` containing exactly `NONE — CURRENT CONTROL ALREADY
   REQUIRES THE DISPUTE TO BE RELEVANT TO THE STATED VALIDATION BURDEN` when
   the verdict is already handled. Do not propose a dispute taxonomy, score,
   remedy, or new acceptance rule.
10. `## Frontier Verification` listing only exact evidence, admitted-dispute,
    assumption-link, changed-condition-link, adequate-revalidation, burden,
    supplied-premise, qualification, wording, and boundary checks needed
    before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---` and the frontmatter must end with a second `---` before the title.
