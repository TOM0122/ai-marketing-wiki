# First Batch Triage · 2026-05-19

## Scope

This triage covers the first batch of files placed under `raw/`.

This is not a full wiki distillation. It only classifies source material and recommends what should be wiki-fied first.

## Batch Overview

### A. Personal Operating System / Self-Skill

Files:

- `raw/files/SKILL.md`
- `raw/files/persona.md`
- `raw/files/self.md`
- `raw/files/work.md`
- `raw/files/interview_notes.md`

Recommended destination:

- `wiki/personal-judgment/`
- possibly a separate `wiki/personal-operating-system/` later

Priority:

- High, but do not over-merge into marketing notes yet.

Reason:

These files define the user's judgment system, language style, decision model, and work handling defaults. They should become the judgment layer that helps evaluate marketing material, not be mixed into source summaries.

Suggested next move:

- Create one index note: `wiki/personal-judgment/user-judgment-system.md`
- Extract only stable decision rules relevant to AI + marketing:
  - preference for practical outputs
  - distrust of inflated language
  - two-layer decision model
  - source quality and evidence preference
  - work prioritization and risk logic

### B. Brand / Campaign / GTM Assets

Files:

- `raw/files/Diveblues GTM方案草稿.pdf`
- `raw/files/Diveblues Fanzy 系列｜2026 全球风扇品牌发布会初稿.pdf`
- `raw/files/（已压缩）Campaign框架 - Ocoopa品牌重塑.pdf`
- `raw/files/2026世界杯整合营销项目（Crazyfan Campaign）.pdf`
- `raw/files/IG红人建联SOP交接文档.docx`

Recommended destination:

- `wiki/brands/`
- `wiki/content/`
- `wiki/concepts/`
- `workflows/`

Priority:

- Highest.

Reason:

This is the closest match to the AI + marketing goal. These files can produce reusable notes for:

- GTM planning
- brand launch structure
- campaign architecture
- influencer outreach SOP
- UGC / KOL collaboration workflow
- brand repositioning and product narrative

Suggested next move:

- Start with `IG红人建联SOP交接文档.docx` because it is already procedural and can become a workflow quickly.
- Then process Diveblues and Ocoopa together as brand/campaign case studies.
- Use Crazyfan as a separate campaign case once the campaign template is stable.

### C. Academic / Research / Audience Analysis

Files:

- `raw/files/Research Report.docx`
- `raw/files/Researching Audiences and Reception (MECM40003)_MingJunLiu_1441230_Research Report.pdf`
- `raw/files/CSR调研报告和用户参与设计报告.pdf`

Recommended destination:

- `wiki/reports/`
- `wiki/consumers/`
- `wiki/concepts/`

Priority:

- Medium.

Reason:

These are not direct marketing operation files, but they contain useful audience research patterns:

- emotional drivers
- fear as media behavior driver
- misinformation sharing logic
- qualitative interview analysis
- CSR/user participation framing

Suggested next move:

- Do not turn them into campaign notes first.
- Extract reusable research methods and audience insight patterns.
- Link later to content strategy and consumer insight notes.

### D. Strategic / Creative Writing Samples

Files:

- `raw/files/Strategic Narrative.docx`
- `raw/files/NHK马王堆纪录片策划.docx`
- `raw/files/人生加载中 分镜.docx`

Recommended destination:

- `wiki/content/`
- `wiki/concepts/`
- `wiki/personal-judgment/`

Priority:

- Medium-high.

Reason:

These files show how the user structures narrative, emotional framing, documentary concepts, and visual scene planning. They are valuable for building a content strategy and creative direction layer.

Suggested next move:

- Extract frameworks, not full prose:
  - strategic narrative structure
  - documentary proposal structure
  - storyboard language and scene breakdown
  - how emotional value is added to factual/cultural content

### E. Web Clips

Files:

- `raw/web-clips/What are the 4 R's of Marketing? - 2026-05-19.md`

Recommended destination:

- `wiki/concepts/`

Priority:

- Low for now.

Reason:

The current clipped file contains metadata but not actual article content. The `Clip` section is empty except for `-`.

Suggested next move:

- Re-clip the page with article content included, or paste/highlight the parts worth saving.
- After content exists, distill into a concept note only if the source is worth keeping.

## Recommended Processing Order

1. `IG红人建联SOP交接文档.docx`
   - Turn into `workflows/influencer-outreach.md`
   - Extract KOL/KOC/UGC screening rules.

2. Diveblues / Ocoopa / Crazyfan PDFs
   - Build campaign case template.
   - Create brand notes and campaign architecture notes.

3. `Strategic Narrative.docx`
   - Extract strategic narrative structure and campaign planning vocabulary.

4. Academic reports
   - Extract research methods and audience insight patterns.

5. Self-skill files
   - Extract only the user's marketing-relevant judgment rules into `personal-judgment`.

## Proposed Wiki Structure Adjustment

Add:

```text
wiki/campaigns/
wiki/methods/
wiki/creative/
```

Reason:

Current folders cover brands, competitors, concepts, content, consumers, reports, and personal judgment. This batch shows three missing types:

- campaign cases
- research/planning methods
- creative execution samples

## File Hygiene Notes

- `.DS_Store` files should be ignored and never wiki-fied.
- `raw/` should stay source-only.
- Do not rename raw files unless the user wants a cleanup pass.
- Web clips should be checked after clipping; empty clips should be re-captured before distillation.

## First Wiki-Fication Recommendation

Do a narrow first wiki-fication pass on:

- `IG红人建联SOP交接文档.docx`

Expected outputs:

- `workflows/influencer-outreach.md`
- `wiki/concepts/influencer-collaboration-types.md`
- `wiki/concepts/ugc-kol-koc-screening.md`

This gives the knowledge base its first usable marketing workflow without opening too many fronts.

