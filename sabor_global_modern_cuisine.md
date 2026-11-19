---
name: Sabor Global Modern Cuisine
colors:
  surface: '#fff8f6'
  surface-dim: '#ebd6cc'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1eb'
  surface-container: '#ffeae0'
  surface-container-high: '#fae4d9'
  surface-container-highest: '#f4ded4'
  on-surface: '#241913'
  on-surface-variant: '#574237'
  inverse-surface: '#3a2e27'
  inverse-on-surface: '#ffede5'
  outline: '#8b7265'
  outline-variant: '#dec1b1'
  surface-tint: '#9a4600'
  primary: '#9a4600'
  on-primary: '#ffffff'
  primary-container: '#f47b25'
  on-primary-container: '#592500'
  inverse-primary: '#ffb68d'
  secondary: '#6b5b52'
  on-secondary: '#ffffff'
  secondary-container: '#f4ded2'
  on-secondary-container: '#716158'
  tertiary: '#00658f'
  on-tertiary: '#ffffff'
  tertiary-container: '#5ca4d1'
  on-tertiary-container: '#003852'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc9'
  primary-fixed-dim: '#ffb68d'
  on-primary-fixed: '#321200'
  on-primary-fixed-variant: '#763400'
  secondary-fixed: '#f4ded2'
  secondary-fixed-dim: '#d7c2b7'
  on-secondary-fixed: '#241912'
  on-secondary-fixed-variant: '#52443b'
  tertiary-fixed: '#c7e7ff'
  tertiary-fixed-dim: '#88cefe'
  on-tertiary-fixed: '#001e2e'
  on-tertiary-fixed-variant: '#004c6d'
  background: '#fff8f6'
  on-background: '#241913'
  surface-variant: '#f4ded4'
  background-light: '#f8f7f5'
  background-dark: '#221710'
  slate-900: '#0f172a'
  slate-600: '#475569'
  slate-100: '#f1f5f9'
  success-green: '#16a34a'
  warning-orange: '#ea580c'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 60px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '800'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-padding-mobile: 1.5rem
  container-padding-desktop: 5rem
  section-gap: 4rem
  grid-gutter: 1.5rem
  card-padding: 1.25rem
  component-gap-sm: 0.5rem
  component-gap-md: 1rem
---

## Brand & Style

Sabor Global is a premium, approachable culinary platform that blends cultural authenticity with modern technology. The brand personality is vibrant, optimistic, and sophisticated—acting as a "culinary passport" for the home cook.

The visual style is **Corporate Modern with a Lifestyle edge**, characterized by:
- **Warmth & Energy:** Utilizing a high-energy primary orange to evoke appetite and enthusiasm.
- **Editorial Clarity:** High-contrast typography and generous whitespace that mimic a high-end food magazine.
- **Subtle Layering:** A mix of clean surfaces and soft, sophisticated shadows to create a clear hierarchy of information.
- **Responsive Depth:** A layout that feels grounded but uses semi-transparent overlays (glassmorphism) in navigation and hero elements to maintain a sense of lightness and modernity.

## Colors

The color palette is anchored by "Sabor Orange," a warm, energetic hue that drives all primary actions. 

- **Primary (#f47b25):** Used for CTA buttons, active states, and brand iconography.
- **Secondary/Neutral Dark (#221710):** A deep, "coffee-bean" brown used for text and dark-mode backgrounds to provide a warmer alternative to pure black.
- **Surface Palette:** The design uses a tiered "Slate" system for secondary containers and borders, ensuring a neutral canvas that lets food photography remain the focal point.
- **Functional Accents:** Soft green and blue washes are used for ingredient tags (e.g., Healthy, Picante) to provide quick visual scanning without competing with the primary brand color.

## Typography

The system exclusively uses **Plus Jakarta Sans** to achieve a soft, rounded, and welcoming feel while maintaining high legibility.

- **Scale:** The system relies on a dramatic scale contrast. Display sizes are heavy (ExtraBold/Black) and tight, while body text remains airy and functional.
- **Hierarchy:** Headlines use `slate-900` for maximum impact. Secondary descriptions and "metadata" (like cooking times) use `slate-500` or `slate-400` to create a clear reading order.
- **Micro-copy:** Tags and labels use uppercase with increased letter spacing to differentiate them from prose.

## Layout & Spacing

The layout follows a **Hybrid Fluid Grid** system. 

- **Desktop:** A 12-column grid with wide horizontal margins (80px/5rem) to center content and provide an "editorial" feel.
- **Mobile:** A single-column stack with 24px/1.5rem side margins.
- **Vertical Rhythm:** Sections are separated by large gaps (64px+) to prevent visual clutter.
- **Component Spacing:** Small internal elements (icons + text) use 8px gaps, while larger blocks (headline + paragraph) use 16px to 24px gaps.

## Elevation & Depth

Visual hierarchy is established through a combination of **Surface Tiers** and **Soft Ambient Shadows**:

- **Level 0 (Background):** `background-light` (#f8f7f5) serves as the canvas.
- **Level 1 (Cards/Navigation):** Pure white (#ffffff) surfaces with a `shadow-sm` (subtle grey blur) to separate them from the background.
- **Level 2 (Hover States):** On interaction, cards lift using `shadow-xl`, creating a tactile sense of depth.
- **Overlays:** The Navigation bar uses a semi-transparent white with a 12px Backdrop Blur (glassmorphism) to feel integrated with the content passing beneath it.
- **Images:** Hero images and card thumbnails use a slight inner "scrim" (gradient) to ensure text legibility when overlaid.

## Shapes

The shape language is **Warm and Rounded**, avoiding sharp corners to maintain the friendly brand persona.

- **Standard Elements:** Buttons and interactive chips use `full` (pill) rounding to encourage clicking.
- **Containers:** Cards and Feature blocks use `rounded-xl` (24px on desktop) for a modern, soft container look.
- **Contextual Shapes:** Feature icons are housed in `rounded-xl` (12px) squares to provide a distinct structural rhythm compared to the more organic pill shapes used elsewhere.

## Components

### Buttons
- **Primary:** Pill-shaped, `primary` background, white text. Bold weight. Hover state: 105% scale transform.
- **Secondary:** Pill-shaped, `slate-100` background, `slate-900` text. Bordered for high contrast.
- **Icon Buttons:** Circular, subtle background (`slate-100` or `primary/10`), housing Material Symbols.

### Cards (Recipe)
- Vertical stack: Image (top) with aspect ratio 4:3.
- Floating Rating badge (top-right) using glassmorphism.
- Footer with metadata separated by a 1px `slate-100` border.
- Hover effect: Image scale (1.1x) and increased box-shadow.

### Chips/Tags
- **Filter Chips:** Pill-shaped. Active: `primary` bg/white text. Inactive: `slate-200` bg/`slate-700` text.
- **Attribute Tags:** Small, rectangular with soft rounding (4px). High-chroma color for text, 10% opacity for background (e.g., Green for Healthy).

### Input Fields
- Search bars use a subtle `slate-100` background, no borders, and rounded corners. Leading icons are mandatory for context.

### Navigation
- Sticky header with 72px height. Links use `semibold` weight and transition to `primary` color on hover.