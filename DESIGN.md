---
name: Coroner's Office Tooling
colors:
  surface: '#031427'
  surface-dim: '#031427'
  surface-bright: '#2a3a4f'
  surface-container-lowest: '#000f21'
  surface-container-low: '#0b1c30'
  surface-container: '#102034'
  surface-container-high: '#1b2b3f'
  surface-container-highest: '#26364a'
  on-surface: '#d3e4fe'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d3e4fe'
  inverse-on-surface: '#213145'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#e8c344'
  on-secondary: '#3c2f00'
  secondary-container: '#ae8d03'
  on-secondary-container: '#342800'
  tertiary: '#c4c7c9'
  on-tertiary: '#2d3133'
  tertiary-container: '#15181a'
  on-tertiary-container: '#7e8183'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffe081'
  secondary-fixed-dim: '#e8c344'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#564500'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#031427'
  on-background: '#d3e4fe'
  surface-variant: '#26364a'
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

The brand personality for this design system is authoritative, somber, and hyper-efficient. It is designed for an institutional environment where clarity of information and dignity of process are paramount. The transition to a **Dark Mode** default provides a low-fatigue environment for medical examiners, investigators, and administrative staff who require high-density data visualization during long shifts.

The design style utilizes **Minimalism** with a **Modular/Boxed** structure. It leverages structural containment to organize complex medical and legal data. The emotional response is one of reliability and quiet confidence, avoiding clinical coldness by introducing warmth through precise gold accents against a deep, professional slate backdrop.

## Colors

This design system uses a high-contrast dark palette optimized for professional rigor and reduced eye strain.

- **Primary (Deep Slate):** The foundation of the interface. Used for backgrounds, structural elements, and deep containers. It provides a serious, grounded anchor for all content.
- **Secondary (Gold):** Used as a high-visibility accent for "Verified" statuses, active navigation states, and critical branding highlights. It denotes prestige and official certification.
- **Neutral/Tertiary:** Cool whites (`#F8FAFC`) are used for high-contrast typography, while medium slates are used for secondary metadata.
- **Surface:** Darker slate variants are reserved for modular boxes to differentiate them from the primary background.

## Typography

The typography uses **Public Sans** to maintain an institutional and official character. The typeface was selected for its exceptional legibility in tabular data and administrative forms, particularly when rendered as light text on dark backgrounds.

Headlines are tight and heavy to provide clear section anchoring. Body text is optimized for long-form reading of reports. Label styles utilize uppercase tracking for metadata headers, creating a clear distinction between "Field Label" and "Field Value."

## Layout & Spacing

The layout follows a **Fixed Grid** modular philosophy. Information is organized into distinct "boxed" containers that align to a 12-column grid system. 

The spacing rhythm is disciplined, using a 4px base unit. Modular boxes should have consistent internal padding of 20px. Between modules, a 24px gutter ensures that distinct data sets (e.g., Case Information vs. Evidence Logs) remain visually separate and easy to scan.

## Elevation & Depth

This design system avoids deep shadows, utilizing **Tonal Layering** and **Low-Contrast Outlines** to define hierarchy in dark mode.

Depth is achieved by placing slightly lighter slate containers on the deep slate (`#0F172A`) background. To further define these modules, a 1px border using a subtle slate-grey is applied. No ambient shadows are used; instead, "elevation" is signaled by subtle shifts in background value or a change in border color to Gold for active or selected states.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the institutional aesthetic without becoming overly casual or playful. 

All modular boxes, input fields, and buttons share this uniform corner radius. For smaller elements like chips or status indicators, the same 0.25rem radius is used to maintain a consistent geometric language across the entire suite.

## Components

- **Buttons:** Primary buttons are Solid Gold with Dark Slate text for maximum prominence. Secondary buttons use a Slate 1px outline with Light Slate text.
- **Modular Boxes (Cards):** These are the primary vessel for content. They feature a background one step lighter than the page background, a subtle 1px border, and no shadow.
- **Input Fields:** Use a dark fill with a subtle 4-sided border. Focus states transition the border to Gold.
- **Status Chips:** Use a neutral palette (Grey, Blue-Grey) for most states. Use Gold for "Certified" or "Official" statuses. 
- **Data Tables:** High-density, no vertical lines, using subtle horizontal dividers in mid-range Slates. Header rows use the `label-caps` typography style.
- **Institutional Seals:** Subtle watermark placements or small gold-accented icons to denote official government tooling branding.