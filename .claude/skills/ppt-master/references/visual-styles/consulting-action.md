# Visual style: consulting-action

Strategy-consulting boardroom discipline. Every content page is carried by a full-sentence action title over a hairline rule, ruled evidence underneath, and a sourced footer. Flat, square, and quiet — the argument is the visual. For board / executive reports, strategy recommendations, investor pitches, and institutional briefings.

---

## 1. Shape & decoration

- Shape language: square corners only (`rx="0"`); single-weight hairline rules; 1px-bordered panels and ruled tables. No blobs, no badges, no decorative blocks.
- Composition geometry: an action-title band across the top with a hairline rule directly beneath it; a numbered section grid or aligned column set underneath; one evidence exhibit that fills its zone; a sourced footer strip (hairline + source line left, page number right) on every content page.
- Signature components (use where content fits; never force):
  - **Agenda tracker** — a short row of small squares at top-right, the current section filled with the primary color, the rest outlined in the border tone. Only when the deck has 3–8 explicit sections.
  - **Takeaway box** — a light tinted panel with a thick primary left border holding the page's single key takeaway. At most one per page.
  - **Horizontal bar tracks** — bars drawn on pale full-length tracks, only the key bar in the primary color, values right-aligned at the bar end.
  - **Section matrix** — a 2×2 on hairline axes with labeled dimensions (for example Effort / Impact); the winning quadrant filled with the primary color and reversed text.
  - **Numbered sections** — large section numbers anchoring a grid of aligned blocks, for investor-style decks.
- Title voice: every non-cover title is a complete sentence stating the page's conclusion. Label-style titles ("Market Overview") are not allowed.
- Formatting discipline:
  - Bullets are structured, never a text dump: ✓ included / positive, × excluded / negative, • neutral, 1. 2. 3. sequence, ‣ or – sub-point. One symbol system per box.
  - At most 6–7 bullets per box and at most 2 lines per bullet; avoid orphan words.
  - Tables are native table objects: text columns left-aligned, numeric columns right-aligned, header row in the primary color with reversed bold text, total row bold with a heavier top rule.
  - Parallel boxes share left edge, text start, width, top, and internal padding; same-level text uses one size across all boxes.
  - Arrows and flow connectors are drawn shapes, never text arrows (→ ⟹).
- Whitespace: disciplined and even; exhibits fill their zones — no thumbnail-sized charts, no large empty regions.

## 2. Typography character

- One sans family; hierarchy from weight and size only. Bold action titles, regular body, semibold exhibit titles, medium small labels.
- Section labels and data labels may run uppercase with slight letter-spacing. Stat numbers are large and semibold, set directly beside their unit.
- Left-aligned throughout; never center body paragraphs.

> Families are chosen at confirmation `g`; this style asks for a neutral grotesque *character* with weight-driven hierarchy, not a specific font.

## 3. Using the deck's colors

- White or near-white field; the primary color carries structure — titles, section numbers, table headers, the key bar, the filled tracker square.
- Exactly one accent hue beyond the primary, used only as a pointer to the single focus of a page. Never more than two accent colors on a deck.
- Grays carry body text, rules, tracks, and footers. Positive / negative colors appear only with data meaning and always beside a text label.

> HEX values come from confirmation `e`; this style only governs the primary-as-structure, single-pointer discipline — it names no colors.

## 4. Texture / elevation

- Strictly flat. No shadows, no gradients, no glow, no 3D — including on charts and chart templates.
- Separation comes from hairline rules, borders, and tint panels only.

## 5. Paired image-rendering

`minimalist-swiss` — only when the deck genuinely needs an image; decorative imagery is otherwise excluded.

## 6. Illustration propensity

**sparse** — the evidence and the action titles carry the page; decorative imagery weakens the boardroom register. With no user steer, default to none. If the user explicitly asks, keep them minimal and diagrammatic. `image_usage: none` writes no illustration rows.
