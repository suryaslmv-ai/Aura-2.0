---
name: Ethereal Obsidian
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c1f29'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#bdc2ff'
  on-secondary: '#131e8c'
  secondary-container: '#2f3aa3'
  on-secondary-container: '#a8afff'
  tertiary: '#3de2e8'
  on-tertiary: '#003739'
  tertiary-container: '#00c5cb'
  on-tertiary-container: '#004c4f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bdc2ff'
  on-secondary-fixed: '#000767'
  on-secondary-fixed-variant: '#2f3aa3'
  tertiary-fixed: '#5cf8fe'
  tertiary-fixed-dim: '#31dbe1'
  on-tertiary-fixed: '#002021'
  on-tertiary-fixed-variant: '#004f52'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
  surface-base: '#090D16'
  surface-raised: '#0F172A'
  surface-glass: rgba(15, 23, 42, 0.65)
  border-glass: rgba(255, 255, 255, 0.08)
  border-glow: rgba(56, 189, 248, 0.35)
  aura-cyan: '#1AD1D7'
  aura-indigo: '#818CF8'
  aura-violet: '#C084FC'
  accent-amber: '#F5A623'
  text-primary: '#F8FAFC'
  text-muted: '#94A3B8'
typography:
  display-hero:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Sora
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-action:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system blends **Hyper-Modern Minimalism** with **Atmospheric Glassmorphism**, tailored for advanced artificial intelligence generation, model orchestration, and conversational developer tooling. The brand identity balances technical precision with organic luminosity—evoking deep, focused intelligence suspended within an infinite digital void.

The visual style is defined by pitch-deep obsidian surfaces, laser-crisp borders with subtle inner hairline glows, and vibrant multidimensional bioluminescent aura gradients (cyan to indigo and electric violet). It avoids heavy flat opacities in favor of layered, frosted diffusion filters, allowing underlying neon energy fields to subtly bleed through structural frames. The emotional posture is calm, authoritative, hyper-focused, and cutting-edge.

## Colors

The palette revolves around deep obsidian slate foundations layered with energetic, spectral chromatic lights.

- **Primary (`#38BDF8`)**: Vibrant sky-cyan representing active intelligence, terminal states, active focus indicators, and primary interaction elements.
- **Secondary (`#818CF8`)**: Ethereal electric indigo providing chromatic depth, secondary CTAs, system model badges, and ambient illumination.
- **Tertiary (`#1AD1D7`)**: Radiant teal used for real-time streaming pulses, latency metrics, and verified domain tags.
- **Neutral (`#090D16`)**: Deep obsidian base canvas delivering near-absolute black levels to maximize contrast and aura luminosity.

### Semantic Color Assignments
- **Backdrops & Canvases**: Use `surface-base` (`#090D16`) for root backgrounds. Use `surface-raised` (`#0F172A`) for fixed sidebars and elevated panels.
- **Aura Gradients**: Combine `aura-cyan`, `aura-indigo`, and `aura-violet` into linear and radial lighting effects behind cards, active prompt inputs, and the Aura model selector.
- **Alerts & Warnings**: Reserve `accent-amber` (`#F5A623`) strictly for API usage thresholds, destructive confirmations, and pending states.

## Typography

The typographic hierarchy relies on a technical pairing:
- **Sora** brings geometric, crystalline weight to system titles, modal titles, and navigation nodes, reflecting a forward-looking technological character.
- **Plus Jakarta Sans** ensures long conversation threads, tooltips, and chat transcripts remain legible and fatigue-free across extended generation sessions.
- **JetBrains Mono** powers developer components, prompt tokens, model version counters, parameters, and inline code snippets.

All display titles utilize tight negative tracking to ground the visual weight against dark surfaces. Monospaced elements utilize upper tracking for elevated visual structure.

## Layout & Spacing

The layout is built around an asymmetric fluid workspace:
- **Sidebar Rail**: Fixed 260px collapsible panel housing the Aura version switcher (`Aura 1.0`, `Aura Lite`, `Aura X Creator`), domain filters, and profile anchors. On tablet screens, this reduces to an icon rail (68px); on mobile screens, it collapses into an off-canvas drawer.
- **Chat Stream Canvas**: Centered container with a maximum width of `840px` to maintain optimal conversational reading line lengths.
- **Contextual Inspector / Settings Drawer**: Slide-over panel (420px fixed) for API key configurations, domain telemetry, and model temperature controls.

Spacing adheres strictly to an 8pt increment model. Component gaps inside chat threads scale systematically from compact prompt suggestions (`space-xs` / `space-sm`) to distinct conversational exchange blocks (`space-xl`).

## Elevation & Depth

This design system uses spectral glassmorphism, surface layering, and back-lit halos instead of drop shadows.

- **Level 0 (Base Canvas)**: Solid `#090D16`. Passive backdrop with subtle static radial gradients placed in corners (`rgba(56, 189, 248, 0.04)` and `rgba(129, 140, 248, 0.04)`).
- **Level 1 (Docked Surfaces & Sidebars)**: `#0F172A` at 80% opacity with `backdrop-filter: blur(16px)` and a `1px` continuous border in `rgba(255, 255, 255, 0.06)`.
- **Level 2 (Interactive Floating Cards & Prompt Bar)**: Semi-translucent `rgba(15, 23, 42, 0.65)` with `backdrop-filter: blur(24px)`. Borders receive a top hairline highlight of `rgba(255, 255, 255, 0.12)` fading to `rgba(255, 255, 255, 0.03)` at the bottom edge.
- **Level 3 (Modals & Flyouts - API Settings)**: Solid `#0F172A` with an ambient external aura halo: `box-shadow: 0 0 60px -15px rgba(56, 189, 248, 0.18), 0 20px 25px -5px rgba(0, 0, 0, 0.5)`.
- **Active Focus & Hover**: Element borders transition to `rgba(56, 189, 248, 0.45)` accompanied by a localized neon glow (`box-shadow: 0 0 15px rgba(56, 189, 248, 0.2)`).

## Shapes

The interface embraces a unified soft geometry (`roundedness: 2`). Standard controls, message callouts, and inputs use `0.5rem` (8px). Larger parent containers, conversational glass pods, and the persistent bottom prompt dock use `1rem` (16px, `rounded-lg`). Overlays and API drawers leverage `1.5rem` (24px, `rounded-xl`).

Small system badges, filter tags, and model indicator pills retain a full pill curvature (`9999px`) to maintain contrast with the angular workspace grid.

## Components

### Buttons
- **Primary Action (Aura Glow)**: Linear gradient background (`to right, #38BDF8, #818CF8`), dark label `#090D16` in `label-action` weight. Hover generates a vibrant diffuse halo (`0 0 20px rgba(56, 189, 248, 0.4)`).
- **Ghost / Glass Variant**: Transparent background, `1px border-glass` border, text in `#F8FAFC`. On hover: `background: rgba(255, 255, 255, 0.05)`, border color increases to `border-glow`.

### Model Selector Dropdown (Aura 1.0 / Aura Lite / Aura X Creator)
Segmented glass selector with an active sliding highlight. The active item displays an animated neon status dot (Cyan for Creator, Indigo for 1.0, Teal for Lite) alongside a `label-code` version tag.

### Domain Knowledge Chips (Sports, News, Medical, Coding)
Pill-shaped toggle tokens with translucent backing (`rgba(255, 255, 255, 0.03)`). Selected states activate a neon cyan border, a faint cyan fill tint (`rgba(26, 209, 215, 0.08)`), and an accompanying domain icon.

### Live Prompt Suggestions
Small glass tiles resting directly above the chat composer. Rendered with `border-glass`, subtle hover lift, and an internal leading arrow indicator (`→`) in `primary_color_hex`.

### Input Fields & Active Prompt Bar
The chat composer acts as a floating command center. Backed by `surface-glass` with a 24px blur radius, padded with `space-md`, and framed with a `1px` border that shifts from neutral white-alpha to vibrant aura-gradient when focused. Houses quick-action buttons (file upload, model picker, submit) inline.

### Modals & Drawers (Real-Time API Settings)
Slide-in glass drawer from the right edge with a backdrop curtain (`rgba(9, 13, 22, 0.7)` with `backdrop-filter: blur(8px)`). Secret key fields feature monospaced typography with a built-in mask/unmask toggle and real-time validation check marks.

### User Account Controls
Compact profile pod pinned to the lower-left sidebar. Displays avatar with a radial halo ring, workspace name, quota usage progress bar (gradient fill from Cyan to Indigo), and quick-access settings flyout.