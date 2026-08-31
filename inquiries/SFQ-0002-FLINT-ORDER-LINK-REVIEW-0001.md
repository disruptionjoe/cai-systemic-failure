---
review_id: SFQ-0002-FLINT-ORDER-LINK-REVIEW-0001
status: provisional_source_review
subject: SFQ-0002
selected_source: EPA_SDWA_SECTION_1431_ORDER_2016-01-21
claim_posture: provisional
receiver_fit: cai-mechanism-design_candidate_only
external_action: none
---

# Flint EPA Emergency-Order Link Review

## Boundary

This review asks only what later authority, validation, and stop objects are
supported by EPA's January 21, 2016 Safe Drinking Water Act Section 1431
Emergency Administrative Order. It does not use the later order to establish
custody, recipient authority, disposition, validation treatment, or causal
relevance for one earlier complaint; merge the Flint and Texas chains; broaden
`SFQ-0002`; accept a schema; assign blame or duty; prescribe a remedy; create
receiver work; or request external action.

## Source Custody

- U.S. Environmental Protection Agency, *Emergency Administrative Order*,
  Safe Drinking Water Act Section 1431, January 21, 2016:
  https://www.epa.gov/sites/default/files/2016-01/documents/1_21_sdwa_1431_emergency_admin_order_012116.pdf

Source posture: public official order. Frontier reviewed order pages 1, 13-14,
and 18. The order controls the bounded later-link finding; the earlier EPA OIG
complaint trace remains a separate source object.

## Evidence Ledger

| Link | Source-local result | Order pages | Boundary |
| --- | --- | --- | --- |
| authority object | supported: EPA exercised Section 1431 emergency-order authority and bound the City of Flint, the Michigan Department of Environmental Quality, and the State of Michigan as respondents | 1 | This is later emergency authority, not proof of the authority applied to one earlier complaint. |
| corrosion-control validation object | supported: paragraphs 58-59 require continued corrosion inhibitor and plans for corrosion-control optimization, sampling, monitoring, operations, calibration, verification, reporting, and posting | 13 | Later treatment and monitoring requirements do not establish how an earlier complaint was validated or dispositioned. |
| source-transition validation object | supported: paragraph 60 prohibits a new-source transition until a written plan, expert consultation, public comment, demonstrated capacity, infrastructure upgrades, analysis, testing, and a treatment performance period support the transition | 13-14 | The prohibition and performance bar are later stop and validation objects, not a reconstructed complaint chain. |
| termination object | supported: paragraphs 75-76 keep the order effective until its provisions are met with written EPA approval and make satisfaction depend on written EPA notice | 18 | Written termination supplies an accountable later closure condition only. |
| earlier complaint chain | `unknown`: custody of one selected complaint, complaint-specific authority, disposition, decision-time validation treatment, timely unresolved stop, and causal relevance remain unsupported by this order | n/a | The later order cannot be backdated into the earlier chain. |

## Disposition

`admit_later_authority_and_stop_link_only`.

The order supports a later accountable authority, several explicit validation
objects, and bounded stop or termination conditions. It does not complete the
earlier complaint-to-decision chain. Keep `SFQ-0002` unmodified, keep the Texas
chain separate, retain `require_source_local_completion_before_receiver`, and
leave Mechanism Design fit candidate-only.

## Alternatives, Counterevidence, And Falsifier

Drinking-water treatment, corrosion control, public health, federal and state
oversight, emergency authority, source transition, public communication, and
legal accounts remain sovereign. The order's explicit later controls are
counterevidence to treating authority or stop status as permanently absent,
but chronology is counterevidence to using those controls as proof of earlier
complaint treatment.

Reverse this review only if source-local evidence connects one earlier
complaint through custody, complaint-specific authority, disposition, then-
current validation treatment, unresolved stop, and causal relevance. Narrow it
if closer order review changes one cited later object.

## Candidate Effect

ADMIT ONE LATER FLINT AUTHORITY, VALIDATION, AND STOP LINK ONLY - NO INQUIRY,
SCHEMA, REMEDY, ACCEPTANCE, RECEIVER-WORK, OR EXTERNAL-ACTION CHANGE

## Correction Route And Frontier Verification

Correct this review and dependent summaries if the official order or a closer
source-local reading changes a material fact or boundary. Frontier retained
the candidate's exact `admit_later_authority_and_stop_link_only` decision and
earlier-chain refusal, independently reviewed the named pages, and authored the
source custody, evidence ledger, chronology boundary, alternatives, falsifier,
owner-state reconciliation, and no-receiver-work posture.

Family lineage: `SF-LIN-FLINT-EPA-ORDER-AUTHORITY-STOP-01`.
