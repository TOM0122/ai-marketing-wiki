# Obsidian Web Clipper Setup

Use this configuration for the `ai-marketing-wiki` vault.

## Vault

Select:

```text
ai-marketing-wiki
```

Make sure the vault path is:

```text
/Users/mingjunliu/ai-marketing-wiki
```

## Template

Create a Web Clipper template named:

```text
Marketing Web Clip
```

## Note Location

Use folder only:

```text
raw/web-clips
```

Do not put the filename pattern in this field.

## Note Name

Use:

```text
{{date|date:"YYYY-MM-DD"}} - {{title}}
```

## Note Content

Use the content from:

```text
_templates/web-clip.md
```

If `{{content}}` saves an empty article, use the fallback template:

```text
_templates/web-clip-full-page.md
```

This template keeps `{{content}}` and also adds:

```text
{{selectorHtml:body|markdown}}
```

It captures the full page body and converts it to Markdown. It will be messier, but it is more reliable for pages where smart article extraction fails.

## Expected Result

A clipped article should become one markdown note directly under:

```text
raw/web-clips/
```
