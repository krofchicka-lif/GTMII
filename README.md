# LIF — GTM Deck (Love It Forward)

A self-contained, scroll-style HTML presentation for **LIF (Love It Forward)** — trust infrastructure for relationship-layer commerce. Eleven full-screen "slides" with cross-fade transitions, count-up animations, and a live network-graph canvas. Everything (fonts, images, scripts) is embedded in a single file — no build step, no dependencies, works offline.

## File

- **`GTM II.html`** — the deck. Open it in any modern browser.

> The original source deck is preserved at `uploads/index.html`.

## Running

Just open the file:

```bash
open "GTM II.html"        # macOS
# or double-click it, or drag into a browser tab
```

No server required. Licensed brand typefaces (Graphik, Romana BT) and all imagery are inlined as base64.

## Navigation

| Action | Control |
| --- | --- |
| Next slide | `→` · `↓` · `Space` · on-screen arrow |
| Previous slide | `←` · `↑` · on-screen arrow |
| Replay slide animation | Replay button (bottom-right) |

A progress bar (Sol gold) and an `NN / 11` counter sit at the top and bottom.

## Slides

1. **Hero** — "Your best customer just sent you someone."
2. **The Why** — Someone chose you. Specifically you.
3. **Proof** — LA 2020 experiment (143 / Zero / 70% / 7-deep).
4. **What Actually Happens** — the five-step mechanic.
5. **The Dual Loop** — giver + receiver in the same moment.
6. **Merchant Dashboard** — animated stats + `lif.co/pulse` mockup with the introduction graph and chain visualization.
7. **Who It's For** — brands people already love.
8. **The Lift** — one integration, 30 days.
9. **Close** — "That's not a metric. That's a relationship."
10. **The Network** — live node-ring graph; "Trust is infrastructure."
11. **Brand / CTA** — LIF mark, tagline, 30-day pilot, `amy@loveitforward.co`.

## Brand system

| Token | Value | Use |
| --- | --- | --- |
| Air | `#FDFCF8` | Background |
| Not Black | `#2F2B2B` | Primary text |
| Sol | `#FFAC00` | Gold accent |
| Shell | `#F9EFE5` | Secondary surface |
| Palm | `#0C7A4B` | Merchant-facing elements |
| Poppy | `#CA0000` | Alerts only |
| Blue Jean | `#006298` | Accent |

Type: **Graphik** (headings/body), **Romana BT** (emotional moments, serif italic).

## Notes

- The slide cross-fade is a CSS `opacity`/`visibility` transition. Some headless capture tools freeze transitions when the tab is unfocused — it renders normally in a real browser.
- Print / PDF export and reduced-motion users get a force-revealed static state (no pre-animation hidden content).
