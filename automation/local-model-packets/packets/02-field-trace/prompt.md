# Open a bounded CAPECO storage-terminal overfill record

Lineage ID: `SF-LIN-CAPECO-OVERFILL-PROTECTION-OPENING-01`, opportunity 1.
Prepare one proposal-only case-opening decision from the supplied CSB facts.
Do not retrieve sources. Do not invent the ignition source, complete operator
knowledge, one root cause, blame, legal duty, environmental or health
causation, remedy efficacy, recurrence, schema fit, receiver action, or
external effect.

Supplied official-source facts from the U.S. Chemical Safety Board final
investigation of the October 23, 2009 Caribbean Petroleum Corporation
terminal explosion and fire in Bayamon, Puerto Rico:

- A ship-to-terminal transfer distributed more than ten million gallons of
  gasoline among four tanks over more than 24 hours; operators later directed
  the remaining flow to tanks 409 and 411.
- Tank 409 overflowed for about 26 minutes, releasing nearly 200,000 gallons of
  gasoline through vents into the containment dike before ignition.
- The release formed a 107-acre vapor cloud; ignition caused multiple tank
  explosions and fires, burned 17 of 48 tanks, and took three days to control.
- The pressure wave damaged about 300 nearby homes and businesses, and
  petroleum entered surrounding soil, waterways, and wetlands; no fatalities
  occurred.
- Tank-level measuring devices were poorly maintained and frequently failed;
  tank 409's transmitter card was out of service, requiring manual hourly
  readings.
- The float-and-tape gauging system was the only overfill control. No
  independent high-level alarm or automatic overfill-prevention system was in
  place, and atmospheric gasoline tanks were outside relevant process-safety
  coverage described by the report.

Return exactly eleven short lines:

- **Unit:** exactly `CAPECO storage-terminal public-source case opening`.
- **Transfer boundary:** name only ship unloading, four receiving tanks, flow diversion, and multi-hour transfer.
- **Overfill boundary:** name only tank 409, vent discharge, containment dike, duration, and released gasoline.
- **Gauging boundary:** name only float-and-tape measurement, transmitter-card failure, and manual hourly readings.
- **Protection boundary:** name only independent high-level alarm, automatic overfill prevention, and flow shutoff or diversion.
- **Event boundary:** name only vapor cloud, ignition, explosions, tank fires, and fire-control duration.
- **Standing boundary:** name only workers, nearby homes and businesses, road users, soil, waterways, and wetlands.
- **Oversight boundary:** name only atmospheric-storage process-safety coverage and aboveground-tank standards.
- **Decision:** choose exactly `open_bounded_capeco_record` or `decline_case_opening`.
- **Source limit:** exactly `complete operator knowledge, ignition source, custody, accountable authority, disposition, implementation, environmental or health causation, relative causal weight, recurrence, schema fit, and remedy efficacy remain unknown`.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, environmental or health conclusion, remedy, receiver work, or external action is accepted.`

Use `open_bounded_capeco_record` only if every layer stays separate and all
named unknowns remain explicit. This is a Frontier case-opening decision, not
owner research truth. Plain Markdown, no table or frontmatter, under 420
words.
