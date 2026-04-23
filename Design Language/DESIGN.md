---
name: Midnight Gilded Dashboard
colors:
  surface: '#15130f'
  surface-dim: '#15130f'
  surface-bright: '#3c3933'
  surface-container-lowest: '#100e0a'
  surface-container-low: '#1e1b17'
  surface-container: '#221f1a'
  surface-container-high: '#2d2a24'
  surface-container-highest: '#38342f'
  on-surface: '#e8e1d9'
  on-surface-variant: '#cfc5b5'
  inverse-surface: '#e8e1d9'
  inverse-on-surface: '#33302b'
  outline: '#989081'
  outline-variant: '#4c4639'
  surface-tint: '#e1c380'
  primary: '#e1c380'
  on-primary: '#3e2e00'
  primary-container: '#b29758'
  on-primary-container: '#403000'
  inverse-primary: '#725b23'
  secondary: '#bfc2f9'
  on-secondary: '#282c59'
  secondary-container: '#3f4371'
  on-secondary-container: '#aeb1e6'
  tertiary: '#c2c4e6'
  on-tertiary: '#2b2e49'
  tertiary-container: '#9598b8'
  on-tertiary-container: '#2d304b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdf99'
  primary-fixed-dim: '#e1c380'
  on-primary-fixed: '#251a00'
  on-primary-fixed-variant: '#58440c'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bfc2f9'
  on-secondary-fixed: '#131643'
  on-secondary-fixed-variant: '#3f4371'
  tertiary-fixed: '#dfe0ff'
  tertiary-fixed-dim: '#c2c4e6'
  on-tertiary-fixed: '#161a33'
  on-tertiary-fixed-variant: '#424560'
  background: '#15130f'
  on-background: '#e8e1d9'
  surface-variant: '#38342f'
typography:
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  stat-value:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.1'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-padding: 24px
  element-gap: 16px
  section-margin: 32px
  gutter: 20px
---

## Brand & Style

This design system is built on a **Corporate Modern** foundation with a sophisticated, moody twist. It aims to bridge the gap between high-utility SaaS platforms and premium, executive-level interfaces. The aesthetic is defined by a "middle-ground" dark mode that avoids absolute blacks, opting instead for deep navy tones that feel more expansive and less fatiguing.

The brand personality is **authoritative, focused, and refined**. It evokes a sense of calm productivity, using muted gold accents to draw the eye toward critical data and primary actions without overwhelming the user. The heavy use of large rounded corners softens the professional tone, making the application feel approachable and modern.

## Colors

The palette is anchored by a deep navy hierarchy. The **Primary Background** (#191c40) provides a stable, low-energy canvas. **Card Surfaces** (#404472) create a clear physical distinction for content areas, while a lighter variant (#5c5f7c) is reserved for interactive elements like hover states or secondary tabs.

The **Muted Gold** (#b29758) is the primary engine for visual hierarchy. It is used sparingly for high-value data, active selection indicators, and primary call-to-action buttons. Typography is kept to a **Light Grey** (#c3c0c0) to maintain high legibility while reducing the harsh flicker effect of pure white text on dark backgrounds.

## Typography

This system uses a pairing of **Space Grotesk** for headlines and data values, and **Inter** for functional UI and body copy. This combination balances technical precision with universal readability.

- **Data Visibility:** Statistics and key values use Space Grotesk in the Muted Gold accent color to ensure they are the first thing a user sees.
- **Readability:** Body text uses Inter with a generous line height (1.6) to ensure long-form content remains legible against the dark blue-grey containers.
- **Hierarchy:** Labels use a semi-bold weight and slight letter spacing to differentiate them from interactive text.

## Layout & Spacing

The layout follows a **fluid grid** model designed for dashboard environments where information density must be balanced with whitespace. 

- **Grid:** A 12-column layout with 20px gutters. 
- **Rhythm:** An 8px base unit governs all spacing. 
- **Containment:** Parent containers use a 24px internal padding to provide a "breathable" frame around content. 
- **Grouping:** Related items (like summary blocks) are grouped with 16px gaps, while major sections are separated by 32px to create clear mental boundaries.

## Elevation & Depth

Depth is achieved through **Tonal Layering** rather than traditional shadows. Because the background is already saturated, shadows can appear muddy.

1.  **Level 0 (Floor):** The primary navy background.
2.  **Level 1 (Sections):** Dark blue-grey surfaces that appear to sit just above the floor.
3.  **Level 2 (Interactives):** Buttons and active tabs use color shifts (lighter blue-grey or gold) to indicate they are "raised" and ready for interaction.
4.  **Accents:** Dashed borders in Muted Gold are used for "drop zones" or empty states to create a sense of potential space without adding physical weight.

## Shapes

The design system utilizes a **Rounded (Level 2)** shape language to create a friendly, modern silhouette. 

- **Buttons & Small Inputs:** 0.5rem (8px) corner radius.
- **Standard Cards/Containers:** 1rem (16px) corner radius.
- **Large Layout Sections:** 1.5rem (24px) corner radius.

Avoid sharp 90-degree angles entirely. This consistency in curvature ensures that even complex layouts feel unified and organic.

## Components

### Buttons
- **Primary:** Solid Muted Gold (#b29758) with dark navy text. Rounded-lg (16px).
- **Secondary:** Solid Dark Blue-Grey (#5c5f7c) with light grey text. Rounded-lg (16px).

### Cards & Sections
- Background: #404472.
- Padding: 24px.
- Border: None, unless it is a "Drop Zone," which uses a dashed 1px border in #b29758.

### Tabs
- **Active:** Matches the secondary card color (#404472) but sits on a slightly darker track.
- **Indicator:** A 2px Muted Gold underline or left-hand pill can be used for secondary navigation markers.

### Input Fields
- Surfaces should be slightly darker than the card they sit on to create an "inset" feel.
- Large 16px corner radius to match the overall shape language.

### Stat Blocks
- Large, bold values in Muted Gold.
- Labels in Light Grey, positioned above the value with 4px of spacing.