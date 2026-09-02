# Trace San Bruno records to integrity assessment and defect detection

Lineage ID: `SF-LIN-SANBRUNO-RECORD-INTEGRITY-ASSESSMENT-PARTIAL-TRACE-01`,
opportunity 1. Prepare one proposal-only partial trace from supplied official
NTSB evidence and bounded record `SF-0027`. Frontier review decides owner truth.
Do not retrieve sources. Do not invent unsupported facts. Do not prescribe
pipeline, integrity, assessment, isolation, emergency-response, regulatory, or
management changes; infer recurrence, one universal mechanism, blame, duty,
liability, remedy efficacy, health causation, or external effect.

Supplied evidence from `NTSB/PAR-11/01`:

- The ruptured assembly contained longitudinal seam welds, while PG&E records
  identified the accident segment as seamless pipe.
- Integrity management relied on incomplete and inaccurate pipeline information,
  did not adequately account for design and material threats, and selected an
  examination method unable to detect seam-weld defects.
- Line 132 ruptured during a pressure increase associated with terminal work;
  gas ignited in a residential area.
- SCADA limitations delayed recognition and location of the break, and PG&E
  took 95 minutes to stop gas flow and isolate the site.
- Complete fabrication and record custody, integrity decisions, recognition and
  isolation authority, correction, implementation, relative causal weight, and
  control effect remain incomplete.

Return exactly one Markdown table with seven ordered rows and columns
`Trace object | Supplied source-local relation | Missing link or preserved
boundary`: `physical pipe`, `historical record`, `threat identification`,
`assessment method`, `rupture state`, `recognition and isolation`, `standing
and control effect`.

Then return exactly four lines:

- **Decision:** choose `prepare_partial_sanbruno_record_integrity_trace` or
  `bounded_corpus_insufficient`.
- **Falsifier:** name one exact supplied relation whose removal would defeat the
  selected partial trace.
- **Unknowns:** `complete fabrication and record custody, integrity decisions,
  recognition and isolation authority, correction, implementation, relative
  causal weight, and control effect remain incomplete`
- **Non-effect:** `No recurrence, one fabrication, weld, recordkeeping,
  integrity, threat-identification, assessment, pressure-control, detection,
  isolation, emergency-response, regulatory, or safety-management mechanism,
  shared engineer, controller, operator, responder, regulator, community, or
  affected-party authority, schema, blame, duty, remedy, acceptance, receiver
  work, health causation, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 750 words.
