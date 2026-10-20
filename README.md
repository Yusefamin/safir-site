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

## Brand

- Olive `#354B1F` · Deep olive `#26361A` · Sage `#A9B47E` · Kraft `#D8CA98` · Cream `#F4EEDF` · Gold `#B58D4D`
- Type: Readex Pro (Arabic), Jost (Latin), from Google Fonts
- Logo mark: `assets/safir-s.webp` (PNG fallback in `assets/safir-s.png`)

## Before going live

- Replace every bracketed placeholder (`[٠٠]`, `[0000]`, `[sales@safir.sa]`, phone, address, commercial registration, certificate logos, leadership photo and quote) with real details.
- Confirm the product list matches Safir's actual range.
- Connect the quote form and newsletter field to a real backend or form service; they don't submit anywhere yet.
- The English toggle (EN) is a visual placeholder; English pages aren't built yet.

## Notes

Scroll-linked animations use CSS scroll-driven animations (Chrome/Edge). Other browsers show the full content without those effects. Motion is disabled for visitors who prefer reduced motion.

## Deploy to GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / root.
