---
name: Artisanal Industrial
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c3c8c2'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8d928d'
  outline-variant: '#434844'
  surface-tint: '#b8cbbe'
  primary: '#b8cbbe'
  on-primary: '#24342b'
  primary-container: '#1b2b22'
  on-primary-container: '#819387'
  inverse-primary: '#516257'
  secondary: '#ffb4ab'
  on-secondary: '#690006'
  secondary-container: '#b20213'
  on-secondary-container: '#ffbdb6'
  tertiary: '#f6bb88'
  on-tertiary: '#4b2802'
  tertiary-container: '#3f2000'
  on-tertiary-container: '#b88456'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d4e7d9'
  primary-fixed-dim: '#b8cbbe'
  on-primary-fixed: '#0f1f16'
  on-primary-fixed-variant: '#3a4b40'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000d'
  tertiary-fixed: '#ffdcc1'
  tertiary-fixed-dim: '#f6bb88'
  on-tertiary-fixed: '#2e1500'
  on-tertiary-fixed-variant: '#663d15'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  title-lg:
    fontFamily: DM Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.5'
    letterSpacing: 0.05em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is built on the intersection of raw industrial architecture and the warm, soulful heritage of Italian craftsmanship. It targets an aspirational audience looking for an elevated yet authentic dining experience. The UI must feel curated and sturdy, like a heavy metal menu held in a warm, dimly lit space.

The visual style is **Industrial-Modern with Tactile Accents**. We lean into high-contrast editorial layouts, generous use of negative space, and a depth model that mimics physical materials like stone, steel, and aged paper. The emotional response should be one of "sophisticated coziness"—professional and sharp, but deeply inviting.

## Colors

The palette is anchored in the physical environment of the restaurant. 

- **Primary (Forest Green):** Used for deep backgrounds and primary brand surfaces. It provides a more sophisticated alternative to pure black.
- **Secondary (Accent Red):** Used sparingly for calls to action, price points, and highlights. It mimics the glow of the hanging lamps.
- **Tertiary (Terracotta/Beige):** Used for secondary text, dividers, and decorative geometric elements. It represents the warmth of the brick and the "prova" (dough).
- **Neutral (Charcoal & Cream):** The charcoal is our base "ink," while a soft cream (#F9F6F0) is used for high-readability body text on dark backgrounds to reduce eye strain.

## Typography

Typography is the primary vehicle for the brand’s elegance. We use **Bodoni Moda** for all high-level headings; its extreme stroke contrast suggests luxury and editorial precision. 

For functional text, **DM Sans** provides a clean, geometric counterpoint that ensures legibility in low-light digital environments. 
- Use **Display** sizes for hero sections and menu categories.
- Use **Label-MD** in all-caps for navigation and metadata to reinforce the industrial, structured feel.
- Maintain wide line-heights for body text to evoke a sense of calm and "slow food" philosophy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a cinematic, controlled composition. 
- **Desktop:** 12-column grid with a max-width of 1280px.
- **Mobile:** 4-column grid with generous 20px side margins.

Spacing is intentionally rhythmic, moving in multiples of 8px. Large vertical gaps (XL spacing) should be used between major sections to mimic the "high ceilings" of the restaurant, allowing photography and typography to breathe. Content blocks should feel like architectural features—solid, aligned, and intentional.

## Elevation & Depth

In this design system, depth is achieved through **Tonal Layers** rather than heavy shadows. We use the "Stacked Material" approach:

1.  **Level 0 (Base):** Forest Green or Charcoal.
2.  **Level 1 (Surface):** A slightly lighter tint of the base color with a 1px low-contrast outline in Terracotta (#C18C5D, 20% opacity).
3.  **Level 2 (Pop):** Subtle amber-tinted ambient shadows (e.g., `rgba(193, 140, 93, 0.1)`) to suggest a warm glow from above.

Glassmorphism is used sparingly for navigation bars, utilizing a "Smoked Glass" effect (Dark charcoal at 80% opacity with a heavy backdrop blur) to maintain the industrial atmosphere while scrolling.

## Shapes

To reflect the industrial architecture—steel beams, brick corners, and wooden tables—the shape language is primarily **Soft (Level 1)**. 
- Standard components use a 4px (0.25rem) radius.
- Larger cards and images use an 8px (0.5rem) radius.
- Buttons remain strictly rectangular or very slightly softened to maintain a sense of structural integrity. Avoid pill shapes, as they conflict with the "geometric floor pattern" inspiration.

## Components

### Buttons
Primary buttons feature a solid Charcoal background with a Terracotta border and Cream text. On hover, they transition smoothly to a solid Red background. This mimics the "ignition" of a wood-fired oven.

### Cards
Cards are "containers of craft." They should use Level 1 elevation (subtle outlines). Use background textures of dark brick or grain at low opacity (5-10%) within the card surface to add tactile interest.

### Inputs
Search and form fields use a "Bottom-only border" style in Terracotta to keep the UI feeling lightweight and sophisticated.

### Navigation
A minimalist top-bar with uppercase labels. Use a geometric pattern (inspired by the floor tiles) as a subtle watermark or divider in expanded mobile menus.

### Imagery
Photography must always use warm amber/sepia tones. Images should have a subtle "vignette" to draw the eye inward, mimicking the cozy, focused lighting of the dining tables.