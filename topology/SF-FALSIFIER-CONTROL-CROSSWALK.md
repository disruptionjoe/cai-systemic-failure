---
artifact_id: SF-FALSIFIER-CONTROL-CROSSWALK
status: provisional_control_crosswalk
candidate: SF-SCHEMA-CANDIDATE-0001
controls: [SF-CEQ-0001, SF-SRL-0001, SF-CRA-0001, SF-CEC-0001, SF-IPC-0001]
lane: "1"
created: 2026-08-25
source_material: repository_falsifier_records
external_action: none
---

# Five-Falsifier Control Crosswalk

## Boundary

This crosswalk makes five existing falsifiers easier to apply together without
collapsing them into one generic source-quality test. It derives no new
evidence, field, hierarchy, acceptance threshold, remedy, domain conclusion,
or external action. The underlying falsifier records remain controlling.

## Crosswalk

| Falsifier | False appearance | Exact refusal trigger | Existing control narrowed | What may still be preserved | Nearest confusable falsifier and nearby decision | Non-collapse rule |
|---|---|---|---|---|---|---|
| `SF-CEQ-0001` | Traceable positive-fit fields make a record look counterevidence-aware. | The only alternative or countermodel is generic, untraceable, and ungraded. | `absorber_or_counterevidence` must expose the alternative's source context or synthetic basis, claim posture, and effect on the candidate residue. | A weak alternative may remain a graded lead or uncertainty. | `SF-IPC-0001` decides whether a direct material conflict already inside the admitted packet was preserved and graded; CEQ decides whether the alternative itself is traceable and graded. | Counterevidence need not match the positive case in volume or certainty, but generic skepticism cannot pass the gate. |
| `SF-SRL-0001` | A named earlier source revision makes the record look lineage-complete. | The record knowingly omits a later admitted revision that materially withdraws, narrows, or contradicts the support carrying qualification. | Source controls must preserve and disposition known material successor revisions. | The earlier revision may remain historical evidence; editorial, unrelated, or immaterial later changes do not defeat it. | `SF-IPC-0001` decides whether a conflict already visible in the admitted packet was left undispositioned; SRL decides whether a known material successor revision was omitted from lineage. | A newer revision is not automatically controlling, but a known material lineage conflict cannot be hidden. |
| `SF-CRA-0001` | Naming a visible correction route makes the route look capable. | The admitted packet shows that the route cannot receive, review, escalate, stop, revise, or expose the relevant claim through an accountable path. | `correction_route_stop_condition` must test relevant capability, not route visibility alone. | A capable route may remain contested, delayed, imperfect, or uncertain with an explicit grade. | `SF-CEC-0001` decides whether evidence fragments belong to one bounded system and review chain; CRA decides whether the named route can carry the correction to accountable review. | Capability is required; success is not guaranteed and no remedy is prescribed. |
| `SF-CEC-0001` | Individually traceable fragments make an assembled record look coherent. | No admitted bridge connects the qualifying assumption, changed condition, affected standing, and review path to one bounded system. | Existing source-context and affected-system controls must state the record-level evidence bridge. | Multiple sources and a contested or incomplete bridge may be preserved with an explicit grade. | `SF-SRL-0001` decides whether a known material successor revision was omitted; CEC decides whether separately traceable fragments form one bounded record at all. | Field-level citations cannot manufacture record-level coherence. |
| `SF-IPC-0001` | A named source and revision make a required field look passed. | The admitted packet directly and materially contradicts support for that field, while the record neither preserves nor grades the conflict. | `assumption_source_context` and `absorber_or_counterevidence` must disposition direct material contradictions already present in the packet. | Contested, narrowed, contradicted, or unresolved support may remain usable when explicit. | `SF-CEQ-0001` decides whether an alternative or countermodel is traceable and graded; IPC decides whether a direct internal conflict was silently selected away. | The repository need not require unanimity or settle every tension, but it cannot label a materially conflicted field passed without a grade. |

## Combined use

More than one falsifier may apply to one record. Each retains its own decision
object: CEQ grades alternatives, SRL preserves material revision lineage, CRA
tests correction-route capability, CEC tests record-level coherence, and IPC
requires disposition of direct internal contradiction. Triggering one control
does not merge, satisfy, or invalidate the others.

## Provisional boundary

This is a local comparison surface for `SF-SCHEMA-CANDIDATE-0001`, not an
accepted schema or universal ontology. The nine core fields remain unchanged.
All uncertainty stays graded, and no real-world finding, remedy, external
action, or Joe action follows from this crosswalk.
