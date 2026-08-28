# Draft a validation-burden revision-alignment pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `validation_burden` field states what adequate revalidation would need to
address and what admitted evidence shows as unmet, disputed, fragmented, or
unresolved. Refuse a burden inferred only from hindsight.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#qualification-gate">
The admitted source packet preserves known material revision, replacement, and
contradiction evidence. A superseded revision may remain historical evidence;
preserving it does not silently make it operative for every later decision.
</evidence>

<synthetic_fixture id="VRA-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Old assumption `A-old` is reused for bounded system `S-bounded` after changed
  condition `C-load` and before final decision `D-final`.
- Burden revision `B-v1` initially requires validation of `C-load`, interface
  condition `C-interface`, and interaction `X-joint`.
- Before `D-final`, admitted revision `B-v2` explicitly supersedes `B-v1` for
  this decision and narrows the operative burden to `C-load`. It states that
  `C-interface` and `X-joint` are outside this decision's bounded system and
  preserves `B-v1` as historical evidence.
- Validation `V-load` addresses the complete stated scope of `B-v2`, completes,
  and passes before `D-final`. No evidence disputes `V-load` or leaves a named
  `B-v2` component unresolved.
- Draft `D-cumulative` marks `validation_burden` `FAIL` solely because `V-load`
  does not address the superseded `B-v1` components. Draft `D-operative`
  preserves the same facts and marks the field `PASS` against `B-v2`.
- Do not infer that `B-v2` is substantively adequate beyond the supplied
  fixture, that `B-v1` was erroneous, that any outcome occurred, or that a
  remedy is required. This tests revision alignment, not domain adequacy.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-VRA-0001-validation-burden-revision-alignment.md` with exactly:

1. YAML frontmatter: `test_id: SF-VRA-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_revision_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF VRA 0001 - Validation Burden Revision Alignment`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-revision-adequacy inference, no-old-revision-error inference,
   no-causal or outcome inference, and no-action status.
4. `## Synthetic Fixture` separating `A-old`, `S-bounded`, `C-load`,
   `C-interface`, `X-joint`, `B-v1`, `B-v2`, `V-load`, `D-final`,
   `D-cumulative`, and `D-operative`. Preserve `B-v1`; do not silently treat
   its superseded scope as operative or erase it.
5. `## Burden Revision Ledger` with exactly two rows, one per draft, and
   columns for draft, assumption, system, initial burden revision, operative
   burden revision, supersession timing, preserved historical scope,
   operative scope, completed validation, completed-validation scope,
   unresolved operative component, draft-claimed target result, verified
   target result, qualification result, and uncertainty. Use identical facts
   in both rows and vary only the draft interpretation. The verified target
   result is `PASS` for both rows; do not turn that supplied field result into
   schema acceptance.
6. `## Candidate Gate Trace` with these nine rows in order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each non-target row `PASS` / `supplied premise`; give
   `validation_burden` `PASS` / `B-v2 supersedes B-v1 before D-final and
   V-load covers every named B-v2 component`. Infer no failed gate.
7. `## Nearby-Control Comparison` keeping revision preservation,
   supersession, operative scope, historical scope, validation completion,
   scope coverage, domain adequacy, qualification, uncertainty, causation,
   and remedy distinct. State whether current wording clearly prevents a
   preserved but superseded burden from accumulating into the operative one.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-VRA-0001 — PRESERVING A SUPERSEDED BURDEN SILENTLY MAKES ITS SCOPE CUMULATIVE`
     only if current wording would require the retired `B-v1` components; or
   - `ALREADY HANDLED — VALIDATION TRACKS THE ADMITTED OPERATIVE BURDEN WHILE SUPERSEDED SCOPE REMAINS HISTORICAL`
     when current controls already preserve that distinction.
9. `## Candidate Effect`: exactly `PROPOSE CLARIFYING validation_burden TO
   DISTINGUISH OPERATIVE AND SUPERSEDED BURDEN SCOPE` for `PROPOSE`, or exactly
   `NONE — CURRENT CONTROLS ALREADY PRESERVE REVISION LINEAGE WITHOUT MAKING
   SUPERSEDED BURDEN SCOPE OPERATIVE` for already handled. Propose no test
   design, remedy, acceptance rule, annotation, or new field.
10. `## Frontier Verification` listing only exact evidence, identifiers,
    revision order, supersession timing, historical and operative scope,
    completed-validation scope, unresolved operative components, supplied
    premises, qualification, wording, and boundary checks.

Return only the finished artifact. Emit raw Markdown without a code fence; the
first line must be `---` and frontmatter must end with a second `---` before
the title. Use one concise row or bullet per required item, do not repeat
evidence, and keep the finished artifact under 1,300 words.
