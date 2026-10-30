---
name: Serene Academic Care
colors:
  surface: '#f7f9ff'
  surface-dim: '#d5dae2'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4fc'
  surface-container: '#e9eef6'
  surface-container-high: '#e3e9f0'
  surface-container-highest: '#dde3eb'
  on-surface: '#161c22'
  on-surface-variant: '#43474f'
  inverse-surface: '#2b3137'
  inverse-on-surface: '#ecf1f9'
  outline: '#73777f'
  outline-variant: '#c3c6d0'
  surface-tint: '#3e608c'
  primary: '#00274b'
  on-primary: '#ffffff'
  primary-container: '#173d67'
  on-primary-container: '#87a8d9'
  inverse-primary: '#a7c9fb'
  secondary: '#1e6296'
  on-secondary: '#ffffff'
  secondary-container: '#8cc6ff'
  on-secondary-container: '#005284'
  tertiary: '#002d16'
  on-tertiary: '#ffffff'
  tertiary-container: '#004625'
  on-tertiary-container: '#48bb78'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#a7c9fb'
  on-primary-fixed: '#001c39'
  on-primary-fixed-variant: '#244873'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#98cbff'
  on-secondary-fixed: '#001d33'
  on-secondary-fixed-variant: '#004a77'
  tertiary-fixed: '#88f9b0'
  tertiary-fixed-dim: '#6bdc96'
  on-tertiary-fixed: '#00210f'
  on-tertiary-fixed-variant: '#00522c'
  background: '#f7f9ff'
  on-background: '#161c22'
  surface-variant: '#dde3eb'
  surface-tint-blue: '#EAF2F8'
  surface-white: '#FFFFFF'
  sage-soft: '#E6F4EA'
  text-muted: '#6C757D'
  border-subtle: '#DCE6F1'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.25rem
    fontWeight: '700'
    lineHeight: 3.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-lg:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '600'
    lineHeight: 1.25rem
  label-md:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.125rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes a welcoming, minimalist, and deeply humanized institutional environment for the Psychopedagogical Support Center (NAP) within a health sciences faculty. Balancing academic authority with psychological safety, the visual language addresses university students who may be seeking counseling, study support, or emotional relief.

The design philosophy combines contemporary educational minimalism with warm healthcare sensibilities:
- **Atmosphere:** Reassuring, unhurried, empathetic, and organized. It eliminates cognitive friction and intimidation.
- **Visual Style:** Modern institutional minimalism built upon soft tonal surfaces, generous negative space, gentle curves, and subtle depth.
- **Accessibility & Clarity:** WCAG AA/AAA compliant contrast ratios, comfortable type scales, and straightforward navigational patterns that convey warmth without sacrificing professional credibility.

## Colors

The palette establishes an emotional landscape of trust, safety, and balance:
- **Primary (`#173D67`):** Deep institutional blue serving as the core anchor for key interactions, major headers, and institutional stability.
- **Secondary (`#2F6FA3`):** Active slate blue for interactive highlights, contextual links, and secondary visual landmarks.
- **Tertiary (`#48BB78`):** Restorative soft green representing psychological growth, health, and positive reinforcement; used for confirmation states, appointment approvals, and supportive tags.
- **Neutral (`#343A40`):** High-readability charcoal gray for primary body text, offering softer contrast than pure black.
- **Surface Tint Blue (`#EAF2F8`):** Calming, low-saturation canvas tint for cards, input containers, and side panels to minimize visual strain.
- **Sage Soft (`#E6F4EA`):** Gentle background tint reserved for positive notifications and health check indicators.

## Typography

The typographic hierarchy pairs the soft, humanist geometric personality of **Plus Jakarta Sans** for titles with the unmatched technical clarity of **Inter** for reading text and user inputs.

- **Headings (Plus Jakarta Sans):** Features gentle rounded terminals that reduce institutional harshness, making psychological intake forms and informational resources feel approachable and considerate.
- **Body & Labels (Inter):** Highly legible across small viewports, ensuring that long-form academic advice, appointment booking instructions, and triage surveys remain effortless to comprehend.
- **Rhythm & Leading:** Generous line heights are maintained throughout all levels to support neurodivergent students and prevent cognitive overload.

## Layout & Spacing

A structured 12-column responsive fluid grid governs desktop displays, condensing to 8 columns on tablet and 4 columns on mobile:
- **Canvas Margins:** Wide desktop borders (`3rem`) create a breathable, non-claustrophobic framing around sensitive content. Mobile viewports compress to `1.25rem` to maximize touch targets.
- **Component Breathing Room:** Components prioritize spacious interior padding (`space-md` to `space-lg`) to foster a tranquil reading cadence.
- **Form Factor Reflow:** Complex multi-step appointment schedules stack into clear single-column vertical flows on screen widths below 768px, ensuring complete focus on one task at a time.

## Elevation & Depth

To avoid overstimulating students, depth is achieved primarily through soft surface color shifts paired with ultra-diffused, cool-tinted ambient shadows rather than stark elevation drops.

- **Base Canvas:** Neutral clean `#FFFFFF` alongside calming `#EAF2F8` background fills for secondary workspace panels.
- **Card & Surface Elevation:** Floating containers utilize an ambient shadow formula tinted with deep institutional navy: `box-shadow: 0 4px 20px -2px rgba(23, 61, 103, 0.06), 0 2px 6px -1px rgba(23, 61, 103, 0.04)`.
- **Modals & Overlays:** Dialogs use a more prominent diffused shadow: `box-shadow: 0 16px 36px -4px rgba(23, 61, 103, 0.12)` complemented by a soft frosted backdrop (`backdrop-filter: blur(4px); background-color: rgba(23, 42, 72, 0.4)`).
- **Outlines:** All elevated containers rest within hairline boundaries (`1px solid #DCE6F1`) to provide structure under varying ambient lighting conditions.

## Shapes

The design system employs a **Rounded** shape language (`roundedness: 2`):
- **Base Components:** Inputs, buttons, chips, and small cards use `0.5rem` (8px) border radiuses to feel soft, friendly, and safe.
- **Containers & Modals:** Standard cards adopt `1rem` (16px) radii (`rounded-lg`), while hero banners and focal wellness containers scale up to `1.5rem` (24px) radii (`rounded-xl`).
- **Interactive Badges:** Full-pill radiuses (`9999px`) are reserved exclusively for status indicators, student tag indicators, and quick-filter category pills to communicate informality and ease.

## Components

### Buttons
- **Primary:** Filled with `#173D67`, crisp white typography, `0.5rem` radius, and `space-sm` vertical by `space-md` horizontal padding. Transitions gracefully to `#2F6FA3` on hover with a subtle upward translate (`-1px`).
- **Secondary:** Surface tint `#EAF2F8` with `#173D67` text and hairline border in `#DCE6F1`.
- **Tertiary / Gentle Action:** Borderless text buttons or filled with `#E6F4EA` and `#2E7D4B` text for stress-free secondary scheduling actions.

### Cards
- Constructed with `#FFFFFF` background, a hairline `1px solid #DCE6F1` stroke, `1rem` border radius, and `space-lg` internal padding. Dedicated psychopedagogical resource cards feature soft `#EAF2F8` header bars to group topical information logically.

### Form Inputs & Textareas
- Built for low-anxiety interactions. Surfaces are `#FFFFFF` wrapped in a `1.5px solid #DCE6F1` border.
- Focus states smoothly expand to an outline ring with `#2F6FA3` at 20% opacity and a solid `#2F6FA3` border. Labels sit in `#343A40` with `label-md` formatting, always persistent above inputs to ensure assistive technology compatibility.

### Selection Controls (Checkboxes & Radios)
- Gentle `0.25rem` radius for checkboxes and circular geometry for radios. When selected, they fill with `#173D67` and display a clean white checkmark or center pip. Focus states display an accessible soft-blue outer halo.

### Status Chips & Tags
- Compact `9999px` pill elements using muted backgrounds:
  - **Support / Active:** Background `#E6F4EA`, text `#2E7D4B`.
  - **Appointment Pending:** Background `#EAF2F8`, text `#2F6FA3`.
  - **Institutional / General:** Background `#F1F5F9`, text `#343A40`.

### Appointment & Intake Steps (Specialized Component)
- Horizontal step trackers on desktop, vertical on mobile. Completed steps highlight with `#48BB78`, current step marked with an encircled `#173D67` node, ensuring students always have a clear overview of session booking progress.