# STATE UPDATE PROTOCOL

## Goal
Keep the career state current without rewriting the whole history.

## Every day
Update only if something meaningful happened:
- what was learned
- what was built/tested
- current blocker
- next action

## Every week
Update:
- CURRENT_STATE.md
- relevant knowledge entries
- one progress/review note

## Every month
Update:
- skill matrix
- job-readiness view
- resume evidence
- ROADMAP.md priorities if necessary
- one month-end review

## When changing AI
Provide the new AI with:
1. `AI_HANDOFF.md`
2. `CURRENT_STATE.md`
3. latest review

Then ask it to:
- acknowledge the current state
- preserve decisions already made
- continue from `NEXT ACTION`
- ask only for missing information that materially changes the plan

## Versioning
Use Git if possible.
Recommended cadence:
- daily/weekly commits for meaningful progress
- monthly tagged snapshot, e.g. `2026-09-month-end`

## Important rule
The chat transcript is not the source of truth. The files are the source of truth.
