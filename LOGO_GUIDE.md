# Horizon Financial Services - Logo Files

## Logo Variations

Your website now includes 4 professional logo variations:

### 1. **horizon_logo.svg** (Main Logo)
- **Size:** 200x60px
- **Use:** Primary logo for headers, letterheads, business cards
- **Colors:** Navy blue (#001C3D) with gold accent (#C9A961)
- **Best for:** Light backgrounds

### 2. **horizon_logo_horizontal.svg** (Navigation Logo) ✅ ACTIVE
- **Size:** 180x40px
- **Use:** Website navigation bar (currently in use)
- **Colors:** Navy blue (#001C3D) with gold accent (#C9A961)
- **Best for:** Compact spaces, website headers
- **Currently used in:** Both Goldman Sachs-style pages

### 3. **horizon_icon.svg** (Icon Only)
- **Size:** 50x50px
- **Use:** Favicons, app icons, social media avatars
- **Colors:** Navy blue (#001C3D) with gold accent (#C9A961)
- **Best for:** Square spaces, small formats

### 4. **horizon_logo_white.svg** (Dark Background Version)
- **Size:** 200x60px
- **Use:** Footer, dark backgrounds, print on dark materials
- **Colors:** White (#FFFFFF) with gold accent (#C9A961)
- **Best for:** Dark backgrounds (navy, black)

## Logo Design Elements

### Symbol Meaning
The logo features a compass/horizon symbol representing:
- **Circle:** Completeness and trust
- **Upward Arrow:** Growth and progress
- **Horizon Line:** Clear vision and direction
- **Center Point:** Focus and stability

### Color Palette
- **Navy Blue (#001C3D):** Trust, professionalism, stability
- **Gold (#C9A961):** Premium quality, success, achievement
- **Gray (#424242):** Modern, sophisticated, balanced

## Usage Guidelines

### DO:
✅ Use the horizontal version for website navigation
✅ Use the white version on dark backgrounds
✅ Maintain proper spacing around the logo
✅ Keep the proportions intact when scaling
✅ Use the icon version for social media profiles

### DON'T:
❌ Change the colors
❌ Stretch or distort the logo
❌ Add effects or shadows
❌ Use low-resolution versions
❌ Place on busy backgrounds that reduce legibility

## File Formats

All logos are provided in **SVG format** which means:
- ✅ **Scalable:** Perfect quality at any size
- ✅ **Lightweight:** Small file sizes for fast loading
- ✅ **Editable:** Can be customized in design software
- ✅ **Web-optimized:** Perfect for websites

## Converting to Other Formats

If you need PNG or JPG versions:
1. Open the SVG in design software (Figma, Illustrator, Inkscape)
2. Export at your desired size
3. Recommended sizes for PNG:
   - Small: 200px width
   - Medium: 400px width
   - Large: 800px width
   - HD: 1600px width

## Favicon Setup

To use the icon as a favicon:
1. Convert `horizon_icon.svg` to multiple sizes (16x16, 32x32, 180x180)
2. Or use the SVG directly:
   ```html
   <link rel="icon" type="image/svg+xml" href="horizon_icon.svg">
   ```

## Current Implementation

The logo is currently implemented in:
- ✅ `horizon-goldman-style.html` (navigation)
- ✅ `horizon-goldman-megamenu.html` (navigation)

To add to other pages, use:
```html
<a href="index.html" class="logo">
    <img src="horizon_logo_horizontal.svg" alt="Horizon Financial Services" style="height: 35px; display: block;">
</a>
```

## Logo Location

All logos are stored in the root directory:
```
horizon-financial-site/
├── horizon_logo.svg (main)
├── horizon_logo_horizontal.svg (navigation) ⭐
├── horizon_icon.svg (icon only)
└── horizon_logo_white.svg (dark backgrounds)
```

## Questions?

Contact your web developer or designer for:
- Custom logo variations
- Different color schemes
- Print-optimized versions
- Animated logo versions
