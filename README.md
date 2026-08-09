# Portfolio
Interactive developer portfolio built with HTML, Tailwind CSS, and vanilla JavaScript — featuring a blueprint-inspired design, persisted dark/light theming, and dynamic project filtering.
Nandan K — Developer Portfolio

A personal developer portfolio designed around a blueprint/schematic visual theme — grid-paper backgrounds, registration-mark corner brackets, dimension-line dividers, and spec-sheet style cards. Built with semantic HTML5, Tailwind CSS, and vanilla JavaScript, with no framework and no build step.



Features
🌓 Dark / light theme toggle — "blueprint navy" and "vellum drafting-paper" themes, persisted with localStorage
🧩 Dynamic project filtering — filter projects by tag (Data Viz / AI-ML / UI-UX) with plain JS, no libraries
✨ Scroll-reveal animations — powered by IntersectionObserver, respects prefers-reduced-motion
✅ Accessible contact form — client-side validation (required fields, email format, min length) with inline error messages
📱 Fully responsive — mobile-first layout, tested from 375px to desktop
⌨️ Keyboard accessible — visible focus states on all interactive elements
Tech Stack
HTML5 (semantic markup)
Tailwind CSS (via Play CDN)
Vanilla JavaScript (ES6+) — no frameworks
Google Fonts: Space Grotesk, Inter, JetBrains Mono
Project Structure
portfolio-site/
└── index.html   # everything — markup, styles, and script — in one file
Getting Started

Theme colors: all colors are CSS custom properties defined in :root and html[data-theme="light"] at the top of the <style> block — change them there to re-theme the whole site.
Deployment

Author

Nandan K Frontend Engineer · Bengaluru, India LinkedIn · GitHub · nandankrish20@gmail.com

License

This project is open for personal reference. Feel free to fork it for your own portfolio, but please don't copy the content verbatim.
