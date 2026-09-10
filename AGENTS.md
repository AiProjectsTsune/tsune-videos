# tsune-videos — Codex

Claude Code は CLAUDE.md からこのファイルを import する。共通ルール本文を両CLI向けに複製しない。
各依頼の開始時に共通 vault の SHARED_WORKFLOW.md、projects/tsune-videos/memory/ と handoffs/ の最新情報を確認し、確定事項を返答前に新しい共有 handoff へ保存する。

- 最初に `doc/CODEX_HANDOFF.md` と `doc/CHANGELOG.md` を読む。
- 動画紹介ページの生成元は sns。`index.html` の変更前に生成元への反映が必要か確認する。
- `CLAUDE.md` / `.claude/rules/` が追加されていれば関連ルールを読む。
- 全変更を `doc/CHANGELOG.md` に記録。対象差分を secret スキャン後に commit / push。既存差分を保持する。
- `.env`・資格情報・個人情報を記録・送信しない。ブラウザは Browser Use CLI 2.0。Playwright 禁止。
