---
name: Mahakam Wave Riding
colors:
  surface: '#fff8f5'
  surface-dim: '#ebd6c9'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1e9'
  surface-container: '#ffeadd'
  surface-container-high: '#f9e4d7'
  surface-container-highest: '#f3dfd1'
  on-surface: '#241912'
  on-surface-variant: '#564334'
  inverse-surface: '#3a2e25'
  inverse-on-surface: '#ffede3'
  outline: '#8a7362'
  outline-variant: '#ddc1ae'
  surface-tint: '#914c00'
  primary: '#914c00'
  on-primary: '#ffffff'
  primary-container: '#ff8a00'
  on-primary-container: '#613100'
  inverse-primary: '#ffb77f'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006590'
  on-tertiary: '#ffffff'
  tertiary-container: '#00b3fc'
  on-tertiary-container: '#004260'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc4'
  primary-fixed-dim: '#ffb77f'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6f3900'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#c8e6ff'
  tertiary-fixed-dim: '#88ceff'
  on-tertiary-fixed: '#001e2e'
  on-tertiary-fixed-variant: '#004c6d'
  background: '#fff8f5'
  on-background: '#241912'
  surface-variant: '#f3dfd1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-unit: 8px
---

## Brand & Style

The design system is engineered to evoke the adrenaline of high-speed water sports while maintaining an atmosphere of professional safety and premium service. The target audience includes luxury travelers, adventure seekers, and corporate groups looking for high-end river experiences.

The aesthetic follows a **Corporate / Modern** approach with **Minimalist** influences. It relies on expansive white space to denote "premium" status, while utilizing high-energy color accents and "real photography" to ground the experience in reality. The UI should feel fast and fluid, mirroring the movement of a jet ski, but remains anchored by a rigorous 12-column grid to communicate stability and trust.

## Colors

The palette is driven by **JetSki Orange (#FF8A00)**, a high-visibility hue that signals action, energy, and the industry-standard for marine safety gear. This is balanced by **Mahakam Navy (#0F172A)**, which provides a deep, sophisticated contrast representing the depth of the river and professional authority.

- **Primary:** Used for main calls to action, active states, and critical branding elements.
- **Secondary:** Used for deep backgrounds, footers, and primary navigation bars to provide a "premium" weighted feel.
- **Backgrounds:** Pure white is the default to maintain high contrast. The "Dark Background" is reserved for immersive gallery sections or high-impact marketing blocks.
- **Typography:** Deep grays and off-blacks are used instead of pure black to improve long-form readability and maintain a modern digital feel.

## Typography

This design system utilizes a high-contrast typographic pairing. **Montserrat** provides a geometric, bold, and energetic feel for all headings, suggesting momentum. **Inter** is used for body copy and UI labels for its exceptional legibility and systematic, professional appearance.

To maintain accessibility, line heights for body text are generous. Large display titles should use tighter tracking to maintain a "locked-in" editorial look. Mobile headlines are significantly scaled down to prevent awkward word breaks while maintaining the bold weight.

## Layout & Spacing

The design system employs a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. 

- **Vertical Rhythm:** A base-8 unit system is used. All padding and margins between elements must be multiples of 8px (e.g., 16, 24, 32, 64).
- **Safe Areas:** Large page-level margins (64px) on desktop ensure content feels "boutique" and premium, avoiding a cluttered or crowded layout.
- **Content Flow:** Real photography should often break the grid (e.g., full-bleed images) or span across 8-10 columns to create a sense of scale and immersion.

## Elevation & Depth

The design system utilizes **Ambient Shadows** to create a sense of tactile layering without feeling dated.

- **Surface 1 (Base):** Pure white background.
- **Surface 2 (Cards):** Slightly elevated with a soft, diffused shadow (Blur: 30px, Y: 10px, Opacity: 4% Black). This makes cards appear to float gently above the surface.
- **Interaction Depth:** On hover, cards should lift slightly (increase shadow spread) and CTA buttons should have a subtle glow effect using the Primary Orange color at low opacity.
- **Overlays:** Use a subtle backdrop blur (12px) for mobile navigation menus and modal backdrops to maintain the modern, glass-influenced aesthetic.

## Shapes

The shape language is defined by **rounded corners (1rem / 16px)**. This creates an approachable, safe, and modern feel, moving away from the aggressive sharpness of traditional sports sites.

- **Standard Elements:** 16px radius (Buttons, Inputs, Small Cards).
- **Large Components:** 24px radius (Featured image containers, Hero sections).
- **Interactive States:** Use fully rounded (pill-shaped) ends for tags/chips to contrast against the standard rounded buttons.

## Components

- **Buttons:** Primary buttons use a solid JetSki Orange background with White Montserrat Bold text. Secondary buttons use a Mahakam Navy outline (2px) with Navy text.
- **Cards:** Use a "Modern Content Card" style—clean white background, 16px rounded corners, and soft ambient shadows. Images should be top-aligned with no padding to the edge of the card.
- **Input Fields:** 16px rounded corners with a 1.5px border in `#E5E7EB`. Focus state transitions the border to Primary Orange.
- **Chips/Tags:** Used for "Adventure Level" or "Duration." Pill-shaped with a light tint of the primary color and dark text.
- **Booking Widget:** A specialized component with high elevation (Surface 3) and prominent primary CTA, designed to stay sticky on the viewport for conversion.
- **Lists:** Icon-based lists using navy-blue checkmarks to denote safety features or inclusions.