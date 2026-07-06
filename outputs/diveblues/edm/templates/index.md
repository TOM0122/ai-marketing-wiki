# Diveblues EDM Liquid 模块登记

> 翻译模式产出的 Shopify Email custom Liquid 模块/模板登记。每产出一个登记一行。
> 当前为 Diveblues;Ocoopa 后续接入。规则见 `wiki/edm/shopify-email-conventions.md`,发测试前过 `agent/prompts/edm-template-pretest-checklist.md`。

## Modules

| ID | Date | Brand | 优化哪一块 | Scope | Associated EDM | File Path | Dynamic Variables | Assets Status | Test Clients | Status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| _(尚无;第一个翻译模式模块产出后登记)_ | | | | | | | | | | | |
| `DB-MOD-20260706-MATCHDAY-CTA-ICONS` | 2026-07-06 | Diveblues | 长图结尾 CTA + support/social icon row | native-email module | 2026-07-06 Match-Day Editorial Sports Collage Long Image | `outputs/diveblues/edm/templates/2026-07-06-matchday-cta-icons-module.liquid` | None | no image assets; live HTML/CSS badges | Pending: Gmail / Outlook / Apple Mail / mobile / dark mode | 测试中 | Width 750px; CTA URL `https://diveblues.com/`; no black footer / unsubscribe / address generated. |

> Scope = `native-email module`(默认,原生邮件里的局部模块)/ `full custom-coded email`。

## Variable Verification Queue

未在 Shopify Email custom Liquid 上下文证实可用的变量,登记在此,验证后才可进可执行代码。

| Candidate Variable | Status | Test Needed | Decision Rule |
|---|---|---|---|
| `all_products[handle]` | pending variable verification | 用已知 handle 发一次 Shopify Email 测试,确认 product title/image/link 在收到的邮件里渲染。 | 渲染成功后才启用动态 product loop。 |
| `products` / 其它产品对象 | pending variable verification | 从官方文档或实测确认确切对象名与上下文。 | 未证实前不使用。 |
| `customer.accepts_marketing` | pending variable verification | 确认该值在 Shopify Email custom Liquid 中可用且有意义。 | 未证实前不用于分支逻辑。 |

## QA Checklist（每个模块发测试时)

- Shopify Email 编辑器能保存该 custom Liquid。
- Gmail / Outlook / Apple Mail 渲染检查。
- 移动端首屏可读;暗色模式文字/CTA 可读;图关时 live text 仍能读懂。
- 所有 placeholder URL 已替换(或内部测试时有意保留)。
- CTA / 链接可点。
- footer:模块默认依赖原生邮件 footer(退订+地址);整封 custom-coded email 才自带退订。
- 结果记回本表(状态、客户端问题、CTR/退订/转化/RPE;打开率仅辅助)。
