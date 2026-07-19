---
test_id: SF-ABS-0007
status: negative_absorber_test
candidate: SF-SCHEMA-CANDIDATE-0001
records: [SF-0001, SF-0002, SF-0003, SF-0004, SF-0005]
lane: "1"
created: 2026-07-19
source_material: public_official_sources
external_action: none
---

# SF-ABS-0007 - Resource-Adequacy Rolling-Outage Absorber

## Boundary

This negative absorber uses the California August 2020 rotating-outage source
set to test whether `SF-SCHEMA-CANDIDATE-0001` refuses a real public-source
electric-grid reliability failure when the stronger official-source explanation
is extreme-weather stress, resource-adequacy and planning processes, market
practices, import limits, net-load timing, and operating reserve scarcity rather
than source-backed assumption reuse under changed conditions.

It does not create an accepted topology schema, electric-reliability model,
resource-adequacy standard, market-design recommendation, legal conclusion,
regulatory conclusion, CAI doctrine, intervention plan, or owner routing
instruction.

No confidential material, human subjects, field work, account access, external
contact, posting, spending, publication outside normal GitHub versioning, or
deployment was used.

## Source Set

- California ISO, California Public Utilities Commission, and California Energy
  Commission, "Final Root Cause Analysis: Mid-August 2020 Extreme Heat Wave":
  https://www.caiso.com/Documents/Final-Root-Cause-Analysis-Mid-August-2020-Extreme-Heat-Wave.pdf
- California Public Utilities Commission, "CAISO, CPUC, CEC Issue Final Report
  on Causes of August 2020 Rotating Outages":
  https://www.cpuc.ca.gov/news-and-updates/all-news/caiso-cpuc-cec-issue-final-report-on-causes-of-august-2020-rotating-outages
- California ISO library page, "Analysis of August 2020 outages":
  https://www.caiso.com/library/analysis-of-august-2020-outages

Source posture: public official source material. The repository stores pointers
and synthesis only; it does not copy the source artifacts.

## Absorber Question

The provisional candidate should refuse this case as positive evidence if its
gates are doing real work.

The official root-cause materials center a capacity and resource-adequacy
problem under an extreme West-wide heat event. The source set names interacting
factors including extreme weather, resource adequacy and planning processes,
market practices, imports, operating reserves, and the net-load period when
solar production fell while demand remained high. Those are real public-system
failure facts, but they are not enough for this repository to classify the case
as a review-chain assumption-reuse record under
`SF-SCHEMA-CANDIDATE-0001`.

The case is useful because it creates tempting surface fit: planning assumptions
met an extreme operating condition, public agencies had review and correction
routes, affected-party standing is explicit through forced rotating outages,
and official root-cause analysis produced recommendations. Positive fit still
requires a source-backed reused assumption under changed conditions, visible
validation burden, delegation or review fragmentation material to that
contradiction, absorber control, and an owner-visible correction route. Here,
the narrower resource-adequacy, capacity-planning, market-practice, reserve,
import, and net-load account absorbs the candidate.

## Candidate Gate Results

| Candidate gate or field | Result | Constraint preserved |
|---|---|---|
| Public or safely shareable sources | Passes. The source set is public official CAISO, CPUC, and CEC material. | No source artifacts copied; no confidential, personal, or field data used. |
| Assumption reused under changed condition | Refused as central fit. Planning assumptions and procurement practices faced extreme heat and evening net-load conditions, but the official explanation is narrower: resource adequacy, capacity planning, market practice, imports, and reserve scarcity under extreme weather. | A resource shortage under stress is not automatically a review-chain assumption-reuse case. |
| Validation burden source-backed | Partly passes but is absorbed. Official sources discuss planning, procurement, market, and operational review needs, but those are electric-system resource-adequacy controls rather than an independent review-chain topology claim. | Power-system reliability duties are not flattened into generic validation-burden language. |
| Affected standing explicit | Passes. Rotating outages affected electricity customers, grid operators, load-serving entities, public agencies, and reliability planning. | Affected standing and system severity alone cannot qualify a case. |
| Delegation or review visibility gap | Partly passes but is not central. CAISO, CPUC, CEC, load-serving entities, resource owners, and market participants are visible in the source set, but the positive fit is absorbed by the capacity-planning and market-practice account. | Multi-actor public infrastructure governance is not enough to create positive evidence. |
| Absorber or counterevidence present | Passes. The resource-adequacy, capacity-tradeoff, market-practice, operating-reserve, import-limit, and net-load-timing account absorbs the review-chain candidate for this case. | The absorber is recorded without becoming a universal electric-grid or reliability-failure topology. |
| Correction route stop condition | Partly passes but does not rescue candidate fit. Official routes include resource-adequacy reform, procurement, market-rule, reliability-planning, import, and operating-practice changes. | This repository records owner-visible routes without prescribing electric-reliability, market, regulatory, planning, legal, or domain action. |

## Verdict

`SF-SCHEMA-CANDIDATE-0001` refuses this case as positive evidence. That refusal
is useful after the slow-degradation infrastructure-capacity absorber because
it shows that a public, multi-actor infrastructure failure with review,
planning, affected-party, and correction-route visibility does not qualify when
the strongest official-source explanation is resource adequacy, capacity
tradeoff, market practice, reserve scarcity, and net-load timing rather than
the candidate's source-backed review-chain residue.

The candidate remains provisional and local to review-chain failures involving
source-backed assumption reuse under changed conditions, visible validation
burden, affected standing, absorber control, and correction-route discipline.
This negative absorber does not justify schema acceptance.

## Candidate Revision Pressure

Keep the candidate field set as-is, but add one refusal note to the candidate:
when public official sources center resource adequacy, capacity planning,
market practice, operating reserve scarcity, import limits, load forecast,
resource procurement, or similar capacity-tradeoff controls rather than
source-backed assumption reuse under changed conditions, the case should be
recorded as an absorber or separate topology question, not positive evidence
for this candidate.

This note must remain source-gated. It does not authorize this repository to
make electric-reliability, power-market, resource-procurement, operating-
reserve, load-forecasting, planning, legal, regulatory, enforcement, or
domain-remedy conclusions.

## Non-Promotion Result

This absorber test does not:

- accept `SF-SCHEMA-CANDIDATE-0001` as schema;
- create a universal systemic-failure ontology;
- issue an electric-reliability, power-market, resource-procurement,
  operating-reserve, load-forecasting, planning, legal, regulatory, compliance,
  enforcement, public-safety, or domain-remedy recommendation;
- authorize human research, field research, participation, contact, posting,
  publication outside GitHub, deployment, spending, account access, or external
  action;
- change CAI phase, relationship, membership, automation, or proving authority;
  or
- move another repository's claims, canon, or work state.

## Next Test

The candidate remains provisional. The next useful falsifier should come from
a different remaining class: a newly formed assumption rather than reused
assumption, a borderline mixed case, or a false-negative pressure case where a
plausible review-chain failure is not well represented by the current fields.
