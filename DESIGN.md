---
name: Prestige Automation System
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c2c8c2'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8c928d'
  outline-variant: '#424844'
  surface-tint: '#acceb9'
  primary: '#acceb9'
  on-primary: '#183627'
  primary-container: '#0d2c1e'
  on-primary-container: '#759582'
  inverse-primary: '#466554'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#ffb4a5'
  on-tertiary: '#650b00'
  tertiary-container: '#530700'
  on-tertiary-container: '#ff4e2e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c8ebd5'
  primary-fixed-dim: '#acceb9'
  on-primary-fixed: '#022113'
  on-primary-fixed-variant: '#2f4d3d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#ffb4a5'
  on-tertiary-fixed: '#3e0400'
  on-tertiary-fixed-variant: '#8e1300'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  headline-xl:
    fontFamily: Anton
    fontSize: 72px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.2'
  subtitle-serif:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '800'
    lineHeight: '1.2'
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
  section-gap: 80px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

This design system is engineered for high-conversion sales funnels within the LATAM professional market. It targets entrepreneurs, digital marketers, and freelancers who value efficiency, upward mobility, and technological mastery.

The visual style is **Corporate / Modern** with a high-contrast, editorial edge. It leverages a "Dark Mode First" philosophy to convey authority and tech-sophistication. By combining the stability of deep forest greens with the premium associations of gold, the system evokes a sense of established success and reliability. The aesthetic is dense and information-rich but organized, using bold typography and tactile elements like cards and subtle glows to guide the user toward a single, decisive action.

## Colors

The palette is anchored in a deep, professional environment.
- **Primary:** A dark, rich forest green (#0D2C1E) serves as the primary background and foundational brand color, representing growth and stability.
- **Secondary:** A metallic, muted gold (#D4AF37) is used for high-value highlights, success indicators (checkmarks), and key price points.
- **Tertiary:** A vibrant coral-red (#FF4B2B) is reserved strictly for urgent CTAs and critical badges like "Immediate Access."
- **Neutral:** Pure white and off-white (#F4F4F4) provide maximum legibility for body text against the dark backgrounds.

## Typography

The typographic hierarchy utilizes a high-contrast font pairing strategy:
- **Impact Headlines:** Use **Anton** for primary headers. Its condensed, bold nature commands attention and mimics the urgency of high-converting print media.
- **Editorial Elegance:** Use **Libre Caslon Text** (specifically italics) for subtitles and secondary emphasis. This adds a "premium book" feel that builds trust and authority.
- **Functional Clarity:** Use **Manrope** for all body copy, lists, and technical details. Its modern, geometric construction ensures readability on small devices and maintains a tech-forward look.

## Layout & Spacing

The design system utilizes a **Fluid Grid** model with a 12-column structure for desktop. 
- **Sectioning:** Content is divided into high-impact horizontal bands with alternating background shades (Deep Green vs. Near Black) to maintain engagement.
- **Density:** The spacing is tight and efficient, allowing for multiple value propositions to be visible above the fold.
- **Mobile First:** On mobile, columns collapse to a single stack. Use generous vertical padding (64px+) between sections to prevent the UI from feeling claustrophobic, while maintaining tight internal spacing (16px) within component groups.

## Elevation & Depth

Depth is achieved through **Tonal Layers** and subtle **Backdrop Blurs**.
- **Surface Tiering:** The background is the darkest layer. Cards and input fields use a slightly lighter green or a transparent overlay (10% white) with a 20px backdrop blur to create a glassmorphism effect.
- **Inner Glows:** Instead of heavy drop shadows, use subtle inner borders (1px) in gold or light green to "lift" elements from the background.
- **Success Glows:** High-value elements, like a PDF mockup or a primary CTA, may use a soft radial gradient glow behind them in the secondary gold color to create a "halo" effect.

## Shapes

The shape language is **Soft** and professional. 
- **Buttons and Inputs:** Use a 0.25rem (4px) radius to maintain a serious, architectural feel. 
- **Containment:** Featured cards or "Ideal Para" blocks should use `rounded-lg` (8px) to feel distinct from the page structure. 
- **Iconography:** Icons should be enclosed in circles with thin strokes or represented as high-quality, realistic 3D renders to emphasize the "productivity tool" aspect.

## Components

- **Primary CTA Button:** Rectangular with a slight 4px radius. Use the Tertiary Coral-Red background with white text in Anton (Caps). Apply a subtle bottom shadow to suggest "pressability."
- **Benefit List:** Use the Gold color for checkmark icons. Headings in the list should be Manrope Bold (Caps), with descriptions in Manrope Regular.
- **Value Badges:** Circular elements (like the price tag) should use a Gold-to-Dark-Gold gradient with high-contrast white text.
- **Feature Cards:** Dark green background with a 1px border in a lighter shade of green. Icons should be centered and white.
- **Input Fields:** Dark, recessed background with a 1px Gold border on focus. Labels should use the `label-caps` typography style.
- **Urgency Banners:** Full-width strips at the top or bottom of the screen using the Primary Green with Gold or White text for "Flash Offers."