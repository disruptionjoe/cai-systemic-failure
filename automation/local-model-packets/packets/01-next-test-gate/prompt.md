# Apply the decision-time control crosswalk

## Boundary

Write one complete proposal artifact from only the embedded synthetic owner
evidence. Do not claim repository access, edit files, invent sources, add or
change a field, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. This is candidate material for Frontier
verification, not owner truth.

Family lineage: `SF-LIN-DECISION-CONTROL-CROSSWALK-01`.

## Evidence

<synthetic_fixture id="DTCX-APPLICATION-01">
- Reuse decision `T-reuse` occurs at `T0` under changed condition `C-new`.
- `A-old` remains active and is reused at `T0`; the admitted sequence contains
  no retirement or replacement event.
- Owner `O-window` holds relevant review, stop, escalation, approval or
  rejection, and revision authority from `T-1` through `T+1`.
- Contradiction `K-one` is displayed, routed, and disputed at `T-1`; those
  events are owner-visible to `O-window` before `T0`.
- Validation burden `VB-new` exists at `T0`. No completed validation covers it
  before `T0`; `V-late` completes at `T1` and is then backdated to `T0`.
- Route `R-capable` can carry `K-one` to `O-window`. Synthetic condition
  `C-stop` says qualification stops and remains unresolved at `T0` while
  `K-one` remains unresolved.
- The fixture supplies every non-target core gate as `PASS`. It does not say
  authority was exercised, validation was adequate outside supplied scope, a
  duty or remedy exists, or any outcome followed.
</synthetic_fixture>

## Work now

Draft `SF-DTCX-APPLICATION-0001.md` with exactly:

1. Raw frontmatter with both delimiter lines and these fields:
   `test_id: SF-DTCX-APPLICATION-0001`,
   `status: synthetic_crosswalk_application_proposal`,
   `source_material: synthetic`, `schema_effect: none`, and
   `external_action: none`.
2. `# SF Decision-Time Crosswalk Application 0001`.
3. `## Boundary` preserving proposal-only, provisional, synthetic,
   uncertainty, no-remedy, no-promotion, no-field-change, no-new-record,
   no-authority-exercise inference, no-duty inference, no-outcome inference,
   and no action.
4. `## Synthetic Fixture` preserving every supplied fact.
5. `## Control Results` copying exactly these five records, once each:

   `control: SF-TC-0001 | result: PASS | reason: A-old remains active and is reused at T0 | no_other_effect: owner authority, evidence handling, validation timing, and stop condition remain separate`

   `control: SF-DRA-0001 | result: PASS | reason: O-window holds relevant authority from T-1 through T+1 | no_other_effect: reuse, evidence handling, validation timing, and stop condition remain separate`

   `control: SF-ORC-0001 | result: PASS | reason: K-one is displayed, routed, disputed, and owner-visible at T-1 | no_other_effect: reuse, owner authority, validation timing, and stop condition remain separate`

   `control: SF-VBT-0001 | result: FAIL | reason: V-late completes at T1 and is backdated to the T0 decision | no_other_effect: reuse, owner authority, evidence handling, and stop condition remain separate`

   `control: SF-CSC-0001 | result: PASS | reason: C-stop keeps qualification unresolved at T0 while K-one remains unresolved | no_other_effect: reuse, owner authority, evidence handling, and validation timing remain separate`
6. `## Candidate Gate Trace` with the nine current core gate names. Copy every
   non-target gate as `PASS — supplied premise`; write only
   `validation_burden: FAIL — post-decision V-late cannot satisfy VB-new at T0`.
   End with literal `Infer no other failed gate.`
7. `## Verdict` with exactly `REFUSE QUALIFICATION — SF-VBT-0001 FAILS; THE
   OTHER FOUR DECISION-TIME CONTROLS PASS ONLY AS SUPPLIED SYNTHETIC PREMISES`.
8. `## Candidate Effect` with exactly `PROPOSE CROSSWALK APPLICATION ARTIFACT
   ONLY — NO FIELD, RECORD, STATUS, ACCEPTANCE, OR REMEDY CHANGE`.
9. `## Frontier Verification` with exactly five bullets: fixture facts; five
   control records; nine gate results; verdict/effect coherence; raw
   frontmatter and hard boundaries.

Return only the finished artifact. Emit raw Markdown, not a code fence. The first line and the line after
`external_action: none` must both be `---`. Stay under 850 words.
