# Draft a formal-retirement versus documented operative-reuse pressure test

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
The `assumption_source_context` field must preserve any known retirement or
replacement event and include evidence that the assumption remained active or
was reused during the changed condition. Refuse when chronology substitutes
for evidence of continued reliance or reuse.
</evidence>

<evidence path="topology/SF-TC-0001-temporal-coherence.md#verdict">
Same-system identity and chronology do not establish that an old assumption
remained active or was reused during a later changed condition.
</evidence>

<synthetic_fixture id="FOR-FIXTURE-01">
- One bounded synthetic packet supplies changed condition `C-late` and every
  non-target core gate as `PASS` for this exact logic test.
- Master register `R-master` marks assumption `A-old` retired before `C-late`.
- Later exception record `W-live`, issued after `C-late`, explicitly
  reauthorizes `A-old` as an operative premise for decision scope `S-late`.
- `W-live` identifies `R-master`, preserves the prior retirement, limits the
  reuse to `S-late`, and records stop condition `Q-stop`. The admitted packet
  does not treat the retirement as erased or claim reuse outside `S-late`.
- Draft `D-status` marks `assumption_source_context` `FAIL` from the formal
  retirement alone. Draft `D-use` marks the field `PASS` because the packet
  preserves both the retirement and the explicit later operative reuse.
- The fixture does not claim that every exception revives a retired
  assumption, that `W-live` is valid beyond its stated scope, or that the reuse
  is a remedy, safe, adequate, or accepted. It tests only whether documented
  later operative reuse remains evidence despite an earlier formal status.
- The supplied non-target grades are not real findings, a new positive record,
  or schema acceptance.
- All names and facts are synthetic. No real source, system, person,
  organization, remedy, domain conclusion, or external action is represented.
</synthetic_fixture>

## Work now

Draft the finished Markdown artifact
`SF-FOR-0001-formal-retirement-and-operative-reuse.md` with exactly these
sections:

1. YAML frontmatter containing `test_id: SF-FOR-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_formal_status_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF FOR 0001 - Formal Retirement And Operative Reuse`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   no-remedy, no-promotion, no-domain-expertise, uncertainty, no-new-record,
   limited-scope, and no-action status.
4. `## Synthetic Fixture` faithfully separating `R-master`, `A-old`,
   `C-late`, `W-live`, `S-late`, `Q-stop`, `D-status`, and `D-use`. Do not
   erase the retirement, generalize the exception, or infer adequacy from
   reauthorization.
5. `## Status And Operative-Role Ledger` comparing formal status, status
   source, later record, later decision scope, operative premise, reuse
   evidence, scope limit, stop condition, target-field result, qualification
   result, and uncertainty for both drafts.
6. `## Candidate Gate Trace` with these nine rows in this order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give every non-target row `PASS` with the literal reason `supplied premise`.
   Give `assumption_source_context` `PASS` with the literal reason `formal
   retirement and documented later operative reuse are both preserved`. Do
   not infer adequacy, acceptance, or failure of any other gate.
7. `## Nearby-Control Comparison` keeping formal retirement, historical
   evidence, later reauthorization, operative reuse, decision-scope limit,
   continued reliance, chronology, stop condition, and overall qualification
   distinct. State whether current wording already requires both retirement
   lineage and evidence of later operative reuse to be preserved.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-FOR-0001` only if current controls require formal retirement
     to defeat explicit source-backed later operative reuse; or
   - `ALREADY HANDLED — FORMAL RETIREMENT DOES NOT OVERRIDE DOCUMENTED LATER OPERATIVE REUSE`
     when current wording already preserves retirement lineage while judging
     whether the assumption was actually reused in the later decision context.
9. `## Candidate Effect` containing exactly `NONE — CURRENT CONTROL ALREADY
   PRESERVES FORMAL RETIREMENT AND DOCUMENTED LATER OPERATIVE REUSE AS DISTINCT
   FACTS` when the verdict is already handled. Do not propose an exception
   policy, retirement rule, remedy, or new acceptance rule.
10. `## Frontier Verification` listing only exact evidence, formal-status,
    status-source, later-record, decision-scope, operative-premise, reuse,
    scope-limit, stop-condition, supplied-premise, qualification, wording, and
    boundary checks needed before integration.

Return only the finished artifact. Emit it as raw Markdown. Do not wrap the
artifact or its YAML frontmatter in a code fence; the first response line must
be `---` and the frontmatter must end with a second `---` before the title.
