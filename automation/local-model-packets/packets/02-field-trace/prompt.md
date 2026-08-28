# Test validation timing against validation scope

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, prescribe a remedy,
accept the provisional schema, create follow-on work, or request Joe action.
This is candidate material for Frontier verification, not owner truth.

Family lineage: `SF-LIN-VALIDATION-TIMING-01`.

## Evidence

<synthetic_fixture id="VBT-SCOPE-01">
- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- Validation burden `VB-new` exists at `T0` and specifically requires checking
  whether reused assumption `A-old` remains adequate under `C-new`.
- `D-old-scope` cites `V-old`, completed and owner-visible at `T-1`, but its
  admitted scope covers only condition `C-old`, not `C-new` or `VB-new`.
- `D-covered` cites `V-covered`, completed and owner-visible at `T-1`, whose
  admitted synthetic scope explicitly covers `A-old`, `C-new`, and `VB-new`.
- `D-late` cites `V-late`, whose admitted synthetic scope covers `A-old`,
  `C-new`, and `VB-new`, but it completes at `T1` after `T-reuse` is final.
- Every non-target core gate is supplied as `PASS`. The fixture does not prove
  real-world adequacy, authority exercise, duty, cause, remedy, or outcome.
</synthetic_fixture>

## Work now

Draft `SF-VBT-SCOPE-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-VBT-SCOPE-0001`, `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_validation_scope_timing_proposal`,
   `source_material: synthetic`, and `external_action: none`.
2. `# SF VBT Scope 0001 - Timing And Coverage`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-new-record, no-authority-exercise
   inference, no-duty inference, no-causal inference, no-outcome inference,
   and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Validation Ledger` copying these three records literally:

   `draft: D-old-scope | event: V-old | completed: T-1 | owner_visible: T-1 | admitted_scope: C-old only | covers_VB-new: NO | timing_result: PASS | scope_result: FAIL | qualification_result: FAIL`

   `draft: D-covered | event: V-covered | completed: T-1 | owner_visible: T-1 | admitted_scope: A-old plus C-new plus VB-new | covers_VB-new: YES | timing_result: PASS | scope_result: PASS | qualification_result: CONTINUE GATE CHECKS`

   `draft: D-late | event: V-late | completed: T1 | owner_visible: T1 | admitted_scope: A-old plus C-new plus VB-new | covers_VB-new: YES | timing_result: FAIL | scope_result: PASS | qualification_result: FAIL`
6. `## Distinction` stating that event existence, scope coverage, completion
   time, owner-visibility time, decision time, synthetic gate result,
   real-world adequacy, authority exercise, duty, outcome, and remedy remain
   separate. Do not call `D-old-scope` a timing failure or `D-late` a scope
   failure.
7. `## Candidate Gate Trace` with exactly the nine current core gate names.
   Copy every non-target gate as `PASS — supplied premise`. For
   `validation_burden`, record the three draft results without inferring any
   other failed gate. End with literal `Infer no other failed gate.`
8. `## Verdict` with exactly `ALREADY HANDLED — VALIDATION MUST BOTH COVER THE
   CHANGED-CONDITION BURDEN AND BE COMPLETED AND OWNER-VISIBLE IN THE RELEVANT
   DECISION WINDOW`.
9. `## Candidate Effect` with exactly `NONE — CURRENT validation_burden
   WORDING PRESERVES SCOPE, COMPLETION, VISIBILITY, AND DECISION TIME WITHOUT
   BACKDATING`.
10. `## Frontier Verification` with exactly five bullets: fixture facts; three
    ledger records; nine gate results; verdict/effect coherence; raw
    frontmatter and boundaries.

Return only the finished artifact. Emit raw Markdown, not a code fence. The first line and the line after
`external_action: none` must both be `---`. Stay under 900 words.
