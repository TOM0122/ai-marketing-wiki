# PDF OCR Module Map · 2026-05-21

## Scope

This note tracks the PDF batch under `raw/files/` after OCR processing.

OCR outputs:

- OCR PDFs: `outputs/ocr-pdfs/*.ocr.pdf`
- Extracted text: `outputs/ocr-text/*.txt`

Batch status:

```text
56 source PDFs -> 56 extracted text files
```

No OCR or text-extraction failures were logged in this pass.

## Module Status

### 1. Ocoopa Brand / Campaign

Source PDFs:

- `raw/files/（已压缩）Campaign框架 - Ocoopa品牌重塑.pdf`

Destination modules:

- `wiki/brands/ocoopa.md`
- `wiki/content/ocoopa-social-content-strategy.md`
- `wiki/campaigns/ocoopa-brand-reshaping.md`

Status:

```text
OCR complete / wiki-fied in this pass
```

Main extracted logic:

- product, visual, and copy must follow one narrative logic
- brand personality: 默契的松弛感
- brand emotion: 阳光 / 自由松弛 / 热爱生活
- brand attitude: 积极 / 快乐 / 放松 / 热情
- social content is the window for brand personality, emotion, and attitude
- Amazon content should lower cognition cost and strengthen purchase confidence
- DTC, B2B, Amazon, EDM, packaging, retail, and social should mutually reinforce one campaign narrative

### 2. Advertising Course Spine

Source PDFs:

- `raw/files/1. Advanced Advertising Week 1 - advertising (published).pdf`
- `raw/files/2. Advanced Advertising Week 2 - strategy (published) 2 2.pdf`
- `raw/files/3. Advanced Advertising Week 3 - ideas.pdf`
- `raw/files/4. Advanced Advertising Week 4 - creativity.pdf`
- `raw/files/5. Advanced Advertising Week 5 - consumer v2.pdf`
- `raw/files/6. Advanced Advertising Week 6 - CX.pdf`
- `raw/files/7. Advanced Advertising Week 7 - GTM.pdf`
- `raw/files/8. Advanced Advertising Week 8 - theory v2.pdf`
- `raw/files/9. Advanced Advertising Week 9  - brand.pdf`

Destination modules:

- `wiki/methods/`
- `wiki/concepts/`

Status:

```text
OCR complete / awaiting topic notes
```

Recommended module split:

- advertising fundamentals
- strategy and planning
- idea generation
- creativity and execution
- consumer insight
- customer experience
- GTM
- advertising theory
- brand building

### 3. Audience / Media Research

Source PDFs:

- `raw/files/MECM40003_L2_2025.pdf`
- `raw/files/MECM40003_L3_2025.pdf`
- `raw/files/W1_Seminar.pdf` to `raw/files/W12_Seminar.pdf`
- `raw/files/Uses and Grats 2.0  New Gratifications for New Media.pdf`
- `raw/files/Impacts_of_Gratifications_on_C.pdf`
- `raw/files/Podcasts and Productivity  A Qualitative Uses and Gratifications Study.pdf`
- `raw/files/The social origins and uses of media and communication research_25_03_18_17_35_18.pdf`
- `raw/files/schroder-2018-audience-reception-research-in-a-post-broadcasting-digital-age.pdf`
- `raw/files/gregory-2018-online-communication-settings-and-the-qualitative-research-process-acclimating-students-and-novice.pdf`
- `raw/files/van-es-de-lange-2020-data-with-its-boots-on-the-ground-datawalking-as-research-method.pdf`
- `raw/files/Researching Audiences and Reception (MECM40003)_MingJunLiu_1441230_Research Report.pdf`

Destination modules:

- `wiki/methods/`
- `wiki/consumers/`
- `wiki/reports/`

Status:

```text
OCR complete / awaiting method extraction
```

Recommended module split:

- uses and gratifications
- audience reception research
- qualitative interview workflow
- platform/interface research
- datawalking as method
- media behavior and everyday life

### 4. Brand / GTM / Campaign Cases

Source PDFs:

- `raw/files/Diveblues GTM方案草稿.pdf`
- `raw/files/Diveblues Fanzy 系列｜2026 全球风扇品牌发布会初稿.pdf`
- `raw/files/2026世界杯整合营销项目（Crazyfan Campaign）.pdf`
- `raw/files/Advanced Industry Practice – Advertising_MECM90026_MingJunLiu_1441230_Final Individual Project.pdf`

Destination modules:

- `wiki/brands/`
- `wiki/campaigns/`
- `wiki/content/`
- `workflows/`

Status:

```text
OCR complete / awaiting case distillation
```

Recommended module split:

- GTM plan structure
- product launch narrative
- sports campaign structure
- final project / campaign case

### 5. Entertainment Sponsorship Decks

Source PDFs:

- `raw/files/网易云音乐2024CNY新春纪招商方案【灵感严选001ppt.com】.pdf`
- `raw/files/网易毕业歌会招商方案-唱响巴黎毕业歌会【灵感严选001ppt.com】.pdf`
- `raw/files/芒果TV《元气满满的哥哥》招商通案【www.001ppt.cn】.pdf`

Destination modules:

- `wiki/campaigns/`
- `wiki/content/`

Status:

```text
OCR complete / awaiting sponsorship deck pattern extraction
```

Recommended module split:

- sponsorship deck structure
- entertainment IP packaging
- brand partnership value language
- CNY / graduation / variety-show campaign packaging

### 6. Strategy / Branding / Marketing References

Source PDFs:

- `raw/files/Strategic Marketing Tactic - Developing Your Competitive Edge in Today's Market (2025). GBP Publications..pdf`
- `raw/files/EmotionalBranding.pdf`
- `raw/files/978-3-030-77083-9.pdf`
- `raw/files/qt6gx9v8r6.pdf`
- `raw/files/tesi.pdf`
- `raw/files/thomson_reuters_webinar_materials_022509.pdf`

Destination modules:

- `wiki/concepts/`
- `wiki/methods/`
- `wiki/reports/`

Status:

```text
OCR complete / awaiting concept extraction
```

Recommended module split:

- emotional branding
- strategic marketing tactics
- market / industry reference patterns
- research or thesis-derived concepts

### 7. Consumer / CSR / Industry Research

Source PDFs:

- `raw/files/CSR调研报告和用户参与设计报告.pdf`
- `raw/files/Consumer Valuation of Fuel Economy in the Australian Automobile M.pdf`
- `raw/files/1853954_Master_Thesis_Xinyi_Fan_May_2024.pdf`
- `raw/files/1241883_Tevi.pdf`
- `raw/files/apo-nid329561.pdf`
- `raw/files/EBSCO-FullText-2025_06_03.pdf`
- `raw/files/EBSCO-FullText-2025_06_03 (1).pdf`
- `raw/files/1-s2.0-S0301421512005162-main.pdf`
- `raw/files/1-s2.0-S1057740804701448-main.pdf`
- `raw/files/1-s2.0-S1361920914001515-main.pdf`
- `raw/files/WRAP_1472684-im-081215-marres__gerlitz_interface_methods_final.pdf`

Destination modules:

- `wiki/consumers/`
- `wiki/reports/`
- `wiki/methods/`

Status:

```text
OCR complete / awaiting selective distillation
```

Recommended module split:

- consumer valuation and decision behavior
- CSR and user participation
- thesis/research report patterns
- academic research methods

## Processing Priority

1. Ocoopa campaign modules: completed in this pass.
2. Advertising course spine: next best backbone for reusable marketing methods.
3. Audience/media research: useful for consumer insight and research methods.
4. GTM/campaign cases: useful after the campaign case template stabilizes.
5. Sponsorship decks: useful for partnership packaging and deck language.
6. Long strategy/reference PDFs: process selectively to avoid turning the wiki into summaries.

