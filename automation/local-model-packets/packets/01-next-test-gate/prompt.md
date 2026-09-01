# Open a bounded West Fertilizer public-source record

Lineage ID: `SF-LIN-WEST-FERTILIZER-CASE-OPENING-01`, opportunity 1.
Prepare one proposal-only case-opening decision from the supplied CSB facts.
Do not retrieve sources. Do not invent fire origin, individual knowledge,
complete hazard-information custody, complete inspection history, one root
cause, blame, legal duty, remedy efficacy, recurrence, schema fit, receiver
action, or external effect.

Supplied official-source facts from the U.S. Chemical Safety Board final report
on the April 17, 2013 West Fertilizer Company fire and explosion:

- A fire preceded detonation of fertilizer-grade ammonium nitrate stored at the
  fertilizer blending, retail, and distribution facility in West, Texas.
- The explosion killed 12 emergency responders and three members of the public,
  injured more than 260 people, destroyed the facility, and damaged more than
  150 offsite buildings, including residences, schools, apartments, and a
  nursing home.
- Combustible storage-bin and building materials and the lack of automatic
  sprinklers plausibly contributed to the detonation; the exact fire cause was
  not determined.
- Federal regulatory coverage did not treat the ammonium-nitrate storage hazard
  through one complete process-safety regime, while state and local land-use
  controls allowed dense community development near the facility.
- The volunteer fire department was not required to perform pre-incident
  planning for an ammonium-nitrate emergency, and volunteer firefighters were
  not required to receive hazardous-chemical fire training.
- An earlier insurer had dropped the facility after safety concerns were not
  addressed; the insurer at the time of the event did not appear to have
  conducted its own facility safety inspection. Complete custody, receipt,
  disposition, and implementation of insurer information remain unknown.

Return exactly twelve short lines:

- **Unit:** exactly `West Fertilizer public-source case opening`.
- **Event boundary:** name only fire, ammonium-nitrate detonation, and offsite blast consequence.
- **Storage boundary:** name only combustible construction, storage configuration, and absent automatic sprinklers.
- **Emergency boundary:** name only pre-incident planning, hazardous-chemical fire training, and volunteer response.
- **Community boundary:** name only facility proximity to residences, schools, apartments, and a nursing home.
- **Regulatory boundary:** name only federal coverage, state and local land use, and inspection layers.
- **Insurance boundary:** name only earlier loss-control concerns and the later insurer's absent apparent inspection.
- **Source limit:** exactly `the exact fire cause and complete custody, authority, disposition, implementation, and relative causal weight remain unknown`.
- **Decision:** choose exactly `open_bounded_west_fertilizer_record` or `decline_case_opening`.
- **Decision basis:** state whether the supplied facts support distinct event, storage, emergency, community, regulatory, and insurance layers without one root-cause claim.
- **Falsifier:** state what missing or contradictory official-source fact would prevent a bounded record.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, remedy, receiver work, or external action is accepted.`

Use `open_bounded_west_fertilizer_record` only if every layer stays separate
and all named unknowns remain explicit. This is a Frontier case-opening
decision, not owner research truth. Plain Markdown, no table or frontmatter,
under 380 words.
