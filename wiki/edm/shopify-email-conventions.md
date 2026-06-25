# Shopify Email Custom Liquid 经验包

> 内部执行笔记。用于 Ocoopa / Diveblues Shopify Email custom Liquid EDM 模板代码。  
> 当前是 v1 经验包, 服务探索实验与后续 QA; 不是最终标准模板规范。

## 1. 适用范围

- 适用: Shopify Email / Shopify Messaging custom Liquid 邮件模板或 custom Liquid section。
- 不适用: Shopify 主题页 Custom Liquid 模块、Klaviyo/Mailchimp 模板、完整邮件服务商迁移方案。
- 默认流程: 任何正式模板或新变体先走 `agent/workflows/task-intake-and-run.md` 审批流, 再走 `agent/workflows/edm-template.md`。

## 2. HTML / CSS 硬约束

- 使用 table 布局承载关键结构。
- 关键样式写 inline CSS。
- 不使用 JS。
- 不依赖外部 CSS、webfont、复杂动画或表单交互。
- 主容器建议约 600px 宽, mobile 使用 `width:100%`。
- 图片使用 `display:block;width:100%;height:auto;`。
- CTA 用普通 `<a>` 链接, 不只做图片内视觉按钮。
- 核心文本尽量用 live text, 不全部压进图片。

## 3. 暗色模式兜底

- 每个大色块都写 `bgcolor` 或 inline `background-color`。
- 关键文字写明确 `color`。
- 避免透明浅色 logo / 白色文字压在不确定背景上。
- 背景图不是必要信息的唯一载体; 必须有纯色 fallback。
- 暗色模式无法完全统一, 必须发测试邮件检查 Gmail / Outlook / Apple Mail。

## 4. 图片与资产

- 正式图片使用 Shopify Files 绝对 URL。
- 探索模板可用清晰 placeholder URL, 但必须标注待替换。
- 每张关键图保留 alt text。
- 图片不可承担唯一法律/CTA/退订信息。
- 图片文件大小由运营/设计在测试邮件前压缩确认。

## 5. Liquid 变量白名单备注

### 本轮默认可使用

| 变量 / 写法 | 用途 | 备注 |
|---|---|---|
| `{{ customer.first_name | default: "there" }}` | 个性化问候 | 用 default 保证空值可读。 |
| `{% if customer.first_name != blank %}` | 简单条件分支 | 只判断已使用的 `first_name`; else 分支必须完整。 |
| `{{ shop.name }}` | 店铺名 fallback | 只用于低风险 fallback 文案。 |
| `{{ unsubscribe_url }}` 或 `{{ unsubscribe_link }}` | 退订 | footer 必须包含其一。 |
| `{{ open_tracking }}` | open tracking | 若 campaign 开启 open tracking, 必须包含。启用状态若未确认, 标为 Missing Context。 |

### 待验证, 暂不进默认模板

| 变量 / 写法 | 状态 | 处理 |
|---|---|---|
| `all_products[handle]` | pending variable verification | Shopify Email custom Liquid 上下文未证实可执行; 第一版探索模板默认用静态商品卡。 |
| 裸 `products` 对象 | pending variable verification | 不使用。若官方/测试证明可用, 再登记具体上下文。 |
| `customer.accepts_marketing` | pending variable verification | 不使用。营销同意条件在 Shopify Email custom Liquid 中需实测后再启用。 |
| `abandoned_checkout.*` | automation-only candidate | 只在弃购 automation 模板里按官方上下文验证后使用。 |
| `abandoned_visit.*` | automation-only candidate | 只在浏览放弃 automation 模板里按官方上下文验证后使用。 |

## 6. Product 区规则

- v1 默认: 静态商品占位卡。
- 静态卡必须清楚标注:
  - 图片待替换
  - 商品名待替换
  - CTA URL 待替换
- 动态 product loop 必须单独登记为实验项:
  - 变量: `all_products[handle]` 或其它候选变量
  - 状态: `pending variable verification`
  - 验证方式: 发 Shopify Email 测试邮件, 检查商品名、图片、价格、URL 是否实际渲染
  - 通过前不得进入正式默认模板

## 7. Footer 与合规

- footer 必须有退订入口。
- **footer 必须含真实实体邮寄地址(美国 CAN-SPAM 强制)**; 真实发送前不可缺, 探索模板用清晰标注的占位。
- 临时品牌 footer 可以探索语气和版式, 但不得视为标准 footer。
- 隐私、偏好管理、地区法规(GDPR / CASL 等)由运营/法务确认; 未确认写 `Missing Context`。
- 法律/合规输出为起草辅助, 非法律意见。

## 8. 体积限制

- custom Liquid section <= 50KB。
- 整封 custom-coded Liquid email <= 500KB。
- 每次交付前用 `wc -c` 检查 `.liquid` 文件体积。

## 9. 测试清单

> 发测试前逐项过 `助手Agent/agent/prompts/edm-template-pretest-checklist.md`(占位替换 + 安全 + 跨客户端 QA + 登记)。

- Shopify Email 编辑器可保存。
- 发测试邮件。
- Gmail desktop / mobile 检查。
- Outlook desktop / web 检查。
- Apple Mail light / dark 检查。
- 图片加载失败时仍能读懂主信息。
- CTA 链接可点击, URL / UTM 正确。
- footer 退订链接存在。
- 如果启用 open tracking, `open_tracking` 变量存在。
- mobile 首屏标题、主图、CTA 不挤压。
- 暗色模式文字和按钮可读。
- 记录到模板实验登记表。

## 10. Source Notes

- Shopify Help Center: Customize your Shopify Messaging campaigns using Liquid — https://help.shopify.com/en/manual/promoting-marketing/create-marketing/shopify-messaging/email/create-email/custom-liquid
- Shopify notifications email variables reference — https://help.shopify.com/en/manual/fulfillment/setup/notifications/email-variables
- 当前 `all_products[handle]` / `customer.accepts_marketing` 的邮件上下文可用性未由本 run 实测证实, 因此标为 `pending variable verification`。

## Related

- `agent/workflows/edm-template.md`
- `agent/workflows/edm-content.md`
- `agent/workflows/edm-visual-request.md`
