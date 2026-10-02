---
name: Obsidian Telemetry
colors:
  surface: '#121413'
  surface-dim: '#121413'
  surface-bright: '#383a38'
  surface-container-lowest: '#0c0f0e'
  surface-container-low: '#1a1c1b'
  surface-container: '#1e201f'
  surface-container-high: '#282a29'
  surface-container-highest: '#333534'
  on-surface: '#e2e3e0'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e2e3e0'
  inverse-on-surface: '#2f312f'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ebf9f0'
  on-tertiary: '#27332d'
  tertiary-container: '#cfddd4'
  on-tertiary-container: '#55625a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d8e6dc'
  tertiary-fixed-dim: '#bccac1'
  on-tertiary-fixed: '#121e18'
  on-tertiary-fixed-variant: '#3d4a43'
  background: '#121413'
  on-background: '#e2e3e0'
  surface-variant: '#333534'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  gutter-lg: 1.5rem
  margin: 1.5rem
  margin-sm: 1rem
  margin-lg: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the precision, high-velocity instrumentation, and technical rigor of physical AI and advanced robotics telemetry. It speaks to systems engineers, roboticists, and autonomy architects who demand total situational awareness without visual noise or cognitive lag. 

The aesthetic merges **minimalist precision engineering** with **high-contrast cybernetic telemetry**. It draws inspiration from mission control consoles, aerospace avionics HUDs, and laboratory-grade diagnostic suites. Surfaces are deeply recessed into near-black voids, illuminated solely by razor-sharp mechanical borders, monochromatic data typography, and electric functional indicators. Visual density is strictly managed: interactions feel immediate, zero-latency, and crystalline.

## Colors

The palette is engineered around high optical contrast and zero-glare low-light operational clarity:

- **Neutral Foundation:** The base operational surface sits at `#070908` (Deep Obsidian Void), shifting upward to `#0d110f` (Carbon Base) for elevated telemetry containers, sidebars, and analytical modules. Pure white (`#ffffff`) delivers uncompromised legibility for high-priority telemetry figures and critical data layers.
- **Structural Boundary:** `#1c2822` (Subtle Dark Matrix) acts as the single low-contrast boundary tone across dividers, grid tracks, module frames, and inactive bounds.
- **Electric Cyan Primary (`#00f0ff`):** Dedicated to primary action triggers, real-world positioning markers, active network links, focus envelopes, and high-frequency stream highlights.
- **Emerald Mint Secondary (`#10b981`):** Applied exclusively to system health verifications, operational latency nominal markers, verified physical AI synchronization states, and active sensor locks.
- **Diagnostic Tints:** Warning states use `#f59e0b` (Amber Telemetry Alert) and critical anomaly states employ `#ef4444` (Kinematic Rupture Red), applied only to discrete badges, vector strokes, and state indicators.

## Typography

The typographic hierarchy implements an uncompromising technical duality:

1. **Display & Structural Messaging (Space Grotesk):** Provides clean geometric contours with sharp mechanical terminals. Used for operational dashboard headers, section milestones, and body text. Kerning is deliberately tight on headlines to create a compact, tactical cadence.
2. **Telemetry, Feeds, and System Metrics (JetBrains Mono):** Drives all real-time telemetry tables, vector coordinates, coordinate axes, hardware status badges, latency indicators, and device UUIDs. Fixed-width metrics prevent layout jitter under rapid data refresh cycles.
3. **Data Legibility Rule:** All numerical data, timestamps, coordinates, and status values default to uppercase formatting with tabular lining figures enabled.

## Layout & Spacing

The layout philosophy is strictly systematic, modeled on a **12-column telemetry grid** that shifts dynamically across operational viewports:

- **Desktop (>= 1280px):** 12-column grid, `1.5rem` gutters, and `2.5rem` canvas margins. Grid units support rigid docking for real-time visualization viewports, raw message streams, and parameter sidebars.
- **Tablet / Split View (768px - 1279px):** 8-column layout with `1rem` gutters and `1.5rem` margins. Telemetry sidebars tuck into collapsable mechanical drawers.
- **Mobile Handheld (< 768px):** 4-column layout with `0.75rem` gutters and `1rem` margins. Critical metrics prioritize stacked modular readouts with vertical hardware inspection panels.
- **Vertical Rhythm:** Rooted in a strict 4px/8px modular base. Interface components maintain tight structural grouping (`space-xs` and `space-sm`), reserving wider intervals (`space-lg` and `space-xl`) for panel separation to reinforce clear modular domains.

## Elevation & Depth

This system avoids soft skeuomorphic shadows or diffuse blurs in favor of **Tonal Layering, Crisp Ghost Borders, and Focused Photonic Glows**:

- **Layer 0 (Canvas Void):** `#070908` serves as the infinite spatial backdrop for hardware nodes and network diagrams.
- **Layer 1 (Card & Module Foundation):** `#0d110f` paired with a sharp 1px structural border of `#1c2822`. No diffuse shadow is applied.
- **Layer 2 (Overlays, Flyouts, Diagnostics):** Surface sits at `#131916` with a `#1c2822` border.
- **Active Focus & Critical Depth:** Interactive elevation is signaled by edge illumination rather than drop shadow. Active inputs or focused robot telemetry nodes transition their border to `#00f0ff` accompanied by a constrained photonic bloom: `0 0 12px rgba(0, 240, 255, 0.25)`.
- **Nominal Telemetry Lock:** Locked physical states use a subtle emerald ambient outline: `0 0 10px rgba(16, 185, 129, 0.20)`.

## Shapes

The design system employs a **Soft Architectural (`roundedness: 1`)** geometry. 

Corners are governed by microscopic radiuses: `0.25rem` (4px) for interactive controls, inputs, data badges, and status pills, scaling to `0.5rem` (8px) for major hardware viewport panels and modal sheets. Rounded pill treatments are prohibited to prevent an overly casual consumer appearance. The visual language conveys machined carbon fiber, solid-state silicon modules, and precision robotics enclosures.

## Components

### Buttons
- **Primary Action:** Solid electric cyan background (`#00f0ff`) with carbon black text (`#070908`), font weight 600, using `Space Grotesk`. Hover triggers a brightness step (`#38f3ff`) and a discrete cyan outer edge glow.
- **Secondary Action:** High-contrast outlined variant. Background is `#0d110f`, border is 1px `#1c2822`, text is `#ffffff`. Hover shifts the border to `#00f0ff` and text to `#00f0ff`.
- **Destructive/Emergency Stop:** Dark carbon core with 1px `#ef4444` border and `#ef4444` text. Active state fills red with pure white text.

### Telemetry Cards & Viewports
- Modular panels sit on `#0d110f` with a 1px uniform `#1c2822` border and `0.5rem` corner radius.
- Card headers feature an integrated technical meta bar: a monospaced tracking ID (`label-sm`), panel status beacon, and optional live Hz streaming indicator.

### Chips & Sensor Badges
- Compact indicators rendered with `JetBrains Mono` (`label-sm`).
- **Nominal/Active:** Border `1px solid rgba(16, 185, 129, 0.4)`, background `rgba(16, 185, 129, 0.08)`, text `#10b981`. Includes a 6px pulsing emerald hardware beacon dot.
- **Standby/Disconnected:** Border `1px solid #1c2822`, background `transparent`, text `#6b7280`.

### Data Tables & Stream Lists
- Minimalist terminal presentation. Row borders sit at 1px `#1c2822` with a `44px` compact height.
- Header columns use `label-md` in uppercase `#9ca3af`.
- Numerical data columns render in `JetBrains Mono`, aligned right, with zero-latency tabular numbers. Hovering over a row highlights the background to `#131916` with a `#00f0ff` 2px left border accent.

### Inputs & Sensor Sliders
- Input fields use `#070908` base, 1px `#1c2822` border, and pure white text. Placeholder text is `#4b5563`.
- Focus state instantly replaces the border with `#00f0ff` and a faint glow.
- Sensor range sliders utilize an ultra-thin 2px track in `#1c2822`, an active cyan fill, and a 12px square machined slider thumb with a 1px border.

### Checkboxes & Toggle Switches
- Checkboxes: 16px square, `#070908` interior, 1px `#1c2822` border. Checked state renders a solid `#00f0ff` frame with `#070908` geometric checkmark.
- Toggles: Mechanical track (32px x 18px) in `#1c2822`. Active thumb snaps to `#00f0ff` with an active emerald or cyan track interior.

### Specialized Hardware Components
- **Vector Metric Matrix:** Dedicated HUD block for displaying 3-axis kinematics (X/Y/Z) with high-legibility fixed-width alignment.
- **Node Status Indicator:** Micro-scale diagnostic ring showing node synchronization frequency and dropped packet ratios.