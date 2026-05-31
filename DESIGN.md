---
name: Spurfaden Design System
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1b1b1d'
  surface-container: '#1f1f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e4e2e4'
  on-surface-variant: '#d4c3ba'
  inverse-surface: '#e4e2e4'
  inverse-on-surface: '#303032'
  outline: '#9d8e85'
  outline-variant: '#50453d'
  surface-tint: '#ecbd9e'
  primary: '#ecbd9e'
  on-primary: '#462a14'
  primary-container: '#b88e71'
  on-primary-container: '#452812'
  inverse-primary: '#7a573d'
  secondary: '#d4c5a1'
  on-secondary: '#383016'
  secondary-container: '#50462a'
  on-secondary-container: '#c2b491'
  tertiary: '#bbcbb3'
  on-tertiary: '#263423'
  tertiary-container: '#8b9b85'
  on-tertiary-container: '#253222'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcc5'
  primary-fixed-dim: '#ecbd9e'
  on-primary-fixed: '#2e1503'
  on-primary-fixed-variant: '#604028'
  secondary-fixed: '#f1e1bc'
  secondary-fixed-dim: '#d4c5a1'
  on-secondary-fixed: '#221b04'
  on-secondary-fixed-variant: '#50462a'
  tertiary-fixed: '#d7e7cf'
  tertiary-fixed-dim: '#bbcbb3'
  on-tertiary-fixed: '#121f10'
  on-tertiary-fixed-variant: '#3c4b38'
  background: '#131315'
  on-background: '#e4e2e4'
  surface-variant: '#353437'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered to evoke the feeling of a premium, high-fidelity audio instrument. It centers on the concept of the "Track-Thread"—a continuous, elegant line that weaves through the musical experience. The brand personality is sophisticated, precise, and understated, catering to audiophiles who value intentionality and high-end aesthetics.

The visual style combines **Glassmorphism** with **Corporate Modern** sensibilities. It utilizes deep, atmospheric layers, frosted glass textures, and metallic accents to create a sense of physical depth. Linear motifs—inspired by the fine "thread" of the logo—act as both decorative elements and functional connectors, emphasizing the rhythmic and continuous nature of "true random" playback.

## Colors

The palette is rooted in a deep, textured **Charcoal (#0F0F10)** that provides a silent, gallery-like backdrop for album art and UI elements. 

- **Muted Copper (Primary):** Used for active states, playback progress, and primary actions. It suggests warmth and high-quality conductivity.
- **Champagne Gold (Secondary):** Reserved for highlights, premium features, and subtle metallic "sheen" on borders.
- **Sage Green (Tertiary):** A calming, organic accent used for secondary information, such as "True Random" status or successful connections.
- **Neutral/Surface:** A range of greys with slight blue-bronze tints ensure the dark mode feels "expensive" rather than purely black.

## Typography

This design system utilizes **Hanken Grotesk** for its clean, contemporary, and geometric precision, ensuring maximum legibility in low-light environments. The type scale is tight and rhythmic, mirroring the precision of audio equipment.

For technical data—such as timestamps, bitrates, and track numbers—**JetBrains Mono** is introduced. This monospaced font reinforces the "tool" aspect of the app, providing a disciplined contrast to the fluid sans-serif used for artist and track names. All labels use uppercase styling with increased letter spacing to enhance the premium, editorial feel.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a base unit of **4px**. 

- **Mobile:** A 4-column grid with 20px side margins. Content is primarily vertically stacked to allow for large-scale album art and tactile playback controls.
- **Desktop/Tablet:** A 12-column grid. The interface utilizes a "Fixed Sidebar / Fluid Content" approach. 
- **Rhythm:** Spacing between elements (Stack) is strictly enforced in multiples of 8px to maintain a rhythmic vertical cadence. 

A unique "Thread Line" (1px width) frequently connects disparate UI elements (e.g., connecting the track start time to the end time across the progress bar), visually representing the "Spurfaden" philosophy.

## Elevation & Depth

Hierarchy is established through **Backdrop Blurs** and **Tonal Layering** rather than traditional heavy shadows.

- **Level 0 (Canvas):** Deep charcoal, slightly textured with a subtle noise grain to mimic brushed metal or high-quality plastic.
- **Level 1 (Surfaces):** Semi-transparent "Glass" panels with a `20px` backdrop blur. These surfaces feature a `1px` inner stroke in Champagne Gold (at 10% opacity) to catch the "light" at the edges.
- **Level 2 (Active/Floating):** Elements like the "Now Playing" bar use a slightly higher opacity glass and a soft, copper-tinted ambient glow (`0px 8px 24px rgba(184, 142, 113, 0.15)`) to appear closer to the user.

## Shapes

The shape language is "Rounded" (Base `8px` / `0.5rem`). This provides a sophisticated balance—soft enough to feel approachable and ergonomic, but sharp enough to maintain a professional, engineered look.

- **Standard Elements:** 8px radius (Buttons, Input Fields).
- **Large Containers:** 16px radius (Cards, Album Art).
- **Special Elements:** Playback buttons and "True Random" toggles use pill-shaped (fully rounded) forms to distinguish them as primary interaction points.

## Components

### Buttons
- **Primary:** Muted Copper background with white or dark charcoal text. High-gloss finish with a subtle top-down gradient.
- **Ghost:** `1px` border in Sage Green or Champagne Gold. Transparent background with high blur.

### Playback Controls
- **Play/Pause:** Large, circular, with a metallic gradient stroke. The "Thread" line should visually enter and exit the button area.
- **Progress Bar:** A thin `2px` line. The played portion is Muted Copper; the remaining portion is a semi-transparent neutral with a "frosted" look.

### Cards & Lists
- **Track List:** Minimalist. Hover states trigger a subtle horizontal "Thread" line that underlines the track title.
- **Album Cards:** Edge-to-edge artwork with a `1px` metallic border. Information is displayed on a frosted glass footer overlay.

### Input Fields & Controls
- **Search:** Darker than the surface level, inset "pressed" look (Neomorphic influence), with the Sage Green accent used for the cursor and focus state.
- **Toggles:** Custom "Thread" toggles where the switch appears to slide along a continuous metallic line.