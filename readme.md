#  La Mamma — Tunisian Restaurant Website

A responsive restaurant webpage built with **HTML**, **CSS**, and **Bootstrap 5**, themed around authentic Tunisian cuisine. All prices are displayed in **Tunisian Dinar (DT)**.

---

##  Project Overview

**La Mamma** ("House of the Olive Tree") is a fictional Tunisian fine-dining restaurant located in the Médina of Tunis. This project demonstrates a fully responsive, multi-section restaurant website using Bootstrap's grid system and custom CSS styling.

---

##  File Structure

```
project/
│
├── restaurant.html      # Main HTML file (single-file project)
└── README.md            # Project documentation
```

> All CSS is embedded in a `<style>` block inside `index.html`. No external CSS file is required.

---

##  How to Run

1. Download or clone the project files.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No build tools, no server, no installation required — it works offline.

```bash
# Option: open directly from terminal (macOS/Linux)
open index.html

# Option: open directly from terminal (Windows)
start index.html
```

---

##  Technologies Used

| Technology | Version | Purpose |
|---|---|---|
| HTML5 | — | Page structure & content |
| CSS3 | — | Custom theming & animations |
| Bootstrap | 5.3.2 | Grid system, responsive layout, components |
| Bootstrap Icons | 1.11.3 | Social media & contact icons |
| Google Fonts | — | Cormorant Garamond + Josefin Sans |

All external libraries are loaded via **CDN** — no npm or local installation needed.

---

##  Bootstrap Grid Usage

The project makes extensive use of Bootstrap's 12-column grid system:

| Section | Grid Classes Used | Layout |
|---|---|---|
| Navbar | `container`, `navbar-nav` | Flexbox nav, collapses on mobile |
| Menu | `col-12 col-md-6 col-lg-4` | 1 col → 2 col → 3 col |
| About Us | `col-12 col-lg-5` / `col-lg-7` | 1 col → 2 col (image + text) |
| Contact | `col-12 col-md-7` / `col-md-5` | 1 col → form + info side-by-side |
| Footer | `col-12 col-md-4` × 3 | 1 col → 3 equal columns |

---

##  Menu — Tunisian Dishes

| Dish | Price (DT) |
|---|---|
| Couscous Tunisien | 28,500 DT |
| Brik à l'Œuf | 9,900 DT |
| Lablabi | 11,500 DT |
| Tajine Tunisien | 16,000 DT |
| Makroudh au Miel | 7,500 DT |
| Thé à la Menthe & Pignons | 5,000 DT |

> Prices are displayed in **Tunisian Dinar (DT)** format (e.g. `28,500 DT`).

---






##  License

This project is created for educational purposes. Free to use and modify.

---

