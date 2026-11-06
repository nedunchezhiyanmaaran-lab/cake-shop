# Cake Atelier — Haute Pâtisserie

A luxury, editorial web experience for **Cake Atelier**, showcasing bespoke handcrafted tiered celebration cakes, seasonal flavours, and artisanal pastry design.

---

## ✨ Features

- **Artisanal Typography & Palette**: Built with *Cormorant Garamond* and *Manrope*, styled with an haute-couture palette (`--cocoa`, `--ivory`, `--gold`, `--rose`, `--beige`, `--choc`).
- **Curated High-Resolution Photography**: 26 verified, unique culinary images distributed across the Hero, Gallery, Flavours, Process, and Ambience sections.
- **Lenis Slow Momentum Scroll**: Silky-smooth inertia scrolling with dampened wheel speed (`wheelMultiplier: 0.6`) and extended glide duration (`2.2s`) to let visitors linger on the imagery.
- **GSAP & ScrollTrigger Animations**:
  - Interactive 3D mouse parallax on the hero arch
  - Dynamic word-by-word scroll lighting on the Atelier philosophy
  - Pinned centerpiece presentation with floating editorial notes
  - Staggered clip-path reveal on gallery items
  - Magnetic cursor with contextual `"VIEW"` modal triggers on desktop
- **Interactive Commissions Gallery**: 12 custom cake commissions categorized into *Birthday Cakes*, *Celebration Cakes*, and *Custom Designs*, backed by an accessible Lightbox dialog with keyboard navigation (`Esc`, `←`, `→`).
- **Artisanal Menu & Flavours**: 5 signature flavour profiles with arched cake-slice imagery and transparent starting prices.
- **Interactive Ordering Process**: 5 numbered stages featuring alternating arched craftsmanship photography.
- **Enquiry Form**: Complete with date validation (today or future), collection times, servings calculator, flavour selector, budget field, and drag-and-drop file upload preview.
- **WhatsApp Direct Integration**: Quick order confirmation trigger with pre-populated enquiry parameters.
- **Full Responsiveness**: Optimized across mobile phones, tablets, and wide desktop screens.

---

## 📁 Repository Structure

```
cake-shop/
├── index.html              # Main website document
├── lenis.min.js            # Offline-ready Lenis smooth scrolling library
├── README.md               # Project documentation
└── images/                 # 26 high-resolution photography assets
    ├── hero-cake.jpg
    ├── feature-cake.jpg
    ├── ambience-atelier.jpg
    ├── ambience-final.jpg
    ├── flavour-01-vanilla.jpg ... flavour-05-strawberry.jpg
    ├── step-01-explore.jpg ... step-05-confirm.jpg
    └── gallery-01-blush-buttercream.jpg ... gallery-12-naked-sponge.jpg
```

---

## 🚀 Getting Started

No build step or package manager is required. The project is completely self-contained with zero compile steps.

### Method 1: Local HTTP Server (Recommended)
```bash
# Using Python
python -m http.server 8080

# Or using Node (http-server / npx serve)
npx serve .
```
Then visit [http://localhost:8080](http://localhost:8080) in your browser.

### Method 2: Direct File Open
Double-click `index.html` to open it in any modern browser (Chrome, Safari, Edge, Firefox). All image links and scripts are relative.

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla CSS3** (CSS Variables, Grid, Safe Area insets)
- **JavaScript (ES6+)**
- **GSAP 3.12.5 & ScrollTrigger**
- **Lenis 1.1.20** (Smooth Momentum Scrolling)
- **Google Fonts** (*Cormorant Garamond* & *Manrope*)
