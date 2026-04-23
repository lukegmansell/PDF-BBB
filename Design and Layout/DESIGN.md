---
name: Coroner's Office Tooling
colors:
  surface: '#121319'
  surface-dim: '#121319'
  surface-bright: '#383940'
  surface-container-lowest: '#0c0e14'
  surface-container-low: '#1a1b21'
  surface-container: '#1e1f26'
  surface-container-high: '#282a30'
  surface-container-highest: '#33343b'
  on-surface: '#e2e2ea'
  on-surface-variant: '#cfc4c5'
  inverse-surface: '#e2e2ea'
  inverse-on-surface: '#2f3037'
  outline: '#988e90'
  outline-variant: '#4c4546'
  surface-tint: '#c6c6c6'
  primary: '#c6c6c6'
  on-primary: '#303030'
  primary-container: '#000000'
  on-primary-container: '#757575'
  inverse-primary: '#5e5e5e'
  secondary: '#e2c466'
  on-secondary: '#3c2f00'
  secondary-container: '#725c00'
  on-secondary-container: '#f5d676'
  tertiary: '#c6c6c6'
  on-tertiary: '#303030'
  tertiary-container: '#000000'
  on-tertiary-container: '#757575'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#ffe080'
  secondary-fixed-dim: '#e2c466'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#564500'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#121319'
  on-background: '#e2e2ea'
  surface-variant: '#33343b'
typography:
  headline-lg:
    fontFamily: Public Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  code-data:
    fontFamily: Public Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin: 32px
  container-padding: 20px
  stack-sm: 8px
  stack-md: 16px
---

## Brand & Style

The brand personality for this design system is authoritative, somber, and hyper-efficient. It is designed for an institutional environment where clarity of information and dignity of process are paramount. The transition to a **Dark Mode** default provides a focused, low-strain environment for medical examiners, investigators, and administrative staff working in varied lighting conditions, mirroring the serious and discreet nature of legal and medical documentation.

The design style utilizes **Minimalism** with a **Modular/Boxed** structure. It leverages structural containment to organize complex medical and legal data. The emotional response is one of reliability and quiet confidence, avoiding clinical coldness by introducing warmth through precise gold accents against a professional, deep slate and midnight backdrop.

## Colors

This design system uses a sophisticated, high-contrast dark palette optimized for professional rigor and reduced eye fatigue during extended use.

- **Primary (Deep Black/Slate):** Used for fundamental structural elements and high-contrast inversions. In this dark theme, it serves as the deepest layer of the interface.
- **Secondary (Gold):** Used as a high-visibility accent for "Verified" statuses, active navigation states, and critical branding highlights. It denotes prestige and official certification.
- **Neutral/Tertiary:** Mid-to-deep greys and slates are used for secondary metadata and disabled states, ensuring a clear hierarchy without overwhelming the user with pure black.
- **Surface:** Deep charcoal and slate-grey variants are reserved for modular boxes to differentiate them from the primary background, creating a sense of organized "slabs" of data.

## Typography

The typography uses **Public Sans** to maintain an institutional and official character. The typeface was selected for its exceptional legibility in tabular data and administrative forms, particularly when rendered as light text on deep, dark backgrounds.

Headlines are tight and heavy to provide clear section anchoring. Body text is optimized for long-form reading of reports. Label styles utilize uppercase tracking for metadata headers, creating a clear distinction between "Field Label" and "Field Value" in high-density views.

## Layout & Spacing

The layout follows a **Fixed Grid** modular philosophy. Information is organized into distinct "boxed" containers that align to a 12-column grid system. 

The spacing rhythm is disciplined, using a 4px base unit. Modular boxes should have consistent internal padding of 20px. Between modules, a 24px gutter ensures that distinct data sets (e.g., Case Information vs. Evidence Logs) remain visually separate and easy to scan, even in a low-light dark interface.

## Elevation & Depth

This design system avoids deep shadows, utilizing **Tonal Layering** and **Low-Contrast Outlines** to define hierarchy in dark mode.

Depth is achieved by placing slightly lighter charcoal containers on the primary dark background. To further define these modules, a 1px border using a subtle slate-grey is applied. No ambient shadows are used; instead, "elevation" is signaled by subtle shifts in background value (moving from darker to lighter shades) or a change in border color to Gold for active or selected states.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the institutional aesthetic without becoming overly casual or playful. 

All modular boxes, input fields, and buttons share this uniform corner radius. For smaller elements like chips or status indicators, the same 0.25rem radius is used to maintain a consistent geometric language across the entire suite, ensuring a cohesive look for all UI components.

## Components

- **Buttons:** Primary buttons are Solid Gold with Deep Slate or Black text for maximum prominence and readability. Secondary buttons use a Slate 1px outline with light-grey text.
- **Modular Boxes (Cards):** These are the primary vessel for content. They feature a elevated dark background, a subtle 1px border, and no shadow.
- **Input Fields:** Use a deep background fill with a subtle 4-sided border. Focus states transition the border to Gold.
- **Status Chips:** Use a neutral palette (Grey, Blue-Grey) for most states. Use Gold for "Certified" or "Official" statuses. 
- **Data Tables:** High-density, no vertical lines, using subtle horizontal dividers in mid-range Slates. Header rows use the `label-caps` typography style.
- **Institutional Seals:** Subtle watermark placements or small gold-accented icons to denote official government tooling branding.