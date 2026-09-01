# Test the Tesoro Anacortes and Chevron Richmond integrity boundary

Lineage ID: `SF-LIN-COMP-TESORO-CHEVRON-INTEGRITY-DISPOSITION-01`,
opportunity 1. Prepare one proposal-only comparison decision. Use only the
supplied owner facts. Do not retrieve sources. Do not invent shared damage
mechanism, complete condition history, common inspection method, shared
custody, one accountable authority, recurrence, blame, legal duty, remedy
efficacy, schema fit, receiver action, or external effect.

Supplied Tesoro owner facts from `SF-0014`:

- HTHA severely weakened a carbon-steel heat exchanger before rupture,
  explosion, and fire during non-routine startup work.
- Historical design data and incomplete actual-condition measurement
  understated HTHA susceptibility; the relevant exchangers had not been
  inspected for HTHA before the incident.
- Inspection was localized, skill-dependent, and possible only after damage
  existed; higher-chromium material was more resistant.
- PHAs listed safeguards without verifying that they controlled HTHA and
  startup exposure; complete custody, authority, disposition, and closure are
  unknown.

Supplied Chevron owner facts from `SF-0015`:

- Sulfidation corrosion thinned one low-silicon carbon-steel pipe component
  before rupture, vapor-cloud release, ignition, and fire.
- Adjacent components with different silicon content corroded at materially
  different rates; the failed component was not among measured locations.
- Internal recommendations called for broader component inspection or material
  upgrade, but did not enter the accepted turnaround scope.
- Leak mitigation continued without a formal protocol, and damage-mechanism
  and operating-temperature information did not fully reach incident command.

Return exactly eleven short lines:

- **Unit:** exactly `Tesoro Anacortes and Chevron Richmond integrity comparison`.
- **Tesoro damage boundary:** name only HTHA, heat-exchanger weakening, and rupture.
- **Tesoro control boundary:** name only operating-condition prediction, HTHA inspection, material resistance, PHA verification, and startup exposure.
- **Chevron damage boundary:** name only sulfidation corrosion, low-silicon component thinning, and pipe rupture.
- **Chevron control boundary:** name only component coverage, material verification, turnaround scope, leak protocol, and incident-command information.
- **Mechanism boundary:** exactly `HTHA and sulfidation corrosion remain distinct damage mechanisms in different equipment and work phases`.
- **Decision:** choose exactly `preserve_separate_integrity_boundaries` or `open_shared_integrity_candidate`.
- **Decision basis:** state whether both records establish the same degradation object, current condition evidence, inspection method, accountable authority, disposition, stop condition, and control effect.
- **Counterevidence:** name equipment, damage mechanism, work phase, inspection limits, and affected-standing differences.
- **Unknowns:** exactly `complete condition history, custody, accountable authority, disposition, stop conditions, relative causal weight, recurrence, schema fit, and remedy efficacy remain unknown`.
- **Non-effect:** exactly `No recurrence, shared mechanism, schema pressure, blame, duty, remedy, receiver work, or external action is accepted.`

Use `preserve_separate_integrity_boundaries` unless both records independently
support the same complete degradation-to-inspection-and-disposition chain.
This is a Frontier comparison decision, not owner research truth. Plain
Markdown, no table or frontmatter, under 400 words.
