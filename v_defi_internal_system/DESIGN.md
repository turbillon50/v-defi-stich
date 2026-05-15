---
name: V DeFi Internal System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#b9cbb9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849585'
  outline-variant: '#3b4b3d'
  surface-tint: '#00e479'
  primary: '#f1ffef'
  on-primary: '#003919'
  primary-container: '#00ff88'
  on-primary-container: '#007139'
  inverse-primary: '#006d37'
  secondary: '#c6c6c6'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#fffaf7'
  on-tertiary: '#3d2f00'
  tertiary-container: '#ffdb79'
  on-tertiary-container: '#795f01'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#60ff99'
  primary-fixed-dim: '#00e479'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005228'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffe08d'
  tertiary-fixed-dim: '#e5c364'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#584400'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  matte-obsidian: '#0A0A0A'
  electric-emerald: '#00FF88'
  liquid-silver: '#E0E0E0'
  surface-elevated: '#161616'
  border-glass: rgba(255, 255, 255, 0.08)
  muted-gray: '#888888'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-safe: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for a premium, high-stakes fintech environment where precision meets cinematic atmosphere. The brand personality is authoritative yet invisible—providing a sophisticated "command center" feel for wealth management. 

The aesthetic is **Modern-Minimalist with Glassmorphism overlays**. It draws inspiration from the utility of developer tools and the luxury of high-end automotive interfaces. The UI should feel like a singular, cohesive piece of hardware; elements don't just sit on the screen, they emerge from a deep, matte-black void through subtle illumination and material depth. The emotional response is one of total control, absolute security, and effortless technical superiority.

## Colors

The palette is anchored in a true **Matte Black (#0A0A0A)** to ensure infinite depth and OLED-optimized performance. 

- **Primary (Electric Emerald):** Used exclusively for success states, critical CTA highlights, and data trend growth. It should be applied with "glow" properties (box-shadows or blurs) rather than flat fills to maintain the cinematic vibe.
- **Secondary (Liquid Silver):** Reserved for primary typography and iconography, providing a metallic, premium contrast against the dark background.
- **Neutral/Surface:** The background is #0A0A0A. Secondary surfaces use #161616. Borders should rarely be solid; instead, use semi-transparent white (rgba 255, 255, 255, 0.08) to create a "glass" edge.

## Typography

The typographic system utilizes a triple-font hierarchy to balance modernism with technical precision.

1.  **Geist (Headlines):** A hyper-clean, technical typeface for large display moments and section headers. Use tight letter-spacing for a "Stripe-like" premium feel.
2.  **Inter (Body):** The workhorse for all interface text, ensuring maximum legibility across all financial data points.
3.  **JetBrains Mono (Data/Labels):** Used sparingly for numerical data, status tags, and secondary metadata to evoke a "pro-tool" or "terminal" aesthetic.

Typography should favor **Liquid Silver (#E0E0E0)** for high emphasis and **Muted Gray (#888888)** for secondary information.

## Layout & Spacing

This design system follows a strict **4px grid** with a focus on generous negative space. 

- **Desktop:** 12-column fluid grid with wide 32px margins to prevent content from feeling "cramped."
- **Mobile:** 4-column layout with 20px margins. 
- **Reflow:** Cards should stack vertically on mobile but utilize horizontal space on desktop to present side-by-side data comparisons.

Layouts should prioritize "Safe Areas"—keeping core financial interactions within easy thumb reach on mobile and centered "Zen-mode" focal points on desktop.

## Elevation & Depth

Depth is achieved through **Glassmorphism and Tonal Layering** rather than traditional drop shadows.

- **Base Level:** Matte Obsidian (#0A0A0A).
- **Surface Level:** Elevated cards use #161616 with a 1px `border-glass` stroke.
- **Glass Effect:** Overlays (modals, dropdowns) use a background blur (20px to 40px) with a semi-transparent black fill (rgba 10, 10, 10, 0.7).
- **The Glow:** Active elements or "hot" financial zones emit a soft, 20% opacity Emerald green glow using a spread-out box shadow. This acts as a "light source" within the UI.

## Shapes

The shape language is **Refined and Intentional**. 

- **Primary Cards/Inputs:** 0.5rem (8px) corner radius. This provides a soft, approachable feel while maintaining a sense of structural integrity.
- **Interactive Tags/Chips:** Full pill-shape for high-contrast visibility against the squared grid.
- **Buttons:** Large, high-priority buttons use a 1rem (16px) radius to distinguish them from data containers.
- **Icons:** Use linear, 2px stroke-weight icons with rounded terminals to match the typography.

## Components

- **Buttons:** Primary buttons are "Electric Emerald" with black text. Secondary buttons are "Liquid Silver" ghost-style with subtle glass borders. Hover states should trigger a "bloom" effect (soft green glow).
- **Cards:** No shadows. Instead, use a subtle 1px border-glass. Inner padding should be a minimum of 24px.
- **Input Fields:** Darker than the background (#050505) with a subtle bottom-border. Focus states should light up the border in Emerald.
- **Progress Indicators:** Use thin, 2px lines. Avoid bulky bars.
- **Charts:** Use "Neon Glow" lines (Emerald) for growth and "Muted Gray" for historical data. Avoid "Red" unless it indicates a critical system error; use silver or subtle amber for negative financial trends to maintain a calm, high-trust atmosphere.
- **Status Chips:** Small, pill-shaped indicators with a 4px "LED" dot next to the label.