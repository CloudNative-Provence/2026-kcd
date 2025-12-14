# Cloud Native Provence - Brand Style Guide

> Official brand guidelines for Cloud Native Provence community materials

---

## 🎨 Color Palette

### Primary Colors

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Deep Navy** | `#00132e` | 0, 19, 46 | Primary brand color - Use for headers, backgrounds, and main elements |
| **Azure Blue** | `#004a9b` | 0, 74, 155 | Secondary brand color - Use for accents and interactive elements |
| **Cream White** | `#fffffd` | 255, 255, 253 | Background color - Use for main backgrounds and contrast |

### Complementary Colors

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Sky Blue** | `#5ba3d0` | 91, 163, 208 | Light accent - Use for highlights, hover states, and secondary elements |
| **Lavender** | `#a78bfa` | 167, 139, 250 | Accent color - Use for CTAs, important highlights, and creative elements |
| **Slate Gray** | `#7a8694` | 122, 134, 148 | Neutral - Use for secondary text, borders, and subtle elements |

### Color Swatches

```
Deep Navy    Azure Blue   Cream White
#00132e      #004a9b      #fffffd
███████      ███████      ███████

Sky Blue     Lavender     Slate Gray
#5ba3d0      #a78bfa      #7a8694
███████      ███████      ███████
```

---

## 📊 Color Usage Guidelines

### ✅ Recommended Combinations

| Background | Text/Foreground | Use Case |
|------------|----------------|----------|
| `#fffffd` | `#00132e` | Primary content, body text |
| `#00132e` | `#fffffd` | Headers, hero sections |
| `#004a9b` | `#fffffd` | Buttons, call-to-action |
| `#fffffd` | `#7a8694` | Secondary text, captions |
| `#a78bfa` | `#00132e` | Accent CTAs on dark backgrounds |

### ❌ Avoid These Combinations

- `#004a9b` on `#00132e` (insufficient contrast)
- `#5ba3d0` on `#fffffd` (too light for text)
- `#7a8694` on `#5ba3d0` (poor readability)
- `#a78bfa` on `#fffffd` (use for decorative elements only)

---

## 🔤 Typography

### Primary Font: Poppins

**Font Family:** [Poppins](https://fonts.google.com/specimen/Poppins) (Google Fonts)

**Import:**
```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');
```

### Type Scale

| Element | Font Weight | Size | Line Height | Color | Use Case |
|---------|-------------|------|-------------|-------|----------|
| **H1 - Display** | Bold (700) | 48px / 3rem | 1.2 | `#00132e` | Page titles, hero headings |
| **H2 - Section** | SemiBold (600) | 36px / 2.25rem | 1.3 | `#00132e` | Section titles |
| **H3 - Subsection** | SemiBold (600) | 28px / 1.75rem | 1.4 | `#004a9b` | Subsection titles |
| **H4 - Component** | Medium (500) | 20px / 1.25rem | 1.5 | `#00132e` | Card titles, component headers |
| **Body** | Regular (400) | 16px / 1rem | 1.6 | `#00132e` | Paragraphs, general content |
| **Body Small** | Regular (400) | 14px / 0.875rem | 1.6 | `#7a8694` | Captions, metadata, footnotes |
| **Button/CTA** | SemiBold (600) | 16px / 1rem | - | `#fffffd` | Buttons, links, CTAs |

**Letter Spacing for CTAs:** 0.5px

---

## 🖼️ Logo Usage

### Logo Versions

We have **three official logo versions**:

#### 1. Full Hexagon Badge Logo
**File:** `cnp-logo-full-hexagon.png`

- Complete logo with hexagonal badge, lighthouse icon, cloud elements, and "CLOUD NATIVE PROVENCE" text
- Features azure blue (`#004a9b`) hexagon with deep navy (`#00132e`) center
- White lighthouse and cloud elements
- **Use for:** Profile pictures, social media, badges, stickers, primary branding
- **Background:** Any light or neutral background - works on `#fffffd`, white, or light gray
- **Minimum size:** 200px width (digital), 40mm (print)

#### 2. Icon - Outlined Cloud Version
**File:** `cnp-logo-outlined-cloud.png`

- Lighthouse icon with outlined cloud shapes
- Navy blue (`#00132e`) lighthouse on transparent background
- Outlined clouds (not filled)
- **Use for:** Backgrounds, watermarks, subtle branding, overlays on photos
- **Background:** Light backgrounds only - `#fffffd`, white, or light colors
- **Minimum size:** 120px width (digital), 25mm (print)

#### 3. Icon - Filled Badge Version
**File:** `cnp-logo-filled-badge.png`

- Lighthouse icon with hexagonal badge (no text)
- Navy blue filled hexagon with white lighthouse
- **Use for:** App icons, favicons, small spaces where text isn't readable
- **Background:** Any background - works on light, dark, or colored backgrounds
- **Minimum size:** 64px (favicons), 512px (app icons)

### Logo Design Elements

**The Cloud Native Provence logo features:**
- **Lighthouse:** Represents Provence's Mediterranean coastal heritage and guidance/navigation
- **Hexagon:** Mirrors Kubernetes/cloud-native community branding patterns
- **Clouds:** Symbolizes cloud-native technology
- **Color Gradient:** Azure blue to deep navy creates depth and dimension
- **3D Effect:** Shadow effect on hexagon badge adds modern, professional appearance

---

## 📐 Logo Usage by Context

| Context | Recommended Version | Notes |
|---------|-------------------|-------|
| Website Header | Full Hexagon Badge | Primary branding |
| Social Media Profile | Full Hexagon Badge | Square format works perfectly |
| Social Media Posts | Any version | Choose based on layout |
| Presentation Title Slide | Full Hexagon Badge | Maximum impact |
| Presentation Recurring | Icon - Filled Badge | Subtle, doesn't dominate |
| Documentation | Icon - Outlined Cloud | Clean, professional |
| Favicon | Icon - Filled Badge | Recognizable at small sizes |
| T-Shirts/Merchandise | Full Hexagon Badge | Best for printing |
| Stickers | Full Hexagon Badge | Die-cut friendly hexagon |
| Email Signature | Icon - Filled Badge | Space-efficient |
| GitHub Avatar | Full Hexagon Badge | Clear at all sizes |
| Watermarks | Icon - Outlined Cloud | Subtle, non-intrusive |

### Background Recommendations

#### Full Hexagon Badge Logo:
- ✅ White (`#fffffd`)
- ✅ Light gray (`#f5f5f5`)
- ✅ Light sky blue (`#e6f3ff`)
- ❌ Avoid dark backgrounds (logo has dark elements)
- ❌ Avoid busy patterns

#### Icon - Outlined Cloud Version:
- ✅ White (`#fffffd`)
- ✅ Very light backgrounds
- ✅ Photo overlays (light areas)
- ❌ Dark backgrounds (outlines won't be visible)

#### Icon - Filled Badge Version:
- ✅ Any background color
- ✅ Photos (dark or light)
- ✅ Colored backgrounds
- ✅ Deep navy (`#00132e`) - creates monochrome effect
- ✅ Azure blue (`#004a9b`) - tone-on-tone effect

---

## 🚫 Logo Don'ts

- ❌ Do not rotate the logo
- ❌ Do not change logo colors (use only the 3 approved versions)
- ❌ Do not add effects (shadows, gradients, outlines) to logo itself
- ❌ Do not stretch or distort proportions
- ❌ Do not place on busy backgrounds without sufficient contrast
- ❌ Do not recreate or modify the logo
- ❌ Do not separate the lighthouse from clouds in outlined version
- ❌ Do not use outlined cloud version on dark backgrounds

---

## 🎯 Design Patterns

### Buttons

#### Primary Button
```css
background: #004a9b;
color: #fffffd;
font-family: 'Poppins', sans-serif;
font-weight: 600;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
border: none;
cursor: pointer;
```
**Hover State:** `background: #003875`

#### Secondary Button
```css
background: transparent;
color: #004a9b;
border: 2px solid #004a9b;
font-family: 'Poppins', sans-serif;
font-weight: 600;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
cursor: pointer;
```
**Hover State:** `background: #f0f7ff`

#### Accent Button (CTA)
```css
background: #a78bfa;
color: #fffffd;
font-family: 'Poppins', sans-serif;
font-weight: 600;
font-size: 16px;
padding: 12px 32px;
border-radius: 8px;
border: none;
cursor: pointer;
```
**Hover State:** `background: #9370f0`

### Cards

```css
background: #fffffd;
border: 1px solid #e5e5e5;
border-radius: 12px;
padding: 24px;
box-shadow: 0 2px 8px rgba(0, 19, 46, 0.08);
```
**Hover State:** `box-shadow: 0 4px 16px rgba(0, 74, 155, 0.12)`

---

## 🌐 CSS Custom Properties

Use these CSS custom properties in your projects:

```css
:root {
  /* Primary Colors */
  --cnp-deep-navy: #00132e;
  --cnp-azure-blue: #004a9b;
  --cnp-cream-white: #fffffd;
  
  /* Complementary Colors */
  --cnp-sky-blue: #5ba3d0;
  --cnp-lavender: #a78bfa;
  --cnp-slate-gray: #7a8694;
  
  /* Typography */
  --cnp-font-family: 'Poppins', sans-serif;
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
}

/* Tablet */
@media (min-width: 769px) and (max-width: 1024px) {
  /* Adjust spacing */
}

/* Desktop */
@media (min-width: 1025px) {
  /* Full layout */
}
```

---

## ♿ Color Accessibility (WCAG Compliance)

| Combination | Contrast Ratio | Rating | Use Case |
|-------------|---------------|--------|----------|
| `#00132e` on `#fffffd` | 18.5:1 | AAA ✓ | Body text |
| `#004a9b` on `#fffffd` | 8.6:1 | AAA ✓ | Headings, buttons |
| `#7a8694` on `#fffffd` | 5.2:1 | AA ✓ | Secondary text |
| `#fffffd` on `#00132e` | 18.5:1 | AAA ✓ | Reverse text |
| `#a78bfa` on `#fffffd` | 3.1:1 | - | Decorative only |
| `#a78bfa` on `#00132e` | 6.1:1 | AA ✓ | Text on dark bg |

**Note:** For best accessibility with lavender, use on dark backgrounds (`#00132e`) or as decorative elements only.

---

## 📄 File Formats & Specifications

### Logo Files

| Version | Format | Transparency | Best For |
|---------|--------|--------------|----------|
| Full Hexagon Badge | PNG | Yes (except badge area) | Web, social media, presentations |
| Icon - Outlined Cloud | PNG | Full transparency | Overlays, watermarks |
| Icon - Filled Badge | PNG | Hexagon only | Icons, favicons, versatile use |

### Recommended Exports

- **Web:** PNG at 2x resolution (retina ready)
- **Print:** Request vector SVG or EPS version
- **Social Media:** PNG at platform's recommended dimensions
- **Favicon:** 512x512px PNG of filled badge version

### Color Profiles

- **Web:** sRGB
- **Print:** CMYK (request print-specific files)

---

## 🤝 Contributing to Brand Materials

When creating materials for Cloud Native Provence:

1. **Use the official logos** - Download from this repository
2. **Follow the color palette** - Use the hex codes provided
3. **Use Poppins font** - Available free from Google Fonts
4. **Maintain accessibility** - Check contrast ratios for text
5. **Keep it clean** - Use plenty of white space
6. **Be consistent** - Follow these guidelines across all materials

### Questions or Custom Assets?

Open an issue in this repository or contact the Cloud Native Provence brand team.

---

## 📞 Brand Assets

All brand assets are available in the `/assets/brand/` directory:

```
/assets/brand/
├── logos/
│   ├── cnp-logo-full-hexagon.png
│   ├── cnp-logo-outlined-cloud.png
│   └── cnp-logo-filled-badge.png
├── colors/
│   └── color-palette.css
└── fonts/
    └── poppins-import.css
```

---

## 📋 Quick Reference

**Primary Colors:**
- Deep Navy: `#00132e`
- Azure Blue: `#004a9b`
- Cream White: `#fffffd`

**Accent Colors:**
- Sky Blue: `#5ba3d0`
- Lavender: `#a78bfa`
- Slate Gray: `#7a8694`

**Font:** Poppins (Google Fonts)

**Logo Versions:** Full Hexagon Badge, Outlined Cloud, Filled Badge

---

**Version:** 1.0  
**Last Updated:** December 2025  
**Maintained by:** Cloud Native Provence Community

---

<div align="center">

Made with ❤️ by the Cloud Native Provence community

[Website](#) • [Twitter](#) • [LinkedIn](#) • [Meetup](#)

</div>