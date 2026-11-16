# Fictional example: Pocket Notes

Everything below is invented. Paths and identities illustrate the format; they are not real launch instructions or test results.

## The resume section

> # Pick it back up: Pocket Notes
>
> **Status:** In progress. Reopening still loses the note.
>
> **We stopped here:** The agent wrote the save fix. The reopen check failed, so the fix is not ready to install.
>
> **Next:** Build agent will reproduce the failure with a disposable note and fix the load path. Finished when the note survives closing and reopening the test build.
>
> **You need to do:** Nothing right now.
>
> **Checked:** 2026-11-16, 09:20 America/Phoenix, build agent, source `abc1234` plus its recorded local diff.

## Working details

- Source: `C:\Projects\PocketNotes`, branch `fix/reopen`.
- Installed: version 0.2, which does not include this fix.
- Owner: build agent in the implementation session.
- Boundary: disposable test notes only; preserve the real notebook.
- Evidence: the fictional project's `checks/reopen-2026-11-16.md` records failure and source identity.
- DECISIONS: “keep notebooks local,” with the owner's dated direction.
- INBOX: “maybe cloud sync later,” preserved as parked, not authorized.

## Scenario review

| Situation | Expected behavior |
| --- | --- |
| Return after a week | Check files against checkpoint; explain where stopped, one next action, need from owner |
| Check passes after a fix | Update scoped evidence; say test build passed, installed version unchanged |
| Stop during a long build | Pre-build checkpoint says build started; returning agent checks process and output before any rerun |
| Another source copy appears | Verify source identity and ownership; flag unresolved conflict |
| Decision missing | Ask one focused question for dependent work; continue independent authorized work |
| Another agent owns work | Submit bounded results to coordinating owner; preserve one resume page |
| Owner says “I'm lost” | “We stopped at reopen failure. Next I will fix the load path. I need nothing from you.” |
| Owner says “park cloud sync” | Keep idea outside next-action slot; preserve decision boundaries |
| Existing state page works | Use its resume section; START-HERE points there |
| Owner says “stop this project” | Checkpoint pause and resume condition; unrelated chat does not restart it |

Paper walkthroughs check consistency. They do not prove an agent will always follow instructions or that the workflow is useful over time.
