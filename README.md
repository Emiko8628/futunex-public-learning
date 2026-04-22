# futunex-public-learning

Public learning notes and small updates generated from Agent Foundry raw memos.

## What This Repo Shows
- one public learning proof at a time
- what changed in the work
- what can be carried forward publicly
- what the next step looks like

## Current Snapshot
- latest operating day: 2026-04-22
- public proofs recorded: 4
- featured public proofs: 3
- active days recorded: 4
- latest daily file: [learning-log/2026-04-22.md](learning-log/2026-04-22.md)

## Recent Daily Proof
- 2026-04-22: [新しい構成 Apps Script Gmail を定期監視 条件に合う未読問い合わせメールを取得 discord-bot の intake webhook に POST 返信依頼を受けたら Gmail から reply discord-bo...](learning-log/2026-04-22.md)
  - 今日の要点: com へ redirect bot 側で redirect 追従対応 redirect 後 405 Google 側の実挙動は 302 後 GET 302 後に POST 継続していたため失敗 301/302/303 は GET に切り替...
  - 次に進めること: まずは今の論点を1つに絞って書き出す。
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
