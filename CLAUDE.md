# glacierphonk.github.io — Claude Code Instructions

## What This Is

GlacierPhonk™ website. Single-page static site served via GitHub Pages at glacierphonk.com.

## Files That Need Updating On Site Changes

When modifying the website content, **always update these files too**:

| File | What to update | When |
|------|---------------|------|
| `sitemap.xml` | `<lastmod>` date to today's date (YYYY-MM-DD) | Any content change to `index.html` |
| `humans.txt` | `Last update:` date to today's date (YYYY-MM-DD) | Any content change |
| `site.webmanifest` | App name, icons, colors | If branding changes |
| `robots.txt` | Sitemap URL | If domain or sitemap location changes |
| `404.html` | Style/branding | If site-wide design changes |

## SEO Checklist

Before pushing any content change, verify:

- [ ] `<title>` tag is descriptive and includes brand name
- [ ] `<meta description>` is 80-160 chars with keywords
- [ ] OG tags (`og:title`, `og:description`, `og:image`, `og:url`) are set and correct
- [ ] Twitter card tags are set (`twitter:card`, `twitter:title`, `twitter:description`, `twitter:image`, `twitter:site`, `twitter:creator`)
- [ ] JSON-LD structured data is present and valid
- [ ] `<link rel="canonical">` points to the correct URL
- [ ] `sitemap.xml` lastmod reflects today's date
- [ ] `humans.txt` last update reflects today's date

## Structure

```
index.html          — Full site (HTML + inline CSS + JS)
404.html            — Custom 404 page
sitemap.xml         — Sitemap for search engines
robots.txt          — Crawler directives
humans.txt          — Colophon
site.webmanifest    — PWA manifest
CNAME               — Custom domain (glacierphonk.com)
assets/             — Favicons, OG image, static assets
```

## Git Identity

Always use: `GlacierPhonk <elo@glacierphonk.com>`
