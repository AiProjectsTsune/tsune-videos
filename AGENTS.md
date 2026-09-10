# tsune-videos — Codex

- 最初に `doc/CODEX_HANDOFF.md` と `doc/CHANGELOG.md` を読む。
- 動画紹介ページの生成元は sns。`index.html` の変更前に生成元への反映が必要か確認する。
- `CLAUDE.md` / `.claude/rules/` が追加されていれば関連ルールを読む。
- 全変更を `doc/CHANGELOG.md` に記録。対象差分を secret スキャン後に commit / push。既存差分を保持する。
- `.env`・資格情報・個人情報を記録・送信しない。ブラウザは Browser Use CLI 2.0。Playwright 禁止。
