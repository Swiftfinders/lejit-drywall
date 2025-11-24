# Lejit Drywall - Professional Website

A premium, high-end static website for Lejit Drywall, a professional drywall services company based in Southern Ontario.

## 🎯 Project Overview

This is a complete static website built with pure HTML, CSS, and vanilla JavaScript, designed for deployment to Netlify with custom domain support.

### Design Features:
- **Color Scheme:** Professional Black & White theme
- **Layout:** Modern, luxury positioning with clean typography
- **Responsive:** Mobile-first design (mobile, tablet, desktop)
- **Performance:** Fast loading times, optimized assets
- **SEO:** Structured data, meta tags, semantic HTML

## 📁 Project Structure

```
lejit-drywall/
├── index.html           # Homepage with hero section
├── about.html           # Company story & credentials
├── services.html        # Detailed service descriptions
├── why-us.html          # Competitive advantages & testimonials
├── portfolio.html       # Project gallery
├── quote.html           # Contact form (Netlify Forms)
├── success.html         # Form submission success page
├── 404.html             # Custom error page
├── netlify.toml         # Netlify configuration
├── css/
│   └── main.css         # Main stylesheet
├── images/              # Website images (see images/README.md)
└── assets/              # Icons, favicon (see assets/README.md)
```

## 🚀 Deployment to Netlify

### Prerequisites:
1. GitHub account
2. Netlify account (free tier works perfectly)
3. All website images added to `images/` directory

### Deployment Steps:

#### Option 1: GitHub → Netlify (Recommended)

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial Lejit Drywall website"
   git push origin main
   ```

2. **Connect to Netlify:**
   - Log in to [Netlify](https://app.netlify.com)
   - Click "Add new site" → "Import an existing project"
   - Choose "GitHub" and authorize access
   - Select the `lejit-drywall` repository

3. **Configure Build Settings:**
   - **Build command:** Leave empty (static site)
   - **Publish directory:** `.` (root directory)
   - Click "Deploy site"

4. **Your site is live!** Netlify will provide a URL like `random-name-123.netlify.app`

#### Option 2: Drag & Drop

1. Log in to [Netlify](https://app.netlify.com)
2. Drag and drop the entire project folder to Netlify dashboard
3. Site deploys instantly

### 🌐 Custom Domain Setup

1. **In Netlify Dashboard:**
   - Go to Site Settings → Domain Management
   - Click "Add custom domain"
   - Enter your domain (e.g., `lejitdrywall.com`)

2. **Configure DNS:**
   - Add Netlify's nameservers to your domain registrar, OR
   - Add these DNS records:
     ```
     Type: A Record
     Name: @
     Value: 75.2.60.5

     Type: CNAME
     Name: www
     Value: [your-site].netlify.app
     ```

3. **Enable HTTPS:**
   - Netlify automatically provisions SSL certificates
   - Wait 24-48 hours for full DNS propagation

## 📧 Netlify Forms Setup

The quote form is already configured with Netlify Forms!

### How It Works:
1. Form submissions are automatically captured by Netlify
2. Submissions appear in Netlify Dashboard → Forms
3. Email notifications can be configured in Netlify

### Configure Email Notifications:
1. Go to Site Settings → Forms → Form notifications
2. Click "Add notification" → "Email notification"
3. Enter email address: `info@lejitdrywall.com`
4. Choose "New form submission" trigger
5. Save

### Viewing Submissions:
- Dashboard → Forms → View submissions
- Export as CSV for record-keeping

## 🖼️ Adding Images

**IMPORTANT:** Before going live, add professional images to the `images/` directory.

### Required Images (see `images/README.md` for complete list):
- Hero background: `hero-bg.jpg`
- Service photos: `service-*.jpg`
- Portfolio photos: `portfolio-*.jpg`
- Team photos: `about-team.jpg`, `team-work.jpg`

### Image Sources:
- **Unsplash.com** - Free, high-quality stock photos
- **Pexels.com** - Free stock photos and videos
- **Pixabay.com** - Free stock images

Search terms: "drywall installation", "construction worker", "home renovation"

### Image Optimization:
Compress images before uploading using:
- [TinyPNG](https://tinypng.com)
- [Squoosh](https://squoosh.app)

Target: Under 500KB per image

## 🎨 Customization

### Update Contact Information

Replace placeholder phone numbers in ALL HTML files:
```
Find: (XXX) XXX-XXXX
Replace with: Your actual phone number
```

Update email:
```
Find: info@lejitdrywall.com
Replace with: Your actual email
```

### Update Company Information

1. **Business Hours** - Update in `quote.html` (right column)
2. **Service Areas** - Modify footer sections in all HTML files
3. **Years of Experience** - Update "10+ Years" if different
4. **Statistics** - Update numbers in `index.html` stats section

### Color Scheme

To modify colors, edit CSS variables in `css/main.css`:
```css
:root {
    --color-black: #000000;
    --color-white: #FFFFFF;
    --color-near-black: #1A1A1A;
    --color-light-gray: #F0F0F0;
    /* ... */
}
```

## 📱 Mobile Testing

Test responsive design at:
- Mobile: 375px, 414px
- Tablet: 768px, 1024px
- Desktop: 1280px, 1920px

Use browser DevTools or:
- [Responsively](https://responsively.app)
- [BrowserStack](https://browserstack.com)

## 🔍 SEO Checklist

- [x] Meta descriptions on all pages
- [x] Semantic HTML5 structure
- [x] Schema.org structured data (LocalBusiness)
- [x] Alt text for images (add when images are uploaded)
- [x] Mobile-friendly design
- [x] Fast page load
- [x] Sitemap (auto-generated by Netlify)
- [x] HTTPS enabled

### Generate Sitemap:
Netlify automatically creates a sitemap at `yoursite.com/sitemap.xml`

### Submit to Google:
1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add your property (website)
3. Submit sitemap URL

## 🎯 Performance

### Lighthouse Scores (Target):
- Performance: 95+
- Accessibility: 100
- Best Practices: 100
- SEO: 100

### Optimization Tips:
1. Compress all images
2. Use WebP format where supported
3. Minimize CSS/JS (already optimized)
4. Enable Netlify's asset optimization

## 🛠️ Maintenance

### Regular Updates:
1. **Portfolio** - Add new project photos monthly
2. **Testimonials** - Add new customer reviews
3. **Service Areas** - Update if expanding coverage
4. **Content** - Keep all information current

### Monitoring:
- Check form submissions weekly
- Monitor Google Analytics (if configured)
- Review Netlify Analytics dashboard

## 📞 Support & Questions

### Netlify Documentation:
- [Netlify Docs](https://docs.netlify.com)
- [Netlify Forms Guide](https://docs.netlify.com/forms/setup/)

### Common Issues:

**Forms not working?**
- Ensure `netlify` attribute is present in form tag
- Check Netlify Dashboard → Forms for submissions
- Verify form name matches exactly

**Images not loading?**
- Check file paths are correct
- Ensure images are in `images/` directory
- Verify image filenames match HTML references

**Custom domain not working?**
- Wait 24-48 hours for DNS propagation
- Verify DNS records are correct
- Check Netlify DNS configuration

## 📄 License

This website is proprietary and confidential. All rights reserved by Lejit Drywall.

## 🎉 Launch Checklist

Before going live:

- [ ] Add all images to `images/` directory
- [ ] Update phone number in all HTML files
- [ ] Update email address in all HTML files
- [ ] Create and add favicon to `assets/` directory
- [ ] Test contact form submission
- [ ] Verify all links work
- [ ] Test on mobile devices
- [ ] Run Lighthouse audit
- [ ] Set up custom domain
- [ ] Enable HTTPS
- [ ] Configure form email notifications
- [ ] Test 404 page
- [ ] Submit sitemap to Google Search Console
- [ ] Set up Google Analytics (optional)

---

**Built with ❤️ for Lejit Drywall**

*Professional drywall services in Southern Ontario*
