# Test the West Fertilizer and Imperial Sugar emergency/community boundary

Lineage ID: `SF-LIN-COMP-WEST-FERTILIZER-IMPERIAL-SUGAR-EMERGENCY-COMMUNITY-01`,
opportunity 1. Prepare one proposal-only comparison decision. Use only the
supplied owner facts. Do not retrieve sources. Do not invent complete warning
or evacuation custody, shared authority, one root cause, recurrence, shared
mechanism, blame, legal duty, remedy efficacy, schema fit, receiver action, or
external effect.

Supplied West Fertilizer owner facts from `SF-0013`:

- A fire preceded fertilizer-grade ammonium-nitrate detonation; the exact fire
  cause remains unknown.
- Combustible storage-bin and building materials and absent automatic
  sprinklers plausibly contributed to detonation.
- The volunteer fire department had not conducted an FGAN-specific
  pre-inspection, drill, or response training at the facility.
- The blast killed responders and members of the public and damaged nearby
  residences, schools, apartments, and a nursing home.

Supplied Imperial Sugar owner facts from `SF-0010`:

- The initial explosion occurred in an enclosed steel conveyor, and secondary
  dust explosions and fires propagated through occupied refinery buildings.
- Accumulated combustible dust fueled propagation; an overheated bearing was
  the most likely, but not certain, ignition source.
- Evacuation plans, drills, and prompt notification were inadequate, while
  explosions damaged lighting and fire-protection systems.
- Fourteen workers died and dozens were injured; complete warning receipt,
  escape decisions, and every protection alternative remain unknown.

Return exactly ten short lines:

- **Unit:** exactly `West Fertilizer and Imperial Sugar emergency/community comparison`.
- **West event boundary:** name only fire, ammonium-nitrate detonation, and offsite blast consequence.
- **West protection boundary:** name only FGAN pre-incident planning, training, sprinklers, and community proximity.
- **Imperial Sugar event boundary:** name only combustible-dust release, primary explosion, and secondary propagation.
- **Imperial Sugar protection boundary:** name only evacuation planning, drills, notification, lighting, and fire protection.
- **Standing boundary:** exactly `West includes responders and nearby community members while Imperial Sugar centers workers in an occupied refinery`.
- **Decision:** choose exactly `preserve_separate_emergency_community_boundaries` or `open_shared_emergency_community_candidate`.
- **Decision basis:** state whether both records establish the same hazard, warning custody, accountable authority, disposition, stop condition, and protection effect.
- **Unknowns:** exactly `complete warning custody, accountable authority, disposition, stop conditions, relative causal weight, recurrence, schema fit, and remedy efficacy remain unknown`.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, remedy, receiver work, or external action is accepted.`

Use `preserve_separate_emergency_community_boundaries` unless both records
independently support the same complete hazard-to-warning-and-protection chain.
This is a Frontier comparison decision, not owner research truth. Plain
Markdown, no table or frontmatter, under 360 words.
