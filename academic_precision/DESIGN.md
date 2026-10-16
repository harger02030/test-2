---
name: Academic Precision
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
  on-surface-variant: '#434654'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#1554d4'
  primary: '#0041b0'
  on-primary: '#ffffff'
  primary-container: '#1d58d8'
  on-primary-container: '#d5ddff'
  inverse-primary: '#b4c5ff'
  secondary: '#49607c'
  on-secondary: '#ffffff'
  secondary-container: '#c7dfff'
  on-secondary-container: '#4b637e'
  tertiary: '#842d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ac3d00'
  on-tertiary-container: '#ffd5c6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003da9'
  secondary-fixed: '#d1e4ff'
  secondary-fixed-dim: '#b0c9e8'
  on-secondary-fixed: '#011d35'
  on-secondary-fixed-variant: '#314863'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#ffb599'
  on-tertiary-fixed: '#370e00'
  on-tertiary-fixed-variant: '#7f2b00'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  academic-preview:
    fontFamily: EB Garamond
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.025em
  code-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-performance, distraction-free environment for students, researchers, and academic advisors. Drawing inspiration from modern productivity platforms like Linear and Notion, the interface rejects academic clutter in favor of crisp architectural order, rigorous typographic hierarchy, and structural clarity. 

The aesthetic is Modern-Corporate infused with Academic Editorial: quiet slate canvases, deliberate 1px structural delineations, high-density data views, and contextual validation badges that turn the anxiety of compliance into a satisfying, auditable workflow. Every interaction evokes rigor, trustworthiness, intellectual focus, and effortless mastery over complex formatting guidelines.

## Colors

The color architecture is built around academic authority and structural clarity:
- **Primary (`#1D58D8`)**: Royal Blue; drives primary actions, interactive focus states, verified badges, and key callouts.
- **Secondary / Deep Anchor (`#0F2942`)**: Deep Sapphire; frames navigation rails, critical structural headers, and high-level academic progress indicators.
- **Base Canvas & Surfaces**: Crisp white (`#FFFFFF`) for paper/document simulation and elevated cards, resting on a clinical slate-blue canvas (`#F8FAFC`).
- **Borders & Dividers (`#E2E8F0`)**: Subtle 1px boundaries defining structural panels without visual noise.
- **Academic Validation States**:
  - **Compliance / Standard Met (`#10B981`)**: Indicates valid citations, correct margins, and approved structures.
  - **Inconsistency / Advisory (`#F59E0B`)**: Flags missing bibliographic metadata, orphan headings, or spacing anomalies.
  - **Violation / Critical (`#EF4444`)**: Highlights critical deviations from standard guidelines, missing elements, or structural breaks.

## Typography

Typography operates on a dual-engine architecture:
1. **Application Shell & UI**: `Plus Jakarta Sans` delivers structured, crisp modern geometry for section titles, modal headers, and metrics. `Inter` handles operational text, inspector sidebars, form controls, and multi-line feedback with maximum micro-legibility.
2. **Academic Document Emulation**: `EB Garamond` is applied exclusively within live paper simulators, citation preview drawers, and formatted bibliography renders, honoring formal typographical tradition alongside modern toolsets.

Tabular figures (`tnum`) are enforced on metrics, page counters, and citation indices.

## Layout & Spacing

The interface uses a multi-pane fixed-fluid workbench model inspired by professional IDEs:
- **Left Rail (Navigation & Tree View)**: Fixed at 260px or collapsible to 64px.
- **Center Canvas (Document / Formatter Stage)**: Fluid stage hosting a centered, fixed-width page preview (max-width 820px) or responsive editing fields.
- **Right Rail (Compliance Inspector & Checklist)**: Fixed at 340px for error auditing and rule metadata.

### Breakpoints & Adaptations
- **Desktop (≥ 1280px)**: Three-pane layout active concurrently.
- **Tablet (768px – 1279px)**: Left rail collapses to an icon bar; inspector converts to an overlay drawer.
- **Mobile (< 768px)**: Single-column linear flow. Center document stage takes precedence; navigation and compliance validation live inside full-screen bottom sheets.

## Elevation & Depth

Visual hierarchy is maintained through crisp 1px borders paired with ultra-diffused, ambient micro-shadows, avoiding heavy drop shadows in favor of a clean, technical atmosphere:

- **Level 0 (Canvas Base)**: `#F8FAFC`, flat, zero shadow.
- **Level 1 (Card & Paper Surfaces)**: `#FFFFFF`, border `1px solid #E2E8F0`, shadow `0 1px 2px 0 rgba(15, 41, 66, 0.04)`.
- **Level 2 (Popovers, Tooltips, Active Dropdowns)**: `#FFFFFF`, border `1px solid #E2E8F0`, shadow `0 4px 12px -2px rgba(15, 41, 66, 0.08)`.
- **Level 3 (Modals, Overlays, Floating Audits)**: `#FFFFFF`, border `1px solid #E2E8F0`, shadow `0 12px 32px -4px rgba(15, 41, 66, 0.12)`.
- **Level 4 (Document Sheet Preview)**: `#FFFFFF`, border `1px solid #CBD5E1`, shadow `0 8px 24px -6px rgba(15, 41, 66, 0.06), 0 2px 6px -1px rgba(15, 41, 66, 0.04)`.

## Shapes

The system adopts a disciplined "Soft" curvature scale (`roundedness: 1`), conveying precision and computational exactness rather than casual softness:
- **Base Components (Inputs, Buttons, Badges)**: 0.25rem (4px) border radius.
- **Panels, Modals & Surface Containers**: 0.5rem (8px) border radius.
- **Preview Canvas & Document Sheets**: Crisp 2px or 4px radius to simulate real paper cuts.
- **Status Dots & Avatars**: Strictly circular (`9999px`).

## Components

### Buttons
- **Primary**: Background `#1D58D8`, text `#FFFFFF`, radius `4px`, height `36px` (desktop) / `40px` (mobile). Hover: `#1746AC`. Focus: ring `2px solid #1D58D8` with `2px` offset.
- **Secondary / Neutral**: Background `#FFFFFF`, border `1px solid #E2E8F0`, text `#1E293B`. Hover: background `#F8FAFC`, border `#CBD5E1`.
- **Destructive**: Background `#FFFFFF`, border `1px solid #FCA5A5`, text `#EF4444`. Hover: background `#FEF2F2`.
- **Ghost**: Background transparent, text `#1E293B`. Hover: background `#F1F5F9`.

### Input Fields & Selects
- Background `#FFFFFF`, border `1px solid #E2E8F0`, text `#1E293B`, height `36px`, padding `0 12px`, radius `4px`.
- **Active / Focused**: Border `#1D58D8`, outline `1px solid #1D58D8`.
- **Invalid**: Border `#EF4444`, ring `1px solid #EF4444`. Includes contextual inline error message below the field in `body-sm`.

### Academic Compliance Badges & Chips
- Compact height (`22px`), uppercase `label-sm`, padding `0 8px`, radius `4px`.
- **Compliant**: Background `#ECFDF5`, text `#065F46`, border `1px solid #A7F3D0`.
- **Inconsistent / Warning**: Background `#FFFBEB`, text `#92400E`, border `1px solid #FDE68A`.
- **Violation / Error**: Background `#FEF2F2`, text `#991B1B`, border `1px solid #FECACA`.
- **Metadata / Informational**: Background `#F1F5F9`, text `#334155`, border `1px solid #E2E8F0`.

### Checklist & Audit Tree (Notion/Linear Inspired)
- Nested list rows with 1px border dividers (`#F1F5F9`), interactive hover states (`#F8FAFC`).
- Custom check states: hollow ring for pending verification, green check for compliant, amber exclamation for warning, red cross for violation.

### Cards & Structured Panels
- Background `#FFFFFF`, border `1px solid #E2E8F0`, radius `8px`, internal padding `16px` or `24px`.
- Headers include a bottom divider line (`1px solid #F1F5F9`) separating metadata titles from functional editors.

### Citation & Reference Builder Box
- Monospaced or serif-infused live preview container with neutral slate background (`#F8FAFC`), bordered with `#E2E8F0`, equipped with one-click copy, quick-format toggles, and real-time guideline rule tags.