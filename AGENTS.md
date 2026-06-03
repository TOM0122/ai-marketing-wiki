# Knowledge Base Rules

Ocoopa 操作任务入口在 `/Users/mingjunliu/Documents/助手Agent/AGENTS.md`。如果是跑社媒日历、社媒帖文、GTM、报告、投流分析等 Ocoopa 工作任务，先读那份操作层规则；本文件只负责 vault 知识库维护规则。

When maintaining this repo:

1. Treat `raw/` as read-only during task work — do not rewrite or delete its contents on your own (user-directed maintenance excepted). Note: `raw/files/` is now markdown-first — binary sources were converted to `.md` via markitdown; only a few visual originals (product decks, image-heavy PDFs) are kept.
2. Add distilled notes to `wiki/` as markdown.
3. Prefer short, linked notes over long isolated documents.
4. Every wiki note should include source references when possible.
5. Separate observed facts from judgment.
6. Put the user's own judgment in `wiki/personal-judgment/`, not mixed into source summaries.
7. If evidence is weak, mark it as `low-confidence`.
8. Do not treat generated outputs as facts unless they are later validated.

Default update flow:

1. Ingest source into `raw/sources/`.
2. Extract facts, claims, patterns, and examples.
3. Update relevant notes in `wiki/`.
4. Add or update links between related notes.
5. Produce a short changelog in the final response.

For Obsidian Web Clipper:

- Save clipped pages into `raw/web-clips/`.
- Keep clipping output close to source text.
- Use `source_url`, `author`, `published`, `captured`, `source_type`, and `status` properties when available.
- After clipping, create or update distilled notes in `wiki/`.
