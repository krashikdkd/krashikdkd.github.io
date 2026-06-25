---
name: Editorial Luxury
colors:
  surface: '#fdf8f7'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f1'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e0'
  on-surface: '#1c1b1b'
  on-surface-variant: '#474741'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#787770'
  outline-variant: '#c8c7be'
  surface-tint: '#5f5e5b'
  primary: '#5f5e5b'
  on-primary: '#ffffff'
  primary-container: '#f9f6f1'
  on-primary-container: '#72706d'
  inverse-primary: '#c8c6c2'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#615d5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#fcf5f6'
  on-tertiary-container: '#747071'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2dd'
  primary-fixed-dim: '#c8c6c2'
  on-primary-fixed: '#1c1c19'
  on-primary-fixed-variant: '#474743'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e7e1e2'
  tertiary-fixed-dim: '#cbc5c6'
  on-tertiary-fixed: '#1d1b1c'
  on-tertiary-fixed-variant: '#494647'
  background: '#fdf8f7'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e0'
  powder-pink: '#F2D5D5'
  graphite-deep: '#2D2D2D'
  warm-white: '#FFFFFF'
  soft-beige: '#EAE3D9'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 84px
    fontWeight: '600'
    lineHeight: 90px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 52px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 42px
    fontWeight: '500'
    lineHeight: 48px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  subheading-italic:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
spacing:
  section-gap: 12rem
  element-gap: 2rem
  margin-page: 4rem
  margin-mobile: 1.5rem
  gutter: 1.5rem
---

## Brand & Style

The design system is anchored in **Immersive Minimalist Luxury**, a philosophy that treats the digital interface as a high-end editorial publication. The brand personality is sophisticated, intimate, and authoritative, evoking the sensation of flipping through a premium fashion magazine. 

Key stylistic pillars include:
- **Minimalism & Negative Space:** Using "air" as a structural element to elevate content and signify premium positioning.
- **Typography as Art:** Large-scale, expressive serif headlines that serve as the primary visual anchor.
- **Asymmetry:** Breaking rigid grid structures to create a bespoke, curated feel that mirrors avant-garde editorial layouts.
- **Human-Centric Textures:** A focus on organic warmth, light, and raw, unfiltered imagery that connects the digital space to the physical salon interior.

## Colors

The palette is built on "Human Tones"—a collection of skin-like, organic hues that provide a warm, inviting canvas. 

- **Primary Canvas:** `#F9F6F1` (Cream/Powder) acts as the foundation, providing a softer, more luxurious feel than pure white.
- **Accents:** Gold (`#D4AF37`) is used sparingly for decorative highlights and hairline dividers to signify exclusivity.
- **Contrast:** Graphite Deep (`#2D2D2D`) ensures readability and provides the "ink" for editorial typography, avoiding the harshness of pure black.
- **Secondary Surfaces:** Soft Beige and Powder Pink are utilized for UI cards and subtle background shifts to create depth without relying on shadows.

## Typography

Typography is the "voice" of the design system. It utilizes a high-contrast pairing of a classic serif and a modern geometric sans-serif.

- **Headlines:** `Playfair Display` provides the dramatic, Vogue-style elegance required for an editorial aesthetic. Large scale and tight tracking on Display levels create a powerful visual impact.
- **Body & Utility:** `Manrope` offers a clean, contemporary contrast, ensuring maximum legibility for service descriptions and pricing.
- **Stylistic Flourish:** Italicized subheadings are used for quotes, philosophy statements, and section intros to add a layer of intimacy and rhythm to the layout.

## Layout & Spacing

This design system rejects rigid, symmetrical grids in favor of an **Asymmetrical Editorial Layout**. 

- **Fluidity:** The layout relies on "Safe Zones" rather than strict columns. Elements should feel intentionally placed, often overlapping or pushed to extreme margins.
- **Negative Space:** Generous vertical spacing (up to `12rem` between sections) is mandatory to maintain the premium "magazine" feel.
- **Breakpoints:**
  - **Desktop (1440px+):** Maximize asymmetry. Use wide margins and varied element widths.
  - **Tablet (768px - 1024px):** Shift to a more structured 6-column grid while maintaining generous whitespace.
  - **Mobile (<768px):** Transition to a single-column flow with centered or left-aligned typography, reducing spacing units to maintain momentum.

## Elevation & Depth

Depth is achieved through **Layering and Materiality** rather than traditional elevation shadows.

- **Tonal Layering:** Use slight shifts in background color (Cream to Soft Beige) to define distinct content areas.
- **Overlapping Elements:** Text should frequently overlap images or video backgrounds to create a sense of physical layering.
- **Backdrop Blurs:** For functional overlays like navigation menus or booking modals, use a high-saturation background blur (`20px+`) with a low-opacity Warm White tint to simulate frosted glass.
- **Shadows:** Avoid drop shadows on cards and buttons. If depth is required, use a single, very soft, tinted ambient shadow (e.g., `0 20px 40px rgba(45, 45, 45, 0.05)`).

## Shapes

The shape language is strictly **Sharp (0px roundedness)**. 

Sharp edges mirror the precision of high-end editorial design and the architectural lines of the salon’s interior. All buttons, image containers, and input fields should utilize 90-degree corners. 

*Exception:* Only the logo or specific decorative circular elements (like "stamp" style labels) may break this rule to provide a focal point of contrast.

## Components

- **Buttons:** Primary buttons are text-only with a bold underline or solid graphite-deep rectangles with white/cream text. No rounded corners. Hover states involve a subtle color shift or a tracking expansion.
- **Input Fields:** Minimalist "floating" lines. Use a 1px hairline bottom border in Gold or Graphite. Label typography should be `label-caps`.
- **Cards:** Borderless containers defined by whitespace or a subtle background color shift (`soft-beige`). Images within cards should use "raw" photography style.
- **Chips/Labels:** Used for service categories. Small caps typography, high letter spacing, and a 1px solid border.
- **Lists & Pricing:** Use a clean, tabular layout with generous leading. Pricing should be clearly separated using whitespace or a faint gold hairline divider.
- **Hero Video:** An immersive, auto-playing, muted video background with a `warm-white` overlay at 10-20% opacity to ensure text legibility.