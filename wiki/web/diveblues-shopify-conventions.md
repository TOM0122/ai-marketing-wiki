# Diveblues Shopify Conventions

Status: working note

Last updated: 2026-06-12

## Source References

- User task input on 2026-06-12: Diveblues page uses Shopify, Symmetry 2.28, Custom Liquid, 750px mobile breakpoint, and Custom Liquid size awareness around 50KB.
- Live page checked on 2026-06-12: https://diveblues.com/pages/be-a-crazyfan
- Brand note: `wiki/brands/diveblues-2026-brand-reshape.md`
- Campaign/support notes: `wiki/social-post-kit.md`, `outputs/diveblues/visual-requests/2026-06-09-crazyfan-ig-guessing.md`

## Platform And Theme Notes

- Shopify theme: Symmetry 2.28, user-provided for the #CrazyFan module task.
- Custom Liquid can carry HTML, inline `<style>`, inline `<script>`, and font `<link>` tags. The live #CrazyFan page already contains Custom Liquid sections with a Google Fonts link and inline CSS.
- Keep Custom Liquid snippets small and well below the approximate 50KB ceiling.
- Default page width should follow surrounding modules unless the task explicitly asks for full page width.
- For module-managed spacing, recommend turning off Shopify section "Show space above/below section" and using CSS padding inside the module.

## Responsive Convention

- Use `@media (max-width: 749px)` for custom module mobile styles when following the Symmetry 750px breakpoint.
- The current #CrazyFan custom modules also use `@media (max-width: 749px)` in their inline CSS.

## Visual Language

- Diveblues brand direction: life participant, relaxed/free/happy, real/dynamic, cool/clean/bright.
- Current #CrazyFan activity page direction: sports-event energy, uppercase campaign language, bold social challenge framing.
- Approved core colors for the 2026-06-12 #CrazyFan module task:
  - Mint: `#A8E6CF`
  - Green: `#27AE60`
- Existing live page custom title module also uses a softer green (`#A8C97A`) and orange accent (`#E85A2A`). Treat these as page-context references, not mandatory future defaults.
- Bebas Neue is already used on the live #CrazyFan Custom Liquid title module and is suitable for large uppercase campaign headlines.
- Buttons can use the existing page interaction pattern: slight upward movement on hover plus a green-tinted shadow.

## Reference Modules On `be-a-crazyfan`

- Hero:
  - Title: `Be a #CrazyFan`
  - Supporting line: `The fan that fans need. 12 colors. 48 teams.One summer.`
- Custom Liquid title block:
  - Eyebrow: `SOCIAL CHALLENGE · LIMITED TIME`
  - Headline: `WIN A FAN. WIN A FLIGHT.`
  - Supporting line: `Join #CRAZYFAN on social — predict the match, win the prize.`
  - Font: Bebas Neue via Google Fonts link.
- Instagram button block:
  - CTA: `FOLLOW US ON INSTAGRAM`
  - Link opens in a new tab.
  - Hover uses `translateY(-2px)` and a green shadow.

## Custom Liquid Module Rules

- Use one unique wrapper class per module, for example `.db-cf-engage`.
- Scope every CSS selector under that wrapper.
- Avoid styling global theme selectors such as `h2`, `a`, `.btn`, `.container`, or `.custom-html`.
- Essential content must render without JavaScript.
- Use real `<a>` links for downloads and external actions.
- If using operator placeholders such as `{{PDF_URL}}`, mark them clearly in comments and replace before publishing. Shopify Liquid may treat unresolved `{{...}}` as a Liquid variable.
- For manually maintained counts, show the final value in the HTML by default and use JS only as enhancement. Avoid "live" or real-time wording unless a real data source exists.

## QA Checklist

- CSS scope: all selectors start with the module wrapper.
- Mobile: `@media (max-width: 749px)` exists and handles text, grid, and button widths.
- No-JS: numbers, text, and PDF link remain visible and usable.
- Placeholder check: only intended placeholders remain.
- Size check: `wc -c <file>` stays comfortably below the Custom Liquid limit.
- Local preview: open the vault HTML or a temporary page and inspect desktop/mobile layout before handoff when feasible.
