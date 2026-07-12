---
name: StyleAI
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c6c6c6'
  on-secondary: '#303030'
  secondary-container: '#474747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#cecece'
  on-tertiary: '#2f3131'
  tertiary-container: '#b2b3b3'
  on-tertiary-container: '#434546'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
spacing:
  margin-mobile: 20px
  margin-desktop: 80px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 48px
---

## Brand & Style
The design system embodies the high-octane energy of "Hollywood Glamour." It is built for a premium audience that values exclusivity, stardom, and high-fashion aesthetics. The UI should evoke the feeling of walking a red carpet—dramatic, confident, and meticulously polished.

The design style is a hybrid of **High-Contrast Bold** and **Cinematic Glassmorphism**. It utilizes deep blacks to create a theater-like backdrop, allowing gold accents to shine with "glossy" intensity. Expect sharp edges mixed with intentional, dramatic depth to simulate the lighting of a film set. Every interaction should feel like a curated, VIP experience.

## Colors
This design system operates primarily in a dark mode to maximize the "Cinematic" impact. 

- **Primary (Gold):** #D4AF37 is used for call-to-actions, highlights, and active states. It represents the "Gold Standard" and luxury.
- **Background (Deep Black):** The primary canvas is pure black (#000000) to create infinite depth and high contrast.
- **Surface (Neutral):** A slightly lifted black (#1A1A1A) is used for cards and containers to create subtle separation.
- **Accents (White):** Crisp white is reserved for high-readability body text and "flash-bulb" highlights.

## Typography
The typography strategy relies on the tension between the dramatic, high-contrast serifs of the silent film era and modern, technical precision.

- **Headlines:** Use **Bodoni Moda**. The extreme contrast between thick and thin strokes creates an editorial, high-fashion feel. Use tight letter-spacing for large display sizes to increase impact.
- **Body & Interface:** Use **Hanken Grotesk**. This provides a clean, sophisticated counterpoint to the headlines, ensuring that functional information is easy to scan.
- **Labels:** Always use Hanken Grotesk with generous letter-spacing and uppercase styling to mimic the "credits" found on movie posters.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy to maintain an editorial "magazine" structure. 

- **Desktop:** A 12-column grid with wide 80px outer margins to create a sense of focused, "center-stage" content.
- **Mobile:** A 4-column grid with 20px margins.
- **Rhythm:** Use large vertical spacing (`stack-lg`) between major sections to allow the high-contrast elements to "breathe" and prevent visual clutter.

## Elevation & Depth
Depth is created through "Cinematic Lighting" rather than standard UI shadows.

- **Glossy Surfaces:** Use semi-transparent overlays with a 20px backdrop blur to simulate frosted glass or camera lenses.
- **Inner Glows:** Instead of drop shadows, use subtle inner borders (1px) in gold or low-opacity white to suggest a light source hitting the edge of an object.
- **Hard Borders:** Use 2px solid gold (#D4AF37) borders for primary elements to create a "framed" effect, reminiscent of a vanity mirror or a spotlighted stage.

## Shapes
This design system utilizes a **Sharp** shape language. 90-degree corners communicate precision, architectural strength, and high-fashion edge. 

Avoid rounded corners unless it is for a specific functional element that requires "squishy" feedback (e.g., a toggle switch). All containers, buttons, and input fields should maintain a crisp, sharp-edged silhouette to reinforce the aggressive, bold nature of Hollywood glamour.

## Components
- **Buttons:** Primary buttons are solid Gold (#D4AF37) with Black (#000000) Hanken Grotesk Bold text. Secondary buttons are Black with a 2px Gold border. Hover states should include a "glimmer" effect—a diagonal white gradient sweep.
- **Cards:** Use the "Surface" color (#1A1A1A) with a thin 1px Gold top-border. Background images within cards should have a subtle dark vignette to draw focus to the center.
- **Input Fields:** Sharp-edged boxes with a 1px white border. On focus, the border transitions to Gold with a soft outer glow.
- **Chips/Badges:** Small, uppercase labels with high letter-spacing. Use Gold text on a Black background for "VIP" or "Exclusive" tags.
- **Lists:** Separated by thin, low-opacity white lines (10% opacity) to maintain structure without breaking the deep black immersion.
- **Navigation:** Top-tier navigation should be centered, utilizing Bodoni Moda in small caps for a "Director's Credit" aesthetic.