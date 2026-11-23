---
name: Vedanta Corporate Narrative
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#43474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#49607e'
  primary: '#000f22'
  on-primary: '#ffffff'
  primary-container: '#0a2540'
  on-primary-container: '#768dad'
  inverse-primary: '#b0c8eb'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#00110f'
  on-tertiary: '#ffffff'
  tertiary-container: '#002926'
  on-tertiary-container: '#409890'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#b0c8eb'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#314865'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#9cf2e8'
  tertiary-fixed-dim: '#80d5cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#00504a'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2.5rem
  margin-desktop: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 3rem
---

## Brand & Style

This design system expresses authoritative corporate stewardship, technological forward momentum, and institutional integrity for Vedanta Enterprises. Designed for enterprise stakeholders, B2B partners, global institutional investors, and talent, the interface balances executive prestige with modern digital agility.

The visual direction employs a refined **Corporate Modern Minimalist** aesthetic. Layouts emphasize deliberate asymmetry, expansive negative space, and calm optical pacing. Depth is established through crystalline structural borders, subtle background tiering, and soft diffused shadows rather than heavy decorative treatments. The overall experience feels institutional yet progressive, disciplined yet welcoming.

## Colors

The palette is engineered around high-contrast structural discipline and trust-inducing tones:

- **Primary (`#0A2540`)**: A deep sovereign navy blue serving as the core anchor for dominant visual hierarchy, key brand assets, primary actions, and hero sections.
- **Secondary (`#0284C7`)**: A bright corporate azure providing high-visibility interaction cues, active state indicators, focus borders, and key data points.
- **Tertiary (`#0F766E`)**: A deep slate teal used sparingly for sustainability metrics, enterprise validation badges, and fiscal stability signals.
- **Neutral (`#64748B`)**: Slate neutral establishing balanced typography hierarchy, inactive borders, and structural dividing planes.
- **Surfaces**: Pure crisp white (`#FFFFFF`) for elevated cards and core interactive canvases; cool porcelain slate (`#F8FAFC`) for foundation canvases, section alternating rows, and data tables. Structural hairpins and low-contrast borders use `#E2E8F0`.

## Typography

The typographic system pairs the structural warmth and precision of Plus Jakarta Sans for titles and strategic calls-to-action with the utilitarian legibility of Inter for continuous reading and dense enterprise data.

- **Headlines**: Use tighter negative tracking (`-0.01em` to `-0.03em`) to preserve visual density in large viewport formats.
- **Body**: Uses standard tracking with open line-heights (`1.5` to `1.6`) to maintain effortless scannability across reports, governance summaries, and service descriptions.
- **Labels & Overlines**: Rendered in uppercase with generous tracking (`0.06em`) for category pills, metric markers, and micro-navigation headers.

## Layout & Spacing

The system runs on a dynamic 12-column responsive fluid grid designed to frame extensive corporate information cleanly.

- **Desktop (1200px+)**: 12-column grid, max-width bounded at 1360px to preserve comfortable scan lengths, 80px section padding, `32px` (`2rem`) gutters, and `80px` (`5rem`) outer canvas margins.
- **Tablet (768px - 1199px)**: 8-column layout with `24px` (`1.5rem`) gutters and `40px` (`2.5rem`) side margins.
- **Mobile (< 768px)**: 4-column layout with `16px` (`1rem`) gutters and `16px` (`1rem`) outer margins. Multi-column cards collapse to single-column stacks with consistent `space-lg` vertical spacing.

Spacing is disciplined around an 8px base module: internal component padding leverages `space-xs` through `space-md`, while layout boundaries and container clearances use `space-lg` and `space-xl`.

## Elevation & Depth

Visual hierarchy uses flat surfaces bounded by clean outlines, supplemented by soft ambient drop shadows that emulate subtle architectural lighting.

- **Flat/Resting State**: Pure white cards placed on slate canvas (`#F8FAFC`) bound by 1px solid `#E2E8F0` hairline strokes. No shadow is applied at rest to keep interfaces uncluttered.
- **Card Hover Elevation**: `0px 10px 25px -5px rgba(10, 37, 64, 0.06), 0px 8px 10px -6px rgba(10, 37, 64, 0.04)`. Outlines shift from `#E2E8F0` to `#CBD5E1`.
- **Navigation & Sticky Appbars**: Backdrop frosted surface using `rgba(255, 255, 255, 0.88)` with `12px` blur and an understated bottom stroke `rgba(226, 232, 240, 0.8)`.
- **Floating Modals & Dropdowns**: `0px 20px 30px -10px rgba(10, 37, 64, 0.12), 0px 1px 3px rgba(10, 37, 64, 0.05)`, edged with a 1px solid `#E2E8F0` border.

## Shapes

The design system incorporates **Pill-shaped (Level 3)** geometry selectively for interactive components and high-salience chips, balanced against slightly softer radii for content containers to maintain corporate authority:

- **Buttons & Chips**: Pure pill contouring (`border-radius: 9999px`) to create tactile focal points and accessible touch boundaries.
- **Cards, Panels & Modals**: Soft structured containment (`rounded-lg` / `16px`) providing stable rectangular scaffolding for metrics, content grids, and balance sheets.
- **Input Fields**: Softened rectangles (`rounded-md` / `8px`) that provide visual contrast against fully rounded CTA buttons.

## Components

### Buttons
- **Primary Pill**: Background `#0A2540`, text `#FFFFFF`, border none, radius `9999px`. Height `48px`, padding `0 28px`. Hover: Background `#0F2C59`, subtle lift.
- **Secondary Pill (Accent)**: Background `#0284C7`, text `#FFFFFF`, radius `9999px`. Hover: Background `#0369A1`.
- **Outline Pill**: Background transparent, border `1.5px` solid `#0A2540`, text `#0A2540`. Hover: Background `#0A2540`, text `#FFFFFF`.
- **Ghost/Tertiary**: Background transparent, text `#0A2540`, font weight 600. Hover: Text `#0284C7`, icon nudges right by 4px.

### Chips & Badges
- **Status/Metric Badges**: Pill-shaped (`9999px`), padding `4px 12px`, typography `label-sm`. Background `rgba(2, 132, 199, 0.08)`, text `#0284C7`.
- **Filter Chips**: Background `#FFFFFF`, border `1px` solid `#E2E8F0`, text `#64748B`. Active: Background `#0A2540`, text `#FFFFFF`, border `#0A2540`.

### Cards & Metrics
- **Executive Metric Card**: Background `#FFFFFF`, 1px solid `#E2E8F0`, radius `16px`, padding `32px`. Includes a top-right accent badge and secondary-colored numeric indicator (`display-hero-mobile`).
- **Feature Card**: Subtle hover shift with 1px border transitioning to `#0284C7` and faint elevation shadow.

### Form Inputs
- **Text Fields**: Background `#FFFFFF`, border `1px` solid `#CBD5E1`, radius `8px`, height `48px`, padding `0 16px`, text `#0A2540`. Focus: Border `1.5px` solid `#0284C7`, outline `3px` solid `rgba(2, 132, 199, 0.15)`.
- **Checkboxes & Radios**: 18px dimensions, border `1.5px` solid `#CBD5E1`, filled state `#0A2540` with white glyph, radius 4px (checkbox) or circular (radio).

### Navigation & Menus
- **Global Header**: Fixed desktop height `72px`, pure white translucent background blur, containing pill action triggers, high-contrast navigation links with animated underline markers, and secondary tier mega-dropdowns.