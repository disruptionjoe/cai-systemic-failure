# Open a bounded DuPont La Porte toxic-release record

Lineage ID: `SF-LIN-DUPONT-LAPORTE-TOXIC-RELEASE-OPENING-01`, opportunity 1.
Prepare one proposal-only case-opening decision from the supplied U.S.
Chemical Safety Board facts. Do not retrieve sources. Do not invent complete
operator knowledge, one root cause, blame, legal duty, offsite health
causation, remedy efficacy, recurrence, schema fit, receiver action, or
external effect.

Frontier review decides owner truth.

Supplied official-source facts from CSB Investigation `2015-01-I-TX`:

- On November 15, 2014, nearly 24,000 pounds of toxic methyl mercaptan escaped
  through two valves into a poorly ventilated manufacturing building at the
  DuPont La Porte facility; four workers died and two additional responders
  survived.
- Water introduced during earlier operations formed a hydrate blockage in the
  methyl-mercaptan feed line. A troubleshooting plan used hot water to clear
  it and opened valves to vent expanding material, without the plan receiving
  the required safety review or having written progress procedures.
- As the hydrate cleared, methyl mercaptan entered a waste-gas vent header.
  Operators treated related high-pressure events as a routine liquid-
  accumulation problem and did not connect them to the clearing work.
- Methyl-mercaptan detectors alarmed, but frequent alarms and hazard
  normalization delayed recognition. The release continued inside the
  building, and the emergency response was disorganized and exposed additional
  workers.
- The CSB treated engineering design, safeguards, troubleshooting, emergency
  response, process-safety management, audit and corrective action, and safety
  culture as distinct issues.

Return exactly eleven short lines:

- **Unit:** exactly `DuPont La Porte public-source case opening`.
- **Troubleshooting boundary:** name only hydrate blockage, hot-water clearing, opened vent path, and missing written progress procedure.
- **Pressure boundary:** name only waste-gas header pressure, routine-problem interpretation, and missing connection to hydrate clearing.
- **Release boundary:** name only methyl mercaptan, two opened valves, enclosed building, poor ventilation, and release duration uncertainty.
- **Detection boundary:** name only detector alarms, frequent-alarm normalization, hazard recognition, and delayed awareness.
- **Response boundary:** name only distress call, responder entry, incident coordination, protective information, and release control.
- **Standing boundary:** name only operators, responders, other workers, and potentially affected public.
- **Management boundary:** name only engineering design, safeguards, process-safety system, audit, corrective action, and safety culture.
- **Decision:** choose exactly `open_bounded_dupont_laporte_record` or `decline_case_opening`.
- **Source limit:** exactly `complete operator knowledge, custody, accountable authority, disposition, implementation, offsite health causation, relative causal weight, recurrence, schema fit, liability, and remedy efficacy remain unknown`.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, health conclusion, remedy, receiver work, or external action is accepted.`

Use `open_bounded_dupont_laporte_record` only if every layer stays separate and
all named unknowns remain explicit. Plain Markdown, no table or frontmatter,
under 420 words.
