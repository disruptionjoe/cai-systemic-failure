# Draft a changed-condition relevance versus mere-difference pressure test

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
The `changed_condition` field identifies a changed function, observed anomaly,
source switch, evidence context, operating condition, or other change that
alters the validation burden. Refuse when the old assumption is reused under
materially unchanged conditions.
</evidence>

<evidence path="ROADMAP.md">
Keep the candidate provisional and add another bounded test only if a new
public or synthetic case creates material pressure on a core field, refusal
note, annotation, source gate, or correction-route gate.
</evidence>

<synthetic_fixture id="CRB-FIXTURE-01">
- One bounded synthetic packet shows old assumption `A-old` continuing in use.
- Difference `C-cosmetic` changes only a screen color, document label, and log
  storage path. It does not change the function, input range, evidence
  context, operating condition, expected behavior, or validation needed for
  `A-old`.
- Contrast `C-burden` would change the accepted input range and therefore
  alter what adequate revalidation of `A-old` must address, but `C-burden`
  did not occur in the tested packet and cannot be borrowed as evidence.
- Draft `D-any` marks `changed_condition` `PASS` solely because
  `C-cosmetic` is a difference. Draft `D-relevant` marks the field `FAIL`
  because the admitted change does not alter the validation burden and keeps
  `C-burden` only as a contrast.
- Every non-target core gate is supplied as `PASS` for this exact logic test.
  Those supplied grades are not real findings, a new positive record, or
  schema acceptance.
- All names and facts are synthetic. No real source, system, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-CRB-0001-change-relevance-to-validation-burden.md` with exactly these
sections:

1. YAML frontmatter containing `test_id: SF-CRB-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_change_relevance_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF CRB 0001 - Changed Condition Relevance To Validation Burden`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, no-new-record,
   and no-action status.
4. `## Synthetic Fixture` faithfully separating `A-old`, `C-cosmetic`,
   `C-burden`, `D-any`, and `D-relevant`. Do not treat a mere difference or
   the non-occurring contrast as a qualifying changed condition.
5. `## Change Relevance Ledger` comparing admitted change, functional effect,
   evidence-context effect, validation-burden effect, target-field result, and
   uncertainty for both drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give every non-target row `PASS` with the literal reason `supplied premise`.
   Give `changed_condition` `FAIL` because the only admitted difference does
   not alter the validation burden. Do not regrade any other gate from the
   target-field failure.
7. `## Nearby-Control Comparison` keeping mere difference, validation-relevant
   change, a hypothetical contrast, and overall qualification distinct. State
   whether current wording already requires the changed condition to alter
   the validation burden.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-CRB-0001` only if current controls treat every difference as
     a qualifying changed condition regardless of validation relevance; or
   - `ALREADY HANDLED — MERE DIFFERENCE DOES NOT ESTABLISH A VALIDATION-RELEVANT CHANGED CONDITION`
     when current wording already requires an altered validation burden.
9. `## Candidate Effect` containing exactly `NONE — CURRENT CONTROL ALREADY
   REQUIRES CHANGE TO ALTER THE VALIDATION BURDEN` when the verdict is already
   handled. Do not propose cosmetic-change, interface, logging, or operational
   wording.
10. `## Frontier Verification` listing only exact evidence, admitted-change,
    functional-effect, evidence-context, validation-burden, supplied-premise,
    qualification, wording, and boundary checks needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---` and the frontmatter must end with a second `---` before the title.
