---
name: Monochrome Architectural Studio
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#4c4546'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 3rem
---

## Brand & Style

This design system expresses an uncompromising, stark architectural portfolio aesthetic defined by binary visual mechanics. The target audience includes design directors, architects, curators, and institutional patrons looking for rigor, clarity, and structural confidence. The emotional response is one of intellectual poise, editorial precision, and visceral clarity—free from decorative noise.

The design movement combines **Minimalism** and **Tactile/Brutalist Monolithism**:
- Absolute binary color space: strictly `#000000` and `#ffffff` with zero interstitial grays, tints, or soft chromatic shadows.
- Alternating polar background zones (pure black sections abutting pure white sections) create rhythmic spatial pacing.
- Architectural tactile feedback: physical, high-speed displacement mechanisms (instant 2px to 4px translational shifts, crisp solid-fill toggles) replace soft lighting or blurred drop-shadows.
- Crisp line-weight structures, razor edges, and planar divisions evoke bespoke book design and physical structural mockups.

## Colors

The palette operates under a strict binary rule: **only pure black (`#000000`) and pure white (`#ffffff`) are permitted**. 

- **No Gray Scales**: No values between `#000000` and `#ffffff`. Intermediate states (disabled states, inactive borders, secondary text) are expressed strictly through line density, typography weight, inverted backgrounds, or structural borders—never through lower contrast gray values or opacity/alpha channels.
- **No Gradients, Spotlights, or Ambient Color Bleeds**: Surfaces are flat, opaque planes of black or white.
- **Alternating Section Contrast**: Pages alternate between full-bleed `#ffffff` sections (with `#000000` text and hairline structural rules) and full-bleed `#000000` sections (with `#ffffff` text and inverted structural elements).
- **Component Inversion**: Interactive elements reverse polarity on state change: a button resting as white text within a black bounding box snaps instantly to black text on white fill upon interaction.

## Typography

The typographic hierarchy utilizes two contrasting type engines: **Space Grotesk** for structural, technical display headers and categorical labels, paired with **Inter** for dense, readable body prose.

- **Uppercase Utility**: Labels, tags, indexes, and numeric section headers are set strictly in uppercase Space Grotesk with tracked letter-spacing (`0.06em` to `0.1em`) to mimic architectural drawings and Swiss exhibition catalogs.
- **Tight Kerning on Displays**: Large headlines utilize negative tracking to pack display weights tightly against the negative space.
- **Hierarchy via Weight and Scale**: Since gray values are forbidden, visual hierarchy relies exclusively on high scale ratios (e.g., 64px to 15px) and weight variations (700 Bold down to 400 Regular).
- **Rule Lines**: When headlines require separation, use solid 1px or 2px black/white lines directly under text blocks rather than varying font opacity.

## Layout & Spacing

The layout operates on a 12-column architectural fluid grid system defined by crisp physical boundaries:
- **Desktop (1024px+)**: 12 columns, 3rem margins, 1.5rem gutters. Sections span 100% viewport width to allow full-bleed black and white alternations.
- **Tablet (768px - 1023px)**: 8 columns, 2rem margins, 1.25rem gutters.
- **Mobile (<768px)**: 4 columns, 1.25rem margins, 1rem gutters. Columns collapse into single-column vertical stacks.

**Section Stacking & Rhythm**:
- Sections alternate vertically between pure `#000000` backgrounds and pure `#ffffff` backgrounds. Each section boundary is sharp, with a mandatory 0px bleed transition (no soft divider spacing).
- Inner content spacing relies on high architectural padding (`space-xl` and higher multiples) to create gallery-scale negative space around portfolio works.
- Grid lines can be physically manifested: optional solid 1px column borders provide blueprint-grade layouts for case-study indices.

## Elevation & Depth

Depth is conveyed through **tactile isometric translation** and **binary layer stacking**, completely omitting ambient shadows, blur, or transparency.

- **Tactile Hard Shadows (The Mechanical Offset)**: Instead of blurred drop shadows, interactive cards and buttons utilize a solid, 100% opaque offset plane:
  - On `#ffffff` canvases: elements use a solid 1px or 2px `#000000` stroke with a solid `#000000` hard shadow offset 4px down and 4px right (`box-shadow: 4px 4px 0px 0px #000000`).
  - On `#000000` canvases: elements use a solid 1px or 2px `#ffffff` stroke with a solid `#ffffff` hard shadow offset 4px down and 4px right (`box-shadow: 4px 4px 0px 0px #ffffff`).
- **Tactile Press Physics**: On `:hover`, the element translates -2px, -2px while the solid shadow expands to 6px, 6px. On `:active`, the element translates +4px, +4px to close the gap completely (`box-shadow: 0px 0px 0px 0px`), creating a mechanical button-click response.
- **Overlapping Monolithic Plates**: Heavy z-index layering is achieved via high-contrast white-on-black or black-on-white planar overlays with razor-sharp 1px or 2px borders defining spatial containment.

## Shapes

The shape system is strictly **Sharp (`roundedness: 0`)**.
- All radii across all components (buttons, input fields, cards, badges, modal dialogs, media frames) are strictly `0px`.
- Every corner is a perpendicular 90-degree angle, reinforcing the architectural, editorial blueprint aesthetic.
- Image containers must not use rounded corners. Images sit directly inside rectilinear framing with 1px solid bounding boxes.

## Components

### Buttons
- **Primary (on White Background)**: Solid `#000000` fill, pure `#ffffff` text, 0px border radius, uppercase `label-md` Space Grotesk. Solid `#000000` 3px hard offset. On `:hover`, text and background invert (pure `#ffffff` fill, solid 2px `#000000` border, `#000000` text). On `:active`, translates down and right into the offset plane.
- **Primary (on Black Background)**: Solid `#ffffff` fill, pure `#000000` text, solid `#ffffff` 3px hard offset. Inverts to `#000000` fill with 2px `#ffffff` border on hover.
- **Secondary / Outline**: 2px solid border (`#000000` on white, `#ffffff` on black), transparent/canvas fill, matching solid hard offset. Inverts fill completely on hover.

### Chips & Tags
- Rectilinear 1px bordered containers.
- Typography: `label-sm` Space Grotesk, all caps.
- Padding: `0.25rem 0.625rem`.
- Inactive state: Bounded by a 1px solid border matching the section contrast. Active state: Completely inverted solid fill with opposite-color text.

### Cards & Work Items
- Structured as structural monolithic blocks.
- Border: Solid 1px or 2px perimeter border.
- Offset: Fixed 4px 4px tactile hard offset shadow.
- Inner divisions: Image and metadata sections are separated by crisp 1px dividing rules.
- Hover interaction: Entire card translates -3px, -3px, expanding its solid offset.

### Lists & Case Study Tables
- Tabular architectural layout with a solid 1px horizontal rule above and below each row.
- Zero alternating gray row fills. Hover states turn the entire list row into a solid inverted fill (row turns pure black with pure white text on light canvases; turns pure white with pure black text on dark canvases).
- Fixed-width numeric indexing (`01/`, `02/`, `03/`) styled in Space Grotesk.

### Checkboxes & Radio Buttons
- **Checkboxes**: 18px × 18px square (0px radius) with a 2px solid border. Checked state displays a solid fill with an inner centered square or an uncompromising 45-degree geometric check mark drawn with solid 2px line weight.
- **Radio Buttons**: 18px × 18px square (retaining the 0px architectural motif) containing a centered 8px × 8px solid square pip when selected.

### Input Fields
- Solid 2px border matching canvas text color. Background matches canvas.
- Placeholder text: Illustrated through italicized or bracketed regular Inter text (e.g., `[ENTER PROJECT QUERY]`), strictly in `#000000` or `#ffffff` without opacity reduction.
- Focus state: Instantly triggers a 4px 4px solid hard shadow offset; cursor is a solid 2px non-blinking block.

### Architectural Portfolio Additions (Project Index & View Switcher)
- **Grid / List Blueprint Switcher**: Monolithic toggle segmented into pure square blocks with 1px internal borders. The selected state is fully filled with the opposing polar color.
- **Fullscreen Lightbox / Inspector**: Pure black or pure white overlay plate with a 2px interior border framing the project drawing/photo, framed by hairline technical dimensional metrics.