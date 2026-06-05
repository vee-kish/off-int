---
name: Warm Sophisticate
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4e4544'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#807474'
  outline-variant: '#d1c3c3'
  surface-tint: '#675c5b'
  primary: '#171010'
  on-primary: '#ffffff'
  primary-container: '#2d2424'
  on-primary-container: '#988a8a'
  inverse-primary: '#d2c3c2'
  secondary: '#725a43'
  on-secondary: '#ffffff'
  secondary-container: '#ffdcbf'
  on-secondary-container: '#795f49'
  tertiary: '#1e0e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#36220b'
  on-tertiary-container: '#a6886a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#efdfde'
  primary-fixed-dim: '#d2c3c2'
  on-primary-fixed: '#221a1a'
  on-primary-fixed-variant: '#4f4444'
  secondary-fixed: '#ffdcbf'
  secondary-fixed-dim: '#e1c1a5'
  on-secondary-fixed: '#291806'
  on-secondary-fixed-variant: '#59422d'
  tertiary-fixed: '#ffddbb'
  tertiary-fixed-dim: '#e3c19f'
  on-tertiary-fixed: '#291803'
  on-tertiary-fixed-variant: '#5a4229'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
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
  margin-mobile: 16px
  margin-desktop: 64px
  container-max-width: 1280px
---

## Brand & Style
The design system is defined by a "Warm Minimalist" aesthetic, blending high-end editorial sophistication with an inviting, organic atmosphere. It targets a premium audience that values clarity, tactile quality, and a sense of calm authority.

The visual style utilizes a mix of **Minimalism** and **Modern Corporate** influences, prioritizing generous whitespace and precision typography. Unlike cold, clinical minimalist systems, this design system leans into a high-temperature spectrum—replacing stark whites with cream and oatmeal tones, and clinical blacks with deep espresso hues. The result is an interface that feels curated and artisanal rather than mass-produced.

## Colors
The palette is anchored in a high-contrast but thermally warm spectrum.

- **Primary (Espresso):** A deep, bronze-tinted charcoal used for primary text, iconography, and high-emphasis components. It provides the grounding "anchor" for the UI.
- **Secondary (Warm Taupe):** A mid-tone used for subtle borders, secondary actions, and supporting UI elements.
- **Surface (Oatmeal & Cream):** The foundation of the layout. These replace pure white to reduce eye strain and provide a sophisticated, paper-like quality. 
- **Functional Colors:** Success, Warning, and Error states should be slightly desaturated and shifted towards warmer variants (e.g., an olive-leaning green or a terracotta-leaning red) to remain cohesive with the warm primary palette.

## Typography
The typography strategy relies on a high-contrast pairing between a high-fashion serif and a precision sans-serif.

- **Headlines:** Use *Bodoni Moda*. Its high stroke contrast conveys luxury and editorial intent. Tighten letter spacing for larger display sizes to maintain a compact, "locked-in" feel.
- **Body:** Use *Hanken Grotesk*. This typeface provides a modern, sharp counterpoint to the traditional serif, ensuring high legibility in dense information blocks.
- **Labels:** Small labels and captions use a slightly tracked-out (0.05em) weight of the sans-serif to ensure clarity at small scales, often in uppercase for metadata.

## Layout & Spacing
The design system utilizes a **Fixed Grid** philosophy to maintain editorial integrity. 

- **Desktop:** A 12-column grid with a 1280px max-width. Margins are intentionally wide (64px) to create a "frame" effect around the content, reinforcing the premium feel.
- **Mobile:** A 4-column fluid grid with 16px side margins.
- **Rhythm:** All vertical spacing follows a 4px baseline, but primary component gaps should favor larger increments (24px, 32px, 48px) to allow the warm surface colors to breathe.

## Elevation & Depth
Depth in the design system is achieved through **Tonal Layering** rather than aggressive shadows.

1.  **Level 0 (Base):** The Cream background (`#FDFBF7`).
2.  **Level 1 (Cards/Containers):** Slightly darker Oatmeal/Taupe surfaces (`#F5F2ED`) with no shadow or a very soft, high-diffusion shadow tinted with the primary espresso color (low opacity).
3.  **Level 2 (Overlays/Popovers):** These use the same surface color but feature a crisp, 1px border in a light warm-grey to provide definition against the background.

Avoid heavy blurs or glassmorphism. The goal is to feel like physical paper or linen cards stacked on a wooden desk.

## Shapes
The shape language is "Soft-Modern." 

Elements use a subtle **0.25rem (4px)** radius as the default. This is enough to take the "edge" off the interface without making it feel overly playful or "bubbly." 

- **Buttons:** Sharp or very slightly rounded (4px).
- **Cards:** 4px or 8px (`rounded-lg`) depending on the scale of the content.
- **Inputs:** Maintain a consistent 4px radius to match the precision of the sans-serif typography.

## Components
Consistent component behavior is vital to the sophisticated narrative:

- **Buttons:** Primary buttons are solid Espresso with Cream text. Secondary buttons are outlined in Warm Taupe. Use a high-contrast "hover" state where the background shifts slightly warmer.
- **Inputs:** Clean, bottom-border only or very light 4-sided borders. Labels should always be visible (never placeholder-only) using the `label-md` style.
- **Cards:** Use a "flat" style. Differentiation from the background is achieved through subtle color shifts (Cream to Oatmeal) rather than shadows.
- **Chips/Tags:** Small, pill-shaped elements using the `accent_warm` color with dark espresso text for high legibility.
- **Lists:** Use generous vertical padding (16px+) and thin, warm-grey dividers to maintain an airy, editorial flow.