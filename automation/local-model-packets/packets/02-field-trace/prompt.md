# Contrast PES RAD and water-spray availability

Lineage ID: `SF-LIN-PES-RAD-WATER-SAFEGUARD-CONTRAST-01`, opportunity 1.
Prepare one proposal-only same-incident active-safeguard contrast from the
supplied official CSB PES report facts. Frontier review decides owner truth.
Do not retrieve sources or invent unsupported facts. Do not infer recurrence,
one root cause, shared authority, blame, duty, remedy efficacy, health
causation, or external effect.

Official source: CSB, *Philadelphia Energy Solutions (PES) Refinery Fire and
Explosions*, final report, October 11, 2022, especially pages 6-8 and 51-68:
https://www.csb.gov/assets/1/20/PES_Final_Report_Published_October_2022_r1.pdf

Supplied official-source facts:

- After ignition, workers activated the rapid acid deinventory system and
  routed about 339,000 pounds of HF from the compromised unit to a separate
  drum; the report says RAD functioned as intended.
- The water-spray system had a different purpose: reduce airborne HF through
  vapor suppression. Control communication to its pumps failed at ignition
  and unit backup power failed nine seconds later.
- At about 4:12 a.m. the remote water-pump start did not work. At about
  4:39 a.m. a supervisor wearing firefighting protective gear manually started
  the pump supplying the elevated water cannons.
- The report treats both RAD and water spray as active safeguards but lists
  different activation, release-rate, availability, maintenance, response-
  time, and mitigation limitations.
- Actual RAD activation does not prove complete counterfactual protection.
  Failed remote water-spray control does not prove the pumps were physically
  unavailable or that later manual activation had no effect.
- Complete alarm custody, component condition, activation authority, field-
  access exposure, remaining inventory, comparative denominators, and
  counterfactual protection effect remain unknown.

Return exactly one Markdown table with seven ordered rows and columns
`Safeguard object | RAD | Water spray | Contrast boundary | Missing link`:
`purpose`, `activation trigger`, `dependency path`, `ignition-time state`,
`observed operation`, `timing`, `protection effect`.

Then return exactly four lines outside the table:

- **Decision:** choose `open_bounded_same_incident_active_safeguard_contrast`
  or `preserve_separate_controls_only`.
- **Falsifier:** name one exact official-source fact that would defeat the
  selected decision.
- **Unknowns:** `complete condition, alarm custody, activation authority,
  field-access exposure, remaining inventory, comparable denominators, and
  counterfactual protection effect remain unknown`
- **Non-effect:** `No recurrence, shared authority, maintenance, management,
  or remedy mechanism, schema, blame, duty, receiver work, HF or health
  conclusion, environmental conclusion, liability, or external action is
  accepted.`

Plain Markdown, no frontmatter, under 850 words.
