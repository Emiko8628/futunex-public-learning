# futunex-public-learning

Public learning notes and small updates generated from Agent Foundry raw memos.

Agent Foundry の Raw Memo から生成した、公開用の学びメモと小さな更新記録をまとめるリポジトリです。

## このリポジトリで分かること
- 1件ずつ公開できる learning proof
- その日に何を動かしたか
- 公開知見として何を持ち帰れるか
- 次にどこを進めるとよいか

## 現在のスナップショット
- 最新の稼働日: 2026-04-23
- public proof 記録数: 5
- README 掲載中の featured proof 数: 4
- 記録済み稼働日数: 5
- 最新の日次ファイル: learning-log/2026-04-23.md

## 直近の Daily Proof

### 2026-04-23: Agent Foundry で主要 route が all green になったあと。
- 今日の要点: all green のあとに unknown_drift / today_os_focus / today_growth_focus を先に見る、という post-green の運用モードが固定された。
- 次に進めること: all green になったら queue を空にして終わりにせず、次に前に出す maintenance focus を 2〜3 個だけ正本化する。

### 2026-04-22: discord-bot の Gmail 連携を。
- 今日の要点: 取得から intake までは見えても、reply まで含めると redirect 後の挙動を前提に構成を見直す必要があると分かった。
- 次に進めること: まずは redirect 後のメソッド変化を前提に reply 側の構成を見直す。

### 2026-04-21: MCP サーバーをどう運用するかを整理し、VPS 常駐の internal MCP と朝の runtime delivery まで実装した
- 今日の要点: AI の朝運用は、裏の固定メモと表の新規配達を分けると続けやすい。

### 2026-04-18: 公開資産へ変換する仕組みを、現在の repo と Notion 運用に合わせて整えた
- 今日の要点: 公開用の別作業を増やさず、今日の変更や経緯から Raw Memo を自動で起こせると継続しやすい。

## Structure
- `learning-log/YYYY-MM-DD.md`
  default daily public proof target
- `learning-log/YYYY-MM.md`
  monthly roll-up when a day-level file is not the best fit
- `notes/YYYY-MM.md`
  short public notes that do not need the daily proof format

## Operating Rule
- prefer `1 memo = 1 commit`
- append reviewed `public-safe summary` blocks only
- keep private ops details, credentials, and internal-only paths out of this repo

## Reflect Flow
- source material is generated in `Emiko8628/Agent-Foundry`
- `Raw Memo Portal` save can auto-reflect one `public-safe summary` here
- auto-reflect appends the target note and refreshes this README
- duplicate protection is based on `memo_ref=...`, so the same memo is not appended twice

## Source
- draft material is generated in `Emiko8628/Agent-Foundry`
- the public output here should stay aligned with the daily cadence:
  `GitHub public proof -> FUTUNEX draft -> X -> note / LinkedIn / Wantedly`
