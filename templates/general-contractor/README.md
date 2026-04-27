# General Contractor Template

A professional website template for general contractors, builders, and construction companies.

## Template Location
`/templates/general-contractor/index.html`

## What to Customize

### 1. Company Information (Find and Replace All)
- `[Company Name]` → Your actual company name
- `(555) 123-4567` → Your phone number
- `info@company.com` → Your email
- `123 Main Street, City, State 12345` → Your address
- Update hours if different

### 2. Badges/Trust Signals (Hero Section)
Edit these to match your actual credentials:
- `15+ Years Experience` → Your actual years
- `100+ Projects Completed` → Your actual count
- Add other badges like:
  - "BBB A+ Rated"
  - "Licensed #123456"
  - "Bonded & Insured"

### 3. Photos (Portfolio Section)
Replace the placeholder `[Project Photo]` text with actual images:

```html
<div class="portfolio-img">
    <img src="images/kitchen-remodel.jpg" alt="Kitchen remodel project">
</div>
```

**Photo recommendations:**
- Before/after shots (high impact)
- Team photos (builds trust)
- Completed projects
- Work-in-progress shots

### 4. Services
Modify the services grid to match what you actually offer:
- Add/remove service cards
- Change icons (use emoji or add custom icons)
- Update descriptions

### 5. Contact Form
The form submits to `#` (nowhere) by default. To make it work:

**Option A: Formspree (Easiest - Free)**
1. Go to https://formspree.io
2. Sign up and create a form
3. Replace `action="#"` with your Formspree URL:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

**Option B: Netlify Forms**
If hosting on Netlify, just add `netlify` attribute:
```html
<form name="quote" netlify>
```

**Option C: Custom Backend**
Connect to your own server/email service.

## Color Scheme

Current colors (easy to change in CSS):
- **Primary:** `#f4a261` (orange accent) - change this for brand color
- **Secondary:** `#e76f51` (coral - hover states)
- **Dark:** `#1a1a2e` (navy header/footer)
- **Gray:** `#2d3436`, `#636e72` (portfolio cards)

To change: Search and replace in the CSS section.

## Making It Live

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload these files
3. Enable Pages in Settings
4. URL: `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)
1. Go to https://app.netlify.com/drop
2. Drag folder onto the page
3. Instant live site + free SSL

### Option 3: Your Own Domain
1. Buy domain (Namecheap, Google Domains, etc.)
2. Point to hosting (GitHub Pages, Netlify, or your server)
3. Update DNS settings

## Mobile Optimization

✅ Template is fully responsive
✅ Click-to-call phone number
✅ Easy-to-tap buttons
✅ Fast loading

## SEO Checklist

- [ ] Update page title (`<title>` tag)
- [ ] Add meta description (add to `<head>`)
  ```html
  <meta name="description" content="[Company Name] provides quality construction and remodeling services in [City]. Licensed & insured. Free estimates.">
  ```
- [ ] Add Google Analytics (optional)
- [ ] Submit to Google Search Console
- [ ] Add Google Business Profile link

## Pricing This Template

**Suggested client pricing:**
- Setup + customization: $1,500-2,500
- Content population (photos, text): +$500
- Domain + hosting (1 year): +$200
- **Total package: $2,200-3,200**

## Files Included

- `index.html` - Complete website (single file)
- `README.md` - This file

**Optional additions:**
- Create `/images/` folder for photos
- Add `style.css` for easier editing (separate from HTML)
- Add `script.js` for interactive features

## Customization Service

Don't want to DIY? Lakefront Digital can customize this template for you.

Contact: lakehannah@hotmail.com

---

**Template Version:** 1.0  
**Created:** April 2026  
**Built by:** Lakefront Digital (https://lakehannah.github.io/lakefront-digital)
