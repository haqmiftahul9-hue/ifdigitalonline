---
name: the design system
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#515f79'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c33'
  on-primary-container: '#7684a0'
  inverse-primary: '#b9c7e5'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a42'
  on-tertiary-container: '#3980f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e5'
  on-primary-fixed: '#0d1c33'
  on-primary-fixed-variant: '#394760'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-display:
    fontFamily: Manrope
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-display-mobile:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  grid-columns: '12'
  gutter-desktop: 32px
  gutter-tablet: 24px
  gutter-mobile: 16px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  space-2: 8px
  space-4: 16px
  space-6: 24px
  space-8: 32px
  space-12: 48px
  space-16: 64px
  space-24: 96px
---

## Brand & Style

This design system is crafted for a professional digital studio and web development agency, establishing an air of sophisticated authority, technical precision, and modern elegance. The brand personality is rooted in reliability, cutting-edge capability, and strategic insight. 

The aesthetic style merges **Minimalism** with a **Corporate / Modern** framework. It relies on heavy, purposeful whitespace, crisp grid structures, highly legible typography, and a refined color palette that commands trust. The UI should evoke a sense of calm competence, assuring enterprise clients and ambitious startups alike of flawless execution and high-end digital craftsmanship.

## Colors

The color palette establishes a deep, commanding presence through Dark Navy tones, balanced by an expansive soft off-white background, and punctured by high-energy electric blues for conversion points and interactive states. 

- **Primary (Dark Navy):** Used for heavy structural elements, primary typography, and deep surface layers (`#071426`, `#0A1930`, `#0D2140`).
- **Secondary / Accent (Electric Blue):** Drives calls-to-action, active states, and focal interactive elements (`#2563EB`, `#3B82F6`).
- **Neutral (Off-White/Gray):** Serves as the breathable canvas for all content layers (`#F8FAFC`, `#FFFFFF`).

## Typography

Typography pairs geometric structure with utilitarian clarity. **Manrope** drives all headlines with a confident, modern geometric posture, while **Inter** anchors the system for unmatched readability in body copy and interface labels. 

Type scales are strictly enforced to maintain a clean editorial rhythm. Large display sizes automatically step down on mobile viewports to preserve layout integrity without sacrificing visual impact. Line heights are intentionally generous to reinforce the airy, spacious atmosphere of the agency's digital presence.

## Layout & Spacing

The layout philosophy relies on a strict **Fixed Grid** model (max-width 1280px container) coupled with generous section padding to enforce whitespace. 

- **Desktop:** 12-column grid with 32px gutters and generous outer margins (minimum 80px) to frame content like high-end editorial spreads.
- **Tablet:** 12-column fluid grid scaling down to 24px gutters and 40px margins.
- **Mobile:** Single-to-multi column reflow utilizing 16px gutters and 20px safe margins. 

Vertical rhythm is maintained using a base-8 scale, ensuring consistent spacing between structural components, typography blocks, and section dividers.

## Elevation & Depth

Depth is communicated through subtle **ambient shadows** and **low-contrast outlines** rather than heavy skeuomorphic effects. 

- **Surface Tiers:** The UI is built upon clean off-white backgrounds (`#F8FAFC`) with pure white (`#FFFFFF`) card surfaces.
- **Shadows:** Floating elements (dropdowns, navigation bars, modal dialogs) utilize ultra-soft, diffused shadows tinted with the primary Dark Navy hue (`rgba(10, 25, 48, 0.06)` to `0.12`), creating a gentle lift.
- **Borders:** Structural cards and input fields employ crisp, low-opacity ghost borders (`#E2E8F0`) that maintain a flat, modern architectural appearance.

## Shapes

The shape language follows a **Soft** roundedness model (`0.25rem` base, scaling to `0.5rem` for cards and `0.75rem` for large containers). 

This subtle corner curvature strikes the exact balance between approachable digital utility and sophisticated enterprise precision. Sharp 0px corners are reserved strictly for technical data tables or full-width image containers, while interactive elements maintain friendly, softened geometry.

## Components

### Buttons
Primary actions utilize the Electric Blue (`#2563EB`) background with crisp white text, a soft rounded radius (`0.375rem`), and a subtle hover state shift to `#1D4ED8`. Secondary actions employ ghost styling with a Dark Navy outline and transparent fill.

### Chips & Tags
Compact metadata labels feature soft neutral or light blue backgrounds with label-sm typography, utilized for categorizing case studies, tech stacks, and service offerings.

### Lists
Clean, highly structured vertical lists with generous padding (min 16px per item) and subtle bottom dividers (`#E2E8F0`). Often paired with leading icons rendered in Electric Blue.

### Checkboxes & Radio Buttons
Precision-engineered controls featuring a 2px border in Dark Navy neutral-dark states, filling solidly with Electric Blue upon selection.

### Input Fields
Form inputs feature a crisp white background, a 1px ghost border, and clear floating or external labels. Focus states instantly elevate the border to Electric Blue accompanied by a subtle 2px ring shadow.

### Cards
Service cards, project case studies, and metric callouts sit on pure white surfaces with subtle outlines, generous internal padding (`space-8`), and smooth hover elevation transitions.

### Additional Components
- **Navbars:** Sticky glassmorphism header with a 80% opacity backdrop blur, housing agency branding and streamlined menu links.
- **Metric Counters:** Large-scale numeric stat callouts utilizing headline-display typography paired with body-sm descriptive labels for client proof points.