# SEO Setup Guide - Your Action Plan

## ✅ What's Already Done

Your portfolio now has:
- SEO-optimized meta tags in index.html
- Open Graph tags for social media previews
- Structured data (JSON-LD) for search engines
- robots.txt, sitemap.xml, manifest.json, .htaccess

---

## 🎯 What You Need to Do Now

### STEP 1: Update Your Domain (5 minutes)

Replace `https://utsavsingh.dev/` with your actual domain in these 3 files:

**File 1: index.html**
- Open index.html
- Find lines 20-40 (in `<head>` section)
- Replace all instances of `https://utsavsingh.dev/`
- Save

**File 2: sitemap.xml**
- Open sitemap.xml
- Replace all `<loc>https://utsavsingh.dev/` URLs
- Update `<lastmod>` dates to today's date
- Save

**File 3: robots.txt**
- Open robots.txt
- Replace the Sitemap URL
- Save

**Don't have a domain?** Use GitHub Pages URL: `https://yourusername.github.io/`

### STEP 2: Create Social Media Images (15 minutes)

**Option A: Use Canva (Recommended)**
1. Go to https://www.canva.com/ and sign up (free)
2. Click "Create a design" → "Custom size" → 1200 x 630 px
3. Design your image:
   - Background: Dark blue (#0a192f)
   - Add text: Your name (large), "Software Engineer" (medium)
   - Add: "Python • Django • React" (small)
   - Optional: Add your photo
4. Download as JPG → Save as `og-image.jpg`
5. Duplicate, resize to 1200 x 675 px → Save as `twitter-image.jpg`
6. Upload both to your website root folder

**Option B: Skip for now**
- You can add images later
- Portfolio will still work without them

### STEP 3: Generate Favicons (5 minutes)

1. Go to https://realfavicongenerator.net/
2. Upload your logo or a photo
3. Click "Generate favicons"
4. Download the package
5. Extract and upload these files to your root folder:
   - favicon.ico
   - apple-touch-icon.png
   - favicon-32x32.png
   - favicon-16x16.png
   - android-chrome-192x192.png
   - android-chrome-512x512.png

### STEP 4: Submit to Google (10 minutes)

**Google Search Console:**
1. Go to https://search.google.com/search-console
2. Click "Add property"
3. Enter your domain
4. Choose verification method (HTML file upload is easiest)
5. Upload verification file to your website
6. Click "Verify"
7. Go to "Sitemaps" in left menu
8. Enter: `sitemap.xml`
9. Click "Submit"

**Bing (Optional):**
1. Go to https://www.bing.com/webmasters
2. Follow same process as Google

### STEP 5: Optimize Performance (10 minutes)

**Compress Images:**
1. Go to https://tinypng.com/
2. Upload all your images
3. Download compressed versions
4. Replace original images

**Test Speed:**
1. Go to https://pagespeed.web.dev/
2. Enter your website URL
3. Check score (aim for 90+)
4. Fix any issues shown

### STEP 6: Share Your Portfolio (5 minutes)

Add your portfolio link to:
- [ ] LinkedIn profile (in contact info and about section)
- [ ] GitHub profile README
- [ ] Twitter/X bio
- [ ] Email signature
- [ ] Resume

Post about it on:
- [ ] LinkedIn (announce your new portfolio)
- [ ] Twitter/X
- [ ] Reddit (r/webdev, r/portfolios)
- [ ] Dev.to

### STEP 7: Set Up Analytics (Optional - 10 minutes)

**Google Analytics 4:**
1. Go to https://analytics.google.com/
2. Create account and property
3. Get tracking code
4. Add this code before `</head>` in index.html:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

Replace `G-XXXXXXXXXX` with your tracking ID

---

## 📊 What to Expect

**Week 1-2:**
- Site indexed by Google
- Appear in search for your name

**Month 1:**
- Start getting organic traffic
- Professional social media previews

**Month 2-3:**
- Ranking improvements
- More keyword rankings

**Month 3-6:**
- Steady growth
- Competing for competitive keywords

---

## 🔄 Monthly Maintenance

Do this once a month:
- [ ] Check Google Search Console for errors
- [ ] Update sitemap dates if you added content
- [ ] Add new projects/achievements
- [ ] Test page speed
- [ ] Share new content on social media

---

## 🔗 Essential Links

**Must-Have Tools:**
- Google Search Console: https://search.google.com/search-console
- Google Analytics: https://analytics.google.com/
- PageSpeed Insights: https://pagespeed.web.dev/
- TinyPNG (compress images): https://tinypng.com/
- Canva (create images): https://www.canva.com/
- Favicon Generator: https://realfavicongenerator.net/

**Testing Tools:**
- Meta Tags Checker: https://metatags.io/
- Mobile-Friendly Test: https://search.google.com/test/mobile-friendly
- Schema Validator: https://validator.schema.org/

---

## 🆘 Troubleshooting

**Not appearing in Google?**
- Wait 1-2 weeks after submitting sitemap
- Check robots.txt allows crawling
- Verify in Search Console

**Social preview not showing?**
- Ensure og-image.jpg is uploaded
- Test with https://www.opengraph.xyz/
- Clear cache on social media

**Slow page speed?**
- Compress all images
- Minify CSS/JS
- Enable HTTPS

---

## ✅ Quick Checklist

```
TODAY:
[ ] Update domain URLs (3 files)
[ ] Create social images
[ ] Generate favicons
[ ] Upload all files

THIS WEEK:
[ ] Submit to Google Search Console
[ ] Set up Google Analytics
[ ] Compress images
[ ] Test page speed
[ ] Share on social media

MONTHLY:
[ ] Check Search Console
[ ] Update content
[ ] Monitor analytics
```

---

**Questions?** Check Google Search Console for specific errors and recommendations.
