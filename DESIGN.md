---
name: JS Present
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
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#7a580f'
  on-secondary: '#ffffff'
  secondary-container: '#ffd07d'
  on-secondary-container: '#79570d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1e'
  on-tertiary-container: '#818486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffdea8'
  secondary-fixed-dim: '#edc06e'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5e4200'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Noto Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Noto Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Noto Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Noto Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

This design system is engineered for a premium B2B distribution platform catering to government agencies and public institutions. The visual narrative balances **Institutional Authority** with **High-End Hospitality**, ensuring the user feels they are engaging with a reliable partner capable of delivering excellence at scale.

The design style is **Refined Minimalism**. It utilizes expansive white space to frame high-quality product photography, treating every promotional item as a curated luxury object rather than a commodity. The interface avoids unnecessary decorative elements, opting instead for precise alignment, generous margins, and subtle transitions to convey a sense of calm efficiency and "Quick and Easy" service.

**Target Audience:** Procurement officers, HR directors, and government administrative staff.
**Emotional Response:** Confidence, respect, curated quality, and professional ease.

## Colors

The palette is anchored by **Midnight Navy**, providing a foundation of stability, trust, and institutional weight. This is complemented by **Heritage Gold**, used sparingly as a premium accent to highlight curated selections, "Best-in-Class" badges, and primary calls to action.

- **Primary (Midnight Navy):** Used for navigation, headers, and primary typography to establish authority.
- **Secondary (Heritage Gold):** Reserved for luxury cues, premium curation indicators, and high-priority interactions.
- **Surface (Cloud Gray):** A very light, cool-toned neutral used for background sections to maintain a clean, airy feel.
- **Neutral (Slate):** Used for secondary text and borders to ensure legibility without competing with the primary brand colors.

## Typography

The typography utilizes **Noto Sans** (or its optimized web variant) to bridge the gap between accessibility and elegance. The hierarchy is structured to be "Information First," allowing busy procurement officers to scan specifications and delivery timelines effortlessly.

- **Display & Headlines:** Use tight letter-spacing and bold weights in Midnight Navy to command attention.
- **Body Text:** Set with generous line-height (1.6) to ensure readability during long research sessions or catalog browsing.
- **Labels:** Use **Inter** for functional metadata (SKUs, dimensions, stock levels). Small caps and slight tracking are applied to labels to provide a sophisticated, "architectural" feel to technical data.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for desktop to maintain a "catalog-on-a-pedestal" feel, transitioning to a fluid model for mobile devices.

- **The 8px Rhythm:** All spacing, padding, and margins are multiples of 8px. 
- **Section Breathing Room:** Large vertical gaps (120px+) separate major content blocks to prevent the interface from feeling cluttered or "cheap."
- **Desktop:** A 12-column grid with 24px gutters. Content is centered within a 1280px container.
- **Mobile:** A 4-column fluid grid. Margins are reduced to 20px, and vertical section gaps are compressed to 64px to maintain momentum while scrolling.

## Elevation & Depth

To maintain a minimalist and professional aesthetic, this design system avoids heavy shadows in favor of **Tonal Layering** and **Ghost Outlines**.

- **Surface Tiers:** The primary background is white. Secondary content (filters, sidebars) sits on a Cloud Gray (#F8FAFC) surface.
- **Low-Contrast Outlines:** Instead of shadows, use 1px borders in a soft Slate (#E2E8F0) to define card boundaries.
- **The "Premium Lift":** Only the primary product cards and "Order Now" modules receive an elevation effect. Use a very soft, highly diffused Midnight Navy shadow (4% opacity, 20px blur) to suggest the item is physically resting on a surface.

## Shapes

The shape language is **Soft (Level 1)**. Sharp 0px corners feel too aggressive for a hospitality-focused brand, while overly rounded corners feel too "tech-startup." 

- **Base Radius (4px):** Applied to buttons, input fields, and small UI elements to provide a subtle professional finish.
- **Large Radius (8px):** Applied to product cards and modal containers to soften the overall layout.
- **Product Photography:** Images should always be contained in these soft-cornered frames, never full-bleed circles or organic shapes.

## Components

### Buttons
- **Primary:** Solid Midnight Navy with white text. 4px radius. 
- **Premium:** Heritage Gold background with Midnight Navy text. Used exclusively for "Checkout" or "Request Premium Curation."
- **Ghost:** 1px Slate border with Midnight Navy text. Used for secondary actions like "View Specifications."

### Product Cards
- Clean white background with a 1px Slate border. 
- Product imagery must be high-resolution on a neutral gray or white background. 
- Use the Heritage Gold accent for "In Stock" or "Public Office Approved" badges.

### Input Fields & Selectors
- Minimalist design: Bottom-border only or very light 1px surrounding border. 
- Focus state uses a 2px Midnight Navy bottom-border to signal professional precision.

### Status Indicators
- **Delivery Progress:** A sophisticated linear tracker using Midnight Navy for completed steps and Heritage Gold for the "In-Transit" status, emphasizing the "Sense of Gratitude" and reliable delivery.

### Lists & Tables
- Used for bulk ordering. High-density but clear, with subtle alternating row colors in Cloud Gray. Column headers use the Small-Cap Inter label style.