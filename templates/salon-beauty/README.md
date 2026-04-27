# Salon & Beauty Template

A beautiful, feminine website template for salons, spas, and beauty businesses.

## Template Location
`/templates/salon-beauty/index.html`

## Features

- **Soft pink gradient design** — feminine and inviting
- **Service cards with pricing** — Hair, nails, facials, massage
- **Photo gallery** — Showcase transformations and styles
- **Online booking form** — Service selection, date picker, special requests
- **Testimonials section** — Build trust with reviews
- **Social media links** — Instagram, Facebook integration ready

## What to Customize

### 1. Company Information (Find and Replace All)
- `[SalonName]` → Your actual salon name
- `(555) 123-4567` → Your phone number
- `hello@[salon].com` → Your email
- `123 Beauty Lane, City, State 12345` → Your address
- Update hours if different

### 2. Services & Pricing
Update the service cards with your actual offerings:
```html
<div class="service-card">
    <div class="service-img">💇</div>
    <div class="service-content">
        <h3>Hair Styling</h3>
        <p>Your description here</p>
        <div class="service-price">From $XX</div>
    </div>
</div>
```

**Service icons** (change in .service-img):
- 💇 Hair
- 💅 Nails
- ✨ Spa/Facial
- 💆 Massage
- 💄 Makeup
- 👁️ Lashes/Brows

### 3. Photos (Gallery Section)
Replace the placeholder `[Photo X]` with actual images:

```html
<div class="gallery-item">
    <img src="images/hairstyle1.jpg" alt="Beautiful balayage hairstyle">
</div>
```

**Photo recommendations:**
- Before/after transformations
- Nail art designs
- Facial treatments
- Salon interior
- Team photos
- Happy clients (with permission)

### 4. Testimonials
Replace the placeholder testimonials with real ones:

```html
<div class="testimonial-card">
    <div class="stars">⭐⭐⭐⭐⭐</div>
    <p class="testimonial-text">"Actual client quote here"</p>
    <p class="testimonial-author">— Client Name</p>
</div>
```

### 5. Booking Form
The form submits to `#` (nowhere) by default. To make it work:

**Option A: Formspree (Easiest)**
1. Go to https://formspree.io
2. Create a form
3. Replace `action="#"` with your Formspree URL

**Option B: Square Appointments / Fresha**
Embed their booking widget instead of the custom form.

**Option C: Acuity Scheduling / Calendly**
Link to external booking page with `a href="your-booking-link"`.

### 6. Social Media Links
Update the footer social links:

```html
<div class="social-links">
    <a href="https://instagram.com/yoursalon">IG</a>
    <a href="https://facebook.com/yoursalon">FB</a>
    <a href="https://tiktok.com/@yoursalon">TT</a>
</div>
```

## Color Scheme

**Current colors (pink/coral theme):**
- Primary gradient: `#ff9a9e` → `#fecfef`
- Accent: `#ff6b6b` (coral)
- Text: `#333` (dark gray)
- Background: `#fafafa` (light gray)

To change: Edit the CSS gradients in the `<style>` section.

**Alternative color schemes:**
- **Luxury/Black:** Change to black/gold
- **Natural/Organic:** Change to green/beige
- **Cool/Modern:** Change to blue/purple

## Pricing This Template

**Suggested client pricing:**
- Template setup + customization: $1,500-2,000
- Photo gallery population: +$300
- Booking system integration: +$500
- Instagram feed integration: +$300
- **Total package: $2,600-3,100**

## SEO Checklist

- [ ] Update page title
- [ ] Add meta description
  ```html
  <meta name="description" content="[Salon Name] offers luxury hair, nail, and spa services in [City]. Book your appointment online today!">
  ```
- [ ] Add Google Business Profile link
- [ ] Set up Google Analytics
- [ ] Submit to Google Search Console

## Making It Live

Same as other templates:
1. GitHub Pages (free)
2. Netlify (free)
3. Your own domain + hosting

## Files Included

- `index.html` — Complete website
- `README.md` — This file

**Optional additions:**
- `/images/` folder for photos
- Separate CSS file for easier editing
- JavaScript for interactive features

## Support

Need help customizing? Contact Lakefront Digital:
- 📧 lakehannah@hotmail.com
- 🌐 https://lakehannah.github.io/lakefront-digital

---

**Template Version:** 1.0  
**Created:** April 2026  
**Built by:** Lakefront Digital
