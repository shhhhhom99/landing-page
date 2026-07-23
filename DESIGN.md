---
name: Heritage & Grandeur
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#55433f'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#87726e'
  outline-variant: '#dac1bc'
  surface-tint: '#964737'
  primary: '#6d281a'
  on-primary: '#ffffff'
  primary-container: '#8b3e2f'
  on-primary-container: '#ffbaac'
  inverse-primary: '#ffb4a5'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#3e3e3e'
  on-tertiary: '#ffffff'
  tertiary-container: '#555555'
  on-tertiary-container: '#cbcac9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a5'
  on-primary-fixed: '#3e0501'
  on-primary-fixed-variant: '#783022'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
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
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  max-width: 1280px
---

## Brand & Style
This design system is anchored in the concept of "Sacred Permanence." It bridges the gap between ancient stone craftsmanship and modern digital storytelling. The aesthetic is a sophisticated blend of **Editorial Minimalism** and **Tactile Heritage**, where the raw texture of granite meets the warmth of glowing oil lamps. 

The UI should feel grounded, venerable, and awe-inspiring. It avoids the clutter of many cultural sites, instead opting for high-quality whitespace to let intricate Dravidian motifs and architectural photography serve as focal points. The emotional response is one of reverence, academic curiosity, and timeless beauty.

## Colors
The palette is derived from the elemental materials of South Indian temples:
- **Primary (Deep Terracotta):** Used for primary actions, heading accents, and structural dividers. It represents the baked earth and sacred vermillion.
- **Secondary (Sandstone Gold):** Reserved for decorative borders, subtle iconography, and premium states. It evokes the weathered brilliance of gopurams at sunset.
- **Tertiary (Granite Grey):** Used for primary body text and high-contrast backgrounds to ground the design in stone.
- **Neutral (Temple Cream):** The primary background color, providing a soft, parchment-like canvas that feels more historic than pure white.
- **Accent (Lamp Yellow):** A vibrant gold used sparingly for highlights, small call-to-actions, and active states, mimicking the flicker of a *diya*.

## Typography
The typographic hierarchy reflects the contrast between stone-carved inscriptions and modern scholarship.
- **Headlines:** Use high-contrast serifs with sharp terminals. This evokes the precision of chisel-on-stone. Headlines should often be paired with Sandstone Gold underlines or ornate Dravidian border flourishes.
- **Body:** A functional, slightly wider sans-serif ensures high legibility for long-form content regarding history and iconography.
- **Labels:** Small caps and increased letter spacing for labels and categories create an "archival" feel, similar to museum plaques.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid** model. Content is contained within a 12-column grid to maintain an editorial feel, but background textures and decorative horizontal motifs should bleed to the edge of the screen to suggest the infinite scale of temple complexes.

- **Symmetry:** Use central alignment for hero sections and introductory passages to mimic the "Garbhagriha" (sanctum) focus.
- **Rhythm:** Generous vertical spacing (80px - 120px between sections) is required to give each piece of art room to "breathe," reflecting the spaciousness of temple courtyards.
- **Margins:** Desktop uses wide margins to create a focused reading column, while mobile transitions to a tight, efficient stack with 20px safe areas.

## Elevation & Depth
Depth in this system is achieved through **Tonal Layering** rather than modern shadows.
- **Surface Stack:** The neutral background acts as the primary layer. Overlays should use slightly darker "Granite" tints or semi-transparent "Terracotta" washes.
- **Etched Details:** Instead of drop shadows, use 1px inner borders or subtle bevel effects to give elements an "incised" or "carved" appearance.
- **Decorative Framing:** Use "floating" ornate frames for image galleries. These frames use high-detail line work (lotus patterns) to create a sense of layering without the need for blurs or heavy shadows.

## Shapes
The shape language is primarily **Rectilinear with Softened Edges**, reflecting the architecture of monolithic stone blocks. 
- **Corners:** Standard UI elements like buttons and inputs use very small radii (4px) to avoid feeling "bubbly" or overly modern.
- **Arch Motifs:** Feature sections and hero images should utilize the "Kudu" (arch) shape from Dravidian architecture as a masking element.
- **Dividers:** Horizontal rules are never plain lines; they should incorporate a central Lotus motif or a repeating geometric pattern inspired by temple friezes.

## Components
- **Buttons:** Primary buttons are solid Terracotta with Gold text and a 1px Gold inner border. Hover states should transition to a Deep Granite. Secondary buttons are "Ghost" style with a 1px stone-grey border and Serif text.
- **Cards:** Cards should have a very subtle Sandstone Gold top-border. Images within cards should have a slight sepia or high-contrast stone-texture overlay.
- **Chips/Tags:** Used for "Era" or "Dynasty" labels (e.g., Chola, Pallava). These should look like small stone seals—low contrast, uppercase, with a Granite Grey background.
- **Input Fields:** Bottom-border only, mimicking the baseline of a stone inscription. The focus state turns the border to Lamp Yellow.
- **Lists:** Bullet points are replaced with stylized "Lotus" icons in Terracotta.
- **Ornate Dividers:** A specific component for this system, used to separate major narrative sections. It consists of a horizontal line with a decorative architectural element in the center.