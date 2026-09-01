# Trace PES HF mitigation control timing

Lineage ID: `SF-LIN-PES-HF-MITIGATION-CONTROL-TIMING-01`, opportunity 1.
Prepare one proposal-only source-local timing trace from these supplied
official CSB report facts. Frontier review decides owner truth. Do not retrieve
sources or invent unsupported facts. Do not infer recurrence, one root cause,
blame, duty, remedy efficacy, health causation, or external effect.

Official source: U.S. Chemical Safety and Hazard Investigation Board,
*Philadelphia Energy Solutions (PES) Refinery Fire and Explosions*, final
report released October 11, 2022, especially pages 6-8 and 51-68:
https://www.csb.gov/assets/1/20/PES_Final_Report_Published_October_2022_r1.pdf

Supplied official-source facts:

- The rapid acid deinventory system was activated after ignition and routed
  about 339,000 pounds of HF from the unit to a separate drum.
- At 4:02:06 a.m., vapor-cloud ignition occurred and control-system
  communication to the HF-mitigation water pumps failed.
- At 4:02:15 a.m., the unit's uninterruptible backup power supply failed.
- At about 4:12 a.m., the control-room operator tried to start the water pumps
  remotely, but they did not start.
- At about 4:39 a.m., a shift supervisor in firefighting protective gear
  manually started the pump supplying the elevated water cannons.
- The system was designed to reduce airborne HF through water-spray vapor
  suppression; these facts do not quantify the counterfactual protection
  effect of earlier activation.
- Complete alarm custody, component damage, command authority, field-access
  exposure, implementation, and comparative mitigation effect remain unknown.

Return exactly one Markdown table with seven ordered rows and columns
`Time or object | Supplied source fact | Control distinction | Missing link`:
`RAD action`, `4:02:06 ignition`, `4:02:06 communication failure`, `4:02:15
backup-power failure`, `4:12 remote attempt`, `4:39 manual activation`,
`mitigation-effect boundary`.

Then return exactly four lines outside the table:

- **Decision:** choose `open_bounded_hf_mitigation_timing_trace` or `current_facts_insufficient`.
- **Falsifier:** name one exact official-source fact that would defeat the selected trace decision.
- **Unknowns:** `complete alarm custody, component damage, command authority, field-access exposure, implementation, and comparative mitigation effect remain unknown`
- **Non-effect:** `No recurrence, shared authority mechanism, schema, blame, duty, remedy, receiver work, HF or health conclusion, environmental conclusion, liability, or external action is accepted.`

Plain Markdown, no frontmatter, under 750 words.
