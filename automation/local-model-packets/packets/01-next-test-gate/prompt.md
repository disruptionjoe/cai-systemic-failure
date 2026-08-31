# Draft one bounded Equifax evidence packet

Prepare a proposal-only record packet for the 2017 Equifax data breach using
only the supplied U.S. Government Accountability Office facts. Do not retrieve
sources or invent breach mechanics, decisions, owners, duties, or remedies.

Source boundary:

- `GAO-18-559, Data Protection: Actions Taken by Equifax and Federal Agencies
  in Response to the 2017 Breach`, published August 30, 2018.
- GAO says attackers gained unauthorized Internet access through Equifax's
  online dispute portal, which maintained documents used to resolve consumer
  disputes.
- GAO says the attackers accessed personal information of at least 145.5
  million individuals.
- GAO reports that Equifax's investigation identified four major factor
  classes: identification, detection, database-access segmentation, and data
  governance.
- This packet supplies no exact attack sequence, patch history, accountable
  decision owner, complete counterevidence, causal allocation, or remedy test.

Answer with exactly eight short lines using these labels:

- **Unit:** exactly `Equifax online dispute portal and connected databases`.
- **Period:** exactly `2017 breach period`.
- **Evidence object:** one supplied GAO finding, without adding detail.
- **System relation:** exactly one of `identification`, `detection`,
  `database-access segmentation`, or `data governance`.
- **Affected standing:** the supplied population fact.
- **Alternative:** one narrower intrusion or security-control explanation that
  remains possible without claiming it is sufficient.
- **Unknown:** one missing decision, authority, sequence, or causal link.
- **Disposition:** exactly `draft_bounded_record` or `insufficient_for_record`.

This is a source-bounded candidate, not an accepted failure record, recurrence
claim, schema fit, blame finding, policy judgment, remedy, or external-action
request. Use plain Markdown, no table or frontmatter, and keep it under 180
words.
