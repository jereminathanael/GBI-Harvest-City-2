# GBI Harvest City 2 🌾

A multi-page church profile website for **GBI Harvest City 2**, built with HTML, Bootstrap, and SCSS for custom styling.

---

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)

- **HTML5** — page structure and content
- **Bootstrap CSS** — responsive layout and components
- **SCSS** — custom class overrides and styling extensions on top of Bootstrap

---

## Pages (12 Pages)

| # | Page | File |
|---|---|---|
| 1 | Home | `index.html` |
| 2 | Hubungi Kami | `public/hubungi-kami.html` |
| 3 | Tentang Gereja | `public/tentang/tentang-gereja.html` |
| 4 | Lokasi | `public/tentang/lokasi.html` |
| 5 | Gembala Sidang | `public/tentang/gembala-sidang.html` |
| 6 | Pembaptisan | `public/pelayanan/pembaptisan.html` |
| 7 | Penghiburan | `public/pelayanan/penghiburan.html` |
| 8 | Penyerahan Anak | `public/pelayanan/penyerahan-anak.html` |
| 9 | Ibadah Youth | `public/ibadah-youth.html` |
| 10 | Komsel | `public/komsel.html` |
| 11 | Kegiatan | `public/kegiatan/` |
| 12 | Pelayanan (list) | `public/pelayanan/` |

---

## Getting Started

No framework or build tools required for just viewing. Open directly in browser:

```bash
# Clone the repository
git clone https://github.com/jereminathanael/GBI-Harvest-City-2.git
cd GBI-Harvest-City-2

# Open homepage
open index.html
```

### SCSS Compilation (optional)

If you want to modify the SCSS and recompile:

```bash
npm install
npm run build
```

This compiles `main.scss` → `style.css`.

---

## Project Structure

```
.
├── assets/          # Images and media files
├── css/             # Compiled CSS output
├── fonts/           # Custom fonts
├── public/
│   ├── kegiatan/    # Kegiatan pages
│   ├── pelayanan/   # Pelayanan pages (pembaptisan, penghiburan, penyerahan-anak)
│   ├── tentang/     # Tentang pages (tentang-gereja, lokasi, gembala-sidang)
│   ├── ibadah-youth.html
│   ├── komsel.html
│   └── hubungi-kami.html
├── index.html       # Home page
├── main.scss        # SCSS source file
├── style.css        # Compiled CSS
└── package.json
```