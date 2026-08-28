# Draft a validation-object scope pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `validation_burden` field states what adequate revalidation would need to
address and what source-backed evidence shows as unmet, disputed, fragmented,
or unresolved. Refuse a burden inferred only from hindsight.
</evidence>

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#record-qualification-gate">
Required fields must be traceable to admitted source material or an explicit
synthetic fixture. Preserve uncertainty and refuse positive qualification
when a required field lacks that basis.
</evidence>

<synthetic_fixture id="VOS-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Old assumption `A-old` is reused under changed condition `C-load` for bounded
  affected system `S-primary` before final decision `D-final`.
- Source-backed burden `B-primary` requires load-response validation of
  `S-primary` under `C-load` before `D-final`.
- Validation `V-proxy` completes before `D-final` on different system
  `S-proxy` under `C-load` and returns `PASS` under its admitted proxy criterion.
- The packet supplies no source-backed equivalence, representativeness,
  transfer, or other bridge from `S-proxy` to `S-primary`. Do not infer that
  `S-proxy` is invalid or that its result has no evidentiary value.
- Draft `D-substitute` marks `validation_burden` `PASS` because `V-proxy`
  completed and passed. Draft `D-scoped` preserves the proxy result but marks
  the target field `UNRESOLVED` for `S-primary`.
- Do not invent a bridge, test method, acceptance rule, threshold, outcome,
  safety or adequacy inference, or remedy.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-VOS-0001-validation-object-scope.md` with exactly:

1. YAML frontmatter: `test_id: SF-VOS-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_scope_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF VOS 0001 - Validation Object Scope`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-proxy-invalidity inference, no-bridge invention, no-test-method or
   acceptance-rule invention, no-safety or adequacy inference, no-causal or
   outcome inference, and no-action status.
4. `## Synthetic Fixture` separating every named object and preserving both
   the admitted `V-proxy` result and the absent bridge to `S-primary`.
5. `## Validation Scope Ledger` using exactly these two keyed records and keys
   in this order. Copy every supplied value literally; edit only `draft_claim`
   and `verified_result`:

   `draft: D-substitute | assumption: A-old | affected_system: S-primary | condition: C-load | burden: B-primary | validation: V-proxy | tested_system: S-proxy | validation_result: PASS | timing: before D-final | bridge_to_affected_system: NONE | draft_claim: PASS | verified_result: UNRESOLVED | qualification: REFUSE | uncertainty: transfer basis absent`

   `draft: D-scoped | assumption: A-old | affected_system: S-primary | condition: C-load | burden: B-primary | validation: V-proxy | tested_system: S-proxy | validation_result: PASS | timing: before D-final | bridge_to_affected_system: NONE | draft_claim: UNRESOLVED | verified_result: UNRESOLVED | qualification: REFUSE | uncertainty: transfer basis absent`
6. `## Candidate Gate Trace` with the nine candidate fields in current order.
   Give every non-target field `PASS — supplied premise`; give
   `validation_burden` `UNRESOLVED — V-proxy passed on S-proxy but no admitted
   bridge connects that result to B-primary for S-primary`. Infer no other
   failed gate.
7. `## Nearby-Control Comparison` keeping affected-system identity, tested-
   system identity, validation completion, proxy result, bridge evidence,
   burden satisfaction, qualification, uncertainty, outcome, and remedy
   distinct. State whether current source-backed-burden wording already
   refuses unbridged substitution of `S-proxy` for `S-primary`.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-VOS-0001 — A PASSING PROXY TEST SATISFIES THE AFFECTED-SYSTEM VALIDATION BURDEN WITHOUT A BRIDGE`; or
   - `ALREADY HANDLED — A PASSING PROXY TEST DOES NOT SATISFY AN AFFECTED-SYSTEM BURDEN WITHOUT AN ADMITTED BRIDGE`.
9. `## Candidate Effect`: exactly `PROPOSE CLARIFYING validation_burden TO
   REQUIRE A SOURCE-BACKED VALIDATION-OBJECT BRIDGE` for `PROPOSE`, or exactly
   `NONE — CURRENT SOURCE-BACKED BURDEN CONTROLS ALREADY REFUSE UNBRIDGED PROXY
   SUBSTITUTION` for already handled. Propose no bridge, validation method,
   remedy, acceptance rule, annotation, or new field.
10. `## Frontier Verification` listing only exact evidence, identifiers,
    affected and tested systems, proxy result and timing, bridge absence,
    supplied premises, qualification, wording, and boundary checks.

Return only the finished artifact. Emit raw Markdown without a code fence; the
first line must be `---` and frontmatter must close before the title. Use one
concise row or bullet per required item, do not repeat evidence, and keep the
finished artifact under 1,100 words.
