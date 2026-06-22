---
name: Artemarmol Elite
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1b'
  on-tertiary-container: '#838482'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e3e2e0'
  tertiary-fixed-dim: '#c7c6c5'
  on-tertiary-fixed: '#1a1c1b'
  on-tertiary-fixed-variant: '#464746'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
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
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-upper:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
---

## Brand & Style
The brand personality is rooted in the timelessness of natural stone—monumental, precise, and enduring. It targets a high-end clientele of architects, interior designers, and luxury homeowners who value craftsmanship and material authenticity.

The design style is **Modern Luxury Minimalism** with a focus on high-contrast compositions and architectural structure. The interface mimics the experience of a high-end gallery: expansive whitespace, sharp geometric precision, and a deliberate absence of decorative clutter. Subtle marble-inspired textures and grain patterns are used as structural backdrops to ground the digital experience in the physical reality of the product.

## Colors
The palette is architectural and sophisticated, leaning heavily on monochromatic values with metallic punctuation.

- **Primary (Obsidian):** Used for primary backgrounds, heavy typography, and main UI containers to provide a grounded, heavy feel.
- **Secondary (Champagne Gold):** Reserved for highlights, active states, and premium CTAs. This color should be used sparingly to maintain its status as a luxury signifier.
- **Tertiary (Bone White):** A warm off-white used for page backgrounds to prevent the clinical feel of pure hex white, evoking the surface of polished marble.
- **Neutral (Slate):** Used for secondary text and structural lines.
- **WhatsApp Green:** A utility-specific brand color used exclusively for the floating contact action.

## Typography
The typographic hierarchy relies on the tension between the classic, high-contrast serif for titles and the technical, clean precision of the sans-serif for functional text.

- **Headlines:** Set in Playfair Display. Use high-contrast sizing to create an editorial feel. Tighten letter-spacing for large display headers to mimic luxury magazine layouts.
- **Body:** Set in Hanken Grotesk. The generous x-height ensures readability even at smaller scales.
- **Labels:** Always use the `label-upper` style for categories, overlines, and small navigational elements to maintain a disciplined, structured appearance.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to ensure content remains framed like a piece of art, while transitioning to a fluid model for mobile.

- **Desktop:** 12-column grid with a 1440px max-width. Use 64px outer margins to provide "breathing room" that signifies luxury.
- **Vertical Rhythm:** Use increments of 8px. Large sections (e.g., Hero to Gallery transition) should utilize massive vertical padding (120px - 160px) to emphasize the scale of the materials.
- **Mobile:** 4-column grid with 24px margins. Elements should stack vertically, maintaining the sharp edges of the grid.

## Elevation & Depth
In alignment with the stone-material theme, depth is communicated through **Tonal Layering** and **Hard Shadows** rather than soft blurs.

- **Surfaces:** Use shifts in background color (Bone White to pure Obsidian) to define hierarchy. 
- **Shadows:** Use extremely subtle, large-spread shadows for high-level components like Product Cards. Avoid heavy blurs; the goal is to make elements look like they are "resting" on a slab, not floating in air.
- **Borders:** Use thin (1px), high-contrast dividers (Obsidian on Bone or Gold on Obsidian) to separate sections, mimicking the grout lines or joins in masonry.

## Shapes
The shape language is strictly **Sharp (0px)**. This mimics the precision cutting of marble slabs and the architectural nature of stone blocks. Do not use rounded corners on any UI element, including buttons, input fields, or image containers. The only exception is the WhatsApp floating icon, which retains its native circular branding for instant recognition.

## Components
- **Primary Button:** Solid Obsidian (#1A1A1A) background with Gold (#C5A059) text and a Gold 1px border. On hover, the background fills with Gold and text switches to Obsidian.
- **Secondary Button:** Ghost style. 1px Obsidian border with Obsidian text. No background.
- **WhatsApp CTA:** Circular green floating button, positioned bottom-right with a subtle "pulse" animation to attract attention without breaking the sober aesthetic.
- **Input Fields:** Bottom-border only (1px Obsidian). Labels use the `label-upper` typography style, positioned above the line.
- **Cards (Material Gallery):** Full-bleed imagery with a sharp 1px border. Text overlays should appear on hover using a semi-transparent Obsidian wash.
- **Lists:** Bullet points are replaced with small Gold squares (4px x 4px) to maintain geometric consistency.