# Ounass PLP Redesign — Mobile Prototypes

Five self-contained mobile HTML prototypes for the Ounass "Curated For You" product listing surface. Each pushes beyond the current 2-up grid toward a distinct browsing model.

**[Open the index](index.html)** to see all variants with previews and navigation.

## Variants

| # | Variant | File | Model |
|---|---|---|---|
| 01 | Story Scroll | [01-story-scroll.html](01-story-scroll.html) | Single-item vertical swipe with curation reason promoted |
| 02 | Dense Discovery | [02-dense-discovery.html](02-dense-discovery.html) | 3-up grid with inline quick-add and sticky chip rail |
| 03 | Swipe Stack | [03-swipe-stack.html](03-swipe-stack.html) | Tinder-style: right=save, left=pass, up=details, down=bag |
| 04 | Magazine | [04-magazine.html](04-magazine.html) | Asymmetric hero + thumbs rhythm with editorial quote strip |
| 05 | Masonry | [05-masonry.html](05-masonry.html) | Pinterest-style two-column staggered grid |

## Running locally

Every file is standalone — no build step, no server required. Open any HTML directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# visit http://localhost:8000/
```

Product imagery is embedded as base64 data URIs so the prototypes work offline and when opened via `file://`.

## Tech

- Plain HTML/CSS/JS — no framework
- Fraunces (serif) + Nunito Sans (sans) from Google Fonts
- Mobile-first: viewport units, safe-area insets, touch gestures via pointer events
- Dark / Light mode toggle on every screen (persists on the index)

## Design source

Originally exported from Claude Design as a handoff bundle. See `ounass/README.md` in the source bundle for the design intent behind each variant.
