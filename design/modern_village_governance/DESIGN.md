---
name: Modern Village Governance
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
  on-surface-variant: '#40484e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#70787f'
  outline-variant: '#c0c7cf'
  surface-tint: '#10658b'
  primary: '#004967'
  on-primary: '#ffffff'
  primary-container: '#086288'
  on-primary-container: '#a5dbff'
  inverse-primary: '#8bcef9'
  secondary: '#19648f'
  on-secondary: '#ffffff'
  secondary-container: '#8fcdfd'
  on-secondary-container: '#005881'
  tertiary: '#004966'
  on-tertiary: '#ffffff'
  tertiary-container: '#146285'
  on-tertiary-container: '#a4dbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c6e7ff'
  primary-fixed-dim: '#8bcef9'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#004c6b'
  secondary-fixed: '#cae6ff'
  secondary-fixed-dim: '#8fcdfd'
  on-secondary-fixed: '#001e30'
  on-secondary-fixed-variant: '#004b70'
  tertiary-fixed: '#c5e7ff'
  tertiary-fixed-dim: '#8ecef6'
  on-tertiary-fixed: '#001e2d'
  on-tertiary-fixed-variant: '#004c6a'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  title:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  metric-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
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
  space-xl: 2rem
---

## Brand & Style

This design system establishes an authoritative, reliable, and approachable digital standard for village financial governance and administrative accountability (SISKEUDES). The interface mediates between strict regulatory oversight and accessible daily operations for local government officials, village treasurers, and audit inspectors.

The aesthetic follows **Corporate / Modern** principles reinforced by crisp administrative clarity:
- **Tone:** Authoritative yet non-punitive, organized, institutional, and transparent.
- **Visual Weight:** Deliberate, structured, and legible at density. Dense financial registries, state budget categorizations (APBD/APBDes), and audit trails are balanced by generous table breathing room, legible typographic scales, and purposeful hierarchical accents.
- **Atmosphere:** Clean architectural planes over deep institutional teals and administrative blues, anchored with warm highlight accents to avoid sterile bureaucratic coldness while preserving public-sector gravitas.

## Colors

The palette relies on foundational public-trust tones: deep institutional teal provides authoritative structure, balanced by mid-tone sky accents and warm utilitarian tints for budget highlights and notifications.

### Semantic Mapping
- **Primary (`#086288`):** Top-level navigation bars, primary workflow action buttons, brand crest containers, and primary active states.
- **Secondary (`#4D8DBA`):** Interactive subheadings, secondary actions, selected row indicators, active tab borders, and analytical charts.
- **Accent Soft Cyan (`#97D7FF`):** Selection rings, hover backdrops on dark elements, chart auxiliary series, and subtle information callout containers.
- **Warm Accent / Highlight Cream (`#FFEFC4`):** Fiscal year markers, pending verification badges, audit-needed highlights, and key informational banners.
- **Surface & Backgrounds:**
  - Base Application Canvas: `#F8FAFC` (Slate 50)
  - Card, Metric Tile & Modal Surface: `#FFFFFF` (Pure White)
  - Subtle Borders & Separators: `#E2E8F0` (Slate 200)
  - Heavy Functional Borders: `#CBD5E1` (Slate 300)
- **Typography:**
  - Headings & Primary Data: `#0F172A` (Slate 900)
  - Supporting Labels & Secondary Body: `#475569` (Slate 600)
  - Disabled & Muted Text: `#94A3B8` (Slate 400)
- **Status & Compliance Tokens:**
  - **Success / Disbursed / Approved:** `#10B981` (Emerald 500) | Surface: `#ECFDF5`
  - **Warning / Pending Review:** `#F59E0B` (Amber 500) | Surface: `#FFFBEB`
  - **Alert / Over-budget / Deficit:** `#EF4444` (Red 500) | Surface: `#FEF2F2`

## Typography

Typography pairs **Plus Jakarta Sans** for structure, branding, section hierarchy, and key financial metric displays with **Inter** for data tables, form inputs, audit logs, and system navigation.

- **Numbers & Accounting:** Tabular lining figures (`font-variant-numeric: tabular-nums`) are mandatory for all currency notations (Rupiah amounts), percentages, dates, and budget code account numbers (`Kode Rekening Akun`).
- **Administrative Metadata:** Badges, table headers, and form section tags use `label-sm` with slight uppercase tracking (`0.04em`) to ensure instant categorization under rapid scanning.
- **KPI Metrics:** `metric-lg` and `metric-md` prioritize immediate visual absorption of budget realizations, total village revenues (Pendapatan Desa), and active disbursement milestones.

## Layout & Spacing

The interface prioritizes a **12-column desktop-first fluid grid** tailored for workstation displays (1280px minimum target, scaling cleanly to 1920px ultrawide screens).

- **Navigation Architecture:** A persistent 260px left sidebar anchors institutional menus (Master Data, Perencanaan, Penatausahaan, Akuntansi, Pelaporan). The central canvas dynamically fills remaining width with a maximum content clamp of 1600px to maintain data glanceability.
- **Grid Structure:** 12 columns with 24px (`1.5rem`) gutters. Sub-panels within ledger sheets split into 4-column (summary/filter) and 8-column (transaction journal) splits.
- **Rhythm Rules:**
  - KPI tiles in the upper dashboard utilize `space-md` gaps.
  - Internal card padding is consistently `space-lg` (24px) for major administrative blocks and `space-md` (16px) for compact data tables.
  - Form field groupings adhere to an 8px vertical baseline (`space-sm`), with 24px (`space-lg`) separating thematic administrative fieldsets.

## Elevation & Depth

To preserve administrative clarity and minimize distraction during sustained screen time, the design system utilizes **crisp low-contrast outlines coupled with soft ambient micro-elevations**:

- **Layer 0 (Canvas Base):** Flat `#F8FAFC`. Zero elevation.
- **Layer 1 (Cards, Metric Tiles, Table Containers):** `#FFFFFF` base with a 1px solid border in `#E2E8F0` and an ultra-subtle ambient drop: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`.
- **Layer 2 (Dropdowns, Popovers, Filter Menus):** Pure white container with a 1px solid border in `#CBD5E1` and an elevated shadow: `0 8px 16px -4px rgba(8, 98, 136, 0.08), 0 4px 6px -2px rgba(15, 23, 42, 0.04)`.
- **Layer 3 (Modal Dialogs, Administrative Overlays):** Fixed `#FFFFFF` container with `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 10px 10px -5px rgba(15, 23, 42, 0.04)` over a 50% opacity backdrop of `#0F172A`.
- **Focus / Active Elevation:** Inputs and active rows do not elevate via high z-axis drop shadows. Instead, they receive a crisp 2px border or focus halo of `#086288` with a 3px outer ring tinted with `#97D7FF` at 40% opacity.

## Shapes

The design system enforces a **Soft (`1`)** shape geometry:
- Standard UI components (buttons, input fields, badges, select menus) use `rounded` (0.25rem / 4px).
- Larger containers (summary cards, analytical tables, modal containers) use `rounded-lg` (0.5rem / 8px).
- Micro elements such as status pills, verification badges, and counters use fully rounded caps (9999px) to establish visual contrast against the otherwise rectilinear administrative layout.
- The modest corner radius reinforces institutional precision, maximizing internal space efficiency for extensive tabular financial data.

## Components

### Buttons
- **Primary:** Background `#086288`, text `#FFFFFF`, border none, 4px corner radius. Hover: `#064e6d`. Focus: 3px `#97D7FF` ring.
- **Secondary:** Background `#FFFFFF`, text `#086288`, 1px border `#CBD5E1`. Hover: `#F1F5F9`.
- **Tertiary / Destructive:** Neutral ghost actions or `#EF4444` text with `#FEF2F2` hover states for irreversible budget voiding.
- **Sizing:** Fixed heights (36px compact for data-dense tables, 40px default for modal and header action bars).

### Data Tables & Financial Ledgers
- **Header:** Background `#F8FAFC`, uppercase `label-sm` in `#475569`, 1px solid bottom border `#CBD5E1`.
- **Rows:** Zebra alternating pattern optional, default `#FFFFFF` with `#F8FAFC` on hover. Row height 44px with 1px border `#E2E8F0`.
- **Alignments:** Left-aligned for text and village account codes; right-aligned for monetary balances with tabular figures; centered for status chips and action buttons.

### KPI Metric Tiles
- Surface `#FFFFFF`, border 1px solid `#E2E8F0`, 8px corner radius.
- Includes an institutional teal or status-colored top border accent (3px).
- Contains semantic delta indicators: an icon, percentage change, and fiscal year reference (`label-sm`).

### Chips & Badges
- **Status Pills:** 22px height, 9999px pill radius, `label-sm` weight:
  - *Disetujui (Approved):* Background `#ECFDF5`, text `#065F46`, 1px border `#A7F3D0`.
  - *Menunggu Verifikasi (Pending):* Background `#FFFBEB`, text `#92400E`, 1px border `#FDE68A`.
  - *Ditolak / Defisit (Alert):* Background `#FEF2F2`, text `#991B1B`, 1px border `#FECACA`.
  - *Tahun Anggaran (Fiscal Tag):* Background `#FFEFC4`, text `#78350F`, 1px border `#FDE68A`.

### Form Inputs & Selectors
- Standard height 38px, border 1px solid `#CBD5E1`, background `#FFFFFF`, text `#0F172A`.
- Placeholder text `#94A3B8`.
- Focus ring: 1px `#086288` with 2px `#97D7FF` ambient aura.
- Monetary inputs embed a static prefix box (`Rp`) filled with `#F1F5F9`, border-r `#CBD5E1`, font weight 600.

### Checkboxes & Radio Buttons
- 16px square (checkbox) or circle (radio), 1.5px border `#94A3B8`. Checked state fills `#086288` with a white checkmark or center dot. Focus ring mirrors text input tokens.

### Real-Time Status Indicators
- 8px circular dot pulsing with CSS keyframes for live database sync or network status:
  - Connected: `#10B981` with faint green ping ring.
  - Offline / Local Cache: `#F59E0B`.