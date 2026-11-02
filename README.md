# KKM Restaurant Website

A static, multi-page website for **KKM (Key To More)**, a community restaurant in Odendaalsrus, Free State, South Africa. Built for the WEDE5020 portfolio of evidence (Part 1).

**Student:** Masego Moche (ST10513950)

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `home.html` | Welcome, featured dishes, testimonials, story |
| About | `about.html` | History, opening hours, team, values |
| Services | `services.html` | Fresh food, retail products, customer support |
| Menu | `menu.html` | Starters, mains, family meals, desserts, drinks |
| Gallery | `gallery.html` | Photos of food, team and dining space |
| Contact | `contact.html` | Phone, email, address, contact form |

`index.html` redirects to `home.html`.

## Features

- Responsive layout (desktop, tablet, mobile)
- "Book a Table" and "Order Now" pop-up forms on every page
- Sticky header and scroll animations
- SEO meta tags, `sitemap.xml` and `robots.txt`

## Project structure

```
KKM/
├── index.html, home.html, about.html, services.html,
│   menu.html, gallery.html, contact.html
├── styles.css
├── js/            (sticky.js, scroll-anim.js, seo.js, site-features.js)
├── IMAGES/        (all site photos)
├── DOCUMENTS/PROPOSAL/   (project proposal)
├── sitemap.xml, robots.txt, package.json
```

## Running locally

Open `home.html` in a browser, or run a local server:

```
npm install
npm start
```

Then visit http://localhost:3000.

## Notes

- All pages use the lowercase `contact.html` filename, so links work on case-sensitive hosts.
- Opening hours are the same on the About and Contact pages (Mon to Sat 08:00 to 21:00, Sun 09:00 to 18:00). Confirm these with KKM.
- The forms are front-end only: they validate input and show a success message but do not send data anywhere yet.

## Documents

- `DOCUMENTS/PROPOSAL/WEDE5020POE.docx`: Part 1 proposal
- `WEBSITE_PROJECT_PROPOSAL.txt`: plain-text proposal summary
