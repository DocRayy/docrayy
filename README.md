# 👋 Hi, I'm Rayyan Kheisar Syaifullah

<p align="center">
  <b>Software Engineering Technology Graduate · Frontend Developer · Web Enthusiast</b><br/>
  <i>I build fast, reliable web apps end to end — from database to pixel.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-🚀_Open_to_work-4ea1a3?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Experience-2%2B%20years-f26d58?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Projects-10%2B-8fd8c8?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://docrayy.my.id" target="_blank"><img src="https://img.shields.io/badge/🌐_Website-docrayy.my.id-333?style=flat-square" /></a>
  <a href="mailto:rayyankheisar@gmail.com"><img src="https://img.shields.io/badge/✉️_Email-Say_Hi-4ea1a3?style=flat-square" /></a>
  <a href="#"><img src="https://img.shields.io/badge/💼_LinkedIn-Let's_Connect-0a66c2?style=flat-square" /></a>
  <a href="#"><img src="https://img.shields.io/badge/🐙_GitHub-view_projects-333?style=flat-square" /></a>
</p>

---

## 📋 About This Repo

This repository contains the source code for my **personal portfolio website** — a modern, animated, fully responsive single-page + multi-route site built with **Astro**. It showcases my work experience, technical skills, education, and **10+ portfolio projects**, each with its own dedicated detail page, gallery, and tech breakdown.

> ✨ **Live preview:** [https://docrayy.my.id](https://docrayy.my.id)

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Astro-7.1.6-BC52EE?style=for-the-badge&logo=astro&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.3.3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-6.0.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/GSAP-3.15.0-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />
  <img src="https://img.shields.io/badge/DaisyUI-5.7-green?style=for-the-badge" />
</p>

| Category | Technology |
| :--- | :--- |
| **Framework** | [Astro](https://astro.build) (static site generation) |
| **Styling** | Tailwind CSS v4 · DaisyUI · self-hosted Montserrat fonts |
| **Animations** | GSAP (radial FAB menu) · Tailwind animated · IntersectionObserver scroll reveals |
| **Icons** | astro-icon · Lucide · Font Awesome 6 Brands |
| **SEO** | Open Graph · Twitter Cards · JSON-LD structured data · sitemap |

---

## 🗂️ Project Structure

```
docrayy/
├── public/                 # Static assets (images, fonts, favicons, project covers)
│   ├── images/
│   │   ├── experience/     # Company logos
│   │   └── projects/       # Project covers & galleries (10 projects)
│   └── fonts/              # Self-hosted Montserrat
└── src/
    ├── components/         # Reusable UI components
    │   ├── header.astro        # Desktop fixed glass nav
    │   ├── headerMobile.astro  # Mobile bottom icon nav
    │   ├── footer.astro        # Footer w/ CTA + socials
    │   ├── ProjectCard.astro   # Reusable project card
    │   └── socialFab.astro     # GSAP radial social FAB
    ├── data/
    │   └── project.json    # Data-driven source for all projects
    ├── layouts/
    │   └── Layout.astro    # Shared layout w/ full SEO head
    ├── pages/              # Routes
    │   ├── index.astro         # Homepage
    │   ├── projects.astro      # All projects
    │   ├── projects/[id].astro # Dynamic project detail
    │   ├── blogs.astro         # Placeholder
    │   ├── journals.astro      # Placeholder
    │   └── tools.astro         # Placeholder
    └── styles/
        └── global.css      # Theme, global styles
```

---

## 🌐 Live Pages

| Route | Description |
| :--- | :--- |
| `/` | Homepage — hero, about, education, skills, experience, featured projects |
| `/projects` | Grid of all **10 portfolio projects** |
| `/projects/:id` | Individual project detail — gallery, tech sidebar, related projects |
| `/blogs` · `/journals` · `/tools` | Coming soon placeholders |

---

## ✨ Notable Features

- 🖱️ **Scroll-triggered animations** with staggered reveals
- 🗂️ **Animated tab interface** for Education / Skills / Experience
- 🌐 **GSAP-powered radial social menu** floating button
- 🧊 **Glassmorphism navigation** (top for desktop, bottom for mobile)
- 🎯 **Fully responsive** — mobile-first design
- 🗃️ **Data-driven projects** — add a new project by editing one JSON file
- 🔍 **Comprehensive SEO** — OG tags, Twitter cards, JSON-LD, canonical URLs

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** `>= 22.12.0`
- npm

### Installation & Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/docrayy.git
cd docrayy

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev        # → http://localhost:4321
```

### Build & Preview

```bash
npm run build      # Build production site to ./dist/
npm run preview    # Preview the production build locally
```

---

## 🧞 Commands

| Command | Action |
| :--- | :--- |
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview the build locally |
| `npm run astro ...` | Run CLI commands (e.g. `astro add`) |
| `npm run astro check` | Type-check the project |

---

## 📁 Portfolio Projects

| Project | Category | Tech Stack |
| :--- | :--- | :--- |
| **Ondary** | Web App | Angular · Nest.js · Electron · MySQL · Socket.io |
| **Liszthoven Web** | Website | Angular · Tailwind CSS |
| **Leazone** | Web App | Next.js · Strapi · MySQL · Midtrans · PWA |
| **CV Kilat** | Web App | Next.js · Strapi · MySQL · Midtrans |
| **SITKDN** | Web App | Laravel · MySQL |
| **AmalShare** | UI/UX Design | Figma |
| **CariCelah** | IoT + Website | Arduino · C++ · React · ESP32 |
| **Sportscamp** | UI/UX Design | Figma · Pixellab |
| **Sentra HKI Polibatam** | Web App | Laravel · Bootstrap · MySQL |
| **SIPERU** | Web App | HTML · CSS · Bootstrap · MySQL |

---

## 💼 Work Experience

| Company | Role | Period |
| :--- | :--- | :--- |
| PT. Sat Nusapersada Tbk | Frontend Developer | Feb 2026 – Aug 2026 |
| Folxcode | Frontend Developer | Aug 2025 – Jan 2026 |
| IFATIVE | Web Programmer | Sep 2024 – Apr 2025 |
| RRI Tanjungpinang | Office Engineer | Oct 2021 – Dec 2021 |

---

## 🎓 Education

- **Politeknik Negeri Batam** — Diploma IV, Software Engineering Technology (2022–2026) · **GPA 3.89**
- **SMKN 4 Tanjungpinang** — (2018–2022)

---

## 🧰 Skills

- **Frontend:** HTML · CSS · Tailwind · JavaScript · React · Next.js · Angular
- **Backend:** SQL · REST API · PHP · Node.js
- **Tools:** VS Code · Git · GitHub · Figma · Postman

---

## 🤝 Connect with Me

| Platform | Link |
| :--- | :--- |
| 🌐 **Website** | [docrayy.my.id](https://docrayy.my.id) |
| ✉️ **Email** | [rayyankheisar@gmail.com](mailto:rayyankheisar@gmail.com) |
| 💬 **WhatsApp** | [+62 896-5437-7569](https://wa.me/6289654377569) |
| 🐙 **GitHub** | [@your-username](https://github.com/) |
| 🏢 **LinkedIn** | [Rayyan Kheisar Syaifullah](https://www.linkedin.com/) |
| 📸 **Instagram** | [@your-username](https://instagram.com/) |

---

## 📄 License

This project is licensed under the MIT License. Feel free to use it as a template for your own portfolio — just give credit where it's due. 💙

---

<p align="center">
  Made with ❤️ by <b>Rayyan Kheisar Syaifullah</b> — Built with <a href="https://astro.build">Astro</a><br/>
  <sub>© 2026 · All Rights Reserved</sub>
</p>
