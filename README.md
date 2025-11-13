# Awards – Gaming Landing Page

Modern landing page built with React, Vite, and Tailwind CSS. It features animated sections (Hero, Products, Contact), responsive layout, and assets served from an app-level public directory.

![Hero Preview](/src/public/img/heroPreview.png)

**Tech Stack**
- React + Vite
- Tailwind CSS (via `@tailwindcss/vite`)
- `react-icons`

**Getting Started**
- Install: `npm install`
- Run dev: `npm run dev` then open `http://localhost:5176`
- Build: `npm run build`

**Assets Configuration**
- Public assets live under `src/public` and are served from `/` due to `publicDir: 'src/public'` in `vite.config.js`.
- Examples:
  - Images: `/img/contact-1.webp`
  - Video: `/videos/hero-1.mp4`
  - Audio: `/audio/loop.mp3`

**Key Files**
- `src/components/Contacts.jsx` – Contact section layout and images
- `src/components/Footer.jsx` – Footer with social links and icons
- `src/index.css` – Tailwind base styles and any custom utilities




**Troubleshooting**
- If media (videos/audio) 404 or show `net::ERR_ABORTED`, ensure files exist under `src/public` and paths use absolute public URLs like `/videos/hero-1.mp4`.
- If an icon fails with `ReferenceError`, confirm imports from `react-icons/fa` in `Footer.jsx`.

**License**
- For personal/demo use unless otherwise specified.
