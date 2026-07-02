# Diveblues EDM 视觉需求：Sticker Bomb Team Color Newsletter

> 内部视觉需求稿。外发图片内文案为英文；中文用于对齐设计意图。  
> 本稿服务 Diveblues 2026-07-14 预期发送的 newsletter。视觉参考用户提供的 Stanley 贴纸化邮件截图，但不复刻其具体活动机制、品牌元素或原图贴纸。

## 1. 项目基础信息

| 项目 | 内容 |
|---|---|
| Brand | Diveblues |
| EDM 名称 | Sticker Bomb Team Color Newsletter |
| 需求提交时间 | 2026-07-02 |
| 预期发布时间 | 2026-07-14 |
| 邮件类型 / 用途 | Newsletter；互动 / 转化导向，用品牌内容包装颜色选择入口 |
| 平台 | Shopify |
| 目标用户 / segment | 本视觉需求不提供；后续搭建 EDM 时直接使用实际分群 |
| 跳转 URL / 活动页 / collection | 本视觉需求不提供；后续搭建 EDM 时直接绑定 |
| 出图范围 | 只做 2 个图片模块：贴纸主图、产品展示模块 |
| 非出图范围 | 两个图片模块后的 live button + 页脚；这部分无需设计成图片 |
| 点击方式 | 两个图片模块均作为点击热区；图片内按钮是视觉 CTA 提醒 |
| 产品 | Diveblues 产品；具体型号 / SKU 由后续搭建与设计素材决定 |
| 产品颜色 | 展示 4 个产品；颜色由设计师定夺，可参考热门球队相关色彩：深蓝、红、白、红黄 / 金色点缀 |
| 图片尺寸 | 宽度、高度、首屏安全区由设计师自行设计；本需求不锁死尺寸 |
| 外发语言 | 英文 |
| 是否有优惠 | 没有；不写折扣、赠品、免邮、free sticker pack 或 surprise |

## 2. 邮件定位与点击目标

这封 EDM 的任务不是讲复杂产品卖点，而是用 **Sticker Bomb / Doodle Art** 的球迷贴纸风制造点击欲，把用户带到 `Shop by color` 的选择动作。

核心策略：

- 第一眼像一张球迷贴纸墙：大标题、球迷图形、足球符号、风扇贴纸、冰感元素一起形成轻快氛围。
- 视觉上承接用户提供的 Stanley 参考：白底、强标题、贴纸围绕主文案和 CTA 分布。
- 内容上不做免费贴纸包、不做购买条件、不做真实球队联名。
- 点击目标统一指向后续搭建时绑定的活动页 / collection / shop-by-color 入口。
- 复盘时优先看 CTR、落地页点击、转化、RPE、退订；打开率只做辅助信号。

## 3. 整体模块结构

本封采用 **模块化 live text + image 混排**，但本视觉需求只负责两个图片模块。

| 模块 | 是否需要设计出图 | 邮件位置 | 模块任务 | 点击 |
|---|---|---|---|---|
| M1 Sticker Hero 主图 | 是 | 首屏 | 用贴纸化球迷视觉和大标题建立情绪与点击欲 | 整张图点击热区 |
| M2 Product Display / Shop by color | 是 | Hero 下方 | 展示 4 个颜色产品，把“球迷贴纸”转成“按颜色逛产品” | 整张图点击热区 |
| M3 Live Button | 否 | 两个图片模块后 | 用 HTML / Shopify live button 再给一次清楚动作 | live button 点击 |
| M4 Footer | 否 | 邮件底部 | 使用 Shopify 原生 footer + 固定联系信息边界 | 原生页脚 |

## 4. EDM 技术与实现注意事项

| 项目 | 要求 |
|---|---|
| 平台 | Shopify |
| 结构 | 模块化 live text + image 混排；本次只交付两张图片模块的视觉需求 |
| 图片尺寸 | 宽度、高度由设计师决定；需保证移动端首屏可读和邮件加载可控 |
| Hero 文字 | Hero 的主文案和按钮都做到图片里，但 subject / preheader / alt text 应保留 live / fallback |
| 图片点击 | M1、M2 均为点击热区；若后续切片，每个可点击切片应链接同一目标，除非官网同事另行设置 |
| Live button | 两张图后加一个 live button：`Shop by color`；无需做成图片 |
| 页脚 | 本需求不设计页脚图片；Shopify 原生 footer 负责退订与实体地址 |
| Dark mode | 贴纸图建议使用非透明背景或加白 / 冰白底兜底，避免暗色模式下贴纸白边脏乱 |
| Alt text | 需要配置；建议见第 7 节 |
| 文件大小 / 压缩 | Missing Context：由设计师与官网 / EDM 执行同事确认 |
| URL / tracking | 本视觉需求不提供；后续搭建 EDM 时直接绑定 |

## 5. 视觉调性总要求

### 5.1 风格定义

中文执行名：**球迷贴纸轰炸风 / Sticker Bomb Fan-Color EDM**。

关键词：

```text
sticker bomb / doodle art / football fan culture / bright white layout / playful / clickable / cool / clean / team color / fan energy / product sticker cutout
```

### 5.2 Diveblues 品牌要求

- 仍然要清凉、干净、明亮，不能做成脏乱涂鸦墙。
- 色彩可以更响亮，但底色要留白，信息区要清楚。
- 人和产品应像真实球迷生活的一部分，而不是静态货架图。
- 产品可以贴纸化，但要保留识别度，不要画成儿童玩具。

### 5.3 贴纸元素建议

可用贴纸方向：

- generic football fans
- soccer ball / cleats / scarf / megaphone / ticket stub
- Diveblues fan sticker / airflow sticker / ice burst / freeze line
- color swatches / color labels / small product cutouts
- generic rooster, Pampas eagle, three stylized lions, Spanish cathedral / arch sticker

球队相关元素只作为 **色彩和文化符号灵感**，不是官方授权素材。

## 6. 模块视觉需求表

### M1. Sticker Hero 主图

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 首屏 Hero。用户打开邮件第一眼看到的贴纸主图。 |
| 基础信息 | 图片内包含主标题、supporting line 和视觉 CTA 按钮；整张图片为点击热区。图片宽高由设计师决定。 |
| 核心信息 | 这是一封给球迷的清凉颜色入口：rep your team, rep your passion, then shop by color. |
| 设计重点 | 1. 参考附件的白底贴纸化结构：大标题在左 / 中部清楚可读，贴纸围绕标题和按钮分布。<br>2. 贴纸不要铺满整张图，必须保留白底 / 冰白底呼吸感。<br>3. 风扇可以做成 1-2 个贴纸化产品 cutout，配合风线、冰晶、freeze burst。<br>4. 球迷贴纸要有不同性格：举围巾、吹喇叭、踩球、跳起庆祝、车贴 / 球票等，但不出现真实球队。<br>5. 图片内 CTA 按钮做成 sticker patch / bumper sticker，而不是普通电商按钮。 |
| 视觉主角 | 大标题 + 球迷贴纸群 + Diveblues 风扇贴纸。产品不是唯一主角，但必须能被看见。 |
| 背景环境 | 白底 / 冰白底；可加入轻微纸张纹理、贴纸阴影、手绘线条、足球路径线。不要做复杂球场背景。 |
| 视觉调性 | 明亮、轻快、贴纸感、年轻、有点击欲；多彩但不脏乱。 |
| 图片内文案 | `Rep Your Team, Rep Your Passion!`<br>`0% heat, 100% passion.`<br>`Bring the freeze to your side before the final whistle.`<br>按钮：`Shop by color` |
| CTA / 点击 | 图片内按钮只是视觉 CTA；整张 Hero 图点击跳转。 |
| Prompt 指向 | Prompt 1、Prompt 3。 |

### M2. Product Display / Shop by color

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | Hero 下方的产品展示模块。 |
| 基础信息 | 展示 4 个 Diveblues 产品，强调 `Shop by color`。产品颜色由设计师定夺。整张图片为点击热区。 |
| 核心信息 | 用户可以按自己支持的颜色 / 情绪选择 Diveblues 产品。 |
| 设计重点 | 1. 做成 4 个产品贴纸卡 / 产品 cutout，不要做白底电商货架。<br>2. 每个产品周围配一个对应的球迷贴纸符号，让产品颜色与球迷情绪发生关系。<br>3. 建议颜色灵感：深蓝（France-inspired）、红色（Portugal-inspired）、白色（England-inspired）、红黄 / 金色点缀（Spain-inspired）。<br>4. 色彩只做灵感，不画官方球衣、队徽、国旗或真实队名。<br>5. 产品要比 Hero 更清楚；四个产品的大小、间距、阴影要统一，便于移动端浏览。 |
| 视觉主角 | 4 个 Diveblues 产品 cutout / 产品贴纸卡。 |
| 背景环境 | 白底 / 冰白底，搭配少量 color swatch、球票、贴纸边、风线；不要塞满文字。 |
| 视觉调性 | 像一张可逛的颜色贴纸页：清楚、明亮、产品可识别、颜色有差异。 |
| 图片内文案 | `Shop by color`<br>小字可选：`Pick your side. Bring the freeze.` |
| CTA / 点击 | 整张产品展示图点击跳转；产品单独分区点击不是本需求要求，除非官网同事后续决定做热区拆分。 |
| Prompt 指向 | Prompt 2、Prompt 3。 |

### M3. Live Button + Footer（无需做图）

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 两个图片模块之后。 |
| 基础信息 | 使用 Shopify / HTML live button 和原生 footer，不作为图片交付。 |
| 核心信息 | 在图片之后给用户一个清楚、可访问、可追踪的点击动作。 |
| 设计重点 | live button 文案与图片内 CTA 保持一致；按钮样式清爽，不抢贴纸主视觉。 |
| 图片内文案 | 无需做图。live button：`Shop by color` |
| CTA / 点击 | live button 点击跳转；URL 后续搭建 EDM 时绑定。 |
| 页脚 | 固定信息参考 `edm-footer-kit.md`；Shopify 原生 footer 提供退订与实体地址。 |

## 7. 图片内英文文案最终版

### 邮件外层 live text

| 位置 | 文案 |
|---|---|
| Subject | `Rep Your Team, Rep Your Passion!` |
| Preheader | `Loud graphics for the ultimate fans. Tap in!` |

### 图片内文案

| 模块 | 文案 |
|---|---|
| M1 Hero headline | `Rep Your Team, Rep Your Passion!` |
| M1 Supporting line | `0% heat, 100% passion.` |
| M1 Body line | `Bring the freeze to your side before the final whistle.` |
| M1 Image CTA | `Shop by color` |
| M2 Product heading | `Shop by color` |
| M2 Optional line | `Pick your side. Bring the freeze.` |
| M3 Live button | `Shop by color` |

### Alt text 建议

| 模块 | Alt text |
|---|---|
| M1 | `Diveblues sticker-style soccer fan artwork with the message Rep Your Team, Rep Your Passion and a Shop by color call to action.` |
| M2 | `Four Diveblues products shown as colorful fan-inspired sticker cards with a Shop by color message.` |

文案说明：

- `0% heat` 是情绪化创意表达，不应扩写为可量化降温 claim。
- 如内部合规希望更保守，可把 `0% heat, 100% passion.` 替换为 `All passion. Less heat.`。
- 不写 `free sticker pack`、`limited gift`、`official team`、`World Cup` 等未经确认或可能涉及 IP / 活动承诺的表达。

## 8. 参考图生成提示词

使用说明：

- 生成图只做视觉参考，最终文字由设计师手动排版。
- 不要让生图工具生成可读品牌字、官方队名、官方队徽、真实国旗、球员肖像。
- 不要出现 Stanley logo、Stanley cup 产品轮廓或附件原图里的具体贴纸。

### Prompt 1：Sticker Hero 主图

```text
Email newsletter hero image in a clean sticker bomb and doodle art style for a portable cooling fan brand, bright white or icy white background, large empty copy-safe area for headline and CTA, playful soccer fan stickers arranged around the center, generic football fans cheering, scarves, soccer balls, cleats, megaphones, ticket stubs, airflow lines, ice burst shapes, one or two portable fan product cutout stickers, cool and bright Diveblues mood, colorful but not cluttered, sticker shadows, paper texture, crisp vector-doodle mix, modern sports fan culture, mobile-friendly composition, no official team logos, no real players, no official jerseys, no flags, no FIFA or World Cup marks, no Stanley products, no readable text generated by AI.
```

### Prompt 2：Shop by color 四产品展示模块

```text
Email product display module in a clean sticker-sheet layout, four portable cooling fan product cutouts presented as colorful sticker cards, each product paired with a generic soccer fan culture icon, deep navy color inspiration, bright red color inspiration, clean white color inspiration, red and gold accent color inspiration, color swatches, ticket stub stickers, airflow doodles, icy white background, balanced grid, product clearly visible, playful but premium, mobile-friendly spacing, Shopify email module feel, no white-background ecommerce shelf look, no official team logos, no real flags, no official jerseys, no player likeness, no copyrighted mascots, no Stanley products, no readable text generated by AI.
```

### Prompt 3：贴纸素材补充页

```text
Sticker asset sheet for a soccer fan themed email campaign, generic rooster sticker, generic Pampas eagle sticker, three stylized lions sticker, Spanish cathedral arch or tile-inspired sticker, soccer ball, scarf, megaphone, ticket stub, bumper sticker, portable fan sticker, airflow and freeze icons, bright clean white background, bold sticker outlines, playful doodle art, cool blue and bright accent colors, no official crests, no national flags, no federation badges, no team uniforms, no real player likeness, no trademarked characters, no readable text generated by AI.
```

## 9. IP / 合规 / 设计避坑

### 可用

- 泛化球迷、泛化球队颜色、虚构球迷人物。
- 足球、球鞋、围巾、喇叭、球票、车贴、贴纸边框、风线、冰晶。
- 泛化文化符号：公鸡、鹰、三只狮子、教堂 / 拱门 / 瓷砖纹样。
- 产品贴纸 / 产品 cutout。

### 不可用，除非后续确认授权

- FIFA / World Cup / Club World Cup / 联赛 / 俱乐部官方资产。
- 真实球队 logo、队徽、球衣、号码组合、官方 slogan。
- 国家队官方球衣或精确国旗复刻。
- 真实球员 / 名人肖像。
- Stanley 商标、产品轮廓、活动文案结构或原图贴纸直接复刻。
- 任何暗示“官方合作”“官方球队颜色”“官方授权”的表达。

### 设计避坑

- 不要把贴纸铺满导致移动端无法读标题。
- 不要把产品做得太小，M2 产品必须清楚可识别。
- 不要使用红金大促风、黑五风或过重折扣感。
- 不要把 `Shop by color` 做成多个同级 CTA；本封一个主动作即可。
- 不要让图中文字全部依赖生图输出，最终文案必须由设计师排版。

## 10. Missing Context / Not Required

### Not Required For This Visual Request

- 目标用户 / segment。
- 跳转 URL / 活动页 / collection。
- 具体 EDM 搭建配置。

以上信息后续搭建 EDM 时直接使用，不在本视觉需求里补。

### Missing Context

- 最终 4 个产品 SKU / 产品素材路径。
- 最终 4 个产品颜色 / 官方色名。
- 图片最终宽度、高度、文件大小限制。
- Shopify 内是否拆分点击热区或只做整图点击。
- `0% heat` 是否需要合规保守替换。

## 11. Source Notes

- 用户提供的 Stanley 截图仅作为视觉参考，不作为外部事实来源，也不复刻其具体活动机制。
- Diveblues 品牌方向来自 `/Users/mingjunliu/ai-marketing-wiki/wiki/brands/diveblues-2026-brand-reshape.md`：生活参与者、清凉、干净、明亮、动态。
- EDM 视觉与文案规则来自 `2026-06-10-edm-visual-brief-v1.md` 与 `2026-06-10-edm-copy-standards-v1.md`：移动端优先、CTA 清楚、避免未确认 claim、避免把 DTC EDM 做成硬促销 / 招商物料。
- 页脚固定信息来自 `/Users/mingjunliu/ai-marketing-wiki/wiki/edm/edm-footer-kit.md`；Shopify 原生 footer 提供退订与实体地址。
