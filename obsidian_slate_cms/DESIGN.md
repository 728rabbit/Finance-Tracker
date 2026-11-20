---
name: Obsidian Slate CMS
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.9375rem
    fontWeight: '600'
    lineHeight: 1.375rem
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.125rem
  label-md:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.125rem
  label-sm:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is tailored for high-performance content management, digital publishing, and enterprise-grade SaaS environments. The visual language blends ultra-clean modern minimalism with razor-sharp editorial clarity, stripping away legacy admin visual debt—such as heavy multi-colored primary buttons, thick border tables, and noisy icon clutter—in favor of purposeful whitespace, crisp typography, and micro-interactions.

The aesthetic philosophy draws heavily from high-contrast editorial minimalism:
- **Calm, Focused Foundations:** Canvas layers leverage optical whites and soft zinc tones, allowing editorial status, metadata, and page structures to breathe effortlessly.
- **Intentional Contrast:** Typography anchors the interface with deep slate-obsidian blacks, paired with calibrated secondary grays that guide the eye without causing visual fatigue over extended workflows.
- **Precision Engineering:** Subtle hairline borders (1px solid slate-tinted strokes), hairline dividers, and whisper-soft diffused drop shadows replace outdated boxy card boundaries.
- **Micro-Refinements:** Pill-shaped status indicators, tactile hover transitions, and compact action controls elevate utility into a premium administrative experience.

## Colors

The palette embraces a monochrome core accented by tactical semantic hues. Deep slate black serves as the primary anchor for decisive actions and prominent elements, while neutral zinc tones establish surface hierarchy.

- **Primary (`#0F172A` - Slate Obsidian):** Used for primary buttons, active navigation states, high-priority titles, and crisp iconography.
- **Secondary (`#2563EB` - Precision Cobalt):** Reserved for interactive links, focused state outlines, and primary system indications without overwhelming the screen.
- **Tertiary (`#10B981` - Emerald Indicator):** Used exclusively for success states, live published indicators, and operational health badges.
- **Destructive (`#EF4444` - Crimson):** Reserved strictly for destructive page deletions and critical error alerts.
- **Neutral Backgrounds & Surfaces:**
  - `canvas`: `#F8FAFC` (Cool slate tint)
  - `surface-elevated`: `#FFFFFF` (Pure white containers)
  - `border-hairline`: `#E2E8F0` (Delicate 1px structure)
  - `text-primary`: `#0F172A` (Obsidian readability)
  - `text-secondary`: `#64748B` (Grounded metadata)
  - `text-tertiary`: `#94A3B8` (Muted placeholder and subtle column indicators)

## Typography

Typography delivers crisp rhythm and strict legibility across dense data tables, navigation sidebars, and configuration forms.

- **Headings (Plus Jakarta Sans):** Brings a geometric yet warm, highly modern executive voice to titles, view headings, and section partitions.
- **Body & Data (Inter):** Maximizes readability across table cell data, breadcrumbs, inputs, and system logs with clear numeral differentiation.
- **Data Table Headers:** Set in `label-sm` with uppercase transformation, +0.05em letter spacing, and a subdued slate tone to ensure columns remain distinct without pulling focus from table rows.

## Layout & Spacing

The dashboard relies on an asymmetric master-detail layout structured for persistent administrative focus:
- **Left Navigation Rail / Sidebar:** Fixed 260px width, extending full vertical height with a clean `#FFFFFF` ground and a right hairline border (`1px solid #E2E8F0`).
- **Main Canvas:** Fluid viewport with a minimum responsive constraint of 1024px. The canvas uses a generous outer padding (`margin`: 2rem) ensuring table cards never press against browser edges.
- **Data Densities:**
  - Table rows maintain a balanced 52px height (`space-md` vertical padding) to prevent cramping while retaining dense scan-ability.
  - Toolbar controls, filters, and actionable search inputs share a coordinated 38px baseline height.

## Elevation & Depth

Visual separation avoids heavy, muddy drop shadows in favor of architectural surface stratification and hairline boundaries:

- **Surface Tiers:**
  - **Tier 0 (Background):** Canvas base `#F8FAFC`.
  - **Tier 1 (Surface Containers):** Pure `#FFFFFF` panels with a subtle 1px perimeter border `#E2E8F0`.
  - **Tier 2 (Floating Popovers & Modals):** Crisp `#FFFFFF` with ambient diffused shadow `0 10px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.
- **Active & Hover States:** Subtle upward physical shifts are replaced with pure border tone changes (e.g., transitions to `#CBD5E1` on card hover) and soft button glows for a clean digital-first response.

## Shapes

The design system employs a refined geometric shape language with subtle, intentional curvature:
- **Form Controls & Content Cards:** Base roundedness of `0.375rem` (6px) to `0.5rem` (8px), avoiding juvenile high-radius corners for dense functional panels.
- **Pill Tags & Status Badges:** Maximum radius (`9999px`) creating compact, aerodynamic chips for publish states, category tags, and counters.
- **Action Buttons:** Standard `0.375rem` (6px) matching input fields for a tailored, uniform toolbar row.

## Components

### Buttons
- **Primary Action (e.g., "+ Add Page"):** Solid Obsidian `#0F172A` background, white text, 0.375rem corner radius, font-weight 500, subtle hover state `#1E293B`.
- **Secondary Action (e.g., "Export", "Filters"):** Pure white background, hairline border `#E2E8F0`, slate-700 text `#334155`.
- **Destructive Action (e.g., "Delete"):** Soft crimson surface tint (`#FEF2F2`), `#DC2626` text, hairline border `#FEE2E2`. Hover shifts to `#FEE2E2`.
- **Icon Actions:** 32x32px square with 6px border radius, subtle hover wash `#F1F5F9`.

### Status Badges & Pill Tags
- **Published:** Soft mint background (`#ECFDF5`), emerald text (`#047857`), paired with a 6px circular green status dot.
- **Draft / Locked:** Soft amber/zinc background (`#F1F5F9`), slate text (`#475569`), paired with a lock or dot icon.

### Form Inputs & Search Fields
- Single-line search bar with inset search icon, 38px height, 1px border `#E2E8F0`, placeholder `#94A3B8`.
- Focus state activates a 1px border `#2563EB` and a crisp 3px ring (`rgba(37, 99, 235, 0.12)`).

### Data Table
- **Header:** Background `#F8FAFC`, uppercase 11px semi-bold slate text `#64748B`, bottom 1px border `#E2E8F0`.
- **Row:** Background `#FFFFFF`, transition to `#F8FAFC` on hover. Custom styled 16px square checkboxes with rounded corners (4px).
- **Sequence (Seq) Inputs:** Compact centered inputs (44px width, 28px height) with light borders for fast inline reordering.

### Sidebar Navigation
- Clean list items with 8px vertical padding, 12px horizontal padding, 6px border radius.
- Inactive items: `#64748B` text and icons.
- Active items: `#0F172A` text, `#F1F5F9` background, medium font weight, with an optional 3px vertical obsidian indicator on the item left edge.