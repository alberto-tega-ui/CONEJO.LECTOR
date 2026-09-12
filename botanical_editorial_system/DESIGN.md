---
name: Botanical Editorial System
colors:
  surface: '#101413'
  surface-dim: '#101413'
  surface-bright: '#353a38'
  surface-container-lowest: '#0b0f0e'
  surface-container-low: '#181d1b'
  surface-container: '#1c211f'
  surface-container-high: '#262b29'
  surface-container-highest: '#313634'
  on-surface: '#dfe3e0'
  on-surface-variant: '#c1c8c3'
  inverse-surface: '#dfe3e0'
  inverse-on-surface: '#2d3130'
  outline: '#8b928e'
  outline-variant: '#414844'
  surface-tint: '#accebe'
  primary: '#accebe'
  on-primary: '#18362b'
  primary-container: '#0f2e23'
  on-primary-container: '#779788'
  inverse-primary: '#466557'
  secondary: '#ecc15a'
  on-secondary: '#3f2e00'
  secondary-container: '#8c6b01'
  on-secondary-container: '#fff3df'
  tertiary: '#9ed1bd'
  on-tertiary: '#00382a'
  tertiary-container: '#002f23'
  on-tertiary-container: '#689987'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c8ead9'
  primary-fixed-dim: '#accebe'
  on-primary-fixed: '#012016'
  on-primary-fixed-variant: '#2e4d40'
  secondary-fixed: '#ffdf99'
  secondary-fixed-dim: '#ecc15a'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5a4300'
  tertiary-fixed: '#baeed9'
  tertiary-fixed-dim: '#9ed1bd'
  on-tertiary-fixed: '#002117'
  on-tertiary-fixed-variant: '#1d4f40'
  background: '#101413'
  on-background: '#dfe3e0'
  surface-variant: '#313634'
typography:
  headline-xl:
    fontFamily: Source Serif 4
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Source Serif 4
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Source Sans 3
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  layout-margin: 2.5rem
  column-gutter: 1.5rem
  space-3xs: 0.25rem
  space-2xs: 0.5rem
  space-xs: 0.75rem
  space-sm: 1rem
  space-md: 1.5rem
  space-lg: 2.5rem
  space-xl: 4rem
  space-2xl: 6rem
---

## Brand & Style

This design system channels an elegant botanical aesthetic rooted in the psychology of immersive reading. It evokes the solemnity and quiet authority of traditional publishing houses, enriched with a sober, organic warmth. 

The emotional response is one of deep focus, intellectual calm, and tactile luxury. By marrying the profound stillness of a deep emerald canopy with the understated warmth of aged copper, the UI feels both grounded in nature and refined for the modern digital reader. Visual clutter is entirely eliminated, replaced by generous whitespace, deliberate pacing, and structural restraint.

## Colors

The color architecture is built upon a dark, immersive foundation that reduces eye strain and centers the reading experience. 

- **Primary (`#0F2E23`):** Deep emerald forest green. Serves as the foundational canvas, establishing an enveloping, serene atmosphere.
- **Secondary (`#C29B38`):** Warm burnished bronze/copper. Applied selectively to interactive states, active indicators, and high-priority focal points to catch the eye with metallic subtlety.
- **Tertiary (`#1B4D3E`):** Mid-tone botanical moss. Used for surface differentiation, subtle card backgrounds, and container stratification.
- **Neutral (`#E5E9E6`):** Pale parchment white. Ensures optimal contrast for text and iconography against the dark emerald depths, mimicking aged paper illuminated by a soft desk lamp.

## Typography

The typography pairs a high-end editorial serif (`Source Serif 4`) for headlines with a clean, highly legible humanist sans-serif (`Source Sans 3`) for body and structural text. 

Headlines carry the quiet authority of classic literature, utilizing generous tracking and deliberate line heights to enhance legibility. Body text is optimized for long-form reading, balancing comfortable measure lengths with generous vertical spacing. All labels are tracked out slightly and rendered in semi-bold weights to act as crisp navigational anchors.

## Layout & Spacing

The layout employs a fluid editorial grid designed to mimic the proportions of a physical book spread. Content is constrained to an optimal reading measure (maximum 72 characters per line) to eliminate eye fatigue.

Spacing relies on a refined, generous rhythm rooted in multiples of a base grid, ensuring ample negative space around every component. On mobile devices, margins collapse gracefully to 1.25rem, while tablet and desktop viewports expand up to 4rem margins to preserve the luxurious, unhurried pacing of the interface.

## Elevation & Depth

Depth is communicated through subtle tonal layering and low-contrast outlines rather than harsh drop shadows. Surfaces elevate by shifting incrementally lighter along the emerald-to-moss spectrum (`#0F2E23` to `#1B4D3E`), creating a tactile, physical stacking effect reminiscent of layered botanical pressings. 

When absolute focus is required, elements utilize hair-thin borders in warm bronze (`#C29B38`) at low opacity (25%), offering a restrained, luminous boundary that anchors interactive targets without breaking the serene aesthetic.

## Shapes

A soft, restrained shape language (`roundedness: 1`) is enforced across all UI elements. Base components use a delicate `0.25rem` radius, while larger containers and cards utilize `0.5rem` to `0.75rem`. 

This subtle softening prevents the interface from feeling clinical or overly rigid, introducing the gentle, organic curves found in natural leaf structures while preserving a sophisticated, architectural silhouette.

## Components

### Buttons
Primary actions are rendered in burnished bronze (`#C29B38`) with dark emerald text, featuring soft corners and a subtle inset highlight to give a tactile, pressed-metal feel. Secondary buttons use transparent backgrounds with a 1px bronze outline, transitioning to a moss-tinted fill on hover.

### Chips & Tags
Categorical tags and filters appear as pill-like or softly rounded badges in deep moss (`#1B4D3E`), displaying body-sm text in parchment white. Active states invert to bronze fills for instant clarity.

### Lists & Dividers
Lists feature generous vertical padding (minimum 12px between items). Dividers are rendered not as harsh solid lines, but as delicate, fading gradients of bronze that evoke the margin rules of fine typography.

### Checkboxes & Radio Buttons
Custom inputs feature square and circular containers with a 2px bronze border against a dark emerald base. Checked states fill with solid bronze and feature a crisp, high-contrast checkmark or inner dot.

### Input Fields
Text inputs use a deep moss container background with a subtle inner shadow, framed by a delicate bronze border on focus. Placeholder text uses muted parchment for comfortable contrast.

### Cards
Editorial content cards feature a layered moss surface, slight corner rounding, and a hairline bronze border. Hover states introduce a gentle upward translation paired with a luminous border shift, simulating light catching a physical page.