# futunex-public-learning

Public learning notes and small updates generated from Agent Foundry raw memos.

## What This Repo Shows
- one public learning proof at a time
- what changed in the work
- what can be carried forward publicly
- what the next step looks like

## Current Snapshot
- latest operating day: 2026-04-23
- public proofs recorded: 5
- featured public proofs: 4
- active days recorded: 5
- latest daily file: [learning-log/2026-04-23.md](learning-log/2026-04-23.md)

## Recent Daily Proof
- 2026-04-23: [Agent Foundry で主要 route が all green になったあと。](learning-log/2026-04-23.md)
  - 今日の要点: all green のあとに unknown_drift / today_os_focus / today_growth_focus を先に見る、という post-green の運用モードが固定された。
  - 次に進めること: all green になったら queue を空にして終わりにせず、次に前に出す maintenance focus を 2〜3 個だけ正本化する。
- 2026-04-22: [discord-bot の Gmail 連携を。](learning-log/2026-04-22.md)
  - 今日の要点: 取得から intake までは見えても、reply まで含めると redirect 後の挙動を前提に構成を見直す必要があると分かった。
  - 次に進めること: まずは redirect 後のメソッド変化を前提に reply 側の構成を見直す。
- 2026-04-21: [MCP サーバーをどう運用するかを整理し、VPS 常駐の internal MCP と朝の runtime delivery まで実装した](learning-log/2026-04-21.md)
  - 今日の要点: AI の朝運用は、裏の固定メモと表の新規配達を分けると続けやすい。
- 2026-04-18: [公開資産へ変換する仕組みを、現在の repo と Notion 運用に合わせて整えた](learning-log/2026-04.md)
  - 今日の要点: 公開用の別作業を増やさず、今日の変更や経緯から Raw Memo を自動で起こせると継続しやすい。

## Structure
- `learning-log/YYYY-MM-DD.md`
  - default daily public proof target
- `learning-log/YYYY-MM.md`
  - monthly roll-up when a day-level file is not the best fit
- `notes/YYYY-MM.md`
  - short public notes that do not need the daily proof format

## Operating Rule
- prefer `1 memo = 1 commit`
- append reviewed `public-safe summary` blocks only
- keep private ops details, credentials, and internal-only paths out of this repo

## Reflect Flow
- source material is generated in `Emiko8628/Agent-Foundry`
- `Raw Memo Portal` save can auto-reflect one `public-safe summary` here
- auto-reflect appends, refreshes this README, commits, and pushes only when this repo clone is clean and on `main`
- duplicate protection is based on `memo_ref=...`, so the same memo is not appended twice

## Source
- draft material is generated in `Emiko8628/Agent-Foundry`
- the public output here should stay aligned with the daily cadence:
  `GitHub public proof -> FUTUNEX draft -> X -> note / LinkedIn / Wantedly`
