---
name: Minimalist Luxury AI Stylist
colors:
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e604d'
  on-secondary: '#ffffff'
  secondary-container: '#e1e1c9'
  on-secondary-container: '#636451'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b1a'
  on-tertiary-container: '#868382'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e4e4cc'
  secondary-fixed-dim: '#c8c8b0'
  on-secondary-fixed: '#1b1d0e'
  on-secondary-fixed-variant: '#474836'
  tertiary-fixed: '#e6e2df'
  tertiary-fixed-dim: '#cac6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
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
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-unit: 8px
---

## Brand & Style
The design system is anchored in "Minimalist Luxury," a visual narrative that bridges the gap between high-fashion editorial heritage and cutting-edge artificial intelligence. The personality is sophisticated, expert, and curated, aiming to evoke the feeling of a private atelier. 

The aesthetic leverages a **Minimalist** foundation with a **Corporate Modern** execution. It utilizes generous whitespace to let high-fashion imagery breathe, high-contrast typography for hierarchy, and razor-thin lines to maintain a sense of precision and technical prowess. The goal is to make the user feel as though they are interacting with an elite fashion editor who happens to be powered by AI.

## Colors
The palette is restricted to a high-end neutral spectrum to ensure the clothing photography remains the focal point.

- **Primary (Deep Charcoal):** Used for typography, iconography, and high-emphasis interactive surfaces. It provides the "ink on paper" editorial feel.
- **Secondary (Oatmeal):** Applied to large surface areas, container backgrounds, and soft call-to-actions to provide warmth and humanize the AI experience.
- **Accent (Modern Silver):** Reserved for subtle interactive states, dividers, and secondary button borders.
- **Background (Off-White):** The canvas for the entire experience, chosen to reduce eye strain while maintaining a crisp, clinical cleanliness.

## Typography
The typography strategy relies on the tension between the classicism of **Playfair Display** and the functional neutrality of **Inter**.

Headlines should use tight tracking and organic serif shapes to mimic luxury mastheads. Body text is optimized for readability with generous line heights. The `label-caps` style is critical for navigation and metadata, providing a structured, architectural feel to the layout. All serif headings should be set in "Optical" sizing where possible to maintain the hairline details of the font.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop and a **Fluid Grid** for mobile devices. 

- **Desktop:** A 12-column grid with a maximum width of 1440px. Gutters are kept wide (24px) to prevent visual clutter.
- **Vertical Rhythm:** A strict 8px baseline grid ensures alignment between text and UI elements.
- **Whitespace:** Emphasize "Macro-whitespace" between sections (e.g., 160px vertical gaps) to signal premium positioning.
- **Mobile:** Content reflows to a 4-column grid with reduced margins (20px). Large display type should scale down significantly to avoid awkward word breaks.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Subtle Shadows** rather than heavy skeuomorphism.

- **The Base:** The #FAFAFA background is the lowest level.
- **The Surface:** Cards and modals use #FFFFFF with a 1px border in Modern Silver (#D1D1D1).
- **Shadows:** Use extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 4px 20px rgba(0,0,0,0.03)`). Shadows should feel like ambient light in a studio, not a digital effect.
- **Overlays:** AI-driven modals use a slight backdrop blur (4px) to maintain context while focusing the user's attention.

## Shapes
In line with the high-fashion aesthetic, this design system uses **Sharp (0px)** roundedness. 

The use of 90-degree angles conveys a sense of structure, architectural rigor, and authority. This applies to all buttons, input fields, image containers, and cards. Only user avatars or specific AI "status" indicators may deviate into circular forms to differentiate human/living elements from the structural UI.

## Components
Consistent application of the "Sharp" and "High-Contrast" rules defines the component library:

- **Buttons:** Primary buttons are solid Deep Charcoal with white Inter typography (uppercase). Secondary buttons use a 1px Silver border with no fill.
- **Input Fields:** Minimalist underlines or 1px borders. Focus states should transition the border color to Deep Charcoal without thickening the line.
- **Cards:** No borders are preferred for image-heavy cards; use the Oatmeal background to define the container area instead.
- **Chips/Tags:** Small, sharp-edged rectangles using the Oatmeal color with `label-caps` text.
- **Lists:** Separated by ultra-thin 0.5px dividers in Silver.
- **AI Stylist Interface:** Should use a "Drawer" or "Panel" metaphor that slides in from the right, utilizing the Oatmeal surface to distinguish the AI's "workspace" from the main content.