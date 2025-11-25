# Image Replacement Guide for Lejit Drywall Website

This guide will help you replace the placeholder images with actual professional drywall photos.

## 📷 Images to Replace

You need to replace **11 placeholder images** total:

- **1 Hero Background** - `images/hero-bg.jpg`
- **10 Project Gallery Images** - `images/project-1.jpg` through `images/project-10.jpg`

## 🔍 Where to Find Professional Drywall Images

### Free High-Quality Stock Photo Sites:

1. **Unsplash.com** (Recommended - Highest Quality)
   - URL: https://unsplash.com
   - No attribution required
   - Commercial use allowed
   - Search terms to use:
     * "drywall installation"
     * "drywall finishing"
     * "drywall taping"
     * "construction interior"
     * "wall installation"
     * "ceiling drywall"
     * "construction worker drywall"

2. **Pexels.com** (Great Selection)
   - URL: https://pexels.com
   - No attribution required
   - Commercial use allowed
   - Search terms:
     * "drywall"
     * "wall construction"
     * "interior construction"
     * "plastering"
     * "construction site"

3. **Pixabay.com** (Additional Options)
   - URL: https://pixabay.com
   - Free for commercial use
   - Search terms:
     * "drywall finishing"
     * "construction work"
     * "wall repair"

## 📐 Image Specifications

### Hero Background (`hero-bg.jpg`):
- **Recommended Size:** 1920 x 1080 pixels (Full HD)
- **Minimum Size:** 1600 x 900 pixels
- **File Format:** JPEG (.jpg)
- **File Size:** Under 300KB (after optimization)
- **Subject:** Professional drywall worker installing or finishing drywall, close-up of drywall work, or wide shot of construction site

### Project Gallery Images (`project-1.jpg` through `project-10.jpg`):
- **Recommended Size:** 1200 x 800 pixels (3:2 aspect ratio)
- **Minimum Size:** 900 x 600 pixels
- **File Format:** JPEG (.jpg)
- **File Size:** Under 200KB each (after optimization)
- **Variety Needed:**
  1. Drywall installation in progress
  2. Finished smooth wall
  3. Ceiling work/installation
  4. Framing (metal or wood studs)
  5. Texture application or finishing
  6. Before/after repair work
  7. Commercial project
  8. Basement or residential project
  9. Popcorn ceiling removal
  10. Completed painted room

## 🎨 What Makes a Good Drywall Photo

**DO choose images that show:**
- ✓ Professional-looking drywall work in progress or completed
- ✓ Clean, well-lit construction sites
- ✓ High-quality craftsmanship
- ✓ Various angles and project types
- ✓ Real construction work (not stock models posing)
- ✓ Sharp, in-focus images
- ✓ Neutral or white walls (matches brand aesthetic)

**DON'T choose images that:**
- ✗ Are blurry or poorly lit
- ✗ Show messy or unprofessional work
- ✗ Have distracting watermarks
- ✗ Are too dark or too bright
- ✗ Show damaged or poor-quality drywall
- ✗ Generic construction that doesn't show drywall specifically

## 🔧 How to Download and Optimize Images

### Step 1: Download Images

**From Unsplash:**
1. Go to https://unsplash.com
2. Search for "drywall installation" (or other terms above)
3. Click on the image you want
4. Click "Download free" button (choose the size you need)
5. Save to your computer

**From Pexels:**
1. Go to https://pexels.com
2. Search for "drywall"
3. Click on image
4. Click "Free Download" and select size
5. Save to your computer

### Step 2: Optimize Images for Web

**Use Online Tools (Recommended):**

1. **TinyPNG.com** (Best Compression)
   - Go to https://tinypng.com
   - Drag and drop your images
   - Download compressed versions
   - Reduces file size by 50-70% with no visible quality loss

2. **Squoosh.app** (More Control)
   - Go to https://squoosh.app
   - Upload image
   - Adjust quality slider to reduce file size
   - Target: Under 200KB for gallery images, under 300KB for hero
   - Download optimized image

### Step 3: Rename and Replace

1. **Rename downloaded images** to match placeholders:
   - Hero background → `hero-bg.jpg`
   - Project images → `project-1.jpg`, `project-2.jpg`, etc.

2. **Replace placeholder files** in the `images/` folder:
   - Delete old placeholder SVG files
   - Copy your optimized JPG images to `images/` folder
   - Ensure filenames match exactly (case-sensitive)

3. **Verify** images load correctly by opening `index.html` in a browser

## 📱 Testing After Replacement

After replacing images, test:

1. **Desktop:** Open website, check all images load
2. **Mobile:** Test on phone or use browser DevTools responsive mode
3. **Performance:** Images should load quickly (under 2 seconds)
4. **Visual Check:** 
   - Hero background has good contrast with white text
   - All gallery images display properly
   - No broken image icons

## 🎯 Quick Checklist

Before deploying to Netlify, ensure:

- [ ] Hero background (`hero-bg.jpg`) is professional drywall work photo
- [ ] All 10 project images show variety of drywall work
- [ ] All images are optimized (under 200-300KB each)
- [ ] All images are named correctly (project-1.jpg through project-10.jpg)
- [ ] Images are in JPEG format (.jpg extension)
- [ ] Tested on desktop and mobile browsers
- [ ] White text on hero is clearly readable
- [ ] Gallery images look professional and high-quality

## 💡 Tips for Best Results

1. **Variety is key:** Don't use 10 similar images. Show different aspects of drywall work.

2. **Professional quality:** Choose sharp, well-composed photos that look professional.

3. **Consistent style:** Try to maintain similar lighting/color tones across gallery images.

4. **Hero impact:** Choose a striking, high-quality image for the hero that immediately communicates professionalism.

5. **Real work:** Prefer images showing actual drywall work over generic construction.

## 🚀 After Image Replacement

Once all real images are in place:

1. Test the complete website locally
2. Commit changes to git
3. Push to GitHub repository
4. Deploy to Netlify (or redeploy if already deployed)
5. Verify all images load correctly on live site

---

**Need Help?**

If images aren't loading after replacement:
- Check that filenames match exactly (case-sensitive)
- Verify files are in the `images/` folder
- Clear browser cache and reload
- Check browser console for errors (F12 → Console tab)
