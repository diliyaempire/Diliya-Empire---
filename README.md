---
name: Luxe Sri Lankan Heritage
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4d4635'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#415ba4'
  on-tertiary: '#ffffff'
  tertiary-container: '#97b0ff'
  on-tertiary-container: '#254188'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#27438a'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
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
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The design system for this brand is rooted in a "Modern Imperial" aesthetic. It balances the rich heritage of Sri Lankan luxury with a contemporary, minimalist European interface style. The target audience is discerning consumers seeking premium products, requiring a UI that feels high-end, trustworthy, and effortless.

The visual direction follows **Minimalism** with a **High-Contrast** edge. It utilizes generous whitespace (the "White" foundation) to allow product photography to breathe, punctuated by "Deep Black" architectural elements that ground the experience. The use of gold is surgical—reserved for calls to action and premium signifiers to maintain its value.

## Colors
This design system employs a tiered color strategy to define hierarchy and prestige.
- **Primary (Gold):** Used exclusively for interactive elements like primary buttons, active states, and "Limited Edition" badges. It should never be used for large background areas.
- **Secondary (Deep Black):** Used for structural grounding—headers, footers, and full-bleed section dividers. It creates a "frame" for the content.
- **Surface & Text:** Body text uses an "Off-black" (#1A1A1A) on white backgrounds to reduce eye strain while maintaining high contrast. On black surfaces, text shifts to pure white or subtle gold accents.

## Typography
The typography pairing establishes a "Classical Modernist" rhythm. 
- **Headlines:** Use *Playfair Display*. Its high-contrast serifs evoke traditional luxury and editorial sophistication. Use tight letter-spacing for large display sizes to create a compact, expensive feel.
- **Body & Interface:** Use *Montserrat*. Its geometric clarity provides a functional counterpoint to the serif headings. It ensures readability in product descriptions and checkout flows.
- **Labels:** Small labels, category tags, and overlines should use Montserrat in All-Caps with increased tracking (letter-spacing) to mimic high-fashion branding.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to maintain a boutique editorial feel, and a fluid 4-column grid for mobile.
- **Rhythm:** An 8px base unit governs all spacing. 
- **Sectioning:** Large vertical gaps (120px+) are encouraged between different product collections to signify "exclusivity." 
- **Margins:** Desktop margins are generous (64px) to push the content toward the center, creating a focused "lookbook" experience. 
- **Mobile Adaption:** On mobile, margins shrink to 20px, and large display headings scale down to ensure no awkward word-breaks, while maintaining the Serif prominence.

## Elevation & Depth
In alignment with the minimalist professional style, depth is achieved through **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows.
- **Surfaces:** Most cards and containers are flat white against the background, defined by a subtle 1px border (#EEEEEE).
- **Interactive Depth:** When a product card is hovered, it should not lift with a shadow; instead, it should transition to a very slight scale-up (1.02x) or reveal a secondary "lifestyle" image.
- **Overlays:** Modals and drawers use a high-opacity black backdrop (80% alpha) to completely isolate the user's focus on the focused task (e.g., Quick Add to Cart).

## Shapes
The design system utilizes **Sharp (0)** edges. 
In high-end luxury e-commerce, hard 90-degree corners communicate precision, architectural strength, and a modern "edge." This applies to buttons, input fields, product imagery, and containers. The only exception is the natural geometry of product photography itself.

## Components
- **Buttons:** Primary buttons are solid Deep Black with White text, shifting to Gold on hover. They are strictly rectangular (0px radius) with generous horizontal padding.
- **Input Fields:** Use a "Minimalist Line" style—only a bottom border (1px) that turns Gold when focused. Placeholder text is Montserrat Light.
- **Product Cards:** Aspect ratio should be a consistent 4:5 (portrait). No borders; use the image itself to define the shape. Product titles in Playfair Display (Small), prices in Montserrat (Medium).
- **Chips/Badges:** Small, rectangular tags. Use Gold background with Black text for "New In" or "Sold Out" to ensure immediate visibility.
- **Navigation:** The header is a slim, sticky bar. On scroll, it transitions from transparent to solid Deep Black with Gold icons/text to maintain legibility over varying content.
- **Lists:** Clean, underlined list items with high-contrast text and "arrow-right" icons for navigation-heavy menus like account settings.
