---
name: Industrial Precision System
colors:
  surface: '#0c0e35'
  surface-dim: '#0c0e35'
  surface-bright: '#33365d'
  surface-container-lowest: '#070930'
  surface-container-low: '#15173e'
  surface-container: '#191c42'
  surface-container-high: '#23264d'
  surface-container-highest: '#2e3159'
  on-surface: '#e0e0ff'
  on-surface-variant: '#bac9c9'
  inverse-surface: '#e0e0ff'
  inverse-on-surface: '#2a2d54'
  outline: '#859493'
  outline-variant: '#3b4949'
  surface-tint: '#31dbdb'
  primary: '#46e8e8'
  on-primary: '#003737'
  primary-container: '#00cccc'
  on-primary-container: '#005151'
  inverse-primary: '#006a6a'
  secondary: '#00e1a3'
  on-secondary: '#003826'
  secondary-container: '#007f5b'
  on-secondary-container: '#d0ffe6'
  tertiary: '#73e4e4'
  on-tertiary: '#003737'
  tertiary-container: '#53c8c8'
  on-tertiary-container: '#005151'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#5cf8f8'
  primary-fixed-dim: '#31dbdb'
  on-primary-fixed: '#002020'
  on-primary-fixed-variant: '#004f4f'
  secondary-fixed: '#40ffbd'
  secondary-fixed-dim: '#00e1a3'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#005139'
  tertiary-fixed: '#83f4f4'
  tertiary-fixed-dim: '#65d8d7'
  on-tertiary-fixed: '#002020'
  on-tertiary-fixed-variant: '#004f4f'
  background: '#0c0e35'
  on-background: '#e0e0ff'
  surface-variant: '#2e3159'
typography:
  headline-xl:
    fontFamily: manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 24px
  margin: 32px
  container-max: 1440px
---

## Brand & Style

The design system is engineered for the high-stakes environment of CNC and industrial automation. It embodies a persona of **engineering excellence, unwavering reliability, and digital foresight**. The target audience—engineers, plant managers, and solution partners—requires a UI that prioritizes clarity, data density, and a sense of "technological weight."

The visual style is **Corporate / Modern** with a strong leaning toward **Technical Minimalism**. It avoids decorative flourishes in favor of structural integrity. Elements are crisp and deliberate, reflecting the precision of a digital twin or a high-end machining center. The atmosphere is professional and high-tech, leveraging deep dark backgrounds to evoke a "command center" feel while using vibrant teal accents to highlight status and innovation.

## Colors

The palette is anchored by the signature **Deep Navy (#000028)**, which serves as the primary canvas for all industrial interfaces. This dark base reduces eye strain in factory floor environments and provides a high-contrast foundation for technical data.

- **Siemens Petrol (#00CCCC / #009999):** The primary action and brand color. It represents the bridge between traditional industry and the digital future.
- **Innovation Green (#00FFB9):** A high-vibrancy accent used sparingly for success states, active machine signals, and highlighting breakthrough innovations.
- **Clean White (#FFFFFF):** Used exclusively for primary typography and essential iconography to ensure maximum legibility against the dark background.

## Typography

The typography system utilizes **Manrope** for headlines to provide a modern, geometric structure that mimics the precision of industrial design. **Inter** is selected for body copy and UI labels due to its exceptional clarity and neutrality, making it ideal for displaying complex technical parameters and CNC code.

- **Hierarchy:** Strong contrast between bold headlines and utilitarian body text.
- **Labels:** Small caps or increased letter spacing are used for technical labels and machine metadata to differentiate them from prose.
- **Readability:** High line-height ratios are maintained for body text to prevent fatigue during long periods of monitoring.

## Layout & Spacing

The design system employs a **Fixed-Fluid Hybrid Grid**. Content is housed within a 12-column grid system with a maximum width of 1440px to ensure data remains scannable on large industrial monitors. 

The spacing rhythm is based on a **4px baseline grid**, reinforcing the "precise" nature of the brand. For high-density dashboards, the spacing is tightened (8px-12px), while for marketing and solution partner landing pages, the spacing expands (40px+) to allow for a premium, innovative feel.

## Elevation & Depth

In an industrial context, "depth" is used to define operational priority. This design system avoids traditional shadows in favor of **Tonal Layering** and **High-Contrast Outlines**.

- **Surface Tiers:** The base background is the deepest navy. Interactive panels and cards use a slightly lighter tint (#00003A) to appear "lifted."
- **Ghost Borders:** Elements are separated by 1px solid borders in a low-opacity teal or a muted navy. This creates a "blueprint" or "schematic" aesthetic.
- **Active Focus:** A 2px high-vibrancy petrol (#00CCCC) border or glow is used to indicate the active state of a machine or a selected input field, providing an immediate visual signal of "Focus."

## Shapes

The shape language is strictly **Sharp (0px)**. Rectilinear forms convey stability, efficiency, and industrial rigidity. Every UI element—from buttons to input fields to container cards—features hard 90-degree corners. This evokes the precision of CNC-machined components and technical drawings. This lack of rounding differentiates the system from consumer software, signaling that this is a professional-grade tool for industry experts.

## Components

### Buttons
Buttons are rectangular with zero corner radius. 
- **Primary:** Solid Petrol (#00CCCC) with Black or Navy text.
- **Secondary:** Outlined in Petrol with White text.
- **Tertiary:** Text-only with a heavy underline on hover.

### Input Fields
Fields feature a dark background (darker than the card surface) with a 1px bottom border in Teal. When focused, the entire border becomes Teal with a subtle outer glow. Label text is always small-cap and positioned above the field.

### Status Indicators (Chips)
Used for machine health and connectivity. These are flat, rectangular blocks.
- **Active:** Innovation Green (#00FFB9) background.
- **Warning:** Amber (Standard industrial yellow) text with a thin border.
- **Error:** Bright Red text with a thin border.

### Data Cards
Cards are the primary container for machine telemetry. They use the secondary surface color (#00003A) and a 1px border. No shadows. Header areas of cards may use a muted Teal background to separate the title from the data.

### Progress & Gauges
Linear progress bars use a 1px stroke for the track and a solid Teal or Green fill for the progress. In keeping with the CNC theme, monospaced numbers (within the Inter family) are preferred for live data readouts.