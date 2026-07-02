# Monetra Icon Guideline

## Icon Library

Monetra uses [Lucide](https://lucide.dev/) as its primary interface icon
library. Use one icon family consistently to maintain a clear visual language.

Custom icons are allowed only when Lucide does not provide an appropriate
financial concept. Custom icons must follow the same grid, stroke, and corner
principles.

## Style

- Use outline icons by default.
- Use `stroke-linecap="round"` and `stroke-linejoin="round"`.
- Use a consistent stroke width within the same interface area.
- Do not mix outline, filled, 3D, and hand-drawn icons in the application UI.
- Reserve the detailed 3D brand artwork for promotional contexts.

## Sizes

| Context | Size | Stroke width |
| --- | ---: | ---: |
| Compact control | 16 px | 2 px |
| Button or input | 18 px | 2 px |
| Navigation | 20 px | 2 px |
| Standard standalone icon | 24 px | 2 px |
| Empty state | 40–48 px | 1.5 px |

Use even-numbered dimensions and place icons on whole pixels whenever possible.

## Color

- Use the current text color for standard icons.
- Use semantic colors only when the icon communicates a semantic state.
- Disabled icons must retain sufficient visibility.
- Never use color as the only way to communicate meaning.

## Labels

Icons for unfamiliar, destructive, financial, or irreversible actions require
a visible label. Icon-only buttons are acceptable for universally recognized
actions such as close, search, and menu when space is constrained.

Every icon-only button must provide an accessible name with `aria-label` or
equivalent visible text for assistive technology.

## Alignment and Spacing

- Center icons inside square icon-only controls.
- Use an 8 px gap between an icon and a button label.
- Align icons optically rather than relying only on the geometric bounding box.
- Do not scale icons with CSS transforms to compensate for poor alignment.

## Interaction States

Interactive icons must support default, hover, focus-visible, active, and
disabled states. Destructive actions use the danger color only when the action
is available.

Motion should be brief and functional. Avoid continuous rotation, bouncing, or
decorative animation in financial workflows.

## Financial Semantics

Use icons consistently:

| Concept | Recommended Lucide icon |
| --- | --- |
| Income | `ArrowDownLeft` |
| Expense | `ArrowUpRight` |
| Transfer | `ArrowLeftRight` |
| Account | `WalletCards` |
| Cash | `Banknote` |
| Bank | `Landmark` |
| Budget | `Target` |
| Report | `ChartNoAxesCombined` |
| Transaction | `ReceiptText` |
| Settings | `Settings` |

Do not reverse income and expense arrows between pages.

## Accessibility

- Decorative icons use `aria-hidden="true"`.
- Meaningful icons include accessible text.
- Icon-only controls have a minimum 44 × 44 px touch target.
- Focus indication belongs to the control, not only to the icon.
- Status icons are accompanied by text for critical feedback.
