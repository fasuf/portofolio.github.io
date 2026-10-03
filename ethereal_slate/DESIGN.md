---
name: Ethereal Slate
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#40484e'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#70787e'
  outline-variant: '#bfc7ce'
  surface-tint: '#0b658a'
  primary: '#0b658a'
  on-primary: '#ffffff'
  primary-container: '#8acff8'
  on-primary-container: '#00597a'
  inverse-primary: '#8acff8'
  secondary: '#00658b'
  on-secondary: '#ffffff'
  secondary-container: '#7fd0ff'
  on-secondary-container: '#00597a'
  tertiary: '#546067'
  on-tertiary: '#ffffff'
  tertiary-container: '#bcc9d1'
  on-tertiary-container: '#48555b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#8acff8'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#c5e7ff'
  secondary-fixed-dim: '#7fd0ff'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6a'
  tertiary-fixed: '#d7e4ec'
  tertiary-fixed-dim: '#bbc8d0'
  on-tertiary-fixed: '#111d23'
  on-tertiary-fixed-variant: '#3c494f'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system delivers an airy, calm, and exquisitely polished digital showcase tailored for a UI/UX Designer. It merges warm minimalism with contemporary Dribbble-grade portfolio aesthetics: extensive negative space, pill-shaped interactions, tactile micro-elevations, and soft sky-tinted accents. 

The aesthetic projects high craft, intentional restraint, and effortless clarity. Interactions favor subtle spatial transformations, soft atmospheric depth, and fluid states that signal deep UX maturity rather than visual noise.

## Colors
The palette is built around an airy, sky-tinted chromatic hierarchy paired with architectural slates.

- **Primary Canvas (`#FFFFFF`)**: Pure white base for primary showcase sections, case study views, and elevated cards.
- **Subtle Surface (`#F8FBFD`)**: An ultra-soft, cool-tinted alternate surface used for alternating content sections, process highlights, and nested containers.
- **Primary Accent (`#8ACFF8`)**: Soft sky blue utilized for focal interactions, active states, key tags, and visual accents.
- **Primary Interactive / Hover (`#6BBDEB`)**: Deeper sky blue dedicated to hover states, focus rings, and high-emphasis controls.
- **Tint / Fill Layer (`#E8F5FD`)**: Low-saturation sky tint for badge fills, selected table rows, hover glows, and icon containers.
- **Primary Text (`#1E293B`)**: Deep slate neutral ensuring accessible legibility and crisp contrast across all light surfaces.
- **Secondary Text (`#64748B`)**: Muted slate for secondary meta-information, captions, dates, and subtitle hierarchies.
- **Structural Stroke (`#E2E8F0`)**: Crisp, light-neutral perimeter stroke applied to cards, separators, and interactive containers.

## Typography
Plus Jakarta Sans provides geometric balance, generous apertures, and contemporary warmth that mirrors modern portfolio craft.

- **Display Scales**: Reserved for the portfolio hero headline and dramatic project title reveals. Tight tracking gives substantial optical weight without heaviness.
- **Headings**: Semi-bold weight gives structure to case study narrative sections, client lists, and modular card headers.
- **Body & Captions**: Generous line height ensures effortless long-form readability during deep-dive case study breakdowns.
- **Label & Badges**: Crisp medium and semi-bold weights maintain legibility across tiny metadata indicators, role tags, and timeline markers.

## Layout & Spacing
The layout adheres to a 12-column responsive fluid grid pinned to a maximum content container width of 1280px to preserve comfortable scanning distances.

- **Breakpoints**: 
  - Mobile (< 640px): 4-column layout, `margin-mobile` outer padding, vertical stacking for case studies and visual showcases.
  - Tablet (640px – 1024px): 8-column layout, 2-column project grids.
  - Desktop (> 1024px): 12-column layout, expansive structural breathing room.
- **Rhythm**: Generous vertical section spacing (80px–120px) creates clean pauses between hero, featured work, design philosophy, and footer contact modules. Component interiors utilize consistent 4px/8px incremental multiples.

## Elevation & Depth
Depth is treated atmospherically with luminous, cloud-like ambient shadows rather than rigid drop shadows. Surfaces rest gently upon each other with the aid of micro-strokes.

- **Level 0 (Flat)**: Section canvases (`#FFFFFF` and `#F8FBFD`) without elevation.
- **Level 1 (Card Resting)**: Background `#FFFFFF`, 1px border (`#E2E8F0`), shadow `0 2px 12px -2px rgba(30, 41, 59, 0.04), 0 1px 3px rgba(30, 41, 59, 0.02)`.
- **Level 2 (Hover / Floating Navigation)**: Card hover state and persistent headers. Shadow `0 12px 32px -4px rgba(30, 41, 59, 0.08), 0 4px 12px -2px rgba(30, 41, 59, 0.03)`. Subtle vertical lift (`translateY(-4px)`) smoothed by a 200ms cubic-bezier transition.
- **Level 3 (Modal / Featured Preview)**: Shadow `0 24px 48px -8px rgba(30, 41, 59, 0.12), 0 8px 16px -4px rgba(30, 41, 59, 0.04)`.

## Shapes
A unified soft-geometry system balances full pill treatments for interactive elements with generous curves (16px to 24px) for content cards.

- **Pill (Fully Rounded / 9999px)**: Action buttons, tags, chips, search/filter inputs, and floating dock bars.
- **Container Curvature (20px – 24px)**: Project showcase cards, imagery viewports, testimonial blocks, and contextual panels.
- **Nested Inner Radii (12px – 16px)**: Sub-elements, inner thumbnail mockups, and nested callout cards to respect nested concentric geometry.

## Components

### Buttons
- **Primary Button**: Pill-shaped (`rounded-full`), filled with `#8ACFF8`, label in `#1E293B` (SemiBold). Hover shifts smoothly to `#6BBDEB` with a subtle elevation shift. Padding: 12px 28px (`space-sm` + `space-md`).
- **Secondary / Ghost Button**: White surface with 1px border in `#E2E8F0`. Hover triggers background `#E8F5FD` and border color `#8ACFF8`.
- **Icon Button**: Circular pill (44px x 44px), centered SVG icon in `#1E293B`, subtle hover background `#E8F5FD`.

### Project Showcase Cards
- **Structure**: Surface `#FFFFFF`, 1px solid stroke `#E2E8F0`, 24px border radius.
- **Thumbnail Container**: Overflow-hidden top segment with 16px inner radius, housing high-resolution project mockups.
- **Interaction**: On hover, image scales by 1.02x; card subtly elevates to Level 2 with a 4px upward translation.

### Chips & Tags
- **Category Badge**: Pill-shaped (`rounded-full`), background `#E8F5FD`, text `#1E293B`, border none. Font: `label-md`.
- **Status Indicator**: Features a 6px circular dot (e.g., live green or accent blue) paired with a clean text label.

### Input Fields & Textareas
- **Surface**: Background `#FFFFFF`, stroke `#E2E8F0`, radius 9999px for single-line inputs and 20px for textareas.
- **States**: Focused state applies a border of `#8ACFF8` and a 3px soft outer ring in `rgba(138, 207, 248, 0.35)`. Placeholder colored in `#64748B`.

### Checkboxes & Radios
- **Selection**: Rounded box (6px) or circular pill, `#FFFFFF` with `#E2E8F0` stroke. When active, filled `#8ACFF8` with crisp white checkmark/dot.

### Portfolio Floating Dock / Navigation
- **Bar**: Pill-shaped glass container pinned to top or bottom center. Background `rgba(255, 255, 255, 0.85)` with 12px backdrop-blur, bordered by `#E2E8F0`. Features active indicator pills for section browsing.