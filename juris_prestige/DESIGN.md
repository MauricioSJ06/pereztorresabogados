---
name: Juris Prestige
colors:
  surface: '#faf8ff'
  surface-dim: '#dad9e0'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f9'
  surface-container: '#eeedf3'
  surface-container-high: '#e9e7ee'
  surface-container-highest: '#e3e2e8'
  on-surface: '#1a1b20'
  on-surface-variant: '#444650'
  inverse-surface: '#2f3035'
  inverse-on-surface: '#f1f0f6'
  outline: '#757682'
  outline-variant: '#c4c6d2'
  surface-tint: '#415ca0'
  primary: '#002363'
  on-primary: '#ffffff'
  primary-container: '#1d3a7d'
  on-primary-container: '#8da7f1'
  inverse-primary: '#b3c5ff'
  secondary: '#735a3a'
  on-secondary: '#ffffff'
  secondary-container: '#fddab2'
  on-secondary-container: '#785e3e'
  tertiary: '#1a2a36'
  on-tertiary: '#ffffff'
  tertiary-container: '#30404d'
  on-tertiary-container: '#9babba'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#284387'
  secondary-fixed: '#ffddb6'
  secondary-fixed-dim: '#e2c19b'
  on-secondary-fixed: '#291801'
  on-secondary-fixed-variant: '#594325'
  tertiary-fixed: '#d4e5f5'
  tertiary-fixed-dim: '#b8c8d8'
  on-tertiary-fixed: '#0d1d29'
  on-tertiary-fixed-variant: '#394955'
  background: '#faf8ff'
  on-background: '#1a1b20'
  surface-variant: '#e3e2e8'
  oxford-navy: '#1D3A7D'
  heritage-gold: '#A68966'
  statute-gray: '#333333'
  parchment: '#F9F9F9'
  silver-lining: '#DADADA'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  callout:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 32px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

This design system is crafted for a high-end boutique legal practice, prioritizing authority, heritage, and meticulous attention to detail. The brand personality is "Institutional Excellence"—it feels established and unshakeable, yet modern enough to navigate contemporary legal complexities.

The visual style is **Minimalist with an Editorial lean**. It leverages heavy whitespace to convey a sense of calm and clarity, essential in the legal sector. High contrast between deep navy and warm metallic accents creates a premium atmosphere without resorting to "luxury" cliches. The aesthetic avoids generic imagery in favor of structural lines, architectural geometry, and superior typography.

## Colors

The palette is rooted in a deep **Oxford Navy**, symbolizing stability and legal tradition. This is paired with **Heritage Gold**, a refined bronze-gold accent derived from the structural elements of the brand logo, used sparingly to highlight key actions and milestones.

- **Primary (Oxford Navy):** Used for headers, primary buttons, and critical branding elements.
- **Secondary (Heritage Gold):** Reserved for subtle accents, thin borders, and premium interactive states.
- **Neutral (Statute Gray):** Primary color for body text to ensure maximum readability against white or light gray surfaces.
- **Backgrounds:** A mix of pure white and a subtle "silver-lining" gray (#DADADA) creates soft depth without the need for heavy shadows.

## Typography

This design system employs a high-contrast typographic pairing to balance tradition and modernity.

**Playfair Display** is used for all headlines and display text. Its high-contrast serifs evoke the feeling of printed legal briefs and classic stationery. Use tighter letter-spacing for large display sizes to maintain a sophisticated "editorial" look.

**Inter** provides a functional, highly legible counterpoint for all body copy, forms, and data. Its neutral character ensures that the focus remains on the legal content and the elegance of the headers. For labels and small UI hints, use Inter in uppercase with increased tracking to create a "legal document" metadata feel.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a contained, professional appearance, transitioning to a fluid model on mobile devices.

- **Rhythm:** A strict 8px baseline grid is used. Generous vertical spacing (section-padding) is essential to the "Boutique" feel, preventing the interface from feeling crowded or rushed.
- **Grid:** A 12-column grid with wide 32px gutters. Content should often be centered with wide margins to create an "open book" feel.
- **Responsive:** On mobile, margins reduce to 20px, and vertical section padding scales down to 64px to maintain momentum while browsing.

## Elevation & Depth

This design system avoids heavy shadows, instead utilizing **Tonal Layers** and **Low-Contrast Outlines** to communicate hierarchy.

- **Flat Depth:** Use subtle background color shifts (White to #F9F9F9) to separate sections.
- **Thin Lines:** Utilize 1px borders in `silver-lining` (#DADADA) or `heritage-gold` (#A68966) to define cards and input fields.
- **Focus States:** Instead of a shadow, use a 1px `oxford-navy` border for active elements.
- **Imagery:** Any used photography should be high-contrast architectural or abstract textures (marble, steel, wood) with a cool-toned treatment.

## Shapes

The design system uses **Sharp (0px)** corners for all primary UI elements. In the legal context, sharp corners convey precision, rigor, and a "no-nonsense" professional attitude. 

The only exception is for circular icons or avatar containers. Buttons, input fields, cards, and navigation menus must maintain strict 90-degree angles to align with the architectural and structured nature of the brand.

## Components

### Buttons
Primary buttons are solid `oxford-navy` with white text. Secondary buttons use a 1px `heritage-gold` border with navy text. All buttons have 0px roundedness and use the `label-caps` typographic style for an authoritative feel.

### Input Fields
Fields are defined by a bottom-only border (1px) in `silver-lining`, which turns into a full `oxford-navy` outline only on focus. This mimics the look of a signature line on a legal document.

### Cards
Cards are used to house attorney profiles or practice areas. They should have no shadow and a thin `silver-lining` border. On hover, the border transitions to `heritage-gold`.

### Navigation
The main navigation uses a "pinned" approach with a thin gold line at the top of the header. Links should use the `label-caps` style.

### Data Tables
Tables should be minimalist, removing all vertical dividers. Use thin horizontal `silver-lining` rules and `body-md` for row content to emphasize clarity and ease of review.