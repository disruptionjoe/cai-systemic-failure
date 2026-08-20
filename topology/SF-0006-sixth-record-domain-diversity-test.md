---
test_id: SF-0006
test_type: sixth_record_domain_diversity
status: admitted
lane: "1"
created: 2026-08-20
source_revision: 0
records: [SF-0006]
schema_candidate: SF-SCHEMA-CANDIDATE-0001
---

# SF-0006: Sixth Positive Record - Domain Diversity Test

## Objective

Add a sixth positive record from healthcare (distinct from aerospace, water safety, offshore energy, fire safety) to test the schema candidate's cross-domain validity.

## Schema Candidate Under Test

`SF-SCHEMA-CANDIDATE-0001` - the provisional review-chain field schema tested against five bounded positive records plus false-positive, mixed, source-quality, and false-negative pressures.

## Record Being Tested

`SF-0006` - Therac-25 radiation therapy machine software failure (healthcare domain).

## Test

The schema candidate must:

1. **Capture the assumption**: The assumption that "software-based safety interlocks can replace mechanical interlocks" must be captured.
2. **Capture the changed condition**: The changed condition of "increased treatment speeds and software complexity exposing race conditions" must be captured.
3. **Capture affected standing**: Patients, staff, regulators, and manufacturers must be visible.
4. **Capture correction route**: Industry safety standards updates and software safety reviews must be visible.
5. **Maintain schema fields**: The core fields (assumption, changed condition, affected standing, correction route) must be preserved.

## Result

The schema candidate successfully captures the Therac-25 case:

- **Assumption**: "Software-based safety interlocks can replace mechanical interlocks"
- **Changed Condition**: "Increased treatment speeds and software complexity exposed race conditions that disabled safety checks"
- **Affected Standing**: Patients, hospital staff, regulators (NRC, FDA), manufacturers (AECL)
- **Correction Route**: Industry safety standards updates, software safety reviews in medical devices

The schema candidate's fields are valid for healthcare domain cases.

## Branch Re-Weighting

- **More attention**: The healthcare domain is now represented, validating cross-domain applicability.
- **Less attention**: Schema acceptance pressure (document acceptance readiness more concretely).
- **Hold / monitor**: Fukushima mixed case (SF-MIX-0001), Challenger false-negative (SF-FN-0001).
- **Retire or no-go candidate**: None identified.

## Next Test

The next test should examine whether the schema candidate can now be provisionally accepted or if further domain diversity is needed. Alternatively, test with a healthcare false-positive absorber to ensure the schema doesn't overgeneralize.

## Completion Condition

The sixth positive record from healthcare has been successfully tested. The schema candidate's cross-domain validity is demonstrated.
