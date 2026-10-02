---
name: Human Rights & Gender Equality Institutional System
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f2'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e3e1'
  on-surface: '#1a1c1b'
  on-surface-variant: '#404945'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#717975'
  outline-variant: '#c0c8c4'
  surface-tint: '#396759'
  primary: '#154539'
  on-primary: '#ffffff'
  primary-container: '#2f5d50'
  on-primary-container: '#a3d4c3'
  inverse-primary: '#a0d1c0'
  secondary: '#466559'
  on-secondary: '#ffffff'
  secondary-container: '#c8eadb'
  on-secondary-container: '#4c6b5f'
  tertiary: '#72201f'
  on-tertiary: '#ffffff'
  tertiary-container: '#913734'
  on-tertiary-container: '#ffb8b2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bceddc'
  primary-fixed-dim: '#a0d1c0'
  on-primary-fixed: '#002019'
  on-primary-fixed-variant: '#204f42'
  secondary-fixed: '#c8eadb'
  secondary-fixed-dim: '#adcec0'
  on-secondary-fixed: '#012018'
  on-secondary-fixed-variant: '#2f4d42'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3ad'
  on-tertiary-fixed: '#410004'
  on-tertiary-fixed-variant: '#7f2927'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e1'
  verde-salvia-900: '#1F3D33'
  verde-salvia-700: '#2F5D50'
  verde-salvia-500: '#5F8A78'
  verde-salvia-100: '#E3ECE6'
  rojo-cochinilla-700: '#8F3B3B'
  rojo-cochinilla-500: '#B5524D'
  rojo-cochinilla-100: '#F2E1DF'
  oro-cempasuchil: '#C9A15B'
  barro: '#B7826A'
  whatsapp: '#3E9B6A'
  tinta: '#1D1D1F'
  gris-600: '#6E6E73'
  gris-300: '#D2D2D7'
  gris-100: '#F5F5F7'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.05'
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lead:
    fontFamily: Inter
    fontSize: 21px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: '1.55'
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: -0.005em
  label-caps:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.04em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 5rem
  space-4xl: 8rem
---

## Brand & Style

### Personality & Emotional Resonance
This design system articulates an institutional presence that is authoritative yet deeply human, bridging high-level diplomatic gravity with warm Mexican cultural heritage. It rejects the sterile, bureaucratic coldness typical of civil and governmental entities in favor of an understated editorial clarity inspired by modern product minimalism. 

The aesthetic evokes dignity, transparency, ethical responsibility, and quiet strength. Color is applied with deliberate restraint: muted earth and vegetal tones ground the interface, while crisp negative space allows human stories, policy frameworks, and photographic subjects to breathe.

### Design Movement
The visual framework synthesizes **Minimalism** with subtle **Glassmorphism** and organic architectural balance:
- **Cupertino Restraint:** Disciplined typography, strict geometric alignment, spacious padding, and high-performance micro-interactions.
- **Organic Mexican Modernism:** Warm off-white surfaces (`#FBFBF9`), natural sage pigments, cochineal reds, and fine golden accents evoking cempasúchil and fired clay without resorting to folkloric cliches.
- **Optical Depth:** Frosted glass materials (`backdrop-filter: blur(20px) saturate(180%)`), diffused light shadows, and clean hairline boundaries.

## Colors

### Color Budget Distribution
The palette operates strictly within a calibrated architectural ratio to maintain an institutional standard:
- **70% Neutrals (`#FBFBF9`, `#F5F5F7`, `#1D1D1F`, `#6E6E73`):** Canvas backgrounds, layered structural panels, foundational typography, and secondary metadata.
- **20% Sage Greens (`#2F5D50`, `#1F3D33`, `#E3ECE6`):** Primary brand identifiers, main interactive states, deep anchor sections (Hero and Footer), and subtle tinted cards.
- **8% Cochineal Reds (`#B5524D`, `#8F3B3B`, `#F2E1DF`):** High-priority alerts, urgent calls to action, secondary button interactions, and geographic focus points. *Rule: Never deploy cochineal red as a full section background.*
- **2% Fine Accents (`#C9A15B`, `#B7826A`):** Metadata chips, subtle divider lines, active chart anchors, and precise decorative markers.

### Transparency & Surface Overlays
- **Frosted Glass Canvas:** `rgba(251, 251, 249, 0.72)` paired with `rgba(255, 255, 255, 0.4)` borders.
- **Hero Dark Fill:** `linear-gradient(180deg, #1F3D33 0%, #14271F 100%)`.
- **Input Focus Ring:** `rgba(47, 93, 80, 0.15)` extended box-shadow halo.
- **Dark Surface Text:** Primary body text uses `rgba(255, 255, 255, 0.92)`, secondary body copy uses `rgba(255, 255, 255, 0.72)`.

## Typography

### Structural Hierarchy & Editorial Rhythm
The typography system uses a clean, rational neo-grotesque foundation (`Inter`, fallback to `-apple-system` and `SF Pro`). It balances tight negative tracking on display scales with neutral spacing on reading text.

- **Title Treatment:** Apply `text-wrap: balance` to all `display-hero`, `headline-lg`, and `headline-md` elements to prevent orphan lines.
- **Reading Measure:** Restrict running body paragraphs (`body-lead`, `body-md`) to a strict maximum of `70ch` to preserve cognitive ergonomics during long institutional reads.
- **Uppercase Markers:** `label-caps` is reserved for uppercase category eyebrows (e.g., "QUIÉNES SOMOS", "MARCO NORMATIVO"), chip tags, and micro-headers. It requires an expansive `0.04em` tracking to prevent optical crowding.
- **Color Roles:** Default headings and body lead copy inherit `#1D1D1F` (`--tinta`). Supporting descriptive text defaults to `#6E6E73` (`--gris-600`).

## Layout & Spacing

### Layout Architecture
The interface is structured on an **8pt modular rhythm** supporting a flexible **12-column fluid grid**:
- **Max Content Width:** `1200px` for standard layouts, expanding to `1400px` for immersive showcases and edge-to-edge gallery surfaces.
- **Vertical Section Rhythm:** Desktop viewports employ `128px` (`space-4xl`) of padding between major sections to establish breathing room. Mobile devices scale down to `80px` (`space-3xl`).
- **Column Gutter:** Fixed at `24px` (`gutter`) on desktop and tablet, collapsing to `16px` (`gutter-mobile`) on mobile form factors.

### Breakpoint Specifications
1. **Mobile (< 640px):** Single-column stack, full-width fluid layouts, touch targets of at least 44px, and modal dialogs presented as bottom sheets.
2. **Tablet (640px – 1023px):** Two-to-four column layout configurations, with 2-column masonry grids.
3. **Desktop (1024px – 1440px):** Full 12-column grid, 3-column masonry arrangements, and 50/50 split hero layouts.
4. **Wide Desktop (> 1440px):** Constrained centered container with fluid exterior horizontal margins.

## Elevation & Depth

Visual depth is achieved through layered material translucency, refined hairline borders, and atmospheric ambient shadows rather than harsh physical bevels.

### Shadow Scale
- **Subtle Base (`--sombra-sm`):** `0 2px 8px rgba(0, 0, 0, 0.04)` — Used on resting pill buttons and baseline cards.
- **Floating Hover (`--sombra-md`):** `0 8px 30px rgba(0, 0, 0, 0.08)` — Applied to map tooltips, floating popovers, and elevated card hover states.
- **Deep Modal (`--sombra-lg`):** `0 20px 60px rgba(0, 0, 0, 0.14)` — Reserved for primary dialog overlays, takeovers, and persistent bottom-floating navigation elements.

### Material Glass Recipe
Frosted materials must adhere to the following specification:
- **Surface Fill:** `rgba(251, 251, 249, 0.72)` (or `rgba(31, 61, 51, 0.8)` on dark sections).
- **Backdrop Processing:** `backdrop-filter: saturate(180%) blur(20px); -webkit-backdrop-filter: saturate(180%) blur(20px);`.
- **Perimeter Hairline:** `border: 1px solid rgba(255, 255, 255, 0.40)`.

## Shapes

The design system uses a pill-based identity (`roundedness: 3`) calibrated for human interfaces, contrasting organic rounded outer shells with structured inner contents:

- **Pill Silhouette (`980px` / `rounded-full`):** Applied to primary actions, interactive buttons, form input pills, filter chips, tag badges, and floating action triggers.
- **Large Architectural Panels (`28px`):** Used for modal dialog frames, imagery viewports, media containers, and portfolio masonry cards.
- **Medium Structural Cards (`20px`):** Applied to institutional profiles, thematic content modules, and interactive preview cards.
- **Precision Overlays (`14px`):** Reserved for contextual map tooltips, floating dropdown sheets, and standard text field controls.

## Components

### Buttons & Interactive CTAs
- **Primary Pill:** Fill `#2F5D50` with text `#FFFFFF`. Padding: `14px 28px`. Border-radius: `980px`. Subtle scale on hover (`scale(1.02)`), active press (`scale(0.98)`). Transition duration: `200ms cubic-bezier(0.28, 0.11, 0.32, 1)`.
- **Secondary Outlined Pill:** Background `transparent`, border `1px solid #2F5D50`, text `#2F5D50`. On hover: background `#E3ECE6`.
- **Accent Action Pill:** Fill `#B5524D` with text `#FFFFFF`. Used strictly for urgent petitions, critical reports, and secondary dynamic actions.
- **Messaging Floating Button:** Fixed bottom pill filled with `#3E9B6A`, with white icon and typography, using shadow `--sombra-md`.

### Cards & Institutional Panels
- **Standard Content Card:** Background `#F5F5F7`, border-radius `20px`, padding `32px`. Transition on hover with `transform: translateY(-6px)` and shadow elevation upgrade to `--sombra-md`.
- **Member / Team Profile Card:** Fixed width `300px` on desktop (`80vw` on mobile). Houses a `1:1` square headshot with `20px` radius. Images render in desaturated monochrome, transitioning smoothly to full natural color on card `:hover`.

### Chips & Metadata Badges
- **Status & Theme Tags:** Border-radius `980px`, padding `6px 14px`, text `13px` (`label-caps`). 
- **Palette Variations:**
  - *Standard Neutral:* Background `#F5F5F7`, text `#1D1D1F`, border `1px solid #D2D2D7`.
  - *Sage Tint:* Background `#E3ECE6`, text `#1F3D33`.
  - *Cochineal Tint:* Background `#F2E1DF`, text `#8F3B3B`.
  - *Clay / Barro Accent:* Background `rgba(183, 130, 106, 0.15)`, text `#B7826A`.

### Form Controls & Inputs
- **Text Inputs & Textareas:** Background `#FFFFFF`, border `1px solid #D2D2D7`, border-radius `14px`, padding `14px 18px`, typography `17px` (`body-md`).
- **Focus State:** Border color `#2F5D50`, with box-shadow halo `0 0 0 3px rgba(47, 93, 80, 0.15)`. Outline is disabled in favor of the branded focus ring.
- **Checkboxes & Radios:** `20px` diameter with `#2F5D50` fill when checked, white check/dot indicator, and smooth `200ms` scale transition.

### Modals & Dialogs
- **Backdrop:** `rgba(29, 29, 31, 0.4)` with `backdrop-filter: blur(8px)`.
- **Modal Panel:** Background `#FBFBF9`, border-radius `28px`, border `1px solid rgba(255, 255, 255, 0.6)`, shadow `--sombra-lg`, padding `40px`. Includes a top-right `36px` circular frosted-glass close button.