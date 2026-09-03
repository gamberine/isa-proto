---
name: ISA Engineering Precision System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d4daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e8eeff'
  surface-container-high: '#e3e8f9'
  surface-container-highest: '#dde2f3'
  on-surface: '#161c27'
  on-surface-variant: '#424752'
  inverse-surface: '#2a303d'
  inverse-on-surface: '#ecf0ff'
  outline: '#727783'
  outline-variant: '#c2c6d4'
  surface-tint: '#055cb9'
  primary: '#00448c'
  on-primary: '#ffffff'
  primary-container: '#005bb7'
  on-primary-container: '#c4d7ff'
  inverse-primary: '#aac7ff'
  secondary: '#545f72'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f7'
  on-secondary-container: '#586377'
  tertiary: '#40464d'
  on-tertiary: '#ffffff'
  tertiary-container: '#575e65'
  on-tertiary-container: '#d1d7df'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e3ff'
  primary-fixed-dim: '#aac7ff'
  on-primary-fixed: '#001b3e'
  on-primary-fixed-variant: '#00458e'
  secondary-fixed: '#d8e3fa'
  secondary-fixed-dim: '#bcc7dd'
  on-secondary-fixed: '#111c2c'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#dde3eb'
  tertiary-fixed-dim: '#c1c7cf'
  on-tertiary-fixed: '#161c22'
  on-tertiary-fixed-variant: '#41474e'
  background: '#f9f9ff'
  on-background: '#161c27'
  surface-variant: '#dde2f3'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin-desktop: 64px
  margin-mobile: 16px
  container-max-width: 1280px
---

## Brand & Style

The design system for ISA Engenharia is built on the pillars of **Precision, Integration, and Industrial Modernity**. It targets high-level industrial stakeholders, plant managers, and technical engineers who require clarity and reliability. 

The visual style is **Corporate / Modern** with subtle **Minimalist** influences. It avoids unnecessary decorative flourish in favor of functional aesthetics that mirror the "Automation Systems Integration" core of the business. The interface should feel structured and trustworthy, using a systematic approach to hierarchy and space to evoke a sense of organized expertise.

## Colors

The palette is an evolution of the traditional industrial blue and grey seen in the legacy brochures.
- **Primary Blue (#005BB7):** A deep, authoritative blue for branding and primary actions.
- **Accent Blue (#007AFF):** A more vibrant, digital-first blue used for interactive states and highlights to provide modern energy.
- **Industrial Greys:** A range of cool-toned greys (#4A5568, #E2E8F0) used for secondary text and structural containers, providing a clean, "aluminum" or "steel" feel.
- **Status Colors:** Standardized success (Green), warning (Amber), and error (Red) colors should be used with high saturation to ensure they are visible in high-density data environments.

## Typography

This design system utilizes **Hanken Grotesk** for headlines to provide a sharp, contemporary engineering aesthetic. Its geometric clarity suggests technical precision. **Inter** is used for body text and UI labels due to its exceptional legibility in data-heavy industrial applications.

Headlines should be set with tighter letter spacing to maintain a "solid" feel, while labels and captions use slightly increased tracking to ensure readability at small sizes on technical dashboards.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop and a **Fluid** model for mobile.
- **Desktop:** 12-column grid, 1280px max-width, 24px gutters.
- **Tablet:** 8-column grid, fluid width.
- **Mobile:** 4-column grid, fluid width, 16px side margins.

A consistent 4px baseline unit (8px, 16px, 24px, 32px, 48px, 64px) governs all padding and margins to create a rhythmic, predictable layout that mirrors the organized nature of engineering schematics.

## Elevation & Depth

To maintain a clean and professional look, hierarchy is established primarily through **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows.

- **Surface 0 (Background):** #F8FAFC (Light cool grey).
- **Surface 1 (Cards/Containers):** #FFFFFF with a 1px border of #E2E8F0.
- **Elevation 1 (Hover/Active):** A very soft, diffused shadow (0px 4px 12px rgba(0, 0, 0, 0.05)) to indicate interactivity without breaking the flat, technical aesthetic.

Depth is used sparingly to draw attention to active input fields or primary call-to-action buttons.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding provides a modern touch while maintaining the structural "blocky" feel of industrial hardware. 

- **Small elements (Buttons, Inputs):** 4px (0.25rem) radius.
- **Large elements (Cards, Sections):** 8px (0.5rem) radius.
- **Status Tags:** Fully rounded (pill) to distinguish them from interactive buttons.

## Components

### Buttons
- **Primary:** Solid #005BB7 with white text. High contrast, 4px corner radius.
- **Secondary:** Outlined with #005BB7. For secondary actions like "Download Technical Specs."
- **Tertiary:** Text-only with Accent Blue, used for less critical navigation.

### Input Fields
Inputs should feature a subtle grey background (#F1F5F9) and a 1px border. On focus, the border transitions to Primary Blue with a 2px "ring" for high visibility.

### Cards
Cards are the primary container for services like "Industrial Automation" or "Electrical Engineering." They feature a white background, a light grey border, and use Hanken Grotesk for the title.

### Industrial Status Indicators
Specifically for this design system, use "Data Chips" to show system health or project status. These should use semi-transparent backgrounds with high-contrast text (e.g., a soft green background with dark green text for "Active").

### Lists
Use "Technical Lists" with custom bullet points—geometric squares or arrows—that align with the logo's diamond and square motifs.