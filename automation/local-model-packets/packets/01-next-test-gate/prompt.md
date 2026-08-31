# Repair one bounded 2003 blackout opening

Prepare one proposal-only repair decision for the August 2003 North American
blackout. Use only the supplied U.S.-Canada Power System Outage Task Force
facts. Do not retrieve sources. Do not invent operators, duties, event sequences,
causal weights, remedies, recurrence, or schema fit.

Supplied facts:

- The August 14-15 outage affected the northeastern United States and southern
  Canada and approximately 50 million customers.
- The Task Force identified inadequate system understanding, inadequate
  situational awareness, inadequate tree trimming, and inadequate reliability-
  coordinator diagnostic support as four cause groups.
- The Task Force identified seven violations of voluntary NERC reliability
  standards and said the causes were strikingly similar to earlier major North
  American outages.
- The packet does not supply the final report, event-by-event propagation,
  source-local responsibility for each cause group, counterevidence, or proof
  of recurrence.

Return exactly seven short lines:

- **Unit:** exactly `interconnected northeastern U.S. and southern Canadian
  power system`.
- **Period:** exactly `August 14-15, 2003 blackout`.
- **Primary pressure:** choose exactly `system understanding` or `situational
  awareness`.
- **Source support:** state exactly which supplied Task Force cause group
  supports the chosen pressure; do not cite the four-group list generically.
- **Alternative:** exactly `a narrower initiating or containment failure not
  yet connected to cross-border propagation`.
- **Unknown:** choose exactly `event-by-event propagation link from the chosen
  pressure` or `source-local responsibility for the chosen pressure`.
- **Opening decision:** choose exactly `open_bounded_record` or
  `defer_for_source_gap`.

`open_bounded_record` opens only a source-verification candidate for Frontier
review. It accepts no record, cause, recurrence, blame, schema, remedy, or
external action. Use plain Markdown, no table or frontmatter, under 180 words.
