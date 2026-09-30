# Visual style: institutional-memo

Institutional investment-research report — a portrait research journal reflowed into 16:9. Dense but boxless: two-column long-form, editorial small multiples, and sourced evidence modules on a paper-white field. Reads like a fund research note or an investment-committee memo, not a consulting deck. For investment research, due diligence, investment-committee papers, and strategy outlooks.

---

## 1. Shape & decoration

- Shape language: rectilinear, hairline rules, no cards. Rounded rectangles and boxed panels are not used to create hierarchy; lines, whitespace, size, and weight do that. Containers with a real information function (assumption box, status light, quotation box) are the only exception.
- Composition geometry:
  - A top hairline spanning the content width with a light running header and page number at the upper right.
  - Content pages: a title band in the top 15–22%, then 2–3 horizontal evidence zones or a 48% / 4% gutter / 48% two-column grid read top-to-bottom, left then right.
  - Chart-dense pages: one full-width primary evidence module on top with paired modules below, or two columns of small multiples.
  - Section openers: a giant light-weight title occupying roughly the left 55–62%, the summary or first evidence module to the right and below.
  - Never shrink a portrait page and center it on the 16:9 canvas.
- Evidence module: number + one-sentence conclusion in the judgment color → hairline → bold chart title → chart with no card background → basis and source line. Every module carries its own source.
- Signature components (each with a strict budget):
  - **Pull quote** — one borderless judgment sentence in the judgment color at the bottom or side of a column; at most one per page; never over a chart.
  - **Numbered viewpoint** — a large numeral in the section color with a short gray rule above; only for a sequence of numbered viewpoints; at most two per page.
  - **Direction triangles** — up / down triangles in the positive / negative colors, only for grouped positive-negative judgment lists, never as ordinary bullets.
  - **Question dot** — a solid dot plus question number marking only the start of one Q&A sequence; not repeated on continuation pages.
  - **Assumption box** — explicit assumptions stated on the page whose conclusion depends on them.
- Page types: section opener, two-column long-form, small-multiple evidence page, numbered-viewpoint page, positive / negative judgment list, serialized Q&A page.
- Equal splits (three or four equal columns, 2×2) only when the content itself is structured that way — three scenarios, a named framework.
- Chart language: line, grouped / stacked bar, stacked area, waterfall, scatter, scenario tables; heatmaps and phase paths occasionally. Label marks directly; bar charts label every bar; line charts label only inflections, extremes, and the latest point; forecasts use dashed lines or light tints; key inflections get a thin outlined circle or thin arrow. Never rely on a legend alone.
- Formatting discipline:
  - Bullets are structured: ✓ included / positive, × excluded / negative, • neutral, 1. 2. 3. sequence, ‣ or – sub-point. At most 6–7 bullets per block and at most 2 lines per bullet.
  - Financial tables are native table objects following Excel-model discipline: right-aligned numbers, thousands separators, one negative-number convention, separated assumption / driver / check rows, bold total row with a heavier top rule.
  - Same-level text uses one size across parallel blocks; arrows and bridge connectors are drawn shapes, never text arrows.
- Whitespace: concentrated around giant titles, the column gutter, between modules, and the bottom source area. No large unassigned voids in the body zone.

## 2. Typography character

- One sans family used across the whole deck (this style does not take a serif title). Light weight for giant titles and pull quotes, regular for body, bold for evidence labels; italic only for terminology.
- Ratio ramp from body = 1×: captions / tables / sources ≈ 0.8×, module headings and pull quotes ≈ 1.8–2×, content titles ≈ 3.5×, section titles and hero numbers ≈ 5×. Scale these to the deck's locked body size.
- Titles in sentence case and left-aligned; section numbering uppercase. Numbers, units, and percent signs stay together with no decorative tracking.

> Families are chosen at confirmation `g`; this style asks for a single-sans, light-titles / bold-labels *character*, not a specific font.

## 3. Using the deck's colors

- Paper-white field on almost every page; a near-white tint only for full-page coverage of the opening statement page.
- A deep text color for dense small type; a judgment color reserved for section names, pull quotes, conclusions, and evidence numbers — never a body background or a large container fill.
- Chart series: one bright primary series against a gray comparison; extra series hues only for multi-series or phase encoding.
- Positive / negative colors only for directional judgments. Excluding neutrals, standard pages use at most 2 hues and chart pages usually at most 4; accent colors never flood a content page.
- No dark-background content pages with reversed body text; a solid dark block is allowed only as a contents-page sidebar.

> HEX values come from confirmation `e`; this style only governs the paper-field, judgment-color-as-text, meaning-coded-data discipline — it names no colors.

## 4. Texture / elevation

- Flat, publication-grade — fine table rules and precise vector chart lines. No shadows, no gradients, no 3D, no glow — including on charts and chart templates.
- Chart backgrounds stay transparent or the page color; interval backgrounds use only very light gray bands.

## 5. Paired image-rendering

`editorial` — when imagery is used at all. The cover may carry one full-bleed natural photograph with the title over a low-texture area; content pages never substitute photography for data evidence.

## 6. Illustration propensity

**sparse** — the evidence modules and long-form columns carry the page; decorative spots undercut the research register. With no user steer, default to none. If the user explicitly asks, keep them minimal and journalistic. `image_usage: none` writes no illustration rows.
