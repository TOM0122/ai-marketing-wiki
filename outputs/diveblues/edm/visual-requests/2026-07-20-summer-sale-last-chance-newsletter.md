# Diveblues EDM 视觉需求：Summer Sale Last Chance Newsletter

> 内部视觉执行稿。基于既有 `Summer Sale Slot-Reel Newsletter` 做同一促销活动的结束前提醒。设计部门交付更新后的 Hero 静态源帧及必要适配；最终 GIF、live text、按钮、链接、tracking 和 footer 由 EDM / Shopify 搭建侧完成。

## 1. 项目基础信息

| 项目 | 内容 |
|---|---|
| 品牌 | Diveblues |
| EDM 类型 / 用途 | Newsletter；Summer Sale Last Chance 转化型提醒邮件 |
| 需求提交时间 | Missing Context |
| 预计发送时间 | Missing Context；必须安排在已核实截止日的前一天，才能使用 `tomorrow` |
| 目标市场 | 仅美国；沿用首发 Summer Sale 邮件 |
| 目标用户 / Segment | 沿用首发 Summer Sale 的 US DTC newsletter audience；具体活跃度与排除名单由发送侧确认 |
| 平台 | Shopify |
| 核心优惠 | Buy one fan, get the second 50% off |
| 折扣计算 | Discount applies to the item of equal or lesser value |
| 折扣应用 | Discount automatically applied at checkout |
| 对外时效表达 | `Ends tomorrow`；仅在发送日与真实截止日相差一天时可用 |
| 绝对截止时间 | Parent request 记录 `July 30, 2027, ET`，但年份与原发送排期冲突；准确日期、年份和 ET 时间均为 launch-check |
| 建议视觉宽度 | 750px；沿用首发促销邮件母版 |
| 设计部门新增交付 | 3 张 Last Chance Hero GIF 静态源帧 + Community 图片 / 版式适配（如原图不可直接复用） |
| 建议复用 | 首发邮件的 2 张单品模块图、1 张 Shop All 模块图、Logo / navigation 和整体配色系统 |
| EDM 搭建侧负责 | GIF 合成、正文、脚注、按钮、CTA、URL、热区、tracking、静态 fallback、footer 与上线 QA |
| 产品选择 | 沿用首发邮件最终选定的两款产品、颜色和组合；不为 Last Chance 临时更换产品 |
| 产品 / Hero 素材路径 | Missing Context |
| 主 CTA | `Shop the Sale` |
| 次 CTA | `Join the Facebook Group` |

## 2. 邮件定位、复用原则与责任边界

### 邮件定位

本封不是新的 Summer Sale 宣传，而是同一活动的最后提醒。用户应在第一屏立即理解三件事：

1. 活动即将结束。
2. 优惠仍是买一台风扇，第二台五折。
3. 现在应进入购买路径，不需要重新阅读活动介绍。

因此，本封应比首发邮件更短、更直接，减少解释模块，但必须保持促销识别连续性。

### 与首发邮件的关系

| 首发 Summer Sale | Last Chance Reminder |
|---|---|
| `SUMMER SALE` 宣布活动开始 | `LAST CHANCE` 宣布活动将结束 |
| 滚轴表现活动启动与产品选择 | 滚轴表现减速、接近停靠、最终锁定 |
| 正文解释活动机制 | 正文只重述 offer、截止状态和下一步 |
| 产品模块首次建立购买入口 | 复用同一产品入口，帮助快速决策 |
| Community 为品牌收尾 | Community 增加 Facebook Group 次级动作 |

### 资产复用原则

- 若两款产品、颜色、价格路径和 URL 均未改变，M3-M5 直接复用首发邮件产品模块，不重新设计。
- Last Chance 主要新增 M1 Hero 三帧和 M2 文案；这样既节省制作时间，也让用户识别为同一活动的后续提醒。
- 若商品、颜色或库存发生变化，必须由商品 / 运营侧确认后再替换，不由视觉部门自行判断。
- Community 图可复用已有授权生活图；只有在原图不支持文案留白或移动端裁切时才需要重新适配。

### 责任边界

视觉部门负责：

- 3 张同尺寸、同文字位置的 Last Chance Hero 静态源帧。
- 将原促销配色和产品素材适配到新 Hero。
- 复核原 M3-M5 是否可直接复用；只有确认需要时才导出适配版本。
- 选择 / 适配一张 Community 生活图，并给 live text 留区。

EDM / Shopify 搭建侧负责：

- 合成最终 GIF，设置帧时长、循环、压缩与静态 fallback。
- M2 正文、优惠脚注、主 CTA、Community 文案与次 CTA。
- URL、tracking、热区、自动折扣、截止日期、发送排期和 footer。
- 确保 `tomorrow` 在实际发送时间成立。

## 3. 整体模块结构

```text
M0 Logo / Navigation（复用）
  ↓
M1 Last Chance Hero GIF（设计交 3 张静态帧）
  ↓
M2 Urgency Transition + Shop the Sale（后台搭建）
  ↓
M3 Product 1 Image + CTA（优先复用）
  ↓
M4 Product 2 Image + CTA（优先复用）
  ↓
M5 Shop All Image + CTA（优先复用）
  ↓
M6 Facebook Community（已有图片适配 + live text）
  ↓
M7 Final CTA + Shopify Footer（后台搭建）
```

| 顺序 | 模块 | 设计部门 | EDM / Shopify 搭建 |
|---:|---|---|---|
| M0 | Logo / Navigation | 不新增；复用 | Logo、导航和链接 |
| M1 | Last Chance Hero GIF | 3 张完整静态源帧 | GIF、链接、alt、fallback |
| M2 | Urgency Transition | Hero 底部留干净衔接 | live text、脚注、主 CTA |
| M3 | Product 1 | 优先复用首发模块图 | 产品名、CTA、PDP 链接 |
| M4 | Product 2 | 优先复用首发模块图 | 产品名、CTA、PDP 链接 |
| M5 | Shop All | 优先复用首发集合图 | `Shop All Fans`、collection 链接 |
| M6 | Facebook Community | 复用 / 适配 1 张真实生活图 | Community copy、次 CTA、Facebook URL |
| M7 | Final CTA + Footer | 不作图 | 最终购买入口、社媒、Shopify 原生 footer |

## 4. Last Chance Hero GIF 三帧交付规范

### 4.1 固定不动的部分

三张静态源帧必须使用完全相同的：

- 750px 宽画布与最终高度。
- Hero 背景、ticker、标题位置、字号、行距、字重和安全区。
- 左右双产品滚轴列宽、中心线和遮罩范围。
- 固定文案和 offer 层级。
- 产品真实比例与两款产品的视觉重量。

固定文案不得随滚轴位移，否则 GIF 播放时会出现文字抖动。

### 4.2 三帧动作逻辑

| 帧 | 动作任务 | 构图要求 |
|---|---|---|
| Frame 01 / Locked Fallback | 最终锁定状态 | 两款产品完整停靠，`LAST CHANCE` 与完整 offer 一眼可读；必须能独立作为静态 fallback。 |
| Frame 02 / Rolling | 最后一次滚动 | 左右产品沿各自滚轴纵向位移，可一上一下；允许受控运动模糊，但仍能辨认产品。固定文字完全不动。 |
| Frame 03 / Near Lock | 即将停靠 | 一列已接近锁定，另一列仍露出下一格边缘，制造“时间即将结束”的减速感。随后循环回 Frame 01 完成锁定。 |

GIF 搭建时，Frame 01 的停留时间应明显长于滚动帧，让用户能够读完 offer；具体时长由 EDM 搭建侧决定。

### 4.3 Hero 固定文案

主标题：

```text
LAST CHANCE
```

优惠信息：

```text
BUY ONE,
GET THE SECOND 50% OFF
```

促销 ticker：

```text
ENDS TOMORROW • SECOND FAN 50% OFF •
```

执行要求：

- `LAST CHANCE` 是第一层级，完整 offer 是第二层级，两款产品是第三层级。
- `50% OFF` 不得脱离 `GET THE SECOND` 单独成为唯一大字。
- `ENDS TOMORROW` 只在排期核实后使用；设计稿应保留可编辑文字层，以防发送日期变化。
- 不在 Hero 增加具体倒计时数字、库存数量、`almost sold out`、`final hours` 或未经确认的时间点。
- Hero 内不做图片按钮；主 CTA 放在 M2，并使用真实 Shopify 按钮。

### 4.4 文件交付

- 必交：`LastChance_Hero_Frame_01`、`LastChance_Hero_Frame_02`、`LastChance_Hero_Frame_03`。
- 三张必须同尺寸并逐像素对齐固定文案。
- `Frame_01` 同时作为静态 fallback 版本。
- 保留可编辑 `ENDS TOMORROW`、`LAST CHANCE` 和 offer 文字层。
- 最终文件格式、GIF 帧时长、循环次数与压缩标准由设计 / 搭建团队确认。

## 5. 视觉调性总要求

### 核心关键词

- Urgent, not frantic
- Direct
- Product-led
- Cool
- Bright
- High-contrast
- Slowing down
- Locked decision moment
- Clear offer hierarchy

### 配色

沿用首发邮件，确保 campaign continuity：

- 主底色：white / icy white。
- 主促销色：cobalt blue / electric blue。
- 辅助色：icy cyan / aqua。
- 主文字：deep navy / black。
- 紧迫点缀：沿用首发邮件已经选择的 acid lime 或 coral，不新增第二种暖色。

Last Chance 的紧迫感来自标题、减速动作和信息压缩，不通过全红背景、黑红警告条或高温橙色制造压迫。

### 字体与排版

- 沿用首发邮件的粗体无衬线标题系统。
- `LAST CHANCE` 应比 `SUMMER SALE` 更短、更大，但不能压缩到字形变形。
- 标题、offer、产品之间保持明确层级，不增加促销印章、倒计时卡、多个角标和密集贴纸。
- Ticker 的移动感来自重复节奏，不使用难读的极窄字体或倾斜字。

### 产品处理

- Hero 与产品模块必须沿用真实产品素材。
- 两款产品视觉重量接近，不能让第二款看起来像免费赠品。
- 滚动帧只改变纵向位置、角度或颜色格，不改变产品尺寸、透视和光线逻辑。
- 不新增未经确认的产品、配件、功能状态或颜色。

## 6. 模块视觉需求表

### M0 Logo / Navigation

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 邮件顶部。 |
| 基础信息 | 直接复用首发 Summer Sale 的 Diveblues Logo / navigation。 |
| 核心信息 | 确认品牌身份后立即进入 Last Chance offer。 |
| 设计重点 | 不增加新的 alert bar 或第二套促销导航；与 Hero 的 icy white / cobalt 系统自然衔接。 |
| 视觉主角 | Diveblues Logo。 |
| 背景环境 | White / icy white，不透明背景。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 沿用搭建配置。 |
| Prompt 指向 | 不需要。 |

### M1 Last Chance Hero GIF Source Frames

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 首屏；Logo / navigation 下方。 |
| 基础信息 | 设计交 3 张 750px 宽同尺寸静态帧；两款产品沿用首发邮件；最终 GIF 由 EDM 侧制作。 |
| 核心信息 | Summer Sale 明天结束，现在是使用第二台五折优惠的最后提醒。 |
| 设计重点 | 1. 固定 `LAST CHANCE` 与完整 offer。<br>2. 双滚轴从滚动进入锁定。<br>3. `ENDS TOMORROW` ticker 可编辑。<br>4. Frame 01 单独成立。<br>5. 三帧文字逐像素一致。<br>6. 不加倒计时数字、库存或额外 badge。 |
| 视觉主角 | 第一层：`LAST CHANCE`；第二层：完整 offer；第三层：两款真实产品。 |
| 背景环境 | 抽象冷亮促销画面，不使用人物或夏日生活场景。 |
| 视觉调性 | Slot-reel slowing to a stop、bold retail poster、cool high contrast。 |
| 图片内文案 | `LAST CHANCE`<br>`BUY ONE, GET THE SECOND 50% OFF`<br>`ENDS TOMORROW • SECOND FAN 50% OFF •` |
| CTA / 点击 | Hero 内没有按钮；链接和热区由搭建侧处理。 |
| Prompt 指向 | Prompt 1-3。 |

### M2 Urgency Transition

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | Hero 下方。 |
| 基础信息 | 不需要视觉部门单独作图；使用 Shopify live text + 真实按钮。 |
| 核心信息 | 活动明天结束，重述 offer 并立即进入购买路径。 |
| 设计重点 | Hero 底部干净收住，接 white / icy white live-text 区。正文只保留短标题、两句说明、脚注和一个主按钮。 |
| 视觉主角 | `Going, going... gone tomorrow!` 与 `Shop the Sale`。 |
| 背景环境 | White / icy white，最多使用一条低噪音 cobalt rule 或 ticker 延续线。 |
| 视觉调性 | Direct、urgent、high readability。 |
| Live 文案 | 见第 7 节最终版。 |
| CTA / 点击 | 主 CTA：`Shop the Sale`；URL 和 tracking 由搭建侧补充。 |
| Prompt 指向 | 不需要。 |

### M3 Product 1 Image

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 第一个产品购买入口。 |
| 基础信息 | 优先复用首发邮件最终产品模块图。产品、颜色和素材必须保持一致。 |
| 核心信息 | 快速进入第一款已选产品，不重新解释功能。 |
| 设计重点 | 如果原图可用，不新增设计；只检查裁切、移动端识别和当前 URL 是否仍有效。需要适配时继续保留产品在左、右侧 live-text / CTA 安全区。 |
| 视觉主角 | 首发邮件的 Product 1。 |
| 背景环境 | 沿用原 cold high-contrast color field。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 沿用 / 更新 `Shop [Product Name]` 与 PDP 链接；搭建侧负责。 |
| Prompt 指向 | 不重新生图；使用首发真实素材。 |

### M4 Product 2 Image

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 第二个产品购买入口。 |
| 基础信息 | 优先复用首发邮件最终产品模块图。 |
| 核心信息 | 提供第二种选择，并保持与 Product 1 同级。 |
| 设计重点 | 如果原图可用，不新增设计；只检查库存 / 商品状态、裁切和 URL。需要适配时继续保留产品在右、左侧 live-text / CTA 安全区。 |
| 视觉主角 | 首发邮件的 Product 2。 |
| 背景环境 | 沿用原 campaign color field。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 沿用 / 更新 `Shop [Product Name]` 与 PDP 链接；搭建侧负责。 |
| Prompt 指向 | 不重新生图；使用首发真实素材。 |

### M5 Shop All Image

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 两个单品之后。 |
| 基础信息 | 优先复用首发邮件 Shop All 图。 |
| 核心信息 | 用户仍可浏览完整活动商品，不被两个单品限制。 |
| 设计重点 | 只检查原产品组合是否仍在活动范围内；若活动商品变化，必须由商品 / 运营侧给出更新清单。 |
| 视觉主角 | 原双产品或多色产品组合。 |
| 背景环境 | 沿用首发邮件的第三个冷亮色块。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | `Shop All Fans`；collection URL 由搭建侧确认。 |
| Prompt 指向 | 不重新生图；使用首发真实素材。 |

### M6 Facebook Community

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 产品入口之后、final CTA / footer 之前。 |
| 基础信息 | 复用一张已有授权 Community / lifestyle 图片；文案和按钮使用 live text。具体图片路径为 Missing Context。 |
| 核心信息 | 促销结束后，用户仍可通过 Facebook Group 继续参与 Diveblues 社区。 |
| 设计重点 | 1. 选择真实人物在旅行、出街、朋友或家庭夏日活动中的画面。<br>2. 产品自然出现，不再强调折扣。<br>3. 为一行正文和次按钮保留干净色带。<br>4. 影调保持清凉、干净、明亮。<br>5. 不在图片中画礼盒、优惠券或具体赠品。 |
| 视觉主角 | 真实人物关系和生活动作。 |
| 背景环境 | 真实夏日出行 / 社区场景，避免硬广棚拍。 |
| 视觉调性 | Community-led、candid、cool and bright。 |
| Live 文案 | `Join our community to unlock an exclusive Welcome Gift.` |
| CTA / 点击 | 次 CTA：`Join the Facebook Group`；视觉权重低于 `Shop the Sale`。 |
| Launch check | 上线前确认 Welcome Gift 内容、领取资格、触发方式、发放方式、适用地区、库存 / 有效期和对应群组说明。 |
| Prompt 指向 | Prompt 4。 |

### M7 Final CTA + Shopify Footer

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 邮件底部。 |
| 基础信息 | 不需要视觉部门作图。 |
| 核心信息 | 结束购买路径并保留 Shopify 合规页脚。 |
| 设计重点 | 不新增第三个主动作；退订、实体地址和法务信息必须使用原生 footer。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 是否重复 `Shop the Sale` 由搭建侧根据邮件长度决定。 |
| Prompt 指向 | 不需要。 |

## 7. 英文文案最终版

### Subject / Preheader

| 位置 | Final English Copy | 实现与校验 |
|---|---|---|
| Subject | `Last Chance: Summer Sale Ends Tomorrow! ☀️` | Shopify live subject；仅在实际截止日前一天发送 |
| Preheader | `Buy one, get the second 50% OFF—before it's gone!` | Shopify live preheader；offer 必须与活动配置一致 |

### Hero 图片文案

```text
LAST CHANCE

BUY ONE,
GET THE SECOND 50% OFF

ENDS TOMORROW • SECOND FAN 50% OFF •
```

### Backend Transition

```text
Going, going... gone tomorrow!

Buy one fan and get the second 50% OFF before our Summer Sale ends tomorrow.

Discount automatically applied at checkout.

*Discount applies to the item of equal or lesser value. Offer valid through [verified date and time] ET.

Shop the Sale
```

### Product CTA Placeholders

- `Shop [Product 1]`
- `Shop [Product 2]`
- `Shop All Fans`

产品名、URL 和活动资格必须沿用实际 Shopify 配置，视觉稿不编造。

### Community

```text
Join our community to unlock an exclusive Welcome Gift.

Join the Facebook Group
```

### Alt / Fallback 建议

- Hero: `Last chance: buy one fan and get the second 50% off before the Summer Sale ends tomorrow.`
- Product 1: `Shop a featured Diveblues fan before the Summer Sale ends.`
- Product 2: `Shop another featured Diveblues fan before the Summer Sale ends.`
- Shop All: `Explore all eligible Diveblues fans in the Summer Sale.`
- Community: `Join the Diveblues Facebook community for an exclusive Welcome Gift.`

### 时效替换规则

如果邮件不能在截止日前一天发送，以下位置必须同步替换，不能只改 Subject：

- Subject 的 `Ends Tomorrow`
- Preheader 的 `before it's gone`
- Hero ticker 的 `ENDS TOMORROW`
- Transition headline 的 `gone tomorrow`
- Transition body 的 `ends tomorrow`
- Offer footnote 的绝对日期和 ET 时间

## 8. 参考图生成提示词

### 使用说明

- Prompt 仅用于更新 Hero 构图和 Community mood，不替代首发邮件的真实产品资产。
- 精确 Logo、产品、英文文案和按钮由设计师后期完成。
- 三张 Hero 帧必须从同一源文件派生，不能分别生图后强行拼接。
- 产品模块优先复用，不提供重复生图 prompt。

### Prompt 1：Hero Frame 01 / Locked Fallback

```text
Bold vertical last-chance sale email hero for a modern portable fan brand, exact 750-pixel-wide campaign canvas, two accurate real portable fan product cutouts fully stopped and aligned side by side in two vertical slot-reel columns, icy white background, cobalt blue and electric blue ticker bands, one restrained acid-lime or coral accent matching the existing campaign, large stable headline-safe area for “LAST CHANCE”, clear second-level offer-safe area for “BUY ONE, GET THE SECOND 50% OFF”, both products at equal visual weight, crisp high-contrast retail poster design, urgent but controlled, strong mobile readability, no people, no lifestyle scene, no rendered text, no fake countdown numbers, no stock warning, no red-black panic palette, no orange-dominant design, no fake logos, no buttons, no extra accessories, no distorted product geometry.
```

### Prompt 2：Hero Frame 02 / Final Roll

```text
Second source frame for the exact same 750-pixel-wide last-chance slot-reel email hero, identical background, ticker bands, headline-safe area, offer-safe area, reel widths and product scale as the locked fallback, left portable fan moving upward and right portable fan moving downward inside their fixed vertical reel masks, controlled motion blur only on the products, a small portion of the next color or angle entering from the reel edge, all fixed typography areas perfectly stable and empty for later design, icy white, cobalt blue, aqua and one existing campaign accent, energetic final-roll motion, no people, no text, no countdown timer, no warning icons, no orange palette, no product distortion.
```

### Prompt 3：Hero Frame 03 / Near Lock

```text
Third source frame for the exact same 750-pixel-wide last-chance slot-reel email hero, identical campaign background, ticker, copy-safe areas and reel geometry, one accurate portable fan almost fully locked into position while the second reel is only slightly offset with the next product edge still visible, motion nearly stopped, both products clearly recognizable and balanced, visual tension of a decision window about to close, icy white and cobalt-blue campaign palette with restrained aqua and one accent, bold clean mobile-first retail poster, no people, no rendered text, no clock, no inventory claim, no red alert graphics, no orange-dominant palette, no fake logo, no distorted product structure.
```

### Prompt 4：Facebook Community Lifestyle Image

```text
Vertical candid lifestyle photograph for the community section of a cool bright summer email, a small group of adult friends in a real outdoor summer moment, walking, talking and naturally using or carrying compact portable fans, product visible but secondary to the human relationship, clear daylight, realistic skin tones, clean blue and aqua color accents, social-native documentary energy with polished commercial quality, participant point of view, generous stable space for live community copy and a secondary button below or beside the image, no text rendered in the image, no gift box, no coupon, no discount sign, no staged group pose, no people holding products toward the camera, no brand logos, no AI-distorted fan geometry, no warm orange cast.
```

### Prompt 5：整封 Last Chance Mood Reference

```text
Vertical 750-pixel-wide art-direction board for a last-chance summer sale email, campaign continuity with an earlier slot-reel launch email, short logo strip, large cool high-contrast hero with two portable fan reels slowing into a locked position, stable headline and offer-safe areas, concise white or icy-blue live-copy transition with one primary sale button, three reused high-contrast product-entry modules, then one candid community lifestyle image with a quieter Facebook group call-to-action area, icy white, cobalt blue, electric blue and aqua palette with one restrained campaign accent, bold mobile-first retail hierarchy, urgent but not frantic, no rendered text, no exact recreation of another brand email, no red-black alarm aesthetic, no countdown card stack, no dense badges, no orange-dominant palette, no AI-generated replacement products.
```

## 9. Offer / IP / 设计避坑

### Offer 表达

- 必须完整写成 `Buy one, get the second 50% off` 或当前批准的大写版本。
- 不允许把 `50% OFF` 单独放大到可被理解为全场五折。
- 必须保留已确认的 equal-or-lesser-value 条件。
- `automatically applied at checkout` 上线前必须与 Shopify 真实折扣配置和 QA 一致。
- `ends tomorrow` 必须与发送日期、截止日期、年份、时区和具体时间一致。
- 不新增 `final hours`、`almost gone`、`selling fast`、`low stock`、倒计时数字或售罄承诺。
- 不新增叠加规则、次数限制、指定 SKU / 颜色条件或库存例外。

### Welcome Gift

- 当前只使用用户给定的 `exclusive Welcome Gift`。
- 不在图中展示具体礼物、金额、折扣码、礼包数量或领取倒计时。
- 若实际群组机制不是加入后可获得，必须在发送前修改文案，不能只靠脚注补救。

### IP / Reference 边界

- 延续首发邮件已经确定的抽象 slot-reel 逻辑和 Diveblues 配色。
- 不重新引入 Away Logo、字体、橙色系统、旅行箱、原促销条或原模块图。
- 不在图中出现第三方品牌 Logo 或可识别产品。

### 设计避坑

- 不让固定文案在三帧中跳动。
- 不把 Last Chance 变成全红警告页面。
- 不在 Hero 同时加入大标题、倒计时、多个 badge、脚注和 CTA。
- 不为 Last Chance 临时更换首发邮件产品，破坏 campaign continuity。
- 不重新生图产品模块，除非真实产品 / 活动范围发生变化。
- 不让 Community CTA 与 `Shop the Sale` 同级。
- 不用图片替代 Shopify 原生退订、实体地址和法务 footer。

## 10. Missing Context / Launch Check

| 项目 | 状态 | 对执行的影响 |
|---|---|---|
| 设计交付时间 | Missing Context | 不阻塞出方向；进入排期前补充 |
| 预计发送日期 / 时间 | Missing Context | 阻塞 `tomorrow` 正式发送 |
| Offer 绝对截止日期、年份与 ET 时间 | launch-check | 阻塞 `ends tomorrow`、ticker 和 footnote 正式发送 |
| Shopify 自动折扣已配置并通过 QA | launch-check | 阻塞 `automatically applied at checkout` 正式发送 |
| 首发邮件最终产品名 / SKU / 颜色 | Missing Context | 设计应从首发资产中继承，不重新选型 |
| Hero / 产品模块真实素材路径 | Missing Context | 阻塞最终视觉导出 |
| Product 1 / Product 2 / Shop All URL | EDM 搭建时提供 | 不阻塞设计；阻塞上线 |
| Product 1 / Product 2 当前库存与活动资格 | launch-check | 决定模块能否直接复用 |
| Hero GIF 最终时长、循环、压缩 | EDM 搭建侧确认 | 不阻塞静态帧设计 |
| Community 图片路径与授权 | Missing Context | 阻塞 M6 最终图 |
| Facebook Group URL | Missing Context | 阻塞次 CTA 上线 |
| Welcome Gift 内容、资格与发放机制 | launch-check | 阻塞带该承诺的正式发送 |
| Final CTA / footer 形式 | EDM 搭建侧确认 | 不在本次视觉作图范围 |

## 11. Source Notes

- 本稿直接使用用户当前提供的 Subject、Preheader、Hero、过渡段和 Facebook Group 文案。
- Parent campaign source: `/Users/mingjunliu/ai-marketing-wiki/outputs/diveblues/edm/visual-requests/2026-07-13-summer-sale-slot-gif-newsletter.md`。
- Parent campaign 已确认 offer rule：`Discount applies to the item of equal or lesser value. Discount automatically applied at checkout.`
- Parent campaign 记录的截止信息为 `July 30, 2027, ET`，但与原 2026 发送时间存在冲突；本稿不擅自修正年份，继续列为 launch-check。
- Diveblues 清凉、干净、明亮与动态调性来自 `/Users/mingjunliu/ai-marketing-wiki/wiki/brands/diveblues-2026-brand-reshape.md`。
- EDM 促销、CTA、移动端与图片邮件边界参考：
  - `/Users/mingjunliu/ai-marketing-wiki/outputs/edm/standards/2026-06-10-edm-visual-brief-v1.md`
  - `/Users/mingjunliu/ai-marketing-wiki/outputs/edm/standards/2026-06-10-edm-copy-standards-v1.md`
- 页脚边界参考 `/Users/mingjunliu/ai-marketing-wiki/wiki/edm/edm-footer-kit.md`。
- 未使用新外部数据、行业数字或外部 URL。
