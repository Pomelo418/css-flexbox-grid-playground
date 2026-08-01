# CSS Flexbox & Grid Playground

An interactive, single-file tool for exploring CSS layout properties in real time. Tweak Flexbox and Grid values with buttons and sliders, watch the preview update instantly, and copy the generated CSS straight to your clipboard.

**[Open in browser](index.html)** — no install, no build step, no dependencies.

---

## Features

- **Flexbox mode** — control `flex-direction`, `flex-wrap`, `justify-content`, `align-items`, `align-content`, `flex-grow`, and item sizes
- **Grid mode** — edit `grid-template-columns` and `grid-template-rows` as free text or pick from presets, plus `justify-items`, `align-items`, and `justify-content`
- **Shared controls** — `gap` slider (0–40 px) and item count slider (1–12 colored boxes)
- **Live CSS output** — syntax-highlighted code that updates on every change
- **Copy to clipboard** — one click copies clean, paste-ready CSS

## Usage

Download or clone the repo, then open `index.html` in any modern browser.

```bash
git clone https://github.com/Pomelo418/css-flexbox-grid-playground.git
cd css-flexbox-grid-playground
open index.html        # macOS
# or just drag the file into a browser tab
```

No server required.

## Flexbox Properties Covered

| Property | Values |
|---|---|
| `flex-direction` | `row`, `row-reverse`, `column`, `column-reverse` |
| `flex-wrap` | `nowrap`, `wrap`, `wrap-reverse` |
| `justify-content` | `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly` |
| `align-items` | `flex-start`, `flex-end`, `center`, `stretch`, `baseline` |
| `align-content` | `normal`, `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `stretch` |
| `flex-grow` | `0`, `1` |
| `gap` | 0–40 px |

## Grid Properties Covered

| Property | Values |
|---|---|
| `grid-template-columns` | Free text + presets: `repeat(N, 1fr)`, `auto-fill`, `fixed+fr`, `1fr 2fr 1fr` |
| `grid-template-rows` | Free text + presets: `auto`, `repeat(N, Npx)`, `px+auto` |
| `justify-items` | `stretch`, `start`, `end`, `center` |
| `align-items` | `stretch`, `start`, `end`, `center` |
| `justify-content` | `start`, `end`, `center`, `space-between`, `space-around`, `space-evenly` |
| `gap` | 0–40 px |

## Tech

Vanilla HTML, CSS, and JavaScript. One file, ~830 lines, zero dependencies.
