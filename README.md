# سفير — Safir Paper Products Factory

Arabic-first (RTL) marketing site for **مصنع سفير للمنتجات الورقية**, a Saudi paper products manufacturer.

Plain static HTML/CSS/JS — no build step. Open `index.html` in a browser, or host it on GitHub Pages.

## Pages

| File | Page |
| --- | --- |
| `index.html` | الرئيسية — Home |
| `products.html` | منتجاتنا — Product catalog with category filter |
| `story.html` | قصتنا والمصنع — About, timeline, factory, quality |
| `contact.html` | اطلب عرض سعر — 3-step quote request form |
| `en/*.html` | English versions of all four pages (left-to-right) |

The **EN / ع** button in the header switches language and keeps you on the same page.

## Brand

- Olive `#354B1F` · Deep olive `#26361A` · Sage `#A9B47E` · Kraft `#D8CA98` · Cream `#F4EEDF` · Gold `#B58D4D`
- Type: Readex Pro (Arabic), Jost (Latin), from Google Fonts
- Logo mark: `assets/safir-s.webp` (PNG fallback in `assets/safir-s.png`)

## Before going live

- Replace every bracketed placeholder (`[٠٠]`, `[0000]`, `[sales@safir.sa]`, phone, address, commercial registration, certificate logos, leadership photo and quote) with real details.
- Confirm the product list matches Safir's actual range.
- Connect the quote form and newsletter field to a real backend or form service; they don't submit anywhere yet.
- Placeholders appear in both languages: update the Arabic pages and the matching `en/` pages.
- Canonical and hreflang links point to `https://yusefamin.github.io/safir-site/`. If you move to a custom domain, update those `<link>` tags in every page's `<head>`.

## Notes

Scroll-linked animations use CSS scroll-driven animations (Chrome/Edge). Other browsers show the full content without those effects. Motion is disabled for visitors who prefer reduced motion.

## Deploy to GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / root.
