---
name: Vedic Cosmic Narrative
colors:
  surface: '#161308'
  surface-dim: '#161308'
  surface-bright: '#3d392c'
  surface-container-lowest: '#110e05'
  surface-container-low: '#1f1b10'
  surface-container: '#231f14'
  surface-container-high: '#2e2a1e'
  surface-container-highest: '#393528'
  on-surface: '#eae2cf'
  on-surface-variant: '#d0c6ab'
  inverse-surface: '#eae2cf'
  inverse-on-surface: '#343024'
  outline: '#999077'
  outline-variant: '#4d4732'
  surface-tint: '#e9c400'
  primary: '#fff6df'
  on-primary: '#3a3000'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#705d00'
  secondary: '#ffb4a8'
  on-secondary: '#690000'
  secondary-container: '#920703'
  on-secondary-container: '#ff9a8a'
  tertiary: '#defcff'
  on-tertiary: '#00363a'
  tertiary-container: '#00f1ff'
  on-tertiary-container: '#006a70'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#920703'
  tertiary-fixed: '#79f5ff'
  tertiary-fixed-dim: '#00dbe8'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#161308'
  on-background: '#eae2cf'
  surface-variant: '#393528'
typography:
  display-xl:
    fontFamily: Geist
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  title-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
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
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style
This design system establishes an ultra-premium, immersive environment tailored for a high-end tech portfolio. It merges the infinite scale of the cosmos with the structured wisdom of Vedic astrology. The brand personality is authoritative, visionary, and deeply intellectual, evoking a sense of ancient wisdom meeting future technology.

The design style is **Cosmic Glassmorphism**. It utilizes deep, layered transparencies, luminous accents, and high-contrast typography to create a sense of depth and celestial hierarchy. The UI should feel like a high-tech observatory—functional yet awe-inspiring. Every element must feel intentional, balanced, and premium, avoiding cluttered layouts in favor of "infinite" negative space that allows the content to breathe.

## Colors
The palette is rooted in the "Cosmic Midnight" base, providing a vast, infinite background for content. 

- **Primary (Solar Gold):** Used sparingly for high-impact calls to action, active states, and essential focal points. It represents enlightenment and authority.
- **Secondary (Mars Crimson):** Utilized for leadership-driven sections, execution metrics, and energetic highlights. It should be applied with a "glowing" effect rather than flat fills.
- **Surface Strategy:** Backgrounds are never pure black, but a deep navy. Layers are built using translucent glass with a `1px` stroke of gold at low opacity to simulate light catching the edge of a lens.

## Typography
The typography system uses **Geist** for its clinical precision and technical elegance. To contrast the fluid nature of the glassmorphic background, the type is set with tight tracking in headlines to feel "engineered." 

- **Display & Headlines:** Use negative letter spacing to create a dense, authoritative look.
- **Body Text:** Generous leading is required to ensure readability against dark, textured backgrounds.
- **Labels:** Monospaced **JetBrains Mono** is used for metadata and technical specs, grounding the system in its "tech portfolio" roots. All labels should be uppercase with wide tracking to evoke a "system readout" aesthetic.

## Layout & Spacing
The layout follows a **Vastu-influenced directional grid**. Important "opportunities" (Contact, Hire Me) are positioned in the North-West quadrant of the screen, while "execution" (Project results, Code) lives in the South-East.

- **Grid:** A 12-column fluid grid with wide gutters.
- **Vertical Rhythm:** Sections are separated by massive vertical gaps (`160px+`) to represent the vastness of space.
- **Adaptation:** On mobile, the quadrant philosophy shifts to a vertical stack where North-West elements lead the scroll, and South-East elements conclude the narrative.

## Elevation & Depth
Depth is created through **Luminous Layering** rather than traditional shadows.
- **Backdrop Blur:** All interactive surfaces use a `24px` to `40px` blur.
- **Glow Borders:** Surfaces feature a `1px` solid border at 10% opacity. In the top-left corner of the element, a "solar flare" (a linear gradient of Solar Gold) highlights the edge.
- **Z-Index Philosophy:** Higher elevation elements have a lighter background opacity and a more intense backdrop blur, making them appear "closer" to the viewer's lens.

## Shapes
Shapes are intentionally **Sharp and Precise**. While the system uses a slight rounding (`0.25rem`) to prevent a harsh brutalist feel, it avoids the "bubble" look of consumer apps. This maintains the "Mercury-inspired" sharp tech aesthetic. Buttons and cards should feel like precisely cut shards of glass or obsidian.

## Components
- **Buttons:** Primary buttons are Solid Solar Gold with black text. Secondary buttons are "Ghost" style with a 1px Gold border and a subtle hover glow.
- **Cards:** Use a `rgba(255, 255, 255, 0.03)` fill with a heavy backdrop blur. On hover, the border opacity increases, and a subtle Crimson "flare" appears in the background.
- **Input Fields:** Darker than the surface, with a simple bottom border that illuminates in Gold when focused.
- **Chips/Tags:** Small, monospaced text within a Crimson-tinted translucent pill. 
- **Navigation:** A fixed, top-aligned "Orbit" bar that is fully transparent until scroll, then transitions to a glassmorphic state.
- **Starfield Background:** A persistent but subtle particle field behind all content. Interactive elements should "disturb" the particles on hover.