# futunex-public-learning

Public learning notes and small updates generated from Agent Foundry raw memos.

Agent Foundry の Raw Memo から生成した、公開用の学びメモと小さな更新記録をまとめるリポジトリです。

## このリポジトリで分かること
- 1件ずつ公開できる learning proof
- その日に何を動かしたか
- 公開知見として何を持ち帰れるか
- 次にどこを進めるとよいか

## 現在のスナップショット
- 最新の稼働日: 2026-04-29
- public proof 記録数: 7
- README 掲載中の featured proof 数: 5
- 記録済み稼働日数: 7
- 最新の日次ファイル: learning-log/2026-04-29.md

## 直近の Daily Proof

### 2026-04-29: 判断ダッシュボードと Role Progress Dashboard で出ていた github_mcp /。
- 今日動かしたこと: shared card の route key 混線を止め、dedicated card の evidence を優先して見るように直した。
- 今日の要点: 表示上の注意は、作業不足ではなく証跡の選ばれ方のズレで起きることがある。
- 次に進めること: dedicated route の execution result が shared card に上書きされていないか確認する。
- 持ち帰り: dashboard の注意理由を追っている人 に近い状況でも、公開前に要点を薄く整えるだけで運用の継続性は上がる。

### 2026-04-23: Agent Foundry で主要 route が all green になったあと。
- 今日動かしたこと: all green のあとに unknown_drift / today_os_focus / today_growth_focus を先に見る、という post-green の運用モードが固定された。
- 今日の要点: post-green の判断はチャットで都度決めるより、JSON 正本にして MCP と dashboard に同じ summary を返す方が継続運用しやすい。
- 次に進めること: all green になったら queue を空にして終わりにせず、次に前に出す maintenance focus を 2〜3 個だけ正本化する。
- 持ち帰り: 同じように「整った後に何を前に見るか」が曖昧になりやすい AI運用 / automation運用担当 に近い状況でも、公開前に要点を薄く整えるだけで運用の継続性は上がる。

### 2026-04-22: discord-bot の Gmail 連携を。
- 今日動かしたこと: 取得から intake までは見えても、reply まで含めると redirect 後の挙動を前提に構成を見直す必要があると分かった。
- 今日の要点: 発信が止まりやすい時は、量より順番の曖昧さを減らす方が整いやすい。
- 次に進めること: まずは redirect 後のメソッド変化を前提に reply 側の構成を見直す。
- 持ち帰り: 同じ種類の詰まりで次の一手を決めにくい人 に近い状況でも、公開前に要点を薄く整えるだけで運用の継続性は上がる。

### 2026-04-21: MCP サーバーをどう運用するかを整理し、VPS 常駐の internal MCP と朝の runtime delivery まで実装した
- 今日の要点: AI の朝運用は、裏の固定メモと表の新規配達を分けると続けやすい。
- 持ち帰り: AI を使った運用を自動化したいけれど、同じチャットに履歴が積み上がるのがつらい人 に近い状況でも、公開前に要点を薄く整えるだけで運用の継続性は上がる。


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
