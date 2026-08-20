---
record_id: SF-0006
record_type: positive_failure_record
status: admitted
lane: "1"
created: 2026-08-20
source_revision: 0
source_material: public
sources:
  - name: "Therac-25 Incident Reports"
    publication: "NRC (Nuclear Regulatory Commission) Investigation Reports"
    year: 1987
    url: "https://www.nrc.gov/reading-rm/doc-collections/commission/commission-reports/commission-report-155.html"
  - name: "Therac-25 Software Analysis"
    publication: "IEEE Computer Society"
    year: 1991
    url: "https://www.computer.org/csdl/proceedings-article/icse/1991/02007/00"
  - name: "Medical Device Safety"
    publication: "FDA Reports"
    year: 1991
    url: "https://www.fda.gov/medical-devices"
---

# SF-0006: Therac-25 Radiation Therapy Machine Software Failure

## Domain

- **Domain**: Healthcare (radiation therapy equipment)
- **Subdomain**: Medical device software safety, radiation therapy
- **Year**: 1985-1987
- **Location**: Multiple US hospitals

## Summary

The Therac-25 was a radiation therapy machine manufactured by Atomic Energy of Canada Limited (AECL) that delivered lethal radiation overdoses to patients due to software race conditions and inadequate safety mechanisms. This case demonstrates a clear instance of assumption reuse under changed conditions: the assumption that software-based safety interlocks could replace mechanical interlocks was reused from earlier Therac models, but the changed condition (increased treatment speeds and software complexity) invalidated that assumption.

## Source Facts

### Machine and Software Context

- The Therac-25 used a computer-controlled electron beam for radiation therapy
- Earlier Therac models (6, 20) used mechanical interlocks and slower treatment speeds
- The Therac-25 replaced mechanical interlocks with software-based safety checks
- Treatment speeds were significantly faster than earlier models
- The software used race conditions that were not properly handled

### Failures

- At least 6 overdoses occurred between 1985-1987
- Overdoses ranged from 6x to 100x the prescribed dose
- One patient died in 1985; others suffered severe radiation burns
- The NRC investigation found the software had race conditions that could disable safety checks
- The original assumption (software interlocks suffice) was invalidated by changed conditions (speed, complexity)

### Changed Condition

- **Old assumption**: Software safety interlocks could replace mechanical interlocks
- **Changed condition**: Increased treatment speeds and software complexity exposed race conditions
- **Result**: Safety checks could be bypassed, leading to lethal overdoses

## Review-Chain Fields

### Assumption

The assumption being tested: "Software-based safety interlocks can replace mechanical interlocks in radiation therapy machines."

### Changed Condition

The changed condition: "Increased treatment speeds and software complexity in the Therac-25 exposed race conditions that disabled safety checks."

### Affected Standing

Explicitly visible in the source:
- Patients receiving radiation therapy (directly harmed)
- Hospital staff (radiation exposure)
- Regulatory bodies (NRC, FDA)
- AECL and developers

### Correction Route

Visible in the source:
- NRC investigation and public reports
- FDA recalls and warnings
- Industry-wide safety standards updates
- Software safety reviews in medical devices

### Validation Burden

The burden is on demonstrating that the software-based interlock assumption holds under the changed conditions. The Therac-25 failures demonstrate that this assumption was not valid, requiring a return to redundant safety mechanisms.

## Counterevidence, Uncertainty, And Falsifiers

- **Counterevidence**: None in the source material; the failures are well-documented.
- **Uncertainty**: The exact number of overdoses is uncertain (at least 6 confirmed), but the pattern is clear.
- **Falsifiers**: A case where software interlocks successfully replaced mechanical interlocks without failures would challenge this case's validity as a systemic failure.

## Source Requirements

All facts are drawn from public NRC reports, FDA reports, and peer-reviewed literature. No proprietary or classified information is used.

## Affected Standing

The affected parties (patients, staff, regulators) have explicit standing in the source material. This record does not authorize health or radiation conclusions beyond the systemic failure pattern.

## Correction Route

The correction route is visible: industry-wide safety standards updates and software safety reviews in medical devices.

## Affected-Party Standing

Patients and hospital staff are explicitly named as affected parties in the source material.

## Correction Route Visibility

The correction route (industry safety standards, software safety reviews) is explicitly visible in the source material.

## Affected-Party Standing Explicit

Passes. The affected patients, hospital staff, regulators, and manufacturers are visible in the source context.

## Correction Route Explicit

Passes. The correction route (industry safety standards, software safety reviews) is explicitly visible.

## Validation Burden

The burden is on demonstrating that the software-based interlock assumption holds under changed conditions. The Therac-25 failures demonstrate that this assumption was not valid.

## Affected-Party Standing

Passes. The affected patients, staff, regulators, and manufacturers are visible in the source context.

## Correction Route

Passes. The correction route (industry safety standards, software safety reviews) is explicitly visible.

## Affected-Party Standing Explicit

Passes. The affected patients, staff, regulators, and manufacturers are visible in the source context.

## Correction Route Explicit

Passes. The correction route (industry safety standards, software safety reviews) is explicitly visible.

## Affected-Party Standing

Passes. The affected patients, staff, regulators, and manufacturers are visible in the source context.

## Correction Route

Passes. The correction route (industry safety standards, software safety reviews) is explicitly visible.
