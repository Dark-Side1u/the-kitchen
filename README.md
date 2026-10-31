# The Kitchen

**Free frontend-only restaurant website template** by [Ruvexel](https://ruvexel.vercel.app/).

A polished multi-page site for a fictional Portuguese-Mediterranean restaurant in Lisbon. Built with plain HTML, CSS, and JavaScript — no frameworks, no build step, ready to customize or ship as a static site.

[Live preview](https://the-kitchen-smoky.vercel.app/) · [Ruvexel studio](https://ruvexel.vercel.app/) · [Request a paid backend](https://ruvexel.vercel.app/contact)

---

## What’s included

| Page | Purpose |
| --- | --- |
| `index.html` | Hero, story, featured dishes, room atmosphere, hours + map |
| `menu.html` | Full menu with tabs (petiscos, grill, sides, desserts, drinks) |
| `about.html` | Studio story, values, team |
| `reservations.html` | Reservation request form (frontend demo) |
| `contact.html` | Contact details + enquiry form (frontend demo) |

**Stack:** HTML · CSS · JavaScript  
**Fonts:** Newsreader + Sora (Google Fonts)  
**Imagery:** Unsplash (hotlinked; swap for your own in production)

---

## Quick start

1. Download or clone this repository.
2. Open `index.html` in a browser, **or** serve locally:

```bash
npx --yes serve . -p 4173
```

3. Edit copy, colours (`css/styles.css`), and images to match your brand.

No install, bundler, or Node app required for basic use.

---

## Free template vs paid backend

| | Free (this repo) | Paid backend (Ruvexel) |
| --- | --- | --- |
| Static marketing site | Yes | Yes |
| Menu / about / contact UI | Yes | Yes |
| Working reservations & inbox | Demo only (client-side) | Real bookings, email, admin |
| Auth, CMS, hosting setup | — | Included as scoped work |

This template is **frontend only**. Forms show a success state in the browser; they do not send data to a server.

Want the real thing — reservations, contact routing, CMS, or a custom backend?

**[Request a paid backend version →](https://ruvexel.vercel.app/contact)**

Or explore more work: [ruvexel.vercel.app/projects](https://ruvexel.vercel.app/projects)

---

## Customize

- **Brand & type:** CSS variables at the top of `css/styles.css`
- **Content:** Edit the HTML pages directly (real restaurant copy is already written as a starting point)
- **Menu:** Update items in `menu.html`
- **Map:** Change the embed query in `index.html` / `contact.html`
- **Favicon / credit:** Assets in `assets/` — footer credits [Ruvexel Team](https://ruvexel.vercel.app/)

---

## Project structure

```text
the-kitchen/
├── index.html
├── menu.html
├── about.html
├── reservations.html
├── contact.html
├── css/styles.css
├── js/main.js
├── assets/
├── package.json
└── README.md
```

---

## License

MIT — free to use, modify, and ship. Keep attribution in the footer when you can; it helps others find Ruvexel.

---

## Credits

Template by **[Ruvexel Team](https://ruvexel.vercel.app/)**  
Studio: [https://ruvexel.vercel.app/](https://ruvexel.vercel.app/)  
Contact / paid builds: [https://ruvexel.vercel.app/contact](https://ruvexel.vercel.app/contact)
