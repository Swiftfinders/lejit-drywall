# Assets Directory

This directory contains icons, favicons, and other static assets.

## Required Files:

### Favicon
- `favicon.ico` - 32x32px or 16x16px icon file
- Optional: Add additional favicon sizes for better browser support:
  - `favicon-16x16.png`
  - `favicon-32x32.png`
  - `apple-touch-icon.png` (180x180px for iOS)

## Creating a Favicon:

### Online Tools:
1. **Favicon.io** - https://favicon.io
   - Convert text, images, or emojis to favicon
   - Generates all necessary sizes

2. **RealFaviconGenerator** - https://realfavicongenerator.net
   - Comprehensive favicon generator
   - Supports all platforms

### Design Recommendations:
- Use Lejit Drywall logo or initials "LD"
- Keep it simple - favicons are very small
- Use black and white to match brand colors
- Test on both light and dark browser themes

## Placeholder Favicon:
Until a custom favicon is created, you can:
1. Use a simple text-based favicon from Favicon.io
2. Use an emoji-based favicon (🏗️ or 🔨)
3. Create a simple "LD" text favicon

## Installation:
Once favicon files are created, ensure they're referenced in all HTML files in the `<head>` section:

```html
<link rel="icon" type="image/x-icon" href="assets/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="assets/favicon-32x32.png">
<link rel="apple-touch-icon" sizes="180x180" href="assets/apple-touch-icon.png">
```
