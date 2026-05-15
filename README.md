# Elite Home - Agence Immobilière à Monastir

Welcome to **Elite Home**, a professional real estate agency website built with HTML, CSS, and JavaScript.

## 🏠 About Elite Home

Elite Home is a real estate agency located in Monastir, Tunisia. We specialize in:
- **Buying & Selling** residential and commercial properties
- **Investment Opportunities** in prime locations
- **Professional Consulting** for real estate matters

## 🌐 Website Features

- **Responsive Design** - Works on mobile, tablet, and desktop
- **Bilingual Support** - French and English language toggle
- **Modern UI** - Clean, professional design with smooth animations
- **Contact Form** - Easy-to-use contact section
- **Property Listings** - Showcase your properties
- **Photo Gallery** - Beautiful image gallery
- **WhatsApp Integration** - Direct WhatsApp contact button
- **SEO Optimized** - Meta tags and Schema.org markup for better search visibility
- **Embedded Map** - Location display using OpenStreetMap

## 📁 File Structure

```
EliteHome/
├── index.html          # Main website file
├── README.md           # This documentation
└── .gitignore          # Git ignore file
```

## 🚀 How to Use

### Option 1: View Locally
1. Download the `index.html` file
2. Open it in any modern web browser

### Option 2: Deploy on GitHub Pages
1. Go to your repository settings: `https://github.com/EliteHomeSeaView/EliteHome/settings`
2. Navigate to **Pages** section
3. Select **main** branch as the source
4. Click **Save**
5. Your site will be live at: `https://EliteHomeSeaView.github.io/EliteHome/`

### Option 3: Host on Your Own Domain
Upload the `index.html` file to your web hosting provider.

## ✏️ Customization Guide

### Update Contact Information
Edit these lines in `index.html`:

```html
<!-- WhatsApp Number -->
<a href="https://wa.me/21625801607?text=...">

<!-- Contact Info -->
<div><strong>WhatsApp :</strong> +216 25 801 607</div>
<div><strong>Email :</strong> contact@elitehome.tn</div>
<div><strong>Adresse :</strong> Avenue Combattant Suprême, Monastir</div>
```

### Update Property Listings
Find the properties section and edit:

```html
<div class="property">
    <h4>Apartment Title</h4>
    <ul>
        <li>Details</li>
        <li>More details</li>
    </ul>
    <a class="btn" href="#contact">Request Info</a>
</div>
```

### Change Colors
Edit the CSS variables at the top of the `<style>` section:

```css
:root {
    --dark: #0f172a;           /* Header/Footer background */
    --gold: #fbbf24;           /* Accent color */
    --gold-dark: #f59e0b;      /* Hover state */
    --light: #f8fafc;          /* Light background */
    --white: #ffffff;          /* White */
}
```

### Update Gallery Images
Replace the image URLs in the gallery section:

```html
<img src="YOUR_IMAGE_URL" alt="Description" loading="lazy" />
```

### Add Languages
Edit the `translations` object in the JavaScript section to add new languages.

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔧 Features Breakdown

### Navigation
- Sticky header with logo
- Responsive mobile menu
- Language switcher (FR/EN)
- Smooth scrolling to sections

### Sections
- **Hero** - Eye-catching landing section
- **Services** - Your service offerings
- **Properties** - Featured real estate listings
- **Gallery** - Photo showcase
- **Contact** - Contact form and information
- **Map** - Embedded OpenStreetMap

### Interactive Elements
- Hover animations on cards
- Mobile-responsive menu toggle
- Language switcher functionality
- Contact form with validation
- WhatsApp floating button

## 📞 Contact Information

- **Phone/WhatsApp:** +216 25 801 607
- **Email:** contact@elitehome.tn
- **Address:** Avenue Combattant Suprême, Monastir, Tunisia

## 📝 Notes

- Replace placeholder contact information with your actual details
- Add real property images and descriptions
- Customize the map coordinates to your office location
- Update the Meta tags for better SEO

## 🛡️ License

This website is the property of Elite Home. All rights reserved.

---

**Last Updated:** May 2026  
**Built with:** HTML5 | CSS3 | JavaScript (Vanilla)
