---
test_id: SF-SCHEMA-READINESS-0001
status: provisional_schema_readiness_check
records: [SF-0001, SF-0002, SF-0003]
lane: "1"
created: 2026-07-18
external_action: none
---

# SF Schema Readiness 0001 - Review-Chain Fields

## Boundary

This check uses only `SF-0001`, `SF-0002`, `SF-0003`, and the existing
topology tests. It decides whether a source-gated review-chain schema can be
drafted next. It does not accept a topology schema, universal accident model,
domain remedy, public-health recommendation, engineering recommendation,
civil-rights judgment, legal claim, intervention, or CAI doctrine.

## Readiness Verdict

The provisional field set is ready for a constrained schema candidate, not for
accepted schema. The candidate must be source-gated: a record qualifies only
when public, licensed, safely shareable, or synthetic source material identifies
an old assumption reused under a changed condition and a visible correction
route for unresolved contradiction.

The field list should be shorter than the accumulated notes. The useful unit is
not "systemic failure" in general. It is a review-chain failure pattern:
source-backed assumption reuse under changed conditions, where affected-party
standing, validation burden, owner visibility, and correction route must remain
explicit before old assumptions are treated as adequate.

## Necessary Fields

| Field | Readiness | Source requirement |
|---|---|---|
| assumption and source context | necessary | Name the assumption being reused and the source material or revision that supports the synthesis. |
| accountable review owner | necessary | Distinguish the owner of the assumption from the owner who can review or stop its reuse. |
| affected system and affected-party standing | necessary | Name who or what carries risk, including people when the source record makes them central. |
| changed condition | necessary | Identify the changed function, observed anomaly, source switch, evidence context, or other condition that changes the validation burden. |
| validation method and burden | necessary | State what would count as adequate revalidation under the changed condition and what evidence shows the burden was unmet or disputed. |
| operating or observation environment | necessary but narrow | Preserve how evidence was visible or invisible without importing domain-specific engineering or health conclusions. |
| delegation path and visibility gap | necessary | Show how distributed review, authority, or request paths fragmented the contradiction. |
| counterevidence or absorber model | necessary as a control | Record the strongest narrower explanation and whether it absorbs the review-chain residue. |
| correction route and stop condition | necessary | Name the owner-visible route that could correct, escalate, stop, or revise the assumption without this repository prescribing the remedy. |

## Candidate Pressures

These pressures should not become mandatory schema fields yet:

- `hazard_history`: useful when prior tolerated anomalies or infrastructure
  conditions made later evidence appear normal, but it is not required across
  all three records.
- `observation_request_path`: useful as a source gate when requests,
  complaints, measurements, or external evidence failed to become accountable
  contradiction. It should be represented inside `operating or observation
  environment` or `delegation path` unless a later record forces separation.
- `jurisdictional_authority_gap`: useful as an authority-boundary warning,
  especially in `SF-0003`, but it is not yet a general field. Keep it as an
  annotation or absorber test until another non-aerospace record forces it.

## Demotions

Do not carry these into the first schema candidate:

- domain-specific remedy class as a topology field;
- production, organizational, political, legal, or civil-rights motive as a
  required field without source-specific support;
- broad "complex systems fail" language;
- any field that lets a record qualify without a source-backed assumption,
  changed condition, validation burden, and correction route.

## Acceptance Gate

A schema file may be drafted next only if it:

1. marks itself `candidate` or `provisional`, not accepted;
2. refuses records that lack public, licensed, safely shareable, or synthetic
   source support;
3. preserves a correction route for each field and dependent record;
4. includes an absorber/counterevidence column instead of treating every case as
   positive evidence;
5. states that domain remedies and affected-owner decisions remain outside this
   repository; and
6. names at least one next falsifier: a fourth source-backed record or negative
   absorber where assumption reuse is not central.

Until those conditions are met, the topology remains provisional.
