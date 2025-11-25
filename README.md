# Lejit Drywall - Premium Single-Page Website

A premium, high-end single-page scrolling website for Lejit Drywall, professional drywall services in Southern Ontario.

## 🎯 Project Overview

This is a complete static single-page website optimized for lead generation and conversions. Built with pure HTML5, CSS3, and minimal JavaScript for fast loading and easy deployment to Netlify.

### Design Features:
- **Single-page scrolling experience** with smooth navigation
- **Professional Black & White theme** - Clean, luxury aesthetic  
- **Mobile-first responsive design** - Perfect on all devices
- **Sticky navigation** - Always accessible menu
- **Netlify Forms integration** - No backend required
- **SEO optimized** - Structured data, meta tags
- **Conversion-focused** - Multiple CTAs, easy quote request

## 📁 Project Structure

```
lejit-drywall/
├── index.html           # Complete single-page website
├── css/
│   └── main.css         # All styling
├── images/
│   ├── hero-bg.jpg      # Hero background (placeholder)
│   ├── project-1.jpg through project-8.jpg # Gallery (placeholders)
│   └── favicon.ico      # Site favicon
├── assets/
│   └── README.md        # Asset documentation
├── netlify.toml         # Netlify deployment config
└── README.md            # This file
```

## 📄 Page Sections

The single-page website includes 7 main sections:

1. **Hero Section** - Eye-catching headline, subheading, CTA button
2. **Services Section** - 6 core drywall services with icons
3. **Why Us Section** - 6 key differentiators and trust signals
4. **Projects Section** - 8-image gallery of completed work
5. **About Section** - Company story and service areas
6. **Contact/Quote Form** - Netlify form for lead capture
7. **Footer** - Contact info, service areas, quick links

## 🚀 Deployment to Netlify

### Quick Deploy (Drag & Drop):

1. **Download this repository** as ZIP
2. **Extract the files**
3. **Go to** [Netlify](https://app.netlify.com)
4. **Drag and drop** the entire folder to Netlify dashboard
5. **Site is live!** Netlify provides instant URL

### GitHub Deployment (Recommended):

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Deploy Lejit Drywall website"
   git push origin main
   ```

2. **Connect to Netlify:**
   - Log in to [Netlify](https://app.netlify.com)
   - Click "Add new site" → "Import an existing project"
   - Choose "GitHub" and authorize
   - Select your repository

3. **Configure:**
   - Build command: *(leave empty)*
   - Publish directory: `.` (root)
   - Click "Deploy site"

4. **Site is live!** You'll get a URL like `yoursite.netlify.app`

## 🌐 Custom Domain Setup

1. **In Netlify Dashboard:**
   - Go to Site Settings → Domain Management
   - Click "Add custom domain"
   - Enter your domain (e.g., `lejitdrywall.com`)

2. **Configure DNS** with your registrar:
   ```
   Type: A Record
   Name: @
   Value: 75.2.60.5

   Type: CNAME
   Name: www
   Value: [your-site].netlify.app
   ```

3. **Enable HTTPS:**
   - Netlify automatically provisions SSL
   - Wait 24-48 hours for DNS propagation

## 📧 Netlify Forms Setup

The quote form is already configured! Here's how to manage submissions:

### View Form Submissions:
- Netlify Dashboard → Forms → View submissions
- Export as CSV for record-keeping

### Email Notifications:
1. Go to Site Settings → Forms → Form notifications
2. Click "Add notification" → "Email notification"
3. Enter email: `info@lejitdrywall.com`
4. Choose "New form submission" trigger
5. Save

### Form includes:
- Full Name
- Email
- Phone
- Service Type
- Project Description
- Preferred Contact Method
- Honeypot spam protection

## 🖼️ Adding Real Images

**IMPORTANT:** Replace placeholder images before going live.

### Required Images:
- `hero-bg.jpg` - Hero section background (1920x1080px recommended)
- `project-1.jpg` through `project-8.jpg` - Portfolio gallery images (1200x800px)

### Image Sources:
- **Unsplash.com** - Search: "drywall installation", "construction work"
- **Pexels.com** - Search: "drywall", "wall finishing"
- **Pixabay.com** - Search: "drywall finishing", "construction"

### Image Optimization:
- Compress images using [TinyPNG](https://tinypng.com) or [Squoosh](https://squoosh.app)
- Target: Under 200KB per image
- Format: JPEG for photos
- Add descriptive `alt` text for accessibility

## 🎨 Customization

### Update Contact Information:

**Replace in index.html:**
- `(XXX) XXX-XXXX` → Your phone number (appears 3 times)
- `info@lejitdrywall.com` → Your email address
- `+1XXXXXXXXXX` → Your full phone number for tel: links

### Update Service Areas:

Edit the footer section in `index.html` to add/remove cities you serve.

### Change Colors:

Edit `css/main.css` - All colors are defined at the top:
- `#000000` - Primary Black
- `#FFFFFF` - Primary White  
- `#F5F5F5` - Light Gray backgrounds
- `#1A1A1A` - Dark text
- `#E0E0E0` - Borders

## 📱 Mobile Testing

Test responsive design at these breakpoints:
- **Mobile:** 375px, 480px
- **Tablet:** 768px, 1024px
- **Desktop:** 1280px, 1920px

Use browser DevTools (F12) or online tools like [Responsively](https://responsively.app)

## 🔍 SEO Checklist

- [x] Meta title and description
- [x] Structured data (LocalBusiness schema)
- [x] Semantic HTML5
- [x] Alt text for images (add when uploading real photos)
- [x] Mobile-friendly design
- [x] Fast page load
- [x] HTTPS enabled (automatic with Netlify)

### Submit to Google:
1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add your property (website)
3. Netlify auto-generates sitemap at `yoursite.com/sitemap.xml`

## 🎯 Performance Optimization

### Lighthouse Scores Target:
- **Performance:** 95+
- **Accessibility:** 100
- **Best Practices:** 100
- **SEO:** 100

### Tips:
1. Compress all images before upload
2. Use modern image formats (WebP if supported)
3. Enable Netlify's asset optimization (automatic)

## 🛠️ Maintenance

### Regular Updates:
1. **Add new project photos** - Replace `project-X.jpg` files monthly
2. **Update service areas** if expanding coverage
3. **Review form submissions** weekly in Netlify dashboard
4. **Monitor performance** with Google Analytics (optional)

## 🔧 Troubleshooting

### Form not working?
- Verify `data-netlify="true"` attribute is present
- Check Netlify Dashboard → Forms for submissions
- Ensure form `name` attribute matches exactly

### Images not loading?
- Check file paths are correct (`images/filename.jpg`)
- Verify images are in the `images/` directory
- Confirm image filenames match HTML references

### Custom domain not working?
- Wait 24-48 hours for DNS propagation
- Verify DNS records are correct
- Check Netlify DNS configuration

## 📞 Support

### Netlify Documentation:
- [Netlify Docs](https://docs.netlify.com)
- [Netlify Forms Guide](https://docs.netlify.com/forms/setup/)

## 🎉 Launch Checklist

Before going live:

- [ ] Replace all placeholder images with real drywall photos
- [ ] Update phone number in all 3 locations
- [ ] Update email address  
- [ ] Test form submission
- [ ] Verify all sections scroll smoothly
- [ ] Test on mobile device
- [ ] Run Lighthouse audit (aim for 95+ scores)
- [ ] Set up custom domain
- [ ] Enable HTTPS
- [ ] Configure form email notifications
- [ ] Submit sitemap to Google Search Console

---

**Built for Lejit Drywall**

*Professional drywall services in Southern Ontario*

**Website Type:** Single-page scrolling  
**Framework:** Pure HTML/CSS/JS (no dependencies)  
**Hosting:** Netlify  
**Forms:** Netlify Forms (no backend needed)
