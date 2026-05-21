# Velvet Coke

Personal portfolio of Dantell — a multidisciplinary creative site spanning photography, music, and visual work.

**Live:** [velvetcoke.com](https://velvetcoke.com)

---

## What this is

Velvet Coke is a personal portfolio site built with [Astro](https://astro.build) and hosted on [Vercel](https://vercel.com). It serves as a home for analog photography, music, and other creative output — built with the same intentionality as the work it presents.

---

## Stack

| Layer | Tool |
|---|---|
| Framework | [Astro](https://astro.build) |
| Hosting | Vercel |
| Music embeds | SoundCloud |
| Fonts | IBM Plex Mono (primary) |
| Styling | Custom CSS with dark/light toggle |

---

## Design

- **Dark-first aesthetic** — black background, purple and green accents
- **Font blitz animation** — scroll/touch/click-triggered, weighted random font cycling that settles on IBM Plex Mono
- **Analog photography grid** — 4-column layout inspired by Sol LeWitt, with lightbox and keyboard navigation
- **Dark/light toggle** — switchable theme
- **Scrollable homepage** with video section

---

## Project structure

```
/
├── public/             # Static assets (images, fonts, etc.)
├── src/
│   ├── components/     # Reusable Astro components
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

---

## Local development

```bash
npm install       # Install dependencies
npm run dev       # Start dev server at localhost:4321
npm run build     # Build for production → ./dist/
npm run preview   # Preview production build locally
```

---

## Deployment

Deployed automatically to Vercel on push to `main`.

---

## License

Personal work. Not open for reuse without permission.
