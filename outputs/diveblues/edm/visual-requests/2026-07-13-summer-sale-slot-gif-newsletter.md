# Diveblues EDM 视觉需求：Summer Sale Slot-Reel Newsletter

> 内部视觉执行稿。设计部门交付静态源图；最终 GIF、正文、按钮、链接和页脚由 EDM / Shopify 搭建侧完成。

## 1. 项目基础信息

| 项目 | 内容 |
|---|---|
| 品牌 | Diveblues |
| EDM 类型 / 用途 | Newsletter；Summer Sale 转化型邮件 |
| 需求提交时间 | 2026-07-13 |
| 预计发布时间 | 2026-07-24 |
| 目标市场 | 仅美国 |
| 平台 | Shopify |
| 核心优惠 | Buy one fan, get the second 50% off |
| 折扣计算 | Discount applies to the item of equal or lesser value |
| 折扣应用 | Discount automatically applied at checkout |
| 截止信息 | 用户提供 `July 30, 2027, ET`；精确时间未提供，且年份需 launch-check |
| 设计部门交付 | 3 张 Hero GIF 静态源帧 + 2 张单品模块图 + 1 张 Shop All 模块图 + 1 张已有 Community 图片适配裁切 |
| EDM 搭建侧负责 | GIF 合成、过渡正文、脚注、按钮、CTA 文案、URL、热区、最终 CTA、页脚、上线 QA |
| 产品选择 | 两款风扇的产品名、SKU、颜色、素材路径由设计师自行定夺 |
| Hero 组合 | 三帧的产品颜色、角度、组合由设计师自行定夺 |
| 建议视觉宽度 | 750px；最终高度由设计 / 搭建阶段确认 |
| 参考文件 | `/Users/mingjunliu/Desktop/社媒草稿箱/BACK IN STOCK_ Topside luggage.eml` |
| 参考截图 | `/Users/mingjunliu/Desktop/社媒草稿箱/3D501313-4365-463E-8B88-649B58B62C70.png` |

## 2. 邮件定位与责任边界

### 邮件定位

本封为明确的转化型促销 newsletter，与上一封 `Summer, With a Breeze` 生活方式邮件形成清楚区分：

| 上一封品牌内容 | 本封促销内容 |
|---|---|
| 先讲夏日状态与人物 | 先讲 Summer Sale 与折扣 |
| 人物是第一视觉主角 | 大标题、offer 与产品是第一视觉主角 |
| 低压内容 CTA | 明确购买 CTA |
| 编辑化生活图 | 动态产品 Hero + 直接产品入口 |

### 责任边界

视觉部门负责：

- 3 张可合成老虎机式 GIF 的完整 Hero 静态源帧。
- 2 张单品产品模块图。
- 1 张 Shop All 产品集合模块图。
- 从已有图库选取并适配 1 张 Our Community 图片。

EDM / Shopify 搭建侧负责：

- 将 3 张 Hero 源帧合成为 GIF。
- 过渡正文、优惠脚注、按钮、产品名称、CTA、URL、热区和追踪。
- 最终按钮、社媒链接、Shopify 原生 footer。
- 自动折扣、截止时间、静态 fallback、暗色模式和移动端 QA。

## 3. 整体模块结构

```text
M0 Logo / Navigation（沿用）
  ↓
M1 Hero GIF（设计交 3 张静态帧，EDM 侧合成）
  ↓
M2 Offer Transition + Shop the Sale（后台搭建）
  ↓
M3 Product 1 Image + CTA（图片由设计交，文字按钮后台搭建）
  ↓
M4 Product 2 Image + CTA（图片由设计交，文字按钮后台搭建）
  ↓
M5 Shop All Image + CTA（图片由设计交，文字按钮后台搭建）
  ↓
M6 Our Community（复用已有图片）
  ↓
M7 Final CTA + Shopify Footer（后台搭建）
```

| 顺序 | 模块 | 设计部门 | EDM / Shopify 搭建 |
|---:|---|---|---|
| M0 | Logo / Navigation | 本次不新增设计 | 沿用 Logo、导航与链接 |
| M1 | Hero GIF | 3 张完整静态源帧 | GIF、链接、alt、fallback |
| M2 | Offer Transition | 不作图；Hero 下方留自然衔接 | 正文、脚注、主 CTA |
| M3 | Product 1 | 1 张单品模块图 | 产品名、CTA、PDP 链接 |
| M4 | Product 2 | 1 张单品模块图 | 产品名、CTA、PDP 链接 |
| M5 | Shop All | 1 张双产品 / 系列模块图 | `Shop All Fans`、collection 链接 |
| M6 | Our Community | 复用并裁切 1 张已有图片 | 标题 / CTA（如需要） |
| M7 | Final CTA + Footer | 不作图 | 最终 CTA、社媒、原生 footer |

## 4. Hero GIF 三帧交付规范

### 4.1 统一画布

三张静态源帧必须满足：

- 完全相同的画布尺寸，建议 750px 宽。
- 完全相同的背景、标题位置、ticker 位置、字号、行距和产品列宽。
- 左右各一条产品“滚轴”，两款产品并列。
- 产品只能在各自滚轴内纵向移动，不得横向漂移或遮挡固定文字。
- 固定文案在三帧中必须逐像素保持一致，避免 GIF 播放时文字抖动。
- 产品真实比例、轮廓和颜色必须准确，不允许 AI 误画结构。

### 4.2 三帧建议状态

| 帧 | 动作任务 | 构图要求 |
|---|---|---|
| Frame 01 / Fallback | 清楚停靠状态 | 两款产品完整可见；offer 一眼读懂；可单独作为静态 fallback。 |
| Frame 02 / Motion | 滚动过渡状态 | 左列向上、右列向下，或由设计师选择统一逻辑；产品可局部出画并露出下一格，但不能看不出产品。 |
| Frame 03 / Settle | 第二个停靠状态 | 两列重新形成清楚的并列组合；颜色、角度或产品组合由设计师决定。 |

三帧并不要求增加第三款产品；设计师可以使用同两款风扇的不同颜色、角度或组合完成变化。

### 4.3 固定文案

主标题：

```text
SUMMER SALE
```

优惠信息：

```text
BUY ONE FAN,
GET THE SECOND 50% OFF
```

促销 ticker：

```text
SUMMER SALE • SECOND FAN 50% OFF •
```

执行要求：

- `50% OFF` 不能脱离 `SECOND FAN` 单独成为唯一大字，否则容易被理解为全场五折。
- 主标题与优惠信息都必须留在移动端安全区内。
- Ticker 可上下各一条，也可只保留一条；由设计师按画面密度决定。
- 不在 Hero 塞入完整脚注、URL、产品名或多个按钮。

### 4.4 文件交付

- 必交：`Hero_Frame_01`、`Hero_Frame_02`、`Hero_Frame_03` 三张同尺寸静态图。
- 文件格式、最终高度和可编辑源文件形式由设计 / 搭建团队确认。
- 如有真实透明产品 cutout，建议随三帧一并提供，便于 EDM 侧微调 GIF。
- 最终 GIF 帧时长、循环方式、压缩和上传不属于视觉部门交付范围。

## 5. 视觉调性总要求

### 核心关键词

- Direct
- Product-led
- High-contrast
- Cool
- Bright
- Fast-moving
- Summer retail energy
- Clear offer hierarchy

### 配色

- 主底色：white / icy white。
- 主促销色：cobalt blue / electric blue。
- 辅助色：icy cyan / aqua。
- 点缀色：acid lime 或少量 coral，二选一。
- 主文字：deep navy / black。
- 产品模块可使用不同高饱和冷亮色块，但整封最多一个暖色点缀。

不复制 Away 的大面积橙色。Diveblues 的促销感来自冷亮撞色、大字层级和滚轴节奏。

### 字体与排版

- 使用粗体无衬线大标题，字形直接、现代、清晰。
- 字距保持正常，不做极端压缩或拉宽。
- `SUMMER SALE` 是第一层级，offer 是第二层级，产品是第三层级。
- 每一屏只承担一个主任务，不把产品名、价格、折扣脚注和多个 CTA 全压进 Hero。
- 产品模块使用满宽色块或简洁矩形，不做多个卡片套叠；圆角不超过 8px。

### 产品处理

- 使用真实产品素材或准确商业合成。
- 产品可有轻微投影 / 接触阴影帮助落地，但不能做复杂场景棚拍。
- 不增加未经确认的配件、按键、挂绳、支架或功能状态。
- 两款产品在 Hero 中视觉重量接近，避免一款被误认为赠品或附属品。

## 6. 模块视觉需求表

### M0 Logo / Navigation

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 邮件顶部。 |
| 基础信息 | 沿用现有 Diveblues Logo / navigation；本次不新增设计。 |
| 核心信息 | 进入促销前确认品牌身份。 |
| 设计重点 | 与 Hero 背景自然衔接，不增加第二套促销导航。 |
| 视觉主角 | Diveblues Logo。 |
| 背景环境 | White / icy white。 |
| 视觉调性 | 清楚、轻、低噪音。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 搭建侧处理。 |
| Prompt 指向 | 不需要。 |

### M1 Hero GIF Source Frames

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 首屏；Logo / navigation 下方。 |
| 基础信息 | 设计交 3 张 750px 宽同尺寸静态帧；每帧两款风扇并列；最终 GIF 由 EDM 侧制作。 |
| 核心信息 | `Summer Sale` 已开始，买一台风扇，第二台五折。 |
| 设计重点 | 1. 固定大标题与 offer。<br>2. 左右双滚轴产品。<br>3. 三帧文字逐像素一致。<br>4. Frame 01 可独立作为静态 fallback。<br>5. 产品颜色、角度与组合由设计师决定。<br>6. 产品不遮挡 `SECOND FAN`。 |
| 视觉主角 | 第一层：`SUMMER SALE`；第二层：offer；第三层：两款产品。 |
| 背景环境 | 抽象促销画面，不使用人物或夏日生活场景；白 / 冰蓝底 + 冷亮色 ticker。 |
| 视觉调性 | Slot-reel motion、bold retail poster、cool high contrast。 |
| 图片内文案 | `SUMMER SALE`<br>`BUY ONE FAN, GET THE SECOND 50% OFF`<br>`SUMMER SALE • SECOND FAN 50% OFF •` |
| CTA / 点击 | Hero 内不做按钮；链接和热区由搭建侧处理。 |
| Prompt 指向 | Prompt 1-3。 |

### M2 Offer Transition

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | Hero 下方。 |
| 基础信息 | 不需要视觉部门作图。 |
| 核心信息 | 用 live text 重述优惠、补充脚注并给出主 CTA。 |
| 设计重点 | Hero 底部需要干净结束，便于后台接白底 / 冰蓝底正文。 |
| 视觉主角 | 后台文字与 `Shop the Sale` 按钮。 |
| 背景环境 | 由搭建侧设置。 |
| 视觉调性 | Direct、clean、high readability。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 搭建侧处理。 |
| Prompt 指向 | 不需要。 |

### M3 Product 1 Image

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 第一个产品入口。 |
| 基础信息 | 1 张满宽产品模块图；具体产品、颜色和素材由设计师选择。 |
| 核心信息 | 第一款风扇是可直接购买的 Summer Sale 选择。 |
| 设计重点 | 1. 产品放左、右侧留 live-text / CTA 安全区。<br>2. 产品占比足够大，移动端仍能识别。<br>3. 背景使用冷亮高饱和色块。<br>4. 不把产品名、价格和按钮压进图片。<br>5. 产品阴影克制、边缘准确。 |
| 视觉主角 | 第一款风扇。 |
| 背景环境 | 纯色或极简图形底，不放人物与复杂道具。 |
| 视觉调性 | Direct commercial product card；清楚、明快。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 产品名、CTA 与 URL 搭建时提供。 |
| Prompt 指向 | Prompt 4。 |

### M4 Product 2 Image

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 第二个产品入口。 |
| 基础信息 | 1 张满宽产品模块图；具体产品、颜色和素材由设计师选择。 |
| 核心信息 | 第二款风扇形成另一种购买选择，并与第一款保持同级。 |
| 设计重点 | 1. 产品放右、左侧留 live-text / CTA 安全区。<br>2. 版式与 M3 镜像，但颜色不完全重复。<br>3. 两款产品视觉重量接近。<br>4. 不压入产品名、价格或按钮。 |
| 视觉主角 | 第二款风扇。 |
| 背景环境 | 与 M3 同系统的另一冷亮色块。 |
| 视觉调性 | Direct commercial product card；与 M3 形成节奏。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 产品名、CTA 与 URL 搭建时提供。 |
| Prompt 指向 | Prompt 5。 |

### M5 Shop All Image

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 两个单品入口之后。 |
| 基础信息 | 1 张双产品或多色集合图；具体产品组合由设计师选择。 |
| 核心信息 | 不想选单款时，可以浏览全部风扇。 |
| 设计重点 | 1. 两款产品或多色产品形成紧凑组合。<br>2. 下方 / 右侧保留 `Shop All Fans` live-text 安全区。<br>3. 背景色与 M3 / M4 区分，但保持同一促销系统。<br>4. 不做商品瀑布流或过多小产品。 |
| 视觉主角 | 两款产品组合 / 系列选择感。 |
| 背景环境 | 纯色或简洁几何底。 |
| 视觉调性 | Collection entry、bold、clear。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | `Shop All Fans` 与 URL 搭建时添加。 |
| Prompt 指向 | Prompt 6。 |

### M6 Our Community

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 产品入口之后、最终 CTA 之前。 |
| 基础信息 | 从过往图库复用 1 张图片并按 750px 模块适配裁切；不新增拍摄。 |
| 核心信息 | 在强促销之后重新连接真实用户 / 社区感。 |
| 设计重点 | 1. 选择真实使用、朋友 / 家庭 / 出行互动图片。<br>2. 产品自然出现，不选另一张硬广。<br>3. 影调清凉、干净、明亮。<br>4. 图片本身不写折扣或 CTA。 |
| 视觉主角 | 真实人物关系与产品使用。 |
| 背景环境 | 旅行、出街、朋友或家庭夏日场景；避免灰暗和杂乱。 |
| 视觉调性 | Real、participating、community-led。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 标题、CTA、链接由搭建侧决定。 |
| Prompt 指向 | 不生成；复用已有图库。 |

### M7 Final CTA + Footer

| 字段 | 内容 |
|---|---|
| 模块 / 邮件位置 | 邮件底部。 |
| 基础信息 | 不需要视觉部门作图。 |
| 核心信息 | 由搭建侧补充最后购买入口与 Shopify 合规页脚。 |
| 设计重点 | M6 底部留干净衔接；不能用图片替代退订 / 实体地址。 |
| 视觉主角 | 最终 CTA 与 footer。 |
| 背景环境 | 搭建侧处理。 |
| 视觉调性 | 清楚、轻，不再增加新促销层级。 |
| 图片内文案 | 没有。 |
| CTA / 点击 | 搭建侧处理。 |
| Prompt 指向 | 不需要。 |

## 7. 英文文案最终版

### Subject / Preheader

| 位置 | Final English Copy | 实现 |
|---|---|---|
| Subject | `Get ready: Our Summer Sale starts today` | Shopify live subject；需与 2026-07-24 实际发送日一致 |
| Preheader | `Buy one fan, get the second 50% off—automatically applied at checkout.` | Shopify live preheader |

### Hero 图片文案

```text
SUMMER SALE

BUY ONE FAN,
GET THE SECOND 50% OFF

SUMMER SALE • SECOND FAN 50% OFF •
```

### Backend Transition

```text
Don't miss it: buy one fan and get the second 50% off during our Summer Sale.

*Discount applies to the item of equal or lesser value. Discount automatically applied at checkout. Offer valid through July 30 (ET).

Shop the Sale
```

### Product / Community Placeholders

产品 CTA 与 URL 在搭建时提供，视觉稿不写死：

- `Shop [Product Name]`
- `Shop [Product Name]`
- `Shop All Fans`
- `Our Community`

### Alt / Fallback 建议

- Hero: `Summer Sale: buy one fan and get the second 50% off.`
- Product 1: `Shop a featured Diveblues fan in the Summer Sale.`
- Product 2: `Shop another featured Diveblues fan in the Summer Sale.`
- Shop All: `Explore all Diveblues fans in the Summer Sale.`
- Community: `Diveblues fans in real summer moments.`

## 8. 参考图生成提示词

使用说明：

- 以下 prompt 用于构图与背景参考，不用于替代真实产品图。
- 最终产品必须由设计师使用真实 SKU 素材合成；AI 生成的文字、Logo、按钮和产品结构全部舍弃。
- 三张 Hero 帧的固定文案由设计师后期排版，生图工具不负责准确文字。

### Prompt 1：Hero Frame 01 / Fallback

```text
Bold vertical summer sale email hero layout for a modern portable fan brand, 750-pixel-wide canvas, two accurate portable fan product cutouts displayed side by side in two clean vertical reel columns, both products fully visible in a clear stopped position, icy white background, cobalt blue and electric blue sale bands, small acid-lime accent, large stable headline-safe area in the center, fixed promotional ticker zones at the top and bottom, crisp high-contrast retail poster design, cool bright color palette, strong mobile readability, precise product proportions, no people, no lifestyle scene, no orange Away-inspired palette, no luggage, no brand logos, no rendered text, no fake buttons, no excessive rounded cards, no extra accessories, no distorted product geometry.
```

### Prompt 2：Hero Frame 02 / Motion

```text
Second source frame for a vertical slot-reel summer sale email hero, exact same 750-pixel canvas, background, typography-safe zones, reel widths and ticker positions as frame one, two portable fan product columns moving in opposite vertical directions, left product shifted upward and right product shifted downward, partial next product color or angle entering from the edge of each reel, controlled motion blur only on the products, fixed headline area remains perfectly stable and empty for later typography, icy white, cobalt blue, aqua and one acid-lime accent, cool high-contrast retail energy, no people, no orange palette, no luggage, no logos, no text, no button, no product distortion.
```

### Prompt 3：Hero Frame 03 / Settle

```text
Third source frame for a vertical slot-reel summer sale email hero, exact same 750-pixel canvas, background, headline-safe area, reel widths and ticker positions as the previous frames, two accurate portable fan products settled clearly side by side after the roll, designer-selected alternate colors or viewing angles, both products balanced at equal visual weight, icy white background with cobalt blue and aqua sale bands, small coral or acid-lime accent but not both, bold clean commercial poster design, fixed empty copy area for later headline and offer text, no people, no orange Away-inspired design, no luggage, no logos, no rendered text, no fake button, no distorted product details.
```

### Prompt 4：Product Module 1

```text
Full-width commercial product module image for a summer sale email, one accurate portable fan product large on the left, generous clean live-text and CTA-safe space on the right, saturated cobalt-blue or icy-cyan solid background, subtle contact shadow, crisp studio product lighting, bold but minimal retail campaign layout, strong mobile readability, square or slightly vertical email banner composition, no people, no props, no text, no logos, no prices, no fake buttons, no orange palette, no complex gradients, no extra accessories, no distorted product geometry.
```

### Prompt 5：Product Module 2

```text
Full-width commercial product module image for a summer sale email, a second accurate portable fan product large on the right, generous clean live-text and CTA-safe space on the left, contrasting aqua or electric-blue solid background within the same campaign system, subtle contact shadow, precise studio product lighting, bold minimal retail design, equal visual weight to the first product module, mobile-first composition, no people, no props, no text, no logos, no prices, no fake buttons, no orange palette, no extra accessories, no distorted product geometry.
```

### Prompt 6：Shop All Module

```text
Full-width collection-entry image for a portable fan summer sale email, two featured portable fans or a compact fan color lineup grouped clearly in the lower-left or center, generous empty live-text and CTA-safe space for “Shop All Fans”, cool high-saturation solid background using icy blue, cobalt and one acid-lime or coral accent, clean geometric product arrangement, crisp commercial studio finish, bold collection-shopping energy, products large enough for mobile, no people, no lifestyle props, no text, no logos, no price tags, no fake button, no crowded product grid, no orange Away-inspired palette, no distorted product geometry.
```

## 9. Offer / IP / 设计避坑

### Offer 表达

- 必须完整写成 `Buy one fan, get the second 50% off` 或明确等义表达。
- 不允许只写 `50% OFF`，避免被理解为全场五折。
- 脚注使用用户确认的：`Discount applies to the item of equal or lesser value. Discount automatically applied at checkout.`
- 截止文案当前只建议写 `Offer valid through July 30 (ET).`；具体年份与时间上线前核对。
- 不新增“仅限今天”“库存有限”“最后机会”等未确认紧迫性。
- 不新增叠加规则、次数限制、指定颜色或指定 SKU 条件。

### IP / Reference 边界

- 可借鉴：老虎机双滚轴、固定大字、offer-first 层级、产品入口直给。
- 不使用：Away Logo、字体、橙色视觉系统、旅行箱 / 包袋造型、原促销条、原按钮和原模块图。
- 不在图中出现第三方品牌 Logo 或可识别产品。

### 设计避坑

- 不让固定文字在三帧中发生任何位移。
- 不把完整条款压进 Hero。
- 不让两款产品一大一小到像“正品 + 赠品”。
- 不把产品模块做成白底详情页截图或密集商品网格。
- 不出现多个同级主 CTA；整封主动作是 `Shop the Sale`。
- 不使用大面积橙黄暖色覆盖 Diveblues 的清凉、干净、明亮调性。
- 不用 AI 生成的错误产品作为最终上线素材。

## 10. Missing Context / Launch Check

| 项目 | 状态 |
|---|---|
| 设计交付时间 | Missing Context |
| 两款产品名 / SKU / 颜色 / 素材 | 设计师自行定夺 |
| 三帧产品颜色 / 角度 / 组合 | 设计师自行定夺 |
| 产品 CTA 文案与 URL | EDM 搭建时提供 |
| Hero / 产品模块最终高度、格式、可编辑源文件 | 设计 / 搭建阶段确认 |
| GIF 帧时长、循环、压缩、静态 fallback 上传 | EDM 搭建侧确认 |
| Our Community 图片路径 | 设计师从已有图库选择 |
| 自动折扣已在 Shopify 配置并通过 QA | launch-check |
| 截止年份 | 用户提供 2027；因发送时间为 2026-07-24，launch-check，不擅自修改 |
| 截止精确时间 | Missing Context；仅确认 ET |
| 退款 / 取消后的折扣重算规则 | Missing Context；不进入主视觉 |

## 11. Source Notes

- Away 参考邮件可从用户提供的 `/Users/mingjunliu/Desktop/社媒草稿箱/BACK IN STOCK_ Topside luggage.eml` 正常读取；其 HTML 显示 600px 主内容、GIF / 静态图片模块、产品与 Community 模块及底部条款。
- 用户截图 `/Users/mingjunliu/Desktop/社媒草稿箱/3D501313-4365-463E-8B88-649B58B62C70.png` 用于确认移动端的 ticker、双产品滚动、大字 offer 和三产品入口结构。
- Away 的实际折扣、日期、产品和条款仅作为参考邮件内容，不进入 Diveblues offer。
- Diveblues 视觉调性参考 `/Users/mingjunliu/ai-marketing-wiki/wiki/brands/diveblues-2026-brand-reshape.md`。
- EDM 促销 / CTA / 移动端规则参考：
  - `/Users/mingjunliu/ai-marketing-wiki/outputs/edm/standards/2026-06-10-edm-visual-brief-v1.md`
  - `/Users/mingjunliu/ai-marketing-wiki/outputs/edm/standards/2026-06-10-edm-copy-standards-v1.md`
- 与上一封生活方式 newsletter 的差异参考 `/Users/mingjunliu/ai-marketing-wiki/outputs/diveblues/edm/visual-requests/2026-07-10-summer-with-a-breeze-beach-newsletter.md`。
- 页脚边界参考 `/Users/mingjunliu/ai-marketing-wiki/wiki/edm/edm-footer-kit.md`；本需求不设计最终页脚。
