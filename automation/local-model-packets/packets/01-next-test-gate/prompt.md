# Decide one bounded 2003 blackout record opening

Prepare one proposal-only source-opening decision for the August 2003 North
American blackout. Use only the supplied U.S.-Canada Power System Outage Task
Force and U.S. Department of Energy facts. Do not retrieve sources. Do not
invent operators, event sequences, duties, violations, causal allocation,
remedies, or recurrence.

Source boundary:

- U.S. Department of Energy, `August 2003 Blackout`, says the August 14-15
  outage affected the northeastern United States and southern Canada and
  impacted approximately 50 million customers.
- The April 5, 2004 Task Force release says the final report identified four
  cause groups: inadequate system understanding, inadequate situational
  awareness, inadequate tree trimming, and inadequate reliability-coordinator
  diagnostic support.
- The release says the report identified seven violations of voluntary NERC
  reliability standards and found the blackout's causes strikingly similar to
  earlier major North American outages.
- This packet does not supply the complete final report, the event-by-event
  propagation chain, source-local responsibility for each cause group,
  counterevidence, or evidence sufficient to accept a recurrence claim.

Return exactly nine short lines:

- **Unit:** exactly `interconnected northeastern U.S. and southern Canadian
  power system`.
- **Period:** exactly `August 14-15, 2003 blackout`.
- **Scale:** exactly `cross-border interconnected-grid scale`.
- **Affected standing:** exactly `approximately 50 million customers`.
- **Primary pressure:** choose exactly one of `system understanding`,
  `situational awareness`, `tree trimming`, or `reliability-coordinator
  diagnostic support`.
- **Source support:** name the one supplied Task Force fact that supports that
  choice without extending it.
- **Alternative:** name one narrower outage or containment explanation that
  remains possible under the missing propagation chain.
- **Unknown:** name one missing source-local link required before claiming a
  recurring mechanism.
- **Opening decision:** choose exactly `open_bounded_record` or
  `defer_for_source_gap`.

An `open_bounded_record` decision opens only a source-verification candidate
for later Frontier review; it does not accept a record, cause, recurrence,
schema fit, blame finding, policy judgment, remedy, or external action. Use
plain Markdown, no table or frontmatter, and keep it under 220 words.
