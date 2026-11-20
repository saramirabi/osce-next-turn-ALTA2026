# Presentation: Same Context, Different Clinician (ALTA 2026)

Talk slides for the ALTA 2026 paper, built with Quarto and reveal.js
(12 slides, speaker notes on every slide).

## View

The deck is already rendered. From this folder:

```bash
python3 -m http.server 8090
# then open http://127.0.0.1:8090/slides/
```

Keys: `S` speaker view with notes, `T` cycle templates (Green, Original,
NYFW SS26), `F` full screen, `Esc` overview off.

## Edit and re-render

- Slides: `slides/index.qmd` (one `##` heading per slide, notes in `::: {.notes}`).
- Deck styles: `slides/paper.css` (colours come from template tokens).
- Templates and chrome: `_shared/` (`_shared/themes/green.scss` is the default).

```bash
quarto render slides/index.qmd
```

Figures are drawn in HTML from Tables 1, 2, 5, 8 and Figures 1 to 2 of the paper.
