---
name: Autonomous Kinetic Glass
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
  on-surface-variant: '#bacbb9'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#859585'
  outline-variant: '#3b4a3d'
  surface-tint: '#00e475'
  primary: '#75ff9e'
  on-primary: '#003918'
  primary-container: '#00e676'
  on-primary-container: '#00612e'
  inverse-primary: '#006d35'
  secondary: '#a5e7ff'
  on-secondary: '#003543'
  secondary-container: '#00d2ff'
  on-secondary-container: '#00566a'
  tertiary: '#71fdbf'
  on-tertiary: '#003824'
  tertiary-container: '#50e0a5'
  on-tertiary-container: '#006041'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#62ff96'
  primary-fixed-dim: '#00e475'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#005226'
  secondary-fixed: '#b6ebff'
  secondary-fixed-dim: '#47d6ff'
  on-secondary-fixed: '#001f28'
  on-secondary-fixed-variant: '#004e60'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  display-hero:
    fontFamily: IBM Plex Sans
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
  display-hero-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  telemetry-mono:
    fontFamily: Space Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  caption-sm:
    fontFamily: IBM Plex Sans
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style

This design system defines an autonomous, high-reliability background utility tailored for iOS 17. The aesthetic blends Apple Human Interface Guidelines (HIG) depth models with a cyber-kinetic telemetry feel, engineered specifically for hands-free automation of academic tasks within the Saudi educational ecosystem.

### Brand Personality & Emotional Impact
- **Frictionless Autonomy:** Evokes relief and calm reassurance through clear ambient feedback, signaling that critical school duties are processed accurately without intervention.
- **Precision Engineering:** Communicates cryptographic-level reliability through cybernetic accents, smooth micro-meters, and deterministic status displays.
- **Native iOS Elegance:** Adheres to iOS 17 design conventions: continuous fluid curves (squircle geometry), progressive blur surfaces (`UIBlurEffect` / `.ultraThinMaterial`), and natural haptic-led telemetry.

### Visual Style
The design blends **iOS Glassmorphism** with **Deep Navy Cyber-Minimalism**:
- **Backgrounds:** Multi-tier deep midnight navy layers eliminating pure black OLED smearing while maintaining infinite dynamic range.
- **Accents:** Neon Emerald for active autonomy, Cyber Cyan for neural background parsing, and subtle luminous outlines instead of heavy raster dropshadows.
- **Directionality:** Strict Right-to-Left (RTL) ergonomics optimized for single-handed thumb-reach navigation on iPhone Pro Max down to SE form factors.

## Colors

The system uses a pure dark-mode palette designed for continuous background monitoring and low visual fatigue during late-night study cycles.

### Surface System
- **Canvas Base:** `#090D16` (Deep Midnight Void) – Primary canvas tone.
- **Surface Elevation 1 (Card Default):** `#0E1626` (Sub-Navy) at 75% opacity with 24px backdrop blur.
- **Surface Elevation 2 (Elevated Sheets & Floating Wells):** `#162035` (Active Deep Navy).
- **Hairline Structural Border:** `#1E2D48` (Subtle boundary line used at 1px / 0.5pt on Retina displays).

### Accent & Functional Semantics
- **Autopilot Active (Primary):** `#00E676` (Neon Emerald) – Indicates full autonomous background operation, completed assignments, and optimal server synchronization.
- **Autopilot Standby / Steady (Tertiary):** `#10B981` (Deep Mint) – Ambient passive states and non-urgent confirmation indicators.
- **AI Telemetry / In-Progress (Secondary):** `#00D2FF` (Cyber Cyan) – Real-time optical OCR, question analysis, AI logic validation, and payload transmission.
- **Warning / Captcha Challenge:** `#FFB300` (Amber Gold) – Indicates user intervention required (e.g., Two-Factor Auth, Captcha, or session timeout).
- **Critical / Failed Task:** `#FF3B30` (Apple Destructive Red) – Indicates platform disconnect or validation failure.

### Text Contrast Tiers
- **Text Primary (White 95%):** `#F8FAFC`
- **Text Secondary (Sub-Silver):** `#94A3B8`
- **Text Tertiary / Disabled:** `#475569`

## Typography

Typography is fully tuned for Right-to-Left (RTL) Arabic reading flow, utilizing IBM Plex Sans Arabic for native alignment, pristine baseline clarity, and neutral, high-legibility glyph counters.

### Font Hierarchy & Roles
- **Primary Typeface:** IBM Plex Sans Arabic (or San Francisco Arabic on Apple platforms). Provides geometric stability without classical calligraphic distortions that could break data-dense HUDs.
- **Telemetry & Timestamp Typeface:** Space Mono (LTR embedded spans) for technical latency counts, task completion timestamps, percentages, and session cookies.

### RTL Typesetting Rules
- **Numerical Figures:** Western Arabic numerals (0, 1, 2, 3...) are rendered via monospace numbers to facilitate scanning of completion percentages and due dates.
- **Reading Hierarchy:** Headings lead from right to left; metadata tags, live indicators, and telemetry values pin to the leading-left corner of containers.
- **Line Heights:** Generous line heights (minimum 1.45x font size) prevent clipping of Arabic diacritics and ascender/descender collisions.

## Layout & Spacing

The spatial foundation implements an iOS-compliant adaptive single-column flow with fluid, touch-safe container constraints.

### Grid & Canvas Structure
- **Safe Area Insets:** Layout strictly respects iOS Dynamic Island, Home Indicator, and Navigation Bar heights (`safe-area-inset-*`).
- **Screen Margins:** Fixed 16px (1rem) margin on compact screens (iPhone SE through standard models); expanding to 20px on Pro Max and dynamic split-views on iPadOS.
- **Element Rhythm:** Standard vertical spacing adheres to an 8pt architectural rhythm, with 4pt micro-adjustments for badges and data pairs.

### Form Factor Behavior
- **Mobile (Default):** Fluid stack. Bottom navigation sheet sits above the bottom safe area. Main telemetry cockpit resides in the top half; assignment processing logs stream beneath.
- **Adaptive Breakpoints:** Content is constrained to a maximum width of 480px on larger viewports (iPad/Landscape) and centered, keeping thumb reach within optimal arcs.

## Elevation & Depth

Visual hierarchy uses frosted glassmorphic layering and luminous atmospheric boundaries rather than traditional heavy drop-shadows.

### Layer Architecture
- **Layer 0 (Canvas):** Deep Navy Void (`#090D16`), textured with an ambient radial gradient of Cyber Cyan (`#00D2FF` at 4% opacity) localized around the active status engine.
- **Layer 1 (Inactive / Background Cards):** `#0E1626` with 60% alpha, 20px blur, bounded by a 0.5pt border in `#1E2D48`.
- **Layer 2 (Primary Interactive Hub / Autopilot Cockpit):** `#162035` with 80% alpha, 30px backdrop blur, bounded by a top-to-bottom directional gradient border (`#00E676` to `#1E2D48` at 40%).
- **Layer 3 (Floating HUD / Overlays / Alerts):** Pure ultra-thin Apple material with a neon aura:
  - Active Glow: `0 0 24px rgba(0, 230, 118, 0.20)`
  - Processing Glow: `0 0 24px rgba(0, 210, 255, 0.20)`

### Boundary Definition
All translucent surfaces use a `0.5pt` internal highlight border (`rgba(255, 255, 255, 0.08)`) simulating light refracted through the top edge of milled Apple glass.

## Shapes

The design uses continuous curvature squircle geometry matching Apple's native corner radii standards.

### Corner Radii Hierarchy
- **Master Telemetry Cards & Cockpit Hubs:** `rounded-xl` (24px / 1.5rem) continuous squircle.
- **Assignment Rows & Secondary Containers:** `rounded-lg` (16px / 1rem).
- **Controls, Input Fields & Nested Modules:** `rounded` (8px / 0.5rem).
- **Status Pills, Telemetry Chips & Action Badges:** Fully continuous pill geometry (`rounded-full` / 9999px).

## Components

### 1. Autopilot Toggle Switch (Cockpit Hub)
- **Visuals:** Oversized tactile toggle module representing the master automated pipeline. When active, it transitions into an Emerald-lit housing with a pulsating ring.
- **Typography:** Status label set in `headline-md` ("الطيار الآلي: نشط").
- **Haptics & Micro-Interactions:** Dual-state haptic trigger (`UIImpactFeedbackGenerator(style: .rigid)`).

### 2. Glowing Status Pills (Status Badges)
- **Structure:** Pill container (`rounded-full`), padded `space-xs` vertically and `space-md` horizontally.
- **Variants:**
  - *جاري الحل (Processing):* Cyber Cyan background (`rgba(0, 210, 255, 0.12)`), text `#00D2FF`, accompanied by a 6px breathing cyan LED dot.
  - *مكتمل ومسلّم (Submitted):* Neon Emerald background (`rgba(0, 230, 118, 0.12)`), text `#00E676`, static green check indicator.
  - *بانتظار الواجبات (Idle):* Muted Sub-Navy background, text `#94A3B8`.
  - *تحدي رمز التحقق (Action Needed):* Amber Gold background (`rgba(255, 179, 0, 0.12)`), text `#FFB300`.

### 3. Homework Card (Task Feed Item)
- **Geometry:** Frosted Glass Base Layer (`rounded-lg`), padded `space-lg`.
- **RTL Arrangement:**
  - Right: Subject icon in a squircle container + Subject name (`headline-md`) + Lesson title (`body-md`).
  - Left: Due date badge + Status Pill + Execution telemetry (`Space Mono`).
- **Telemetry Footer:** Thin separator line (`#1E2D48`), followed by an activity log: e.g., "تم الحل بنجاح بواسطة النموذج التعليمي • ٩٨٪ دقة".

### 4. Action Buttons
- **Primary Action (Manual Force Run / Sync):** High-sheen Emerald fill (`#00E676`), text `#090D16` (`headline-md`), `rounded-lg`, 48pt height. On active press, scale scales down to 0.98x.
- **Secondary Action (Settings / School Credentials):** Sub-Navy glass container (`#0E1626`), 1px border (`#1E2D48`), text `#F8FAFC`.

### 5. Telemetry & Console Log Drawer
- **Style:** Compact monospaced console list (`Space Mono`, 12px) embedded directly on the lower dashboard fold to transparently show live background headless browser activity (e.g., `POST /api/v1/madrasati/assignments/solve [200 OK]`).
- **Surface:** Recessed Navy base (`#090D16` at 90% opacity) with a subtle Cyan terminal indicator.