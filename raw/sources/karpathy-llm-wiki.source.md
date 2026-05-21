# Source: Karpathy llm-wiki

- URL: https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f
- Created: 2026-04-04
- Captured: 2026-05-19
- Type: idea file / pattern

## Why This Source Matters

The core pattern is to keep raw sources immutable and let an LLM maintain a persistent, interlinked markdown wiki between the user and the sources.

For this repo, the adapted version is:

- `raw/` = original marketing sources
- `wiki/` = distilled marketing knowledge
- `AGENTS.md` = repo rules for Codex
- `log.md` = append-only history
- `workflows/` = repeatable marketing workflows

