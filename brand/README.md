# Cloud Native Provence Brand Assets

Official brand guidelines and assets for Cloud Native Provence.

## 📁 Repository Structure

```
/assets/brand/
├── BRAND_GUIDE.md          # Complete brand guidelines
├── logos/
│   ├── cnp-logo-full-hexagon.png      # Primary logo with text
│   ├── cnp-logo-outlined-cloud.png    # Icon with outlined clouds
│   └── cnp-logo-filled-badge.png      # Icon badge only
└── README.md               # This file
```

## 🎨 Quick Start

### Using the Logos

1. **For social media profiles:** Use `cnp-logo-full-hexagon.png`
2. **For favicons/app icons:** Use `cnp-logo-filled-badge.png`
3. **For watermarks:** Use `cnp-logo-outlined-cloud.png`

### Color Palette

```css
--deep-navy: #00132e;
--azure-blue: #004a9b;
--cream-white: #fffffd;
--sky-blue: #5ba3d0;
--lavender: #a78bfa;
--slate-gray: #7a8694;
```

### Typography

**Font:** [Poppins](https://fonts.google.com/specimen/Poppins) from Google Fonts

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
```

## 📖 Full Documentation

For complete brand guidelines including:
- Detailed color usage
- Typography system
- Logo specifications
- Design patterns
- Accessibility guidelines

**Read the [Complete Brand Guide](BRAND_GUIDE.md)**

## ⚡ Quick Examples

### HTML Button

```html
<button style="
  background: #004a9b;
  color: #fffffd;
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
  background: #fffffd;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 8px rgba(0, 19, 46, 0.08);
}

.cnp-card:hover {
  box-shadow: 0 4px 16px rgba(0, 74, 155, 0.12);
}
```

## 🚀 Using in Your Projects

### CDN Links (CSS Variables)

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

:root {
  --cnp-deep-navy: #00132e;
  --cnp-azure-blue: #004a9b;
  --cnp-cream-white: #fffffd;
  --cnp-sky-blue: #5ba3d0;
  --cnp-lavender: #a78bfa;
  --cnp-slate-gray: #7a8694;
  --cnp-font-family: 'Poppins', sans-serif;
}
```

### React Example

```jsx
import logo from './assets/brand/logos/cnp-logo-full-hexagon.png';

function Header() {
  return (
    <header style={{
      background: '#00132e',
      padding: '1rem'
    }}>
      <img src={logo} alt="Cloud Native Provence" height="60" />
    </header>
  );
}
```

## ✅ Brand Guidelines Checklist

When creating Cloud Native Provence materials:

- [ ] Use official logos from this repository
- [ ] Follow the color palette (no custom colors)
- [ ] Use Poppins font family
- [ ] Maintain minimum logo sizes (200px for full logo)
- [ ] Ensure proper color contrast for accessibility
- [ ] Keep adequate clear space around logos
- [ ] Don't modify, rotate, or distort logos

## 🤝 Contributing

Found an issue with the brand guidelines or need additional assets?

1. Open an issue in this repository
2. Tag it with `brand` label
3. Provide specific details about what you need

## 📞 Contact

**Cloud Native Provence Brand Team**

For questions about brand usage or custom asset requests.

---

## 📜 License

The Cloud Native Provence brand assets are proprietary to the Cloud Native Provence community.

**Usage Guidelines:**
- ✅ Use for Cloud Native Provence events, presentations, and community materials
- ✅ Use on personal websites/social media when referring to Cloud Native Provence
- ❌ Do not use for commercial purposes without permission
- ❌ Do not modify the logos or create derivative works
- ❌ Do not imply official endorsement without authorization

---

<div align="center">

**Cloud Native Provence** 🌊

Building a vibrant cloud-native community in Provence

</div>