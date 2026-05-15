---
name: Aliança Golden
colors:
  surface: '#14130f'
  surface-dim: '#14130f'
  surface-bright: '#3b3934'
  surface-container-lowest: '#0f0e0a'
  surface-container-low: '#1d1c17'
  surface-container: '#21201b'
  surface-container-high: '#2b2a25'
  surface-container-highest: '#36352f'
  on-surface: '#e7e2da'
  on-surface-variant: '#c3c8c1'
  inverse-surface: '#e7e2da'
  inverse-on-surface: '#32302b'
  outline: '#8d928c'
  outline-variant: '#434843'
  surface-tint: '#b8cbba'
  primary: '#b8cbba'
  on-primary: '#243428'
  primary-container: '#0a1a0f'
  on-primary-container: '#738575'
  inverse-primary: '#516354'
  secondary: '#e6c364'
  on-secondary: '#3d2e00'
  secondary-container: '#785d00'
  on-secondary-container: '#fdd977'
  tertiary: '#e2c475'
  on-tertiary: '#3d2e00'
  tertiary-container: '#c5a85d'
  on-tertiary-container: '#503d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d4e8d5'
  primary-fixed-dim: '#b8cbba'
  on-primary-fixed: '#0f1f14'
  on-primary-fixed-variant: '#3a4b3d'
  secondary-fixed: '#ffe08f'
  secondary-fixed-dim: '#e6c364'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#ffdf91'
  tertiary-fixed-dim: '#e2c375'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#584400'
  background: '#14130f'
  on-background: '#e7e2da'
  surface-variant: '#36352f'
typography:
  headline-xl:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '300'
    lineHeight: '1.2'
  headline-md:
    fontFamily: ebGaramond
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: dmSans
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
  body-md:
    fontFamily: dmSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: dmSans
    fontSize: 11px
    fontWeight: '400'
    lineHeight: '1'
    letterSpacing: 0.18em
  headline-xl-mobile:
    fontFamily: ebGaramond
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
The design system embodies the intersection of a high-end private wealth management firm and a contemporary jewelry boutique. It communicates "Calm Authority" through an understated, dark-mode-first aesthetic that avoids the flashy tropes of retail gold trading in favor of "Quiet Elegance."

The visual direction follows a **Minimalist-Luxury** approach. It utilizes expansive whitespace (or "darkspace"), precise hairline borders, and a sophisticated interplay between deep organic tones and metallic accents. The inclusion of a subtle grain texture across surfaces adds a tactile, physical dimension to the digital interface, reinforcing the material value of the assets being traded.

## Colors
The palette is rooted in a "Deep Forest" foundation, using `#0A1A0F` to provide a sense of stability and depth that black cannot achieve. 

- **Primary Background:** `#0A1A0F` creates a prestigious, atmospheric stage.
- **Accent Gold:** `#C9A84C` is a matte, brushed gold used for primary actions and brand moments.
- **Highlight Gold:** `#E8C97A` is reserved for subtle gradients or interactive states to simulate light hitting metal.
- **Typography:** Primary text uses a warm off-white (`#F5F0E8`) to reduce eye strain and maintain the "warmth" of the luxury brand, while secondary info uses `#A09070` for a muted, monochromatic harmony.

## Typography
The typographic hierarchy balances the classical authority of a serif with the modern efficiency of a geometric sans-serif.

- **Headlines:** Uses a premium serif to evoke heritage and trust. Larger displays should favor the 300 weight for a "fashion-editorial" feel, while functional headers use 600 for clarity.
- **Body & UI:** DM Sans provides a clean, neutral counterpoint to the serif, ensuring high legibility for financial data and long-form advisory content.
- **Labels:** Small, wide-tracked uppercase labels are a signature element of this design system, used for categories, overlines, and metadata to create an organized, architectural feel.

## Layout & Spacing
This design system utilizes a **Fixed Grid** philosophy for desktop to maintain a "contained" and controlled luxury experience. 

- **Grid:** 12-column layout with 24px gutters. Elements should often span the center 8 columns to create generous "empty" margins that signify exclusivity.
- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **Mobile:** Transition to a single-column stack with 20px side margins. Padding within cards and containers should remain generous (minimum 24px) to avoid a "cluttered" or cheapened appearance.

## Elevation & Depth
Depth is achieved through color shifts and "light" rather than traditional shadows.

- **Tonal Layering:** Objects "lift" off the primary background by transitioning to the Secondary Background (`#0F2318`).
- **Gold Ambient Shadow:** High-priority elements like active modals or primary cards use a soft, ultra-diffused gold-tinted shadow (`rgba(201, 168, 76, 0.12)`) with a large 40px blur. This creates a "glow" effect as if the gold itself is reflecting light onto the forest green surface.
- **Noise Overlay:** A global, low-opacity grain texture (approx 3%) is applied to all surfaces to eliminate sterile digital gradients and provide a filmic, high-end quality.
- **Outlines:** Hairline borders (1px) using `rgba(201, 168, 76, 0.15)` define shapes without adding visual weight.

## Shapes
The shape language is disciplined and architectural. A "Soft" rounding (`roundedness: 1`) is applied to prevent the interface from feeling aggressive or overly industrial, but corners never exceed 8px. 

- **Standard Elements:** 4px (0.25rem) radius for inputs and small buttons.
- **Containers/Cards:** 8px (0.5rem) radius.
- **Strictness:** Rounding is never used for a "bubbly" effect; it is merely a slight softening of a formal grid.

## Components
Consistent application of these rules across key components:

- **Buttons:**
    - *Primary:* Solid Gold (`#C9A84C`) with Dark Green text (`#0A1A0F`). No gradients.
    - *Secondary:* Hairline Gold border with off-white text. 
- **Input Fields:** Minimalist design with only a bottom border or a very subtle ghost-outline. Labels always use the `label-caps` style positioned above the field.
- **Cards:** Use the Secondary Background (`#0F2318`) with the 1px gold hairline border. Content inside must have at least 32px of padding to feel spacious.
- **Icons:** Use thin-weight strokes (Phosphor Thin style) exclusively in Matte Gold.
- **Progress Indicators:** Use thin, horizontal gold lines. Avoid circular loaders; use elegant, linear transitions to maintain the formal tone.
- **Lists:** Separated by the same hairline gold border (`rgba(201, 168, 76, 0.15)`) with generous vertical padding (16px+).