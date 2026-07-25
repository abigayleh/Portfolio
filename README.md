# Abigayle Hickey — Portfolio

Personal portfolio website showcasing experience, projects, skills, and technical blog posts.

**Live site:** [abigaylehickey.com](https://abigaylehickey.com)

---

## Stack

- **HTML5 / CSS3** — hand-authored semantic markup
- **SCSS** — compiled to CSS via Sass
- **Bootstrap 5** — layout, modals, tooltips, responsive grid
- **Vanilla JS** — Bootstrap tooltip init, contact form handling
- **Font Awesome** — icons
- **EmailJS** — contact form submissions (no backend)

---

## Structure

```
├── index.html               # Main portfolio page
├── blogs.html               # Blog listing page
├── blogs/                   # Individual blog posts
├── public/
│   ├── images/
│   │   ├── site/            # Logo, background, intro image, rocket
│   │   ├── experience/      # Company logos
│   │   └── tech-stack/      # Tech icons and skill images
│   └── videos/              # Project demo videos
├── assets/
│   └── css/                 # Compiled CSS (do not edit directly)
├── scss/                    # Source SCSS files
└── pdfs/                    # Resume
```

---

## Development

Install dependencies:

```bash
npm install
```

Compile SCSS and watch for changes:

```bash
npm run compile:sass
```

Edit `scss/` files — changes compile automatically to `assets/css/style.css`.

---

## Blogs

| Post | Topic |
|------|-------|
| Claude Code Mastery | Token management, loops, CLAUDE.md |
| Refreshing State with `isOpen &&` | React conditional rendering lifecycle |
| React Query & `invalidateQueries` | Server state after mutations |
| SCSS vs CSS vs Tailwind | Styling approach tradeoffs |
| Infinite Looping Without Glitch | Seamless marquee/carousel animation |
