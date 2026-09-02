---
trace_id: SF-SANBRUNO-RECORD-INTEGRITY-ASSESSMENT-PARTIAL-TRACE-0001
status: provisional_public_source_trace
records: [SF-0027]
lane: "1"
created: 2026-09-02
source_material: public_official_report
external_action: none
---

# San Bruno Record-To-Integrity-Assessment Partial Trace

## Boundary

This trace preserves only the source-local relation among physical pipe
fabrication, inaccurate historical records, threat identification, integrity-
assessment method selection, the seam-weld defect, and later rupture
recognition and isolation in `NTSB/PAR-11/01` and `SF-0027`.

It does not reconstruct complete fabrication or record custody, integrity
decisions, assessment disposition, rupture recognition or isolation authority,
correction, implementation, relative causal weight, or control effect; infer
recurrence or one fabrication, weld, recordkeeping, integrity, threat-
identification, assessment, pressure-control, detection, isolation, emergency-
response, regulatory, or safety-management mechanism; or create blame, duty,
remedy, acceptance, receiver work, health causation, liability, or external
action.

## Source Set

- National Transportation Safety Board, *Pacific Gas and Electric Company
  Natural Gas Transmission Pipeline Rupture and Fire, San Bruno, California,
  September 9, 2010*, `NTSB/PAR-11/01`, executive-summary pages x-xii and
  report pages 25-29, 39-45, 51-69, 90-124, and 127-128:
  https://www.ntsb.gov/investigations/AccidentReports/Reports/PAR1101.pdf
- NTSB investigation page `DCA10MP008`:
  https://www.ntsb.gov/investigations/Pages/DCA10MP008.aspx
- Bounded owner record `SF-0027`.

The NTSB report controls. Later recommendation implementation, litigation,
compensation, individual medical history, and third-party material are not
imported.

## Partial Trace

| Trace object | Supported source-local fact | Distinct custody or authority | Missing link |
| --- | --- | --- | --- |
| physical pipe | The ruptured assembly contained longitudinal seam welds, including a deficient partially welded seam in a historical short pipe section. | Pipe manufacture, fabrication quality control, installation, operating pressure, inspection, and later integrity review remain separate objects. | Complete fabrication provenance, inspection custody, installation decision, later challenge, and correction are not reconstructed. |
| historical record | PG&E records identified the accident segment as seamless pipe even though the assembly contained longitudinal seam welds. | Record creation, geographic information, physical verification, threat identification, assessment planning, and correction remain distinct. | Complete record creation, transfer, reconciliation, accountable review, and correction path remain incomplete. |
| threat identification | NTSB found that integrity management relied on incomplete and inaccurate pipeline information and did not adequately account for design and material threats. | Asset data, threat taxonomy, risk weighting, engineering review, program self-assessment, and regulatory oversight are separate. | Complete finding custody, decision-time challenge, accountable disposition, and implementation are not established. |
| assessment method | The selected examination method was unable to detect the seam-weld defects present in the accident pipe. | Threat identification, technology capability, assessment selection, result interpretation, repair decision, and program acceptance remain distinct. | Complete selection rationale, capability review, exception authority, result custody, and corrective disposition remain unknown. |
| rupture state | Line 132 ruptured during a pressure increase associated with terminal work, and the released gas ignited in a residential area. | Terminal work, pressure control, deficient seam, crack growth, rupture, release, ignition, and consequence remain separate. | Complete work-plan custody, pressure-decision sequence, rupture-time knowledge, ignition path, and relative contribution remain incomplete. |
| recognition and isolation | SCADA limitations delayed recognition and location of the break, and PG&E took 95 minutes to stop gas flow and isolate the rupture site. | Physical break, SCADA indication, public report, dispatch, location, valve operation, field response, isolation, and flow cessation are distinct. | Complete signal custody, command transfer, location decision, valve authority, action chronology, and counterfactual effect remain incomplete. |
| standing and control effect | Eight people died, homes were destroyed or damaged, many people were injured or evacuated, and operator, municipal, state, and federal actors occupied different response and oversight positions. | Residents, evacuees, responders, operator staff, CPUC, PHMSA, and NTSB have different exposure, operating, review, regulatory, and recommendation roles. | Complete participation, accountable correction, implementation, relative causal weight, health causation, and verified control effect remain unknown. |

## Decision, Counterevidence, And Falsifier

Decision: `prepare_partial_sanbruno_record_integrity_trace`.

The report supports a bounded relation from physical seam construction and an
inaccurate seamless-pipe record through incomplete threat identification and
an assessment method unable to detect the represented defect. It does not
support a complete record-to-rupture or record-to-isolation authority chain.
Distinct fabrication, record, risk, assessment, pressure, recognition,
isolation, response, standing, and oversight objects are counterevidence to one
complete recordkeeping or integrity mechanism.

Falsify or materially narrow this trace if closer official-source review shows
that the ruptured assembly did not contain longitudinal seam welds, that the
records did not identify the segment as seamless, or that the selected method
could detect the seam-weld defect. Reject any stronger chain that fills
preserved custody, authority, correction, implementation, causal-weight, or
control-effect gaps.

## Correction Route And Frontier Verification

Correct this trace and dependent summaries if the controlling report changes a
cited fact or boundary. Frontier retained the candidate's bounded decision,
ordered objects, supplied record and integrity facts, seam-weld falsifier,
unknowns, and non-effect; repaired the substituted and circular missing-link
cells; independently reconciled `NTSB/PAR-11/01` through `SF-0027`; and
authored source custody, role distinctions, counterevidence, correction, and
non-promotion boundaries.

Family lineage: `SF-LIN-SANBRUNO-RECORD-INTEGRITY-ASSESSMENT-PARTIAL-TRACE-01`.
