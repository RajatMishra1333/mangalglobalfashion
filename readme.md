# 🧥 Mangal Global Fashion — Link-in-Bio Page

A lightweight, animated **link-in-bio / social landing page** for Mangal Global Fashion, a winter garment manufacturing brand based in Ludhiana, Punjab, India.

---

## 📁 Project Structure

```
├── index.html       # Main HTML file (link-in-bio page)
├── style.css        # All styles including animations, layout, and responsive design
└── README.md        # This file
```

---

## ✨ Features

- 🌟 **Parallax star/pixel background animation** — Three-layer animated background using `#stars1`, `#stars2`, `#stars3`
- 🖼️ **Profile picture popup** — Click the logo to open a popup with product categories
- 🔗 **Social & business links** — LinkedIn, Facebook, Instagram, Google Maps, and Website
- 📱 **Responsive design** — Mobile-friendly layout
- ⚡ **No frameworks** — Pure HTML + CSS, no JavaScript libraries needed

---

## 🔗 Links Included

| Platform   | URL |
|------------|-----|
| LinkedIn   | [mangal-global-fashion](https://www.linkedin.com/in/mangal-global-fashion/) |
| Facebook   | [Mangal Global Fashion](https://www.facebook.com/share/1BHnmETLP8/) |
| Instagram  | [@mangal_global](https://www.instagram.com/mangal_global) |
| Google Maps | [View Location](https://www.google.com/maps/place/Mangal+Global+Fashion/@30.9528833,75.8817418,17z) |
| Website    | [mangalglobalfashion.com](https://mangalglobalfashion.com/) |

---

## 🛠️ Setup & Usage

No build tools or installation needed. Just open `index.html` in a browser.

```bash
# Clone or download the project
# Then simply open the file:
open index.html
```

Or deploy directly to any static hosting:
- **GitHub Pages** — Push to a repo and enable Pages
- **Netlify / Vercel** — Drag and drop the folder
- **cPanel / Hostinger** — Upload via File Manager

---

## 🎨 Customization

### Changing Links
Edit the `<div id="links">` section in `index.html`:
```html
<a class="link" href="YOUR_URL" target="_blank">
  <i class="fas fa-icon-name">&nbsp;</i>Label
</a>
```

### Changing Icons
Icons use **Font Awesome 5**. Browse available icons at [fontawesome.com/icons](https://fontawesome.com/icons).

### Changing Profile Image
Replace the image `src` URL in both:
1. `<a id="profilePicture">` section
2. `<div class="overlay" id="popup">` section

### Changing Product Categories (Popup Text)
Edit the `.popup-quote` div:
```html
<div class="popup-quote">
  Cardigan · Coat · Blazer · China Frock · Computer Frock · Knitwear
</div>
```

---

## 📦 Dependencies

| Library | Version | Purpose |
|--------|---------|---------|
| [Font Awesome](https://fontawesome.com/) | 5.8.1 | Social & UI icons |

No npm packages. No build step. No frameworks.

---

## 🏭 About Mangal Global Fashion

Mangal Global Fashion is a winter garment manufacturer based in **Ludhiana, Punjab, India**, specializing in:

- Cardigans & Knitwear
- Ladies' Coats & Blazers
- China Frocks & Computer Frocks
- Woollen Shawls & Thermal Innerwear

🌐 [mangalglobalfashion.com](https://mangalglobalfashion.com)

---

## 👨‍💻 Maintained By

**Rajat** — Digital Head & Social Media, Mangal Global Fashion  
GitHub: [@RajatMishra1333](https://github.com/RajatMishra1333)
