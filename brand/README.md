# Cloud Native Provence Brand Assets

Official brand guidelines and assets for Cloud Native Provence.
Updated February 2026 for the ship's helm/wheel logo.

## Repository Structure

```
/brand/
├── BRAND_GUIDE.md                    # Complete brand guidelines (v2.1)
├── README.md                         # This file
├── logos/
│   ├── cnp-logo-helm-hires.png       # High-res helm badge (2138x2132px)
│   ├── cnp-logo-helm.svg             # SVG version for web/responsive
│   └── cnProvence_light.png
├── banner/
│   ├── banner_waves_blue.png         # Blue Mediterranean waves (1920x600)
│   ├── banner_waves_purple.png       # Blue-to-purple waves (1920x600)
│   ├── banner_meetup.png             # Community Meetup banner with logo
│   ├── Banner_landscape_purple.png
│   ├── banner_landscape_blue.png
│   └── banner_kcd.png                # KCD event banner with logo
│     
├── colors/
│   └── color-palette.css             # CSS variables and palette
└── fonts/
    └── poppins-import.css            # Font import reference
```

## Logo Files

### `cnp-logo-helm-hires.png` — High-Resolution PNG

- **Dimensions:** 2138 x 2132 px (print-ready)
- **Format:** PNG with transparent background (RGBA)
- **Primary color:** Provence Blue (#356cc8) with white elements

**Where to use:**

| Context | Notes |
|---------|-------|
| Social media profiles | GitHub, LinkedIn, Meetup, Twitter/X avatars |
| Website header / hero | Pair with white or Alpine White (#f0f4fa) background |
| Presentations (title slide) | Place on light background for maximum impact |
| T-shirts & merchandise | Transparent background works for any print color |
| Stickers & die-cut prints | Circular shape is ideal for die-cutting |
| Event signage & roll-ups | High-res enough for large-format printing |
| Email signatures | Scale down to ~60px height |

**Background recommendations:**
- White (#ffffff) or Alpine White (#f0f4fa) — best contrast
- Light gray (#f5f5f5) — clean, neutral
- Dark Navy (#1a2d4d) — dramatic, works because logo has white internal elements
- Avoid busy or patterned backgrounds

**Minimum sizes:** 200px width (digital), 40mm width (print)

### `cnp-logo-helm.svg` — Scalable Vector

- **Format:** SVG with embedded raster (for web/responsive)
- **Use for:** Responsive web designs, any context where the logo must scale smoothly
- **Minimum size:** None — infinitely scalable

### Banners (1920 x 600 px)

Use the `banner/` assets for social media covers, website headers, and event materials. Text-free versions (`banner_waves_blue.png`, `banner_waves_purple.png`) can be overlaid in Canva or Figma.

### Color Palette

```css
/* Primary */
--cnp-provence-blue: #356cc8;
--cnp-pure-white: #ffffff;
--cnp-deep-navy: #1a2d4d;

/* Complementary */
--cnp-sky-mist: #6b8fd4;
--cnp-alpine-white: #f0f4fa;
--cnp-storm-gray: #4a5568;
--cnp-mediterranean-teal: #2da3b8;
```

### Typography

**Primary font:** [Poppins](https://fonts.google.com/specimen/Poppins) | **Alternative:** [Work Sans](https://fonts.google.com/specimen/Work+Sans)

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
```

## Full Documentation

For complete brand guidelines including detailed color usage, typography system, logo specifications, banner design system, design patterns, and accessibility guidelines:

**Read the [Complete Brand Guide](BRAND_GUIDE.md)**

## Quick Examples

### HTML Button

```html
<button style="
  background: #356cc8;
  color: #ffffff;
  font-family: 'Poppins', sans-serif;
  font-weight: 600;
  padding: 12px 32px;
  border-radius: 8px;
  border: none;
">
  Join Community
</button>
```

### CSS Card

```css
.cnp-card {
  background: #ffffff;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 8px rgba(26, 45, 77, 0.08);
}

.cnp-card:hover {
  box-shadow: 0 4px 16px rgba(53, 108, 200, 0.12);
}
```

## Using in Your Projects

### CSS Variables

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@400;500;600;700&display=swap');

:root {
  --cnp-provence-blue: #356cc8;
  --cnp-pure-white: #ffffff;
  --cnp-deep-navy: #1a2d4d;
  --cnp-sky-mist: #6b8fd4;
  --cnp-alpine-white: #f0f4fa;
  --cnp-storm-gray: #4a5568;
  --cnp-mediterranean-teal: #2da3b8;
  --cnp-font-family: 'Poppins', sans-serif;
  --cnp-font-family-alt: 'Work Sans', sans-serif;
}
```

### React Example

```jsx
import logo from './brand/logos/cnp-logo-helm-hires.png';

function Header() {
  return (
    <header style={{
      background: '#1a2d4d',
      padding: '1rem'
    }}>
      <img src={logo} alt="Cloud Native Provence" height="60" />
    </header>
  );
}
```

## Brand Guidelines Checklist

When creating Cloud Native Provence materials:

- [ ] Use official helm logo from this repository
- [ ] Follow the color palette (Provence Blue #356cc8 as primary)
- [ ] Use Poppins or Work Sans font family
- [ ] Maintain minimum logo sizes (200px for full logo)
- [ ] Ensure proper color contrast for accessibility
- [ ] Keep adequate clear space around logos
- [ ] Don't modify, rotate, or distort logos
- [ ] Use Mediterranean Waves banner style for backgrounds

## Contributing

Found an issue with the brand guidelines or need additional assets?

1. Open an issue in this repository
2. Tag it with `brand` label
3. Provide specific details about what you need

## Contact

**Cloud Native Provence Brand Team**

For questions about brand usage or custom asset requests.

---

## License

The Cloud Native Provence brand assets are proprietary to the Cloud Native Provence community.

**Usage Guidelines:**
- Use for Cloud Native Provence events, presentations, and community materials
- Use on personal websites/social media when referring to Cloud Native Provence
- Do not use for commercial purposes without permission
- Do not modify the logos or create derivative works
- Do not imply official endorsement without authorization

---

<div align="center">

**Cloud Native Provence**

Building a vibrant cloud-native community in Provence

</div>
