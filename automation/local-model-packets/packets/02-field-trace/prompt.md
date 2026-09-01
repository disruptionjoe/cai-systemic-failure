# Test the Arkema and Texas 2021 common-mode resource boundary

Lineage ID: `SF-LIN-COMP-ARKEMA-TX2021-COMMON-MODE-RESOURCE-01`, opportunity 1.
Prepare one proposal-only comparison decision. Use only the supplied owner
facts. Do not retrieve sources. Do not invent complete risk-information
custody, shared authority, one root cause, recurrence, shared mechanism,
blame, legal duty, remedy efficacy, schema fit, receiver action, or external
effect.

Supplied Arkema owner facts from `SF-0011`:

- Hurricane Harvey flooding exceeded equipment design elevations and caused
  loss of facility power, backup power, and critical refrigeration.
- Refrigeration, emergency generators, liquid nitrogen, and refrigerated
  trailers were distinct safeguards, but floodwater compromised them as a
  common mode of failure.
- FEMA mapping and an insurer report identified flood exposure while the
  process-hazard analysis documented no flooding risk; complete custody,
  accountable receipt, disposition, and implementation remain unknown.

Supplied Texas 2021 owner facts from `SF-0006`:

- Severe cold produced generation outages, derates, and failures to start;
  freezing and fuel issues together accounted for most unplanned losses.
- Power losses at some gas infrastructure and gas-supply loss to generators
  make cross-system interdependence visible without proving one loop explains
  every outage.
- Earlier cold-weather inquiries preserve recurrent official attention, but
  individual knowledge, complete authority, decision chronology, and closure
  remain unknown.

Return exactly ten short lines:

- **Unit:** exactly `Arkema and Texas 2021 common-mode resource comparison`.
- **Arkema stress boundary:** name only flood exposure and exceeded equipment design elevations.
- **Arkema resource boundary:** name only power, backup power, refrigeration, liquid nitrogen, and refrigerated trailers.
- **Texas stress boundary:** name only severe cold, equipment freezing, and fuel constraints.
- **Texas resource boundary:** name only generation availability, gas supply, electric supply to gas infrastructure, and load shedding.
- **Scale boundary:** exactly `Arkema is a facility safeguard system while Texas is a regional interdependent electric and gas system`.
- **Decision:** choose exactly `preserve_separate_common_mode_resource_boundaries` or `open_shared_common_mode_resource_candidate`.
- **Decision basis:** state whether both records establish the same stress knowledge, resource dependency, accountable authority, disposition, stop condition, and control effect.
- **Unknowns:** exactly `complete custody, accountable authority, disposition, stop conditions, relative causal weight, recurrence, schema fit, and remedy efficacy remain unknown`.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, remedy, receiver work, or external action is accepted.`

Use `preserve_separate_common_mode_resource_boundaries` unless both records
independently support the same complete stress-to-resource-and-control chain.
This is a Frontier comparison decision, not owner research truth. Plain
Markdown, no table or frontmatter, under 340 words.
