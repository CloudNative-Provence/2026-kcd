# Cloud Native Provence - Brand Style Guide

> Official brand guidelines for Cloud Native Provence community materials
> Updated for the ship's helm/wheel logo design - February 2026

---

## 🎨 Color Palette

### Primary Colors

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Provence Blue** | `#356cc8` | 53, 108, 200 | Primary brand color - Main element in helm/wheel, logo badge, headers |
| **Pure White** | `#ffffff` | 255, 255, 255 | Background color - Clouds, text, highlights, water elements |
| **Deep Navy** | `#1a2d4d` | 26, 45, 77 | Text and dark backgrounds - Body text, dark overlays |

### Complementary Colors

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Sky Mist** | `#6b8fd4` | 107, 143, 212 | Light accent - Hover states, secondary elements, light backgrounds |
| **Alpine White** | `#f0f4fa` | 240, 244, 250 | Light backgrounds - Card backgrounds, subtle fills |
| **Storm Gray** | `#4a5568` | 74, 85, 104 | Secondary text - Captions, metadata, secondary information |
| **Mediterranean Teal** | `#2da3b8` | 45, 163, 184 | Accent highlights - Interactive elements, emphasis |

### Color Swatches

```
Provence Blue   Pure White      Deep Navy
#356cc8         #ffffff         #1a2d4d
███████         ███████         ███████

Sky Mist        Alpine White    Storm Gray        Mediterranean Teal
#6b8fd4         #f0f4fa         #4a5568           #2da3b8
███████         ███████         ███████           ███████
```

---

## 📊 Color Usage Guidelines

### ✅ Recommended Combinations

| Background | Text/Foreground | Use Case |
|------------|----------------|----------|
| `#ffffff` | `#1a2d4d` | Primary content, body text, main interface |
| `#1a2d4d` | `#ffffff` | Headers, hero sections, dark backgrounds |
| `#356cc8` | `#ffffff` | Buttons, call-to-action, primary interactive elements |
| `#ffffff` | `#4a5568` | Secondary text, captions, metadata |
| `#f0f4fa` | `#1a2d4d` | Card backgrounds, content containers |
| `#2da3b8` | `#ffffff` | Accent buttons, highlight areas |
| `#6b8fd4` | `#ffffff` | Hover states, secondary buttons |

### ❌ Avoid These Combinations

- `#356cc8` on `#1a2d4d` (insufficient contrast)
- `#6b8fd4` on `#ffffff` (too light for body text)
- `#4a5568` on `#6b8fd4` (poor readability)
- `#2da3b8` on `#ffffff` (use primarily for interactive elements)

---

## 🔤 Typography

### Primary Font: Poppins
**Alternative Font: Work Sans**

**Font Families:** [Poppins](https://fonts.google.com/specimen/Poppins) and [Work Sans](https://fonts.google.com/specimen/Work+Sans) (Google Fonts)

**Import:**
```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;500;600;700&display=swap');
```

### Type Scale

| Element | Font Weight | Size | Line Height | Color | Use Case |
|---------|-------------|------|-------------|-------|----------|
| **H1 - Display** | Bold (700) | 48px / 3rem | 1.2 | `#1a2d4d` | Page titles, hero headings |
| **H2 - Section** | SemiBold (600) | 36px / 2.25rem | 1.3 | `#1a2d4d` | Section titles |
| **H3 - Subsection** | SemiBold (600) | 28px / 1.75rem | 1.4 | `#356cc8` | Subsection titles |
| **H4 - Component** | Medium (500) | 20px / 1.25rem | 1.5 | `#1a2d4d` | Card titles, component headers |
| **Body** | Regular (400) | 16px / 1rem | 1.6 | `#1a2d4d` | Paragraphs, general content |
| **Body Small** | Regular (400) | 14px / 0.875rem | 1.6 | `#4a5568` | Captions, metadata, footnotes |
| **Button/CTA** | SemiBold (600) | 16px / 1rem | - | `#ffffff` | Buttons, links, CTAs |

**Letter Spacing for CTAs:** 0.5px

---

## 🖼️ Logo Usage

### Logo Concept

The Cloud Native Provence logo features a **ship's helm/wheel (Kubernetes-inspired)** design representing:
- **Helm/Wheel:** Navigation, direction, and cloud-native orchestration (Kubernetes helm reference)
- **"CLOUD NATIVE PROVENCE" text:** Curved along the top of the circular badge
- **White clouds:** Cloud-native technology and sky elements
- **Blue mountains:** Provence/Alpine landscape references (visual connection to region)
- **Water/waves:** Mediterranean Sea reference and fluidity
- **Circular badge with helm spokes:** Modern, technical aesthetic

### Logo Versions

#### 1. Full Helm Badge Logo
**File:** `cnp-logo-helm-hires.png`

- Complete logo with circular helm badge, "CLOUD NATIVE PROVENCE" text curved at top
- White clouds with Provence Blue mountains
- Water/wave elements at bottom
- Provence Blue color (#356cc8) as primary element
- **Use for:** Profile pictures, social media, badges, stickers, primary branding
- **Background:** Light or neutral backgrounds - works on `#ffffff`, light gray, or `#f0f4fa`
- **Minimum size:** 200px width (digital), 40mm (print)

#### 2. SVG Helm Logo
**File:** `cnp-logo-helm.svg`

- Scalable vector version of complete logo
- Full color, ready for any size requirement
- Supports transparent backgrounds
- **Use for:** Responsive websites, scalable applications, print materials at any resolution
- **Background:** Any background works with appropriate color variants
- **Minimum size:** No minimum - infinitely scalable

### Logo Design System

**Primary Elements:**
- **Provence Blue (#356cc8):** Main helm/wheel spokes, mountains, badge outline
- **Pure White (#ffffff):** Clouds, text, mountain highlights, water elements
- **Deep Navy (#1a2d4d):** Optional shadow/depth (when needed)

**Visual Characteristics:**
- Circular badge format (modern, balanced)
- Kubernetes-inspired helm spokes (cloud-native connection)
- Mediterranean-inspired mountain and water elements
- Professional 3D effect with subtle depth
- Clean, scalable vector design

---

## 📐 Logo Usage by Context

| Context | Recommended Version | Notes |
|---------|-------------------|-------|
| Website Header | Full Helm Badge Logo | Primary branding, SVG for responsiveness |
| Social Media Profile | Full Helm Badge Logo | Square format works perfectly |
| Social Media Posts | Any version | Choose based on layout and background |
| Presentation Title Slide | Full Helm Badge Logo | Maximum impact, use SVG or HiRes PNG |
| Presentation Recurring | Icon Helm Badge | Subtle, doesn't dominate slides |
| Documentation | SVG Helm Logo | Clean, professional, scalable |
| Favicon | Icon Helm Badge | Recognizable at small sizes |
| T-Shirts/Merchandise | Full Helm Badge Logo | Best for printing |
| Stickers | Full Helm Badge Logo | Circular format ideal for die-cutting |
| Email Signature | Icon Helm Badge | Space-efficient |
| GitHub Avatar | Full Helm Badge Logo | Clear at all sizes |
| Watermarks | Icon Helm Badge | Subtle, non-intrusive |
| Documentation Headers | SVG Helm Logo | Responsive, professional |

### Background Recommendations

#### Full Helm Badge Logo:
- ✅ Pure White (`#ffffff`)
- ✅ Light gray (`#f5f5f5`)
- ✅ Alpine White (`#f0f4fa`)
- ✅ Light blue backgrounds
- ❌ Avoid very dark backgrounds (high contrast issues)
- ❌ Avoid busy patterns

#### SVG Helm Logo:
- ✅ Any background color
- ✅ Light or dark
- ✅ Responsive designs
- ✅ Print materials
- Supports color variants for different backgrounds

#### Icon Helm Badge:
- ✅ Any background color
- ✅ Photos (dark or light)
- ✅ Colored backgrounds
- ✅ Deep Navy (`#1a2d4d`) - creates monochrome effect
- ✅ Provence Blue (`#356cc8`) - tone-on-tone effect

---

## 🚫 Logo Don'ts

- ❌ Do not rotate the logo
- ❌ Do not change logo colors (use only the approved versions)
- ❌ Do not add effects beyond original design (shadows, gradients, outlines)
- ❌ Do not stretch or distort proportions
- ❌ Do not place on backgrounds without sufficient contrast
- ❌ Do not recreate or modify the logo design
- ❌ Do not separate design elements from the complete logo
- ❌ Do not use for unrelated purposes or projects
- ❌ Do not apply filters or color overlays to the logo

---

## 🎯 Design Patterns

### Buttons

#### Primary Button
```css
background: #356cc8;
color: #ffffff;
font-family: 'Poppins', sans-serif;
font-weight: 600;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
border: none;
cursor: pointer;
```
**Hover State:** `background: #2a56b0`
**Active State:** `background: #1f3f7d`

#### Secondary Button
```css
background: transparent;
color: #356cc8;
border: 2px solid #356cc8;
font-family: 'Poppins', sans-serif;
font-weight: 600;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
cursor: pointer;
```
**Hover State:** `background: #f0f4fa`
**Active State:** `background: #e0e8f5`

#### Accent Button (CTA)
```css
background: #2da3b8;
color: #ffffff;
font-family: 'Poppins', sans-serif;
font-weight: 600;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
border: none;
cursor: pointer;
```
**Hover State:** `background: #2487a0`
**Active State:** `background: #1d6b85`

#### Tertiary Button (Subtle)
```css
background: transparent;
color: #356cc8;
border: 1px solid #6b8fd4;
font-family: 'Poppins', sans-serif;
font-weight: 500;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
cursor: pointer;
```
**Hover State:** `background: rgba(53, 108, 200, 0.1)`

### Cards

```css
background: #ffffff;
border: 1px solid #e5e5e5;
border-radius: 12px;
padding: 24px;
box-shadow: 0 2px 8px rgba(26, 45, 77, 0.08);
```
**Hover State:** `box-shadow: 0 4px 16px rgba(53, 108, 200, 0.12)`

### Input Fields

```css
background: #ffffff;
border: 1px solid #d0d7e5;
border-radius: 8px;
padding: 12px 16px;
font-family: 'Poppins', sans-serif;
font-size: 16px;
color: #1a2d4d;
```
**Focus State:** `border: 2px solid #356cc8; box-shadow: 0 0 0 3px rgba(53, 108, 200, 0.1)`

---

## 🌐 CSS Custom Properties

Use these CSS custom properties in your projects:

```css
:root {
  /* Primary Colors */
  --cnp-provence-blue: #356cc8;
  --cnp-pure-white: #ffffff;
  --cnp-deep-navy: #1a2d4d;

  /* Complementary Colors */
  --cnp-sky-mist: #6b8fd4;
  --cnp-alpine-white: #f0f4fa;
  --cnp-storm-gray: #4a5568;
  --cnp-mediterranean-teal: #2da3b8;

  /* Semantic Aliases */
  --cnp-primary: var(--cnp-provence-blue);
  --cnp-secondary: var(--cnp-deep-navy);
  --cnp-accent: var(--cnp-mediterranean-teal);
  --cnp-background: var(--cnp-pure-white);
  --cnp-text: var(--cnp-deep-navy);
  --cnp-text-secondary: var(--cnp-storm-gray);

  /* Typography */
  --cnp-font-family: 'Poppins', sans-serif;
  --cnp-font-family-alt: 'Work Sans', sans-serif;
  --cnp-font-weight-regular: 400;
  --cnp-font-weight-medium: 500;
  --cnp-font-weight-semibold: 600;
  --cnp-font-weight-bold: 700;

  /* Spacing */
  --cnp-space-xs: 4px;
  --cnp-space-sm: 8px;
  --cnp-space-md: 16px;
  --cnp-space-lg: 24px;
  --cnp-space-xl: 32px;
  --cnp-space-2xl: 48px;

  /* Border Radius */
  --cnp-radius-sm: 4px;
  --cnp-radius-md: 8px;
  --cnp-radius-lg: 12px;

  /* Shadow */
  --cnp-shadow-sm: 0 2px 8px rgba(26, 45, 77, 0.08);
  --cnp-shadow-md: 0 4px 16px rgba(53, 108, 200, 0.12);
  --cnp-shadow-lg: 0 8px 24px rgba(26, 45, 77, 0.16);
}
```

---

## 📱 Responsive Guidelines

### Breakpoints

```css
/* Mobile */
@media (max-width: 768px) {
  /* Scale typography down 10-15% */
  /* Stack elements vertically */
  /* Increase touch targets to 44px minimum */
}

/* Tablet */
@media (min-width: 769px) and (max-width: 1024px) {
  /* Adjust spacing for medium screens */
  /* Optimize grid layouts */
}

/* Desktop */
@media (min-width: 1025px) {
  /* Full layout */
  /* Maximum spacing */
}
```

### Logo Sizing Guidelines

- **Mobile (< 768px):** Minimum 120px width for full logo
- **Tablet (768px - 1024px):** Minimum 160px width for full logo
- **Desktop (> 1024px):** Minimum 200px width for full logo
- **Favicon:** Fixed 32x32px or 64x64px (icon version)

---

## ♿ Color Accessibility (WCAG Compliance)

| Combination | Contrast Ratio | Rating | Use Case |
|-------------|---------------|--------|----------|
| `#1a2d4d` on `#ffffff` | 16.2:1 | AAA ✓ | Body text, primary contrast |
| `#356cc8` on `#ffffff` | 6.8:1 | AA ✓ | Headings, buttons |
| `#4a5568` on `#ffffff` | 7.9:1 | AA ✓ | Secondary text |
| `#ffffff` on `#1a2d4d` | 16.2:1 | AAA ✓ | Reverse text, dark backgrounds |
| `#ffffff` on `#356cc8` | 4.6:1 | AA ✓ | Buttons, interactive elements |
| `#2da3b8` on `#ffffff` | 5.4:1 | AA ✓ | Accent elements |
| `#6b8fd4` on `#ffffff` | 3.9:1 | - | Decorative/hover only |
| `#2da3b8` on `#1a2d4d` | 3.1:1 | - | Accent on dark (decorative) |

**Accessibility Notes:**
- Always test color combinations with contrast checkers
- Avoid using color alone to convey information
- For Sky Mist (#6b8fd4), use primarily for hover states or with supporting visual elements
- Ensure sufficient contrast for all text and interactive elements

---

## 📄 File Formats & Specifications

### Logo Files

| Version | Format | Transparency | Best For |
|---------|--------|--------------|----------|
| Full Helm Badge Logo | PNG | Background preserved | Web, social media, presentations |
| SVG Helm Logo | SVG | Full transparency | Responsive web, scalable use |
| Icon Helm Badge | PNG | Transparent background | Icons, favicons, tight spaces |

### Recommended Exports

- **Web:** PNG at 2x resolution (retina ready), SVG for responsive designs
- **Print:** Request vector SVG or EPS version from brand team
- **Social Media:** PNG at platform's recommended dimensions (1200x1200px minimum)
- **Favicon:** 32x32px, 64x64px, or 256x256px PNG of icon version

### Color Profiles

- **Web:** sRGB
- **Print:** CMYK (request print-specific files from brand team)

---

## 🤝 Contributing to Brand Materials

When creating materials for Cloud Native Provence:

1. **Use the official logos** - Download from `/brand/logos/` directory
2. **Follow the color palette** - Use the hex codes provided in this guide
3. **Use Poppins or Work Sans fonts** - Available free from Google Fonts
4. **Maintain accessibility** - Check contrast ratios for all text
5. **Keep it clean** - Use plenty of whitespace and clear hierarchy
6. **Be consistent** - Follow these guidelines across all materials
7. **Test responsiveness** - Ensure materials work on all screen sizes

### Questions or Custom Assets?

Open an issue in this repository or contact the Cloud Native Provence brand team.

---

## 🌊 Banner Design System

### Visual Language: "Mediterranean Waves"

The official banner style for Cloud Native Provence draws on the Provençal Mediterranean landscape. It features layered, flowing wave shapes that evoke the sea, soft misty backgrounds like morning light, and thin line art suggesting distant mountain ridges.

### Design Elements

**Background:**
- Soft vertical gradient from Alpine White (#f0f4fa) to near-white (#fafbfd)
- Subtle elliptical cloud shapes in the upper area (low opacity, Gaussian-blurred)

**Mountain Line Art:**
- Thin teal/green lines (#238c9b) tracing gentle mountain ridgelines
- 1–2px stroke, semi-transparent (~120 alpha)
- Positioned in the mid-to-upper zone

**Wave Layers (bottom half):**
- 6–8 layered, translucent wave shapes stacking from light to saturated
- Light layers: pale blue (#d2e6f5 → #b4d2eb) at low opacity (80–100 alpha)
- Mid layers: soft teal/blue (#a0c8e1) at medium opacity (100–110 alpha)
- Foreground layers: Provence Blue (#356cc8) and deep blue (#2d5fb4) at high opacity (200–230 alpha)
- Waves use sine functions with varying amplitude/frequency for organic flow

**Blue-to-Purple Variant:**
- Same structure, but foreground wave layers transition from Provence Blue on the left to Lavender Purple (#8260c8) on the right
- Used for event banners (e.g., KCD) and special occasions

### Banner Files

| File | Dimensions | Description | Use Case |
|------|-----------|-------------|----------|
| `banner_waves_blue.png` | 1920×600 | Blue wave background (no text) | Website headers, social media covers, general backgrounds |
| `banner_waves_purple.png` | 1920×600 | Blue-to-purple wave background (no text) | Event backgrounds, special announcements |
| `banner_meetup.png` | 1920×600 | Blue waves + logo + "Community Meetup" text | Monthly meetup announcements, Meetup.com header |
| `banner_kcd.png` | 1920×600 | Purple waves + logo + "Kubernetes Community Days" text | KCD event branding, conference materials |

### Banner Usage Guidelines

- **Text-free backgrounds** (`banner_waves_blue.png`, `banner_waves_purple.png`) can be used with custom text overlays in Canva, Figma, etc.
- **Text-included banners** should be used as-is; do not add additional text layers
- Logo placement: left side for meetup banners, right side for event banners
- Text color on wave backgrounds: Deep Navy (#1a2d4d) for titles, Storm Gray (#4a5568) for subtitles, Provence Blue (#356cc8) for accents
- Ensure text sits in the upper portion where the background is light

---

## 📞 Brand Assets

All brand assets are available in the `/brand/` directory:

```
/brand/
├── logos/
│   ├── cnp-logo-helm-hires.png
│   ├── cnp-logo-helm.svg
│   └── cnp-logo-helm-icon.png (future)
├── banner/
│   ├── banner_waves_blue.png
│   ├── banner_waves_purple.png
│   ├── banner_meetup.png
│   └── banner_kcd.png
├── colors/
│   └── color-palette.css
├── fonts/
│   └── poppins-import.css
├── BRAND_GUIDE.md
└── README.md
```

---

## 📋 Quick Reference

**Primary Colors:**
- Provence Blue: `#356cc8` (RGB 53, 108, 200)
- Pure White: `#ffffff` (RGB 255, 255, 255)
- Deep Navy: `#1a2d4d` (RGB 26, 45, 77)

**Complementary Colors:**
- Sky Mist: `#6b8fd4`
- Alpine White: `#f0f4fa`
- Storm Gray: `#4a5568`
- Mediterranean Teal: `#2da3b8`

**Fonts:** Poppins (primary), Work Sans (alternative)

**Logo Versions:** Full Helm Badge, SVG Helm, Icon Helm Badge

**Key Features:**
- Ship's helm/wheel design (Kubernetes-inspired)
- Provence/Mediterranean visual elements
- Cloud-native branding alignment
- Professional, scalable aesthetic

---

**Version:** 2.1
**Last Updated:** February 2026
**Maintained by:** Cloud Native Provence Community

---

<div align="center">

Made with ❤️ by the Cloud Native Provence community

[Website](#) • [Twitter](#) • [LinkedIn](#) • [Meetup](#)

</div>
