# Test the Flint emergency-order link without backfilling complaints

Prepare one proposal-only source-link decision for `SFQ-0002`. Use only the
supplied owner and EPA-order facts. Do not retrieve sources. Do not infer an
earlier complaint custodian, complaint disposition, individual knowledge,
decision-time causal link, Texas link, recurrence, shared mechanism, blame,
duty, remedy, receiver action, or acceptance.

Supplied owner facts:

- The existing Flint OIG review supports dated complaint evidence, its EPA
  Region 5 record source, and receipt by Region 5 before the January 2016
  emergency order.
- That review leaves custody of one selected complaint, recipient authority
  then applied to it, linkage to a current validation burden, source-preserved
  disposition, a timely unresolved stop, and causal relevance `unknown`.
- `SFQ-0002` is not receiver-ready and requires source-local completion.

Supplied official-source facts from EPA's January 21, 2016 Safe Drinking Water
Act Section 1431 Emergency Administrative Order:

- Paragraph 1 states EPA's authority to order action when an imminent and
  substantial endangerment exists and state or local actions are inadequate;
  EPA determined Flint and Michigan responses were inadequate and continuing.
- Paragraphs 58-59 require continued corrosion inhibitor and a plan, schedule,
  sampling, monitoring, operations, verification, reporting, and posting for
  optimized corrosion control.
- Paragraph 60 prohibits transition to a new water source until a written plan,
  expert consultation, public notice and comment, demonstrated capacity,
  infrastructure upgrades, analysis, testing, and a treatment-performance
  period support a safe transition.
- Paragraphs 75-76 keep the order effective until its provisions are met with
  written EPA approval and make satisfaction depend on written EPA notice.

Source identity:

- U.S. EPA, *Emergency Administrative Order*, SDWA Section 1431, January 21,
  2016:
  `https://www.epa.gov/sites/default/files/2016-01/documents/1_21_sdwa_1431_emergency_admin_order_012116.pdf`

Return exactly ten short lines:

- **Unit:** exactly `Flint January 2016 EPA emergency order`.
- **Source:** exactly `EPA SDWA Section 1431 order dated January 21, 2016`.
- **Earlier-chain boundary:** exactly `the order does not establish custody, disposition, authority, or causal treatment for one earlier complaint`.
- **Authority object:** name only the order's Section 1431 authority and bound respondents.
- **Validation object:** name only corrosion-control, monitoring, analysis, testing, and performance-plan requirements stated above.
- **Stop object:** name only the new-source prohibition and written-EPA-approval termination condition.
- **Decision:** choose exactly `admit_later_authority_and_stop_link_only` or `treat_as_complete_complaint_chain`.
- **Decision basis:** state whether the source supports a later accountable authority, validation, and stop object without completing the earlier complaint chain.
- **Unknowns:** exactly `earlier complaint custody, complaint-specific authority, disposition, causal relevance, and the Texas chain remain unknown`.
- **Non-effect:** exactly `No inquiry broadening, recurrence, shared mechanism, schema pressure, remedy, acceptance, receiver work, or external action is accepted.`

Use `admit_later_authority_and_stop_link_only` unless the supplied facts connect
one earlier complaint through custody, complaint-specific authority,
disposition, validation, stop, and causal relevance. This is a Frontier source-
link decision, not owner research truth. Plain Markdown, no table or
frontmatter, under 260 words.
