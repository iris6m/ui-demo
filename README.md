# UI demo: Dashboard

A concept dashboard for comparing asset managers, built as a single HTML file. All names and figures are fictional.

**Live demo:** [irisluk.com/ui-demo](https://irisluk.com/ui-demo)
**Designed and built by:** Iris Luk ([irisluk.com](https://irisluk.com))

## One set of components, two design token sets

The switch in the top bar changes the whole page between Style 1 and Style 2. Nothing else is swapped. Every colour, font, corner radius, border, shadow, surface effect and spacing value is a design token, and each style is one set of token values.

- **Style 1:** dark, dense, data-first.
- **Style 2:** light, editorial, with glass panels and monospaced labels.

The charts read the same tokens, so the comparison lines, asset class colours and AI index bars change with the style too.

**See the proof:** [the diff that added Style 2](https://github.com/iris6m/ui-demo/commit/38c7632) shows only a new token set, the switch and Style 2's logo.

You can link straight to either style:

- Style 1: `irisluk.com/ui-demo`
- Style 2: `irisluk.com/ui-demo?style=2`

## What the dashboard shows

- **Rankings:** sortable table of 19 managers by assets under management, with year-on-year movement.
- **Ranking trends:** compare up to 5 managers by position or by assets.
- **Capital flows:** stacked chart by asset class, with a data table view.
- **Portfolio highlights and resources:** paged lists that fit the space available.

Each panel can expand to full width, and the layout adapts from desktop down to mobile.

## Accessibility

- Keyboard support throughout, including arrow keys for tabs and Escape to close an expanded panel.
- Every chart has a text description and a data table for screen readers.
- Skip link, visible focus states and labelled controls.
- Animation turns off for people who prefer reduced motion.

## How it was built

Designed in code and built with Claude Code. Plain HTML, CSS and JavaScript, in one file with no build step.
