# Monetra Typography Guideline

## Typeface

Monetra uses **Inter** for product interfaces, documentation, and portfolio
materials. Its clear numerals and broad language support make it suitable for
financial data.

Fallback stack:

```css
font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont,
  "Segoe UI", sans-serif;
```

Use `ui-monospace, "SFMono-Regular", Consolas, monospace` only for source code,
identifiers, and technical values—not for financial amounts.

## Weights

| Weight | Usage |
| ---: | --- |
| 400 | Body text and supporting content |
| 500 | Labels, table values, and navigation |
| 600 | Buttons, emphasized values, and subheadings |
| 700 | Page titles and high-priority summaries |

Avoid weights below 400 in the application interface.

## Type Scale

| Token | Size / line height | Usage |
| --- | --- | --- |
| Display | 48 / 56 px | Portfolio hero only |
| Heading 1 | 36 / 44 px | Page title |
| Heading 2 | 28 / 36 px | Major section |
| Heading 3 | 22 / 30 px | Card or subsection |
| Body large | 18 / 28 px | Introductory content |
| Body | 16 / 24 px | Default content |
| Body small | 14 / 20 px | Supporting content |
| Caption | 12 / 16 px | Metadata and chart labels |

Mobile page titles may use 30 / 38 px. Body text must not drop below 14 px.

## Financial Numbers

- Use tabular numerals for aligned amounts and tables.
- Keep currency symbols visually attached to their values.
- Use the user's locale for separators and decimal precision.
- Do not abbreviate amounts when exact values are necessary.
- Use positive and negative signs consistently.
- Align comparable monetary values to the end of their column.

```css
.financial-value {
  font-variant-numeric: tabular-nums;
  font-feature-settings: "tnum";
}
```

## Hierarchy

- Each page has one `h1`.
- Do not skip heading levels for visual styling.
- Use weight, size, and spacing before introducing additional colors.
- Keep labels concise and place helper text close to the related control.

## Writing and Capitalization

- Use sentence case for headings, buttons, labels, and navigation.
- Use title case only for the Monetra product name and formal document titles.
- Write the wordmark as lowercase `monetra` only inside the official logo.
- Avoid all caps except short metadata or eyebrow labels.
- Do not use decorative punctuation to create emphasis.

## Accessibility

- Users must be able to zoom text to 200% without losing functionality.
- Avoid justified body text.
- Keep paragraphs reasonably short.
- Do not convey meaning through font weight or color alone.
- Maintain sufficient contrast in every interaction state.
