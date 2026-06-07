<div align="center">

# ✨ Simple Personal Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![Particles.js](https://img.shields.io/badge/Particles.js-00C9A7?style=for-the-badge&logo=javascript&logoColor=white)

<br>

![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![Responsive](https://img.shields.io/badge/Responsive-Yes-blue?style=flat-square)
![License](https://img.shields.io/badge/License-All_Rights_Reserved-red?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-Welcome-orange?style=flat-square)

<br>

A personal portfolio website showcasing work experience, education, projects, skills, and contact information.<br>Built with pure HTML, CSS, and JavaScript — no frameworks, no build tools.

</div>

---

## 📑 Live Sections

| Section | Description |
|:--------|:------------|
| **Home** | Hero area with name, introduction, and call-to-action buttons (Download CV, Contact Me) |
| **Experience** | Interactive timeline layout with alternating left/right cards for work history |
| **Education** | Responsive grid of education cards with degree, university, and date details |
| **Projects** | Featured project cards with thumbnail images, tech-stack tags, and action links |
| **Skills** | Categorized progress bars across Frontend, Backend, Tools & Technologies, and Soft Skills |
| **Contact** | Split layout with contact details (email, phone, location) alongside a message form |

---

## ⚙️ Tech Stack

| Technology | Badge | Usage |
|:-----------|:------|:------|
| HTML5 | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Semantic markup, single-page structure with anchor navigation |
| CSS3 | ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Grid, Flexbox, glassmorphism, gradients, box shadows |
| JavaScript | ![JS](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Mobile sidebar toggle, popup disclaimer modal |
| Particles.js | ![Particles](https://img.shields.io/badge/-Particles.js-00C9A7?style=flat-square&logo=javascript&logoColor=white) | Animated particle background via CDN (v2.0.0) |
| Font Awesome | ![FA](https://img.shields.io/badge/-Font_Awesome-528DD7?style=flat-square&logo=fontawesome&logoColor=white) | Icon set loaded via Kit CDN |

---

## 📁 Project Structure

```
protoflio/
├── 📄 index.html              # Main single-page portfolio
├── 🔒 .htaccess               # Apache server config (caching, security)
└── 📂 assets/
    ├── 🎨 css/
    │   └── style.css           # All styles (~708 lines)
    ├── 🖼️ photo/
    │   ├── shopsmart.png       # Project screenshot
    │   ├── taskflow.png        # Project screenshot
    │   └── wellness.png        # Project screenshot
    └── 📝 resume/
        └── res.html            # Standalone printable resume page
```

---

## 🎨 Design Highlights

| Feature | Details |
|:--------|:--------|
| **Dark Gradient Theme** | `linear-gradient(to right, #0f2027, #203a43, #2c5364)` with a fixed particle canvas |
| **Glassmorphism Cards** | `backdrop-filter: blur(8px)` with transparent backgrounds on all card types |
| **Gradient Accent Bars** | Section title underlines using `linear-gradient(to right, #7669bf, #5187b8, #10bcaa)` |
| **Skill Progress Bars** | Gradient-filled bars with percentage labels for each skill |
| **Grayscale → Color Hover** | Project thumbnails render in grayscale, reveal full color on hover |
| **CTA Button Effects** | Background and text color invert with smooth `0.5s` transition |

---

## 📱 Responsive Behavior

Three breakpoints are implemented:

| Breakpoint | Changes |
|:-----------|:--------|
| `≤ 1210px` | 📐 Reduced nav spacing and font size |
| `≤ 1000px` | ☰ Hamburger sidebar replaces horizontal nav with animated toggle bars |
| `≤ 768px` | 📱 Stacked hero, single-column timeline, full-width contact form, smaller section titles |

---

## 🔒 Server Configuration (`.htaccess`)

- 🚫 Blocks access to `.htaccess`, `.htpasswd`, `.ini`, `.log` files
- ⚡ Sets `Cache-Control` headers (1-month cache for images, CSS, JS)
- 📂 Disables directory listing (`Options -Indexes`)
- 🔐 Protects `ip_log.txt` from public access

---

## 📄 Resume Page

A separate standalone HTML page at `assets/resume/res.html` with fully self-contained styles. Includes career objective, education history, hard/soft skills, and technical project descriptions. Designed for clean printing.

---

## 📜 License

© 2025 Suresh Shrestha. All rights reserved.

---

<div align="center">

**⭐ If you like this project, give it a star!**

![Made with Love](https://img.shields.io/badge/Made_with-❤️-green?style=for-the-badge)
![Made in Nepal](https://img.shields.io/badge/Made_in-Nepal_🇳🇵-blue?style=for-the-badge)

</div>
