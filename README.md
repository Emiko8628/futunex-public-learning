# futunex-public-learning

Public learning notes and small updates generated from Agent Foundry raw memos.

## Purpose
- keep public-facing learning notes out of the `Agent-Foundry` operations repo
- accumulate one small public learning note at a time
- keep one public proof per memo in a stable daily cadence

## Structure
- `learning-log/YYYY-MM-DD.md`
  - default daily public proof target
- `learning-log/YYYY-MM.md`
  - optional monthly roll-up when a daily file is not the best fit
- `notes/YYYY-MM.md`
  - optional public notes stream when a memo fits better as a short note than a learning log

## Operating Rule
- prefer `1 memo = 1 commit`
- append reviewed `public-safe summary` blocks only
- keep private ops details, credentials, and internal-only paths out of this repo

## Current Default
- first target path is `learning-log/YYYY-MM-DD.md`
- if needed, fall back to `learning-log/YYYY-MM.md`
- `notes/YYYY-MM.md` is reserved for cases that fit better as a short public note

## Reflect Flow
- source material is generated in `Emiko8628/Agent-Foundry`
- `Raw Memo Portal` save can auto-reflect one `public-safe summary` here
- auto-reflect appends, commits, and pushes only when this repo clone is clean and on `main`
- duplicate protection is based on `memo_ref=...`, so the same memo is not appended twice

## Source
- draft material is generated in `Emiko8628/Agent-Foundry`
- the public output here should stay aligned with the daily cadence:
  `GitHub public proof -> FUTUNEX draft -> X -> note / LinkedIn / Wantedly`
