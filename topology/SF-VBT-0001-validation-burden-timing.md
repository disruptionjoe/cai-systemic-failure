---
test_id: SF-VBT-0001
status: validation_burden_timing_falsifier
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-28
source_material: synthetic_fixture_and_repository_controls
external_action: none
---

# SF-VBT-0001 - Validation-Burden Timing

## Boundary

This synthetic falsifier tests whether validation completed only after a reuse
decision can be backdated to satisfy the validation burden for that decision.
It adds no record, accepts no schema, infers no real-world adequacy, authority
exercise, duty, cause, outcome, or remedy, requests no action, and performs no
external action.

## Falsifier Class

A changed condition can create a validation burden at the reuse decision while
the only completed validation occurs after that decision is final. Later
validation may remain relevant historical or follow-on evidence, but its later
completion does not establish that the burden was satisfied during the
decision window. This is distinct from whether the old assumption remained
operative (`SF-TC-0001`), who held authority (`SF-DRA-0001`), when evidence was
handled (`SF-ORC-0001`), and whether unresolved contradiction had a backed stop
condition (`SF-CSC-0001`).

## Synthetic Fixture

- Every non-target core gate passes only as a supplied premise.
- Reuse decision `T-reuse` occurred at `T0` under changed condition `C-new`.
- Validation burden `VB-new` existed at `T0` because `C-new` required
  revalidation before the reuse decision could count as adequately validated.
- Draft `D-backdated` supplies no completed validation, dispute resolution, or
  owner-visible validation result before `T0`. Validation event `V-late`
  completes at `T1`, after the decision is final, and the draft backdates it.
- Draft `D-timely` supplies validation event `V-pre`, completed and made
  owner-visible at `T-1`, with admitted synthetic scope covering `VB-new`
  before `T0`.
- The fixture does not establish that either event is real or adequate outside
  its supplied scope, exercised authority, created a duty, selected a remedy,
  caused an outcome, or proves what would have happened otherwise.

## Validation Timing Ledger

| Draft | Decision | Burden | Validation | Owner-visible before decision | Backdated | Gate result | Preserved uncertainty |
|---|---|---|---|---|---|---|---|
| `D-backdated` | `T-reuse` at `T0` | `VB-new` created by `C-new` at `T0` | `V-late` completed at `T1` | No | Yes | Fail | Later validation does not establish decision-time satisfaction. |
| `D-timely` | `T-reuse` at `T0` | `VB-new` created by `C-new` at `T0` | `V-pre` completed at `T-1` | Yes | No | May continue | Synthetic scope coverage does not prove real-world adequacy or outcome. |

## Candidate Gate Results

`D-backdated` fails `validation_burden`: post-decision validation at `T1`
cannot be substituted for satisfaction during the `T0` decision window.
`D-timely` may continue through the remaining gates because the supplied
synthetic event covers the burden and is owner-visible before the decision.
All eight non-target gates remain supplied premises; no other gate result is
inferred.

## Candidate Revision Pressure

Keep the nine core fields and provisional status unchanged. Narrow the existing
`validation_burden` wording so the record preserves whether the burden was
unmet, disputed, fragmented, unresolved, or not owner-visible enough during
the relevant reuse decision window. Later validation remains graded historical
or follow-on evidence and is not backdated.

## Non-Promotion Result

This falsifier does not accept the candidate, create a universal ontology, add
a real-world record, authorize research or participation, prescribe validation
or a remedy, infer duty or outcome, change public posture, or move another
owner's truth or work.
