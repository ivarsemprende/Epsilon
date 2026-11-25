---
name: Haute Horlogerie Obsidian
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393c'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1c1e'
  surface-container: '#1f2022'
  surface-container-high: '#292a2c'
  surface-container-highest: '#343537'
  on-surface: '#e3e2e5'
  on-surface-variant: '#c5c6d0'
  inverse-surface: '#e3e2e5'
  inverse-on-surface: '#2f3033'
  outline: '#8f909a'
  outline-variant: '#44464f'
  surface-tint: '#b2c6fa'
  primary: '#b2c6fa'
  on-primary: '#1a2f5a'
  primary-container: '#6376a5'
  on-primary-container: '#ffffff'
  inverse-primary: '#4a5d8b'
  secondary: '#bfc6dc'
  on-secondary: '#293041'
  secondary-container: '#3f4759'
  on-secondary-container: '#aeb5ca'
  tertiary: '#c6c6c6'
  on-tertiary: '#303030'
  tertiary-container: '#919191'
  on-tertiary-container: '#2a2a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b2c6fa'
  on-primary-fixed: '#011944'
  on-primary-fixed-variant: '#324672'
  secondary-fixed: '#dbe2f9'
  secondary-fixed-dim: '#bfc6dc'
  on-secondary-fixed: '#141b2c'
  on-secondary-fixed-variant: '#3f4759'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#121316'
  on-background: '#e3e2e5'
  surface-variant: '#343537'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 3.5rem
    fontWeight: '400'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '300'
    lineHeight: '1.65'
    letterSpacing: 0.015em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 3.5rem
  space-2xl: 6rem
---

## Brand & Style
This design system reimagines the boutique experience by fusing the sculptural, silent luxury of *Haute Horlogerie* (inspired by Vacheron Constantin and Audemars Piguet) with the understated architectural minimalism of Aesop. The brand voice is composed, authoritative, and deliberate. It elevates precision pieces—from accessible Casio classics to curated Quartz timepieces and jewelry—into objects of desire through gallery-like presentation.

The visual style is characterized by:
- **Obsidian Monolith Atmosphere:** Deep, matte black canvas tiers devoid of bright glare, fostering dramatic contrast with metallic textures and crystal sapphire facets.
- **Editorial Typography Pairing:** Majestic, high-contrast serif headlines conveying generational craftsmanship, grounded by high-precision, widely tracked geometric grotesque body and micro-label typography.
- **Micro-Precision Engineering:** Hairline borders (1px) in muted titanium tones, generous negative space, and disciplined layout alignment mimicking luxury watch dials and horizontal satin-brushed bezels.

## Colors
The color palette deliberately departs from saturated tech blues in favor of an opulent, low-key metallic and mineral schema. 

- **Primary (`#6376a5` Slate Blue):** A desaturated, refined metallic tone reserved for critical accents, active focal indicators, prices, and subtle brand insignias. It conveys heritage and precision without ostentation.
- **Secondary (`#70778b` Cool Steel):** A crisp, muted metallic slate used for primary typographic content, active nav links, and critical CTAs.
- **Tertiary (`#000000` Deep Obsidian):** Used for stark grounding states, heavy structural blocks, and high-contrast shadow boundaries, bringing a deep, absolute darkness counter-balance to the slate tones.
- **Neutral / Canvas (`#77777a` Mineral Gray):** The foundational matte surface, absorbing light and eliminating eye strain while providing maximum dramatic depth for watch dials and macro product photography.
- **Functional Accents:**
  - `emerald-stock` (`#10B981`) provides discreet live-stock confirmation dots.
  - `whatsapp-green` (`#25D366`) is restrained to high-conversion concierge action points.

## Typography
Typography is the architectural backbone of this design system. It establishes an immediate tension between the romanticism of European watchmaking and technical instrumentation.

- **Headline Hierarchy:** Set in `Playfair Display`. Titles should remain balanced, favoring sentence case or discreet title case with generous line height to prevent letter collisions.
- **Editorial Sub-headers:** Subtle, italicized or widely spaced serifs enrich quote blocks, provenance stories (Genaro Ivars & Agustín Fernández), and craftsmanship callouts.
- **Functional Body Text:** `Inter` rendered with light font weights (`300` and `400`) alongside slight positive letter tracking (`0.01em` - `0.02em`) ensures optimal legibility against dark slate surfaces.
- **Micro-Labels & Technical Badges:** All technical specifications, categories, and serial-like notices utilize `label-caps` (`Inter`, uppercase, `0.18em` letter-spacing) to evoke precision dial calibration marks and caseback engravings.

## Layout & Spacing
The layout adheres to an intentional, spacious 12-column grid on desktop screens, transitioning smoothly into a fluid 4-column framework on mobile devices.

- **Negative Space as a Luxury Asset:** White space (or obsidian space) is magnified. Sections are isolated by generous top and bottom padding (`space-2xl`), letting each timepiece command total visual focus without competing noise.
- **Precision Rhythms:** Component internal padding adheres to strict 8-point harmonic multipliers, anchoring metadata, pricing, and button CTA groups consistently.
- **Asymmetric Narrative Modules:** For sections detailing founders and track records ("Quiénes Somos" and "Nuestra Experiencia"), side-by-side split panels of differing weights (e.g., 5-column editorial text balanced by 7-column specimen photography) establish a bespoke atelier experience.

## Elevation & Depth
In alignment with minimalist luxury, this design system rejects heavy, drop-shadow-heavy layering. Depth is expressed through:

- **Tonal Stepping:** Transitions occur via layered dark matte tones—advancing from Canvas (`#0B0C0E`) to Elevated Card (`#121417`), up to Active Substrata (`#16191E`).
- **Hairline Razor Borders (1px):** Cards, badges, and headers utilize fine borders styled with `#272B33` (titanium dust). Interactive elements lighten to `#6376a5` (slate blue) on hover at `30%` opacity.
- **Subtle Radial Shading:** Product showcases incorporate a soft, centered, radial gradient behind the watch bezel (`rgba(99, 118, 165, 0.04)` to transparent), generating a soft halo that mimics museum vitrine lighting.
- **Frosted Navigation:** Fixed header and bottom navigation bars utilize `backdrop-filter: blur(16px)` over an 85% transparent `#0B0C0E` background, preserving continuous spatial continuity during scroll.

## Shapes
To evoke architectural precision and classic horological cases, geometric restraint is mandatory.

- **Crisp Geometry (Roundedness: 0):** Buttons, product cards, dialogue frames, and category filters are rendered with razor-sharp corners (`0px` border-radius) or surgical `1px` chamfers. 
- **Pill Exception for Micro-Signals:** Subtle roundness is reserved exclusively for circular live status indicators (such as the green pulse for immediate stock) and WhatsApp concierge badges, retaining their distinct communication affordance.

## Components

### Buttons & Interactive Triggers
- **Primary Action (Concierge & Cart):** Sharp rectangular silhouette with a warm slate blue outline (`#6376a5`), dark obsidian background, and slate or white typography in `label-caps`. On hover, subtle surface transition to `#6376a5` with dark charcoal ink text (`#0B0C0E`).
- **Secondary Action:** Ghost styling with titanium boundary (`#272B33`), yielding an understated, architectural appearance.
- **WhatsApp Concierge Button:** Minimalist floating or embedded component framed in platinum/titanium with a single emerald point indicator and direct messaging phrasing ("Atención Personalizada 1 a 1").

### Product Cards (Haute Display)
- **Container:** High-density `#121417` card surrounded by 1px `#272B33` borders.
- **Photography Frame:** Deep dramatic vignette backing the timepiece. 1:1 square or 4:5 vertical proportions.
- **Status Badges:** Minimalist tags placed top-left and top-right using `label-caps`. "STOCK INMEDIATO" utilizes an emerald micro-dot rather than loud, distracting ribbons.
- **Price Block:** Monospaced or tabular numeral representation (`label-currency`) in `#6376a5`, paired with clean nomenclature in `Playfair Display`.

### Category Filters & Chips
- Sharp rectangular segmented bars. Active state indicated by a 1px solid slate bottom bar or solid `#000000` fill with white text, avoiding bubble/pill consumer styles.

### Form Inputs & Selectors
- Flat surfaces embedded into the canvas, marked only by a bottom 1px hairline border in `#272B33` that transitions to `#6376a5` upon focus. Placeholder text in muted platinum slate (`#64748B`).

### Founder & Heritage Modular Cards
- Editorial layouts featuring large, subdued metric digits (e.g., "+100", "+6 MESES") paired with hairline dividers separating founder biographies from guarantee seals.