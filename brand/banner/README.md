# Cloud Native Provence - Event Banners

Professional, high-quality event banners for Cloud Native Provence (CNP) community.

## Overview

Three professionally designed 1920x600 pixel banners created with Python and Pillow for social media, websites, and event announcements.

**Brand Color:** Provence Blue (#356cc8)
**Secondary Colors:** White (#ffffff), Dark Blue (#1e3a7a), Light Gray (#f0f4fa)

## Files

### Banner Images

1. **banner_meetup.png** (40 KB)
   - Community Meetup themed banner
   - Blue gradient background
   - White typography
   - Helm logo on left side
   - Perfect for monthly meetup announcements

2. **banner_welcome.png** (40 KB)
   - General purpose welcome banner
   - Light background with blue accents
   - Centered logo and centered text
   - Decorative geometric elements
   - Ideal for community homepage and general events

3. **banner_kcd.png** (47 KB)
   - Kubernetes Community Days event banner
   - Split design (blue left, white right)
   - Large centered logo
   - Dynamic, conference-style aesthetic
   - Best for major event announcements

### Documentation

- **BANNER_DESIGN_GUIDE.md** - Comprehensive design specifications and guidelines
- **README.md** - This file
- **generate_banners.py** - Python script to regenerate or customize banners

## Usage

### Direct Use

Simply use the PNG files as-is for:
- Website headers and banners
- Social media posts (Twitter, LinkedIn, Facebook)
- Email newsletters and announcements
- Event pages and landing pages
- Presentation slides

### Regeneration

To regenerate the banners with the Python script:

```bash
# Generate all banners
python3 generate_banners.py

# Generate specific banner
python3 generate_banners.py --banner meetup
python3 generate_banners.py --banner welcome
python3 generate_banners.py --banner kcd

# Save to custom location
python3 generate_banners.py --output /your/custom/path
```

## Design Features

### Logo Design
- Circular badge with helm/wheel (Kubernetes-inspired)
- 8 spokes representing navigation and community
- Cloud elements (semi-circular arcs)
- Mountain peaks (Provence geography)
- Water waves (Mediterranean)
- Double ring for sophistication
- Solid center circle

### Typography
- **Primary Font:** WorkSans (Bold & Regular)
  - Modern, geometric, tech-forward
  - Excellent readability
  
- **Secondary Font:** Outfit (Bold)
  - Contemporary, clean aesthetic
  - Used for emphasis and variation

### Design Principles
- Professional, modern tech aesthetic
- High contrast for accessibility
- Clean, minimal decoration
- Geometric shapes and subtle gradients
- Anti-aliased rendering for quality
- Consistent brand identity

## Color Specifications

| Color Name | Hex Code | RGB Values |
|-----------|----------|-----------|
| Provence Blue | #356cc8 | (53, 108, 200) |
| Dark Blue | #1e3a7a | (30, 58, 122) |
| White | #ffffff | (255, 255, 255) |
| Light Gray | #f0f4fa | (240, 244, 250) |

## Technical Specifications

- **Dimensions:** 1920 x 600 pixels
- **Aspect Ratio:** 16:9 (standard web banner)
- **Format:** PNG (lossless compression)
- **Color Space:** RGB
- **File Sizes:** 25-47 KB each
- **Quality Level:** 95% (high quality, optimized file size)

## Social Media Usage

### Twitter/X
- Use any banner at full size
- Perfect for header image (recommended: banner_welcome.png)

### LinkedIn
- Use banners 2 and 3 for professional appeal
- Works well in company or event pages

### Facebook
- Use full-size or resize to 1200x628
- All banners work well

### Instagram
- Resize to 1080x1080 square format
- Crop centered portion for best results

## Browser & Device Compatibility

All banners are optimized for:
- Desktop browsers (1920x1080+)
- Tablet displays (iPad, Android tablets)
- Mobile devices (responsive scaling)
- Modern PNG support (all browsers)

## Customization

The banners can be easily customized:

1. **Text Changes:** Update text in the banner generation script
2. **Colors:** Modify RGB values while maintaining contrast
3. **Logo:** Adjust logo size or elements in draw_helm_logo function
4. **Backgrounds:** Modify gradient calculations
5. **Fonts:** Change font files or sizes

See **generate_banners.py** for modification examples.

## Quality Assurance

All banners have been verified for:
- ✓ Correct dimensions (1920x600)
- ✓ PNG format and quality
- ✓ Brand color accuracy
- ✓ Text readability
- ✓ Logo placement and sizing
- ✓ Professional appearance
- ✓ Web-ready optimization

## Production Details

**Created:** February 6, 2025
**Tool:** Python 3 with Pillow (PIL)
**Fonts:** Google Fonts (WorkSans, Outfit)
**Designer:** Claude Code (AI Design Assistant)
**Version:** 1.0 - Professional Release

## Support & Modifications

For banner modifications or custom variations:

1. Review the BANNER_DESIGN_GUIDE.md for design specifications
2. Edit the generate_banners.py script with desired changes
3. Run the script to regenerate banners
4. Verify output quality and brand consistency

## License & Usage Rights

These banners are created for Cloud Native Provence community use. 
Maintain brand consistency and the original design specifications when using or modifying these assets.

## Questions?

Refer to:
- **BANNER_DESIGN_GUIDE.md** for detailed specifications
- **generate_banners.py** for implementation details
- Script comments for technical explanations

---

**Cloud Native Provence - Bringing Cloud Native Community to the South of France**
