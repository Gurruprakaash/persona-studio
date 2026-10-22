---
name: Persona Studio
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#464555'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#006a63'
  on-secondary: '#ffffff'
  secondary-container: '#99efe5'
  on-secondary-container: '#006f67'
  tertiary: '#684000'
  on-tertiary: '#ffffff'
  tertiary-container: '#885500'
  on-tertiary-container: '#ffd4a4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#9cf2e8'
  secondary-fixed-dim: '#80d5cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#00504a'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an analytical, calm, and highly structured workspace tailored for UX researchers, product strategists, and design leads. The visual tone is utilitarian and modern corporate: every element serves clarity, synthesis, and rapid scanning of qualitative and quantitative user data.

By relying on crisp structural borders, predictable surface tiers, and calibrated typographic weights, the interface evokes confidence, rigor, and enterprise-grade reliability. The visual identity avoids ornamental distractions or heavy gradients, centering the user's research artifacts, quotes, persona demographics, and behavioral insights in an unobtrusive, high-legibility environment.

## Colors

The palette establishes clear functional roles across research workflows:

- **Primary (`#4F46E5` - Indigo):** Drives the primary action hierarchy, indicating active views, focused tabs, primary button triggers, and interactive selections.
- **Secondary (`#0F766E` - Deep Teal):** Denotes synthesized research evidence, verified user interview quotes, validated tags, and secondary metrics.
- **Tertiary / Warning (`#F59E0B` - Amber):** Highlights confidence scores, unverified sample warnings, and selective critical attention points.
- **Neutrals (Slate):**
  - Canvas Background: `#F8FAFC` (Cool Slate 50) provides soft contrast against content containers.
  - Card & Modal Surfaces: `#FFFFFF` ensures crisp document fidelity.
  - Borders & Dividers: `#E2E8F0` (Slate 200) maintains clear structural delineation without visual noise.
  - Text Hierarchy: Primary text renders in `#0F172A` (Slate 900) for strict WCAG AAA compliance, supported by `#475569` (Slate 600) for metadata, captions, and secondary labels.

## Typography

Typography relies entirely on the neutral, neo-grotesque legibility of Inter. Letter-spacing tightens slightly at headline scales to maintain typographic tension and coherence across wide canvas viewports, while remaining neutral at body scales for sustained reading of long-form research notes.

Data labels, schema headers, and research tag names use medium-to-semibold weights (`label-md` and `label-sm`) with slight positive tracking to ensure fast identification inside dense grids and persona attribute matrices.

## Layout & Spacing

The layout is built on an adaptable 12-column fluid grid system bounded by an application shell with a persistent 260px navigation rail on desktop screens.

- **Breakpoints:**
  - Mobile (`< 768px`): 4 columns, `margin-mobile` (16px), `gutter-sm` (16px). Sidebar collapses to an off-canvas drawer.
  - Tablet (`768px - 1023px`): 8 columns, `margin` (24px), `gutter` (24px). Sidebar collapses to icon rail.
  - Desktop (`1024px+`): 12 columns, `margin` (32px), `gutter-lg` (32px).
- **Rhythm:** Spacing follows an explicit 4px/8px modular scale. Spacing tokens strictly determine macro separation between layout nodes (`margin`, `gutter`) and internal component rhythm (`space-*`). Persona cards, research synthesis boards, and evidence panels must prioritize vertical rhythm via consistent 16px (`space-md`) or 24px (`space-lg`) stacking gaps.

## Elevation & Depth

Visual separation relies primarily on flat surfaces, 1px structural borders, and restrained ambient shadows. Deep layered drop shadows and blur effects are avoided to maintain data clarity.

- **Level 0 (Base Canvas):** `#F8FAFC` flat surface; no elevation.
- **Level 1 (Cards, Panels, Tables):** `#FFFFFF` fill with a `1px solid #E2E8F0` border and a soft ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Dropdowns, Flyouts, Popovers):** `#FFFFFF` fill with `1px solid #E2E8F0` and `0 4px 6px -1px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals, Slide-over Persona Inspectors):** `#FFFFFF` fill with `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)` over a backdrop tint of `rgba(15, 23, 42, 0.4)`.

## Shapes

The design uses standard rounded geometry (`roundedness: 2` = 8px base radius). This produces balanced, dependable containers that reflect modern desktop UI standards:

- **Base Radius (0.5rem / 8px):** Form inputs, buttons, chips, nested metrics containers, and standard table cells.
- **Large Radius (1rem / 16px):** Persona profile cards, modal dialogs, and workspace canvas containers.
- **Full Radius (9999px):** Status dots, avatar wrappers, and compact pill-style evidence counters.

## Components

### Buttons
- **Primary:** Solid `#4F46E5` background, `#FFFFFF` text, 8px radius, `h-10` (40px) or `h-9` (36px compact), horizontal padding `space-md` (16px). Hover: `#4338CA`. Active: `#3730A3`. Focus ring: 2px offset with `#818CF8`.
- **Secondary:** `#FFFFFF` background, `1px solid #E2E8F0`, `#0F172A` text. Hover: `#F8FAFC`.
- **Tertiary / Ghost:** Transparent background, `#475569` text. Hover: `#F1F5F9`, `#0F172A` text.

### Chips & Evidence Badges
- **Research Badge (Teal):** Background `#F0FDFA`, border `1px solid #CCFBF1`, text `#0F766E`, font `label-sm`.
- **Confidence Rating Badge (Amber):** Background `#FFFBEB`, border `1px solid #FEF3C7`, text `#B45309`, font `label-sm`.
- **Neutral Tag:** Background `#F1F5F9`, border `1px solid #E2E8F0`, text `#475569`.

### Form Inputs
- **Text & Select Fields:** 40px height, `#FFFFFF` surface, `1px solid #E2E8F0`, 8px radius, text `body-md` in `#0F172A`. Placeholder: `#94A3B8`. Focus: `1px solid #4F46E5` with `0 0 0 1px #4F46E5` glow ring. Error: `1px solid #EF4444`.

### Checkboxes & Radios
- Size: 16px x 16px, 4px corner radius for checkboxes, full circle for radios.
- Inactive: `#FFFFFF` fill with `1px solid #CBD5E1`.
- Active: `#4F46E5` fill with white checkmark/dot indicator.

### Cards & Persona Tiles
- Default card: Background `#FFFFFF`, border `1px solid #E2E8F0`, 16px radius, padding `space-lg` (24px).
- Persona Header Tile: Incorporates 48px rounded avatar image, primary persona title (`headline-sm`), quote callout in `body-md` italic (`#475569`), and segmented traits arranged in clean tabular rows.

### Data Tables & Research Strips
- Table headers use `#F8FAFC` background, uppercase tracking `label-sm` (`#64748B`), 40px row height.
- Rows use `#FFFFFF` with `1px solid #F1F5F9` bottom divider, hovering to `#F8FAFC`.