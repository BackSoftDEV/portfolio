# Design System — BackDEV Portfolio (Mission Control / Industrial 3D)
*Generated & Structured following UI UX Pro Max Standards*

## 1. Brand Identity & Product Type
- **Product**: Developer Portfolio / Industrial Software Architect
- **Specialization**: Smart Factory (MES / OEE), SCADA 3D WebGL, Microservices, Real-time IoT
- **Aesthetic Direction**: Bento Box Grid 2.0 + Deep Cyber Obsidian + Frosted Glassmorphism + Kinetic Micro-interactions

---

## 2. Color Palette & Design Tokens

### Dark Mode (Primary Default)
- `--bg`: `#070b14` (Deep Obsidian Void)
- `--bg2`: `#0c1322` (Industrial Slate Base)
- `--bg3`: `#111a2e` (Elevated Surface)
- `--bg4`: `#17233d` (High Contrast Surface)
- `--neon`: `#00f5ff` (Electric Cyan Accent)
- `--neon2`: `#3b82f6` (Cyber Cobalt Accent)
- `--amber`: `#f59e0b` (Telemetry Warning / Highlight)
- `--success`: `#10b981` (Live Telemetry Emerald)
- `--danger`: `#ef4444` (Critical System Red)
- `--text`: `#f8fafc` (Slate 50 - Ultra Crisp)
- `--text2`: `#cbd5e1` (Slate 300 - High Legibility)
- `--muted`: `#94a3b8` (Slate 400 - Contrast Compliant)
- `--card`: `rgba(12, 19, 34, 0.78)` (Frosted Glass Panel)
- `--card2`: `rgba(17, 26, 46, 0.88)` (Dense Frosted Panel)
- `--border`: `rgba(56, 189, 248, 0.16)` (Specular Cyan Border)
- `--border2`: `rgba(255, 255, 255, 0.06)` (Subtle Dividers)
- `--glow`: `0 0 28px rgba(0, 245, 255, 0.18)`
- `--glow-amber`: `0 0 28px rgba(245, 158, 11, 0.22)`
- `--card-shadow`: `0 16px 40px -12px rgba(0, 0, 0, 0.55), inset 0 1px 0 rgba(255, 255, 255, 0.08)`

### Light Mode (Sleek Clean Slate)
- `--bg`: `#f8fafc` (Pure Slate Mist)
- `--bg2`: `#ffffff` (Card Surface)
- `--bg3`: `#f1f5f9` (Surface Level 2)
- `--bg4`: `#e2e8f0` (Surface Level 3)
- `--neon`: `#0284c7` (Sky 600 - High Contrast)
- `--neon2`: `#2563eb` (Blue 600)
- `--amber`: `#d97706` (Amber 600)
- `--success`: `#059669` (Emerald 600)
- `--text`: `#0f172a` (Slate 900)
- `--text2`: `#334155` (Slate 700)
- `--muted`: `#64748b` (Slate 500)
- `--card`: `rgba(255, 255, 255, 0.92)`
- `--card2`: `rgba(248, 250, 252, 0.95)`
- `--border`: `rgba(15, 23, 42, 0.08)`
- `--border2`: `rgba(15, 23, 42, 0.04)`
- `--card-shadow`: `0 16px 36px -12px rgba(15, 23, 42, 0.08), inset 0 1px 0 rgba(255, 255, 255, 0.8)`

---

## 3. Typography & Hierarchy
- **Display / Headings**: `'Space Grotesk', -apple-system, sans-serif`
  - Hero Display: `clamp(3rem, 8vw, 6rem)`, `font-weight: 800`, `letter-spacing: -0.04em`
  - Section Headings: `font-size: 2.2rem`, `font-weight: 700`, `letter-spacing: -0.02em`
- **Code / Metrics / Badges**: `'JetBrains Mono', monospace`
  - Sub-labels, terminal, telemetry: `letter-spacing: 0.08em`, `font-size: 0.72rem - 0.82rem`
- **Body Text**: `'Space Grotesk'`, line-height: `1.65`, comfortable reading on both desktop & mobile.

---

## 4. UI Patterns & Micro-interactions
1. **Interactive Spotlight Cards**:
   Cards dynamically reflect mouse coordinates via subtle radial gradient illumination.
2. **Floating Island Navigation**:
   Modern pill navbar floating gracefully with frosted blur (`backdrop-filter: blur(20px)`).
3. **Bento Grid Asymmetry**:
   Flagship project featured in high-priority span with real-time status beacon and telemetry chips.
4. **Specular Edge Lighting**:
   Cards have `inset 0 1px 0 rgba(255, 255, 255, 0.1)` simulating top light reflection.
5. **Accessibility Standards**:
   - WCAG AA/AAA compliant text contrast.
   - Touch devices gracefully hide custom cursor.
   - Reduced motion fallback supported.
