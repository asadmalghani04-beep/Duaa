---
name: Atelier Minimalist Gallery
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#444748'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#010101'
  on-primary: '#ffffff'
  primary-container: '#1c1c1c'
  on-primary-container: '#858484'
  inverse-primary: '#c8c6c5'
  secondary: '#a53b26'
  on-secondary: '#ffffff'
  secondary-container: '#fe7d62'
  on-secondary-container: '#711605'
  tertiary: '#020100'
  on-tertiary: '#ffffff'
  tertiary-container: '#211b15'
  on-tertiary-container: '#8c827a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdad3'
  secondary-fixed-dim: '#ffb4a4'
  on-secondary-fixed: '#3e0500'
  on-secondary-fixed-variant: '#842411'
  tertiary-fixed: '#ede0d7'
  tertiary-fixed-dim: '#d0c4bb'
  on-tertiary-fixed: '#201a15'
  on-tertiary-fixed-variant: '#4d453f'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 4.5rem
    fontWeight: '400'
    lineHeight: 5rem
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 2.75rem
    fontWeight: '400'
    lineHeight: 3.25rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 3rem
    fontWeight: '400'
    lineHeight: 3.5rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 2rem
    fontWeight: '400'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 2rem
    fontWeight: '500'
    lineHeight: 2.5rem
    letterSpacing: 0em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: 2rem
    letterSpacing: 0em
  title:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '300'
    lineHeight: 1.875rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.12em
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 2rem
  gutter-sm: 1rem
  margin: 4rem
  margin-sm: 1.5rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1.5rem
  space-lg: 2.5rem
  space-xl: 4rem
---

## Brand & Style

The design system embodies the poise, curation, and restraint of a premier international fine art gallery and artist monograph. Targeted at seasoned collectors, curators, art advisors, and cultural patrons, the visual language prioritizes artworks above decorative interface elements. 

The aesthetic is Minimalist Editorial: expansive, architectural whitespace that acts as a physical gallery wall, exacting typographic contrast, and deliberate micro-interactions that feel measured and tactile. The interface conveys quiet confidence, cultural authority, and timeless luxury, avoiding aggressive visual noise in favor of serene, gallery-grade presentation.

## Colors

The palette establishes an organic, museum-quality atmosphere rooted in natural materials and archival paper:

- **Neutral Canvas (`#FAF7F2`)**: A warm, archival plaster off-white that replaces harsh digital whites, reducing optical glare and providing a hospitable ground for varied artwork undertones.
- **Primary Charcoal (`#1C1C1C`)**: A deep, soot-derived charcoal for typographic hierarchy, high-contrast framing, and primary structural elements, providing deep value without the synthetic hardness of pure black.
- **Secondary Terracotta (`#C8553D`)**: An earthen, kiln-fired accent applied sparingly to highlight curatorial statuses, selected states, inquiry triggers, and critical pagination markers.
- **Tertiary Stone (`#8C827A`)**: A warm mid-tone gray for secondary metadata, medium details, year of provenance, and dimension markers.
- **Subtle Surface Tint (`#F2ECE4`)**: Used for secondary container fills, hover cards, and structural separators.

### Usage Rules
- The background canvas should predominantly remain `#FAF7F2`.
- `#C8553D` must never cover broad background fields; it serves strictly as an intentional focal accent.
- Borders and dividers should consistently use an alpha of `#1C1C1C` at 8% (`rgba(28, 28, 28, 0.08)`) to maintain an airy, pencil-drawn precision.

## Typography

The typographical hierarchy strikes a deliberate dialogue between editorial romance and modern functional clarity:

- **Headlines & Artwork Titles (`Playfair Display`)**: Conveys classical pedigree, literary curation, and presence. Used with generous vertical rhythm and restrained weights (Regular to Medium).
- **Body & Secondary Copy (`Inter`)**: Offers neutral legibility to counterbalance the high-contrast flourishes of the serif headers. Rendered predominantly in Light (300) and Regular (400) weights to keep layouts airy.
- **Labels & Cataloging Metadata (`Inter`)**: Capitalized labels leverage increased letter spacing (`0.12em`) to echo traditional exhibition placards and museum wall text.

## Layout & Spacing

The layout operates on an architectural 12-column responsive fluid grid designed to display large-format visual art without visual crowding.

- **Desktop (1200px+)**: 12 columns with `4rem` outer page margins and `2rem` gutters. Artwork spreads often use asymmetrical column arrangements (e.g., 7 columns for primary media, 5 columns for catalog notes and provenance).
- **Tablet (768px - 1199px)**: 8 columns with `2.5rem` margins and `1.5rem` gutters.
- **Mobile (< 768px)**: 4 columns with `1.5rem` outer margins and `1rem` gutters.

Plentiful vertical breathing room (`space-xl` and higher) separates exhibition blocks, mimicking movement between distinct gallery rooms.

## Elevation & Depth

Visual hierarchy relies on quiet tonal layering and ambient soft shadows rather than dramatic artificial drop shadows:

- **Level 0 (Gallery Wall)**: Flat `#FAF7F2` canvas with structural borders defined by subtle line weights (`rgba(28, 28, 28, 0.08)`).
- **Level 1 (Artwork Tiles & Placards)**: Soft ambient diffusion using a warm tint: `box-shadow: 0 8px 24px -4px rgba(28, 24, 20, 0.05), 0 2px 6px -1px rgba(28, 24, 20, 0.03)`.
- **Level 2 (Inquiry Drawers & Modal Dossiers)**: Elevated depth for focus moments: `box-shadow: 0 24px 48px -12px rgba(28, 24, 20, 0.12), 0 4px 12px -2px rgba(28, 24, 20, 0.04)`.
- **Transitions**: State shifts on artwork frames and interactive surfaces employ soft cubic bezier curves (`transition: all 400ms cubic-bezier(0.2, 0.8, 0.2, 1)`), providing a slow, gliding museum pace.

## Shapes

The design system incorporates refined 8px (`0.5rem`) corner rounding across cards, interactive controls, and visual media containers. 

This subtle rounding balances classic museum frame geometry with tactile contemporary digital design, avoiding both the clinical severity of sharp edges and the casualness of heavily rounded pills. Smaller internal UI elements like tags and badges share this proportion proportionally with a 4px curve.

## Components

### Buttons
- **Primary (Inquire / Acquire)**: Deep charcoal (`#1C1C1C`) background, white/sand text (`#FAF7F2`), 8px border radius, uppercase track letter spacing. Smooth hover shifts to `#C8553D` terracotta with a 300ms transition.
- **Secondary (Catalog / View Room)**: Outlined with `1px solid rgba(28, 28, 28, 0.2)`, transparent background, charcoal text. Hovers transition to `#F2ECE4` background with pure `#1C1C1C` border.
- **Text Action**: Playfair Display italic or Inter uppercase with a persistent hairline underline positioned 4px below the text baseline.

### Artwork Cards & Framing
- Contained in crisp 8px rounded corners with `overflow: hidden`.
- Background backing tone matches `#F2ECE4` to handle non-uniform image aspect ratios gracefully.
- Hover states initiate a gentle, slow scale (`transform: scale(1.02)`) accompanied by ambient depth shadow elevation.
- Artwork labels sit beneath the image: title in *Playfair Display* italic, year and medium in *Inter* regular muted stone (`#8C827A`).

### Form Inputs & Inquiries
- Subtle architectural underline inputs or soft enclosed fills using `#FFFFFF` against `#FAF7F2`.
- Border: `1px solid rgba(28, 28, 28, 0.12)`.
- Active focus state: transitions seamlessly to `1px solid #C8553D` without aggressive outer glow rings.

### Exhibition Chips & Metadata Tags
- Minimalist capsules with 4px border radius.
- Muted background (`rgba(28, 28, 28, 0.04)`), text set in `label-caps` (`0.75rem`), with terracotta indicator dots for active filter states.

### Curatorial Dossier (Lightbox / Zoom)
- Full-screen archival overlay (`rgba(250, 247, 242, 0.96)`) with backdrop blur (`8px`).
- Artwork is presented centered with generous margin buffers, allowing users to inspect brushstrokes and high-resolution textures without interface obstruction.