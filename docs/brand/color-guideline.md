# Monetra Color Guideline

## Principles

Monetra uses green to communicate stability, growth, and financial confidence.
Color supports meaning but never replaces text, icons, or structure.

## Brand Palette

| Name | Hex | Primary usage |
| --- | --- | --- |
| Monetra Green | `#087F5B` | Primary actions and brand emphasis |
| Monetra Dark | `#064E3B` | Strong text, dark surfaces, and logo details |
| Monetra Mint | `#A7F3D0` | Highlights and subtle positive emphasis |
| Monetra Off White | `#F8FAF9` | Light foreground and calm backgrounds |
| Monetra Ink | `#111814` | Primary light-theme text |

## Semantic Palette

| Meaning | Base | Soft background |
| --- | --- | --- |
| Success | `#15803D` | `#DCFCE7` |
| Warning | `#B45309` | `#FEF3C7` |
| Danger | `#B42318` | `#FEE4E2` |
| Information | `#175CD3` | `#EAF2FF` |
| Income | `#15803D` | `#DCFCE7` |
| Expense | `#B42318` | `#FEE4E2` |
| Transfer | `#175CD3` | `#EAF2FF` |
| Budget | `#7C3AED` | `#F3E8FF` |

## Neutral Palette

| Token | Light theme | Dark theme |
| --- | --- | --- |
| Background | `#F6F7F5` | `#0E1713` |
| Surface | `#FFFFFF` | `#15211B` |
| Elevated surface | `#FFFFFF` | `#1B2B23` |
| Primary text | `#111814` | `#F3F7F5` |
| Secondary text | `#52645B` | `#A9B8B0` |
| Muted text | `#718078` | `#82938A` |
| Border | `#DDE4E0` | `#2D4036` |
| Divider | `#E9EEEB` | `#24352D` |

## Usage Rules

- Use Monetra Green for the primary action on a page.
- Limit each view to one dominant primary action.
- Use semantic colors only for their assigned meanings.
- Use neutral colors for most surfaces and typography.
- Avoid large areas of highly saturated green.
- Never use expense red for decoration or positive information.
- Charts must remain understandable through labels, patterns, or direct values.

## Contrast

Normal text must meet a minimum contrast ratio of 4.5:1. Large text and
essential interface graphics must meet at least 3:1.

Do not place Monetra Mint text on white. Use Monetra Dark or Monetra Green text
on light surfaces instead.

## CSS Token Example

```css
:root {
  --color-brand: #087f5b;
  --color-brand-strong: #064e3b;
  --color-brand-soft: #a7f3d0;
  --color-background: #f6f7f5;
  --color-surface: #ffffff;
  --color-foreground: #111814;
  --color-muted: #52645b;
  --color-border: #dde4e0;
  --color-income: #15803d;
  --color-expense: #b42318;
  --color-transfer: #175cd3;
}
```
