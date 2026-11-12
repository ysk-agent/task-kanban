# 未完了タスク Kanban

Moriya の未完了タスクを4列（判断・確認待ち／進行中／保留・様子見／完了）で表示する、表示専用のボードです。

- 公開ページ: https://ysk-agent.github.io/task-kanban/
- カードの内容は `data.json` が正本です。状態が変わったら moka が `data.json` を更新して push します。
- `index.html` は依存なしの単一ページで、`data.json` を読み込んで描画します。
