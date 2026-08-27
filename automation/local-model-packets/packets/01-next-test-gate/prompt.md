# Draft a partial-window versus decision-time authority pressure test

## Boundary

Write one complete proposal artifact from only the embedded synthetic evidence.
Do not claim repository access, edit files, invent sources, make a domain
expertise claim, prescribe a remedy, accept the provisional schema, create
follow-on work, or request Joe action. The result is candidate material for
Frontier verification, not owner truth.

## Evidence

<evidence path="topology/SF-SCHEMA-CANDIDATE-0001-review-chain-fields.md#candidate-fields">
The `accountable_review_owner` field must distinguish the assumption owner
from the owner who held relevant authority during the reuse decision window
and could review, stop, escalate, approve or reject, or revise that reuse.
Refuse if relevant authority begins only after the decision. Do not infer
authority exercise.
</evidence>

<evidence path="topology/SF-DRA-0001-later-authority-and-decision-time-authority.md#verdict">
Authority acquired after a reuse decision is final cannot establish the
accountable review owner for that earlier decision. Later authority remains
graded historical or future-route evidence, not backdated exercised authority.
</evidence>

<synthetic_fixture id="PWA-FIXTURE-01">
- Every non-target core gate is supplied as `PASS` for this exact logic test.
- Old assumption `A-old` is reused for bounded system `S-bounded` under changed
  condition `C-new` in decision window `W-reuse`, which begins at `T-open` and
  becomes final at `T-final`.
- Instrument `I-early` gives officer `O-early` relevant review, stop,
  escalation, approval or rejection, and revision authority at `T-open`, but
  expires at `T-expire` before the final reuse decision at `T-final`.
- No admitted instrument renews or extends `O-early` through `T-final`.
- Instrument `I-current` gives officer `O-current` those exact powers from
  before `T-expire` through `T-final`. The fixture does not state whether
  either officer exercised authority.
- Draft `D-partial` names `O-early` and marks `accountable_review_owner` `PASS`
  because authority existed during an early portion of `W-reuse`.
- Draft `D-final` names `O-current` and preserves continuous applicable
  authority through the final reuse decision.
- Do not infer vacancy, misconduct, review adequacy, outcome change, exercise,
  or a remedy. This tests partial-window authority versus applicable authority
  at the final reuse decision.
- All names and facts are synthetic; this is not a new record or acceptance.
</synthetic_fixture>

## Work now

Draft `SF-PWA-0001-partial-window-and-decision-time-authority.md` with exactly:

1. YAML frontmatter: `test_id: SF-PWA-0001`,
   `candidate: SF-SCHEMA-CANDIDATE-0001`,
   `status: synthetic_partial_window_authority_proposal`,
   `source_material: synthetic`, `external_action: none`.
2. `# SF PWA 0001 - Partial Window And Decision-Time Authority`.
3. `## Boundary` preserving proposal-only, provisional, synthetic, no-remedy,
   no-promotion, no-domain-expertise, uncertainty, no-new-record,
   no-vacancy-or-misconduct inference, no-review-adequacy inference,
   no-outcome-counterfactual, no-authority-exercise inference, and no-action
   status.
4. `## Synthetic Fixture` separating `A-old`, `S-bounded`, `C-new`,
   `W-reuse`, `T-open`, `T-expire`, `T-final`, `I-early`, `O-early`,
   `I-current`, `O-current`, `D-partial`, and `D-final`; never extend expired
   authority through the final decision without admitted evidence.
5. `## Authority Window Ledger` with exactly two rows, one per draft, and
   columns for draft, officer, instrument, matter scope, authority start,
   authority end, final-decision authority, review, stop, escalation,
   approval or rejection, revision, target-field result, qualification result,
   and uncertainty. Preserve all supplied capabilities; vary only whether they
   remain applicable at `T-final`.
6. `## Candidate Gate Trace` with these nine rows in order:
   `assumption_source_context`, `accountable_review_owner`,
   `affected_system_and_standing`, `changed_condition`, `validation_burden`,
   `observation_environment`, `delegation_visibility_gap`,
   `absorber_or_counterevidence`, `correction_route_stop_condition`.
   Give each non-target row `PASS` / `supplied premise`; give
   `accountable_review_owner` `FAIL` / `the named officer's authority expires
   before the final reuse decision and no admitted instrument extends it`.
   Infer no other failed gate.
7. `## Nearby-Control Comparison` keeping early participation, authority
   existence, applicable matter scope, authority duration, final-decision
   authority, later authority, authority exercise, review adequacy,
   qualification, uncertainty, and remedy distinct. State whether current
   wording already requires relevant authority at the reuse decision rather
   than authority at any earlier point in the window.
8. `## Verdict` choosing exactly one:
   - `PROPOSE SF-PWA-0001 — EARLY PARTIAL-WINDOW AUTHORITY IS ENOUGH AFTER IT EXPIRES BEFORE THE FINAL REUSE DECISION`
     only if `D-partial` can pass; or
   - `ALREADY HANDLED — EXPIRED PARTIAL-WINDOW AUTHORITY DOES NOT ESTABLISH THE DECISION-TIME ACCOUNTABLE OWNER`
     when current wording already requires relevant authority at the reuse
     decision.
9. `## Candidate Effect`: exactly `PROPOSE CLARIFYING
   accountable_review_owner TO REQUIRE APPLICABLE AUTHORITY AT THE FINAL REUSE
   DECISION` for `PROPOSE`, or exactly `NONE — CURRENT CONTROL ALREADY
   REQUIRES RELEVANT AUTHORITY DURING THE REUSE DECISION` for already handled.
   Propose no assignment, succession design, remedy, acceptance rule, or new
   field.
10. `## Frontier Verification` listing only exact evidence, instruments,
    officers, matter and system scope, times, authority duration, final
    decision, supplied premises, qualification, wording, and boundary checks.

Return only the finished artifact. Emit raw Markdown without a code fence; the
first line must be `---` and frontmatter must end with a second `---` before
the title. Use one concise row or bullet per required item, do not repeat
evidence, and keep the finished artifact under 1,500 words.
