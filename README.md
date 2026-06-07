# R.V Cafe & Sekuwa Corner — Website

A premium, modern restaurant website for R.V Cafe & Sekuwa Corner.

## 🚀 Getting Started in VS Code

1. Open the `rv-cafe/` folder in VS Code
2. Install the **Live Server** extension (by Ritwick Dey)
3. Right-click `index.html` → **"Open with Live Server"**
4. Your website opens at `http://127.0.0.1:5500/index.html`

That's it! No build tools, no npm required. Pure HTML/CSS/JS.

---

## 📁 File Structure

```
rv-cafe/
├── index.html       ← Main website (all-in-one)
└── README.md        ← This file
```

All CSS and JavaScript is embedded in `index.html` for simplicity.

---

## ✏️ Customization Guide

### Update Phone Number
Search for `9779800000000` and replace with your actual WhatsApp number:
```
+977-9800000000 → +977-YOUR_NUMBER
```

### Update Address / Map
Replace the Google Maps embed URL in the `<iframe>` inside the contact section with your actual location embed code from:
👉 https://maps.google.com → Share → Embed a map

### Update Menu Prices
Search for `Rs.` in the file to find and update all menu prices.

### Update Social Media
- Facebook: Search `https://www.facebook.com/rvcafe/` → already correct
- Instagram: Search `instagram.com/explore/locations` → already correct

### Change Photos
Replace `src="https://images.unsplash.com/..."` URLs with your own food photos:
- Upload photos to your server or use Google Drive public links
- Recommended size: 800x600px minimum for dish cards, 1920x1080 for hero

### Update Opening Hours
Find the `footer-hours` section and edit the times.

---

## 🎨 Color Theme

Edit CSS variables at the top of `index.html`:
```css
:root {
  --orange: #FF8A3D;    /* Primary warm orange */
  --amber: #F4B942;     /* Golden accent */
  --charcoal: #222222;  /* Dark background */
  --cream: #FFF8F0;     /* Text color */
  --green: #6BAA75;     /* Fresh green accent */
}
```

---

## 📱 Features Included

- ✅ Sticky glass-effect navbar
- ✅ Full-screen hero with animated particles & smoke effect
- ✅ Scroll-triggered reveal animations
- ✅ Stats counter animation
- ✅ About section with badge & feature cards
- ✅ Signature dish cards with hover zoom
- ✅ Sekuwa collection grid
- ✅ Cafe specialty cards
- ✅ Why Choose Us section
- ✅ Auto-scrolling testimonials carousel
- ✅ Instagram-style photo gallery
- ✅ Table reservation form with toast confirmation
- ✅ Google Maps embed
- ✅ Contact section
- ✅ Full footer with hours
- ✅ Floating WhatsApp button
- ✅ Floating social widget (Facebook + Instagram)
- ✅ Mobile hamburger menu
- ✅ Fully responsive (mobile-first)

---

## 🌐 Deploying Online (Free)

### Option 1: Netlify (Recommended — easiest)
1. Go to https://netlify.com
2. Drag & drop the `rv-cafe/` folder onto their dashboard
3. Done! Get a free URL like `rv-cafe.netlify.app`

### Option 2: GitHub Pages
1. Create a GitHub repo
2. Upload `index.html`
3. Settings → Pages → Source: main branch
4. Get URL: `yourusername.github.io/rv-cafe`

### Option 3: Vercel
1. Go to https://vercel.com
2. Import GitHub repo or drag & drop folder
3. Auto-deploys on every save

---

## 📞 Support

For customization help or adding new sections, feel free to ask Claude!

Built with ❤️ for R.V Cafe & Sekuwa Corner, Kathmandu, Nepal.
