# Test the Lac-Megantic and East Palestine hazardous-material phase boundary

Lineage ID: `SF-LIN-COMP-LACMEGANTIC-EASTPALESTINE-HAZMAT-AUTHORITY-01`, opportunity 1.
Prepare one proposal-only comparison decision. Use only the supplied owner
facts. Do not retrieve sources. Do not invent or infer complete custody,
shared authority, one root cause, recurrence, shared mechanism, blame, legal
duty, health causation, remedy efficacy, schema fit, receiver action, or
external effect.

Supplied Lac-Megantic owner facts from `SF-0012`:

- Insufficient hand-brake force and an effectiveness test that retained
  locomotive air-brake contribution preceded the runaway.
- A locomotive fire, shutdown, and later air-brake loss form a distinct event
  transition.
- Crude-oil classification and Class 111 tank-car containment shaped release
  and consequence.
- Company safety management, safety culture, and Transport Canada oversight
  are distinct control layers; complete custody and relative causal weight
  remain unknown.

Supplied East Palestine owner facts from `SF-0007` and its decision trace:

- A defective bearing and untimely wayside detection preceded the derailment.
- The later vent-and-burn decision concerned five vinyl-chloride tank cars and
  remained with the local incident commander.
- Incomplete and misleading technical information shaped that later decision;
  the bearing phase and post-derailment authority phase remain distinct.
- Complete custody, every alternative, liability, health causation, and remedy
  effects remain unknown.

Return exactly ten short lines:

- **Unit:** exactly `Lac-Megantic and East Palestine hazardous-material phase comparison`.
- **Lac-Megantic event phase:** name only securement, locomotive shutdown, runaway, and crude-oil containment.
- **Lac-Megantic control phase:** name only company safety management and regulatory oversight.
- **East Palestine event phase:** name only bearing failure, detection, derailment, and tank-car condition.
- **East Palestine authority phase:** name only supplied technical information and the local incident commander's later vent-and-burn authority.
- **Common boundary:** exactly `both cases involve hazardous-material consequences but their event, containment, information, and authority phases are not interchangeable`.
- **Decision:** choose exactly `preserve_separate_hazardous_material_authority_phases` or `open_shared_hazardous_material_authority_candidate`.
- **Decision basis:** state whether the supplied facts establish one shared custody-to-authority mechanism rather than only hazardous-material consequence.
- **Unknowns:** exactly `complete custody, relative causal weight, recurrence, schema fit, liability, health effects, and remedy efficacy remain unknown`.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, remedy, receiver work, or external action is accepted.`

Use `preserve_separate_hazardous_material_authority_phases` unless the supplied
facts independently support the same custody, accountable authority,
disposition, and causal chain in both cases. This is a Frontier comparison
decision, not owner research truth. Plain Markdown, no table or frontmatter,
under 310 words.
