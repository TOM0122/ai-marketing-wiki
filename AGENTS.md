# Knowledge Base Rules

When maintaining this repo:

1. Do not rewrite or delete files in `raw/`.
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
