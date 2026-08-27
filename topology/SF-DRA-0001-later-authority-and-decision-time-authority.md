---
test_id: SF-DRA-0001
status: decision_time_review_authority_falsifier
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-08-27
source_material: synthetic_fixture_and_repository_controls
external_action: none
---

# SF-DRA-0001 - Later Authority And Decision-Time Authority

## Boundary

This falsifier tests whether `SF-SCHEMA-CANDIDATE-0001` can mark
`accountable_review_owner` passed for a reuse decision when the only named
owner receives relevant authority after that decision is final.

It is synthetic and provisional. It adds no real-world record, accepts no
schema, makes no domain or legal finding, infers no authority exercise or
outcome counterfactual, prescribes no remedy, requests no action, and performs
no external action.

## Falsifier Class

Later authority does not establish decision-time accountability. A current
draft can name a real charter and a capable owner while still misdescribing the
earlier review chain if that authority became operative only after the reuse
decision under review.

This pressure is distinct from a generic organization label, missing review
attendance, an incapable correction route (`SF-CRA-0001`), missing temporal
coexistence of the assumption and changed condition (`SF-TC-0001`), or absent
evidence that a formally authorized owner exercised authority. The exact issue
is whether relevant authority existed during the bounded decision window.

## Synthetic Fixture

The abstract fixture supplies:

- old assumption `A-old` reused under changed condition `C-new` at `T-reuse`;
- final reuse decision `D-final` at `T-final`;
- reviewer `R-comment`, who may attend, receive the contradiction packet, and
  comment before `T-final`, but cannot authoritatively review, stop, escalate,
  approve, reject, or revise the reuse;
- charter revision `C-late`, operative only at `T-late` after `T-final`, which
  gives `O-late` those powers for future reuse decisions; and
- no other accountable owner during the `T-reuse` through `T-final` window.

Draft `D-current` marks the field passed because `O-late` is capable when the
draft is written. Draft `D-window` preserves the later charter but marks the
field failed for the earlier decision. All non-target gates pass only as
synthetic premises.

## Authority Timeline Ledger

| Draft | Named source | Effective time | Relevant authority during reuse decision | Later authority | Target-field result | Qualification result | Uncertainty |
|---|---|---|---|---|---|---|---|
| `D-current` | `C-late` / `O-late` | `T-late`, after `T-final` | Absent | Present for future decisions | Refused | Refused | Synthetic timing premise |
| `D-window` | no decision-time owner; later `C-late` preserved | `T-reuse` through `T-final` | Absent | Present at `T-late` | Fail | Fail | Synthetic timing premise |

Attendance, packet receipt, comment permission, charter existence, charter
effective time, later authority, decision-time authority, authority exercise,
review adequacy, correction-route timing, and overall qualification remain
separate facts. The fixture does not treat later authority as useless or infer
that earlier authority would have changed the outcome.

## Candidate Gate Results

| Candidate gate or field | Result | Constraint preserved |
|---|---|---|
| Safely shareable material | Passes as a synthetic fixture. | No real-world claim is added. |
| `accountable_review_owner` | Refused. No named owner has relevant review, stop, escalation, approval or rejection, or revision authority during the reuse decision window. | Later authority and decision-time authority remain distinct. |
| Other eight core fields | Pass only as supplied fixture premises. | Failure of this field is not copied into independent gate results. |
| Authority exercise | Not inferred. | Capability and exercise remain distinct. |
| Correction route | Preserved only as a non-target premise. | Route timing does not manufacture decision-time review authority. |

## Verdict

`SF-SCHEMA-CANDIDATE-0001` refuses the fixture as positive evidence. Authority
that begins only after `D-final` cannot establish an accountable review owner
for the earlier reuse decision. The later charter remains relevant historical
or future-route evidence, but it cannot be backdated by the artifact-writing
time.

## Candidate Revision Pressure

Keep the nine core fields and provisional status unchanged. Narrow the existing
`accountable_review_owner` language so the named owner must have relevant
authority during the reuse decision window under review. Refuse a later-only
authority as proof for that earlier decision while preserving it as graded
historical, correction-route, or future-decision evidence. Do not require
proof that the owner exercised authority, invent retroactive authority, or add
a new field.

## Non-Promotion Result

This falsifier does not accept the candidate, create a universal ontology, add
a real-world failure record, issue a recommendation or remedy, authorize human
or field research, change CAI phase or public posture, or move another owner's
truth or work.

## Next Test

Keep the candidate provisional. Add another test only when public or synthetic
material creates distinct pressure on a core field, refusal note, annotation,
source gate, or correction-route gate. Record count alone is not progress.
