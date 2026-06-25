# Diveblues EDM Template Experiments

> 模板代码实验登记表。这里记录 Shopify Email custom Liquid / 邮件 HTML 候选变体, 不代表标准模板已固化。

## Experiment Table

| Variant ID | Date | Brand | Template Type | Mode | Associated EDM | File Path | Dynamic Variables | Effects Tested | Fallbacks | Assets Status | Variable Verification | Test Clients | Metrics To Review | Status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| `DB-EDM-EXP-20260625-EDITORIAL-V1` | 2026-06-25 | Diveblues | editorial | exploration | Missing Context: first exploratory test | `outputs/diveblues/edm/templates/2026-06-25-explore-editorial-v1.liquid` | `customer.first_name`, `unsubscribe_url`, `open_tracking` | Personalized greeting, editorial hero, two-column module, cool-tone bands, static product cards, temporary branded footer, dark-mode cues | `customer.first_name` default/else branch, image alt text, solid bgcolor, static cards, visible unsubscribe | placeholder Shopify Files URLs | `all_products[handle]`: pending variable verification; `customer.accepts_marketing`: pending variable verification | Pending: Gmail / Outlook / Apple Mail / mobile / dark mode | CTR, unsubscribe, conversion, RPE, qualitative QA notes; open rate auxiliary only | 测试中 | Candidate only. Product cards are static until Shopify Email variable rendering is proven. |

## Variable Verification Queue

| Candidate Variable | Status | Test Needed | Decision Rule |
|---|---|---|---|
| `all_products[handle]` | pending variable verification | Create a Shopify Email test using known handles and confirm product title/image/link render in sent email clients. | Enable product loop only after successful Shopify Email send/render test. |
| `products` / other product objects | pending variable verification | Confirm exact object name and template context from Shopify official docs or live Shopify Email test. | Do not use until exact supported object is proven. |
| `customer.accepts_marketing` | pending variable verification | Confirm value is available and meaningful inside Shopify Email custom Liquid. | Do not use for branch logic until proven. |

## QA Checklist

- Shopify Email editor saves the custom Liquid.
- Test email renders in Gmail.
- Test email renders in Outlook.
- Test email renders in Apple Mail.
- Mobile first screen is readable.
- Dark mode keeps text and CTAs legible.
- Images off: hero alt text and live text still explain the email.
- All placeholder URLs are replaced or deliberately kept for internal-only testing.
- `{{ unsubscribe_url }}` renders.
- `{{ open_tracking }}` is included if open tracking is enabled.
