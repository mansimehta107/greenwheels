# Green Wheels Scooters — Blog

The official blog for [Green Wheels Scooters](https://greenwheelsscooters.ie), Ireland's go-to destination for electric scooters and e-bikes. This repo contains **10 SEO-optimised gift guide articles** covering every major occasion, plus a hub page that ties them all together.

**Live site:** [mansimehta107.github.io/greenwheels](https://mansimehta107.github.io/greenwheels/)

---

## What's Inside

| Occasion | Article | Key Products |
|---|---|---|
| Christmas | [Why an E-Scooter Is the Ultimate Christmas Gift](blog/christmas-escooter-gift/) | G2 Pro, G2 Max, ES80 |
| Valentine's Day | [Gift an Adventure This Valentine's Day](blog/valentines-day-escooter-gift/) | G2 Pro, G2 Master, T14 |
| Father's Day | [The Father's Day Gift Dad Actually Wants](blog/fathers-day-escooter-gift/) | G2, G2 Pro, G2 Max |
| Mother's Day | [Give Mum the Gift of Freedom](blog/mothers-day-escooter-gift/) | ES80, AP07, T14 |
| Birthdays | [The Birthday Gift That Stands Out](blog/birthday-escooter-gift/) | ES80, G2, G2 Master |
| Graduation | [Kickstart Their Next Chapter](blog/graduation-escooter-gift/) | ES80, D8 Pro, G2 |
| Back to School | [Back to School? Get There on an E-Scooter](blog/back-to-school-escooter-gift/) | ES80, AP07, D8 Pro |
| Easter | [Spring Into Easter with an E-Scooter](blog/easter-escooter-gift/) | AP07, D8 Pro, G2 |
| St. Patrick's Day | [The Greenest Gift for Ireland's Greenest Day](blog/st-patricks-day-escooter-gift/) | G2, G2 Pro, G2 Master |
| Anniversary | [Celebrate Your Anniversary with Adventure](blog/anniversary-escooter-gift/) | G2 Pro, G2 Master, M20 |

---

## Project Structure

```
├── index.html                          # Root redirect → blog/
├── blog/
│   ├── index.html                      # Blog hub / listing page
│   ├── css/blog-styles.css             # Shared stylesheet (Green Wheels branded)
│   ├── images/                         # Hero images for each article (.webp)
│   ├── christmas-escooter-gift/
│   │   ├── index.html                  # Full HTML article
│   │   └── content.md                  # Markdown source + YAML front-matter
│   ├── valentines-day-escooter-gift/
│   ├── fathers-day-escooter-gift/
│   ├── mothers-day-escooter-gift/
│   ├── birthday-escooter-gift/
│   ├── graduation-escooter-gift/
│   ├── back-to-school-escooter-gift/
│   ├── easter-escooter-gift/
│   ├── st-patricks-day-escooter-gift/
│   └── anniversary-escooter-gift/
└── README.md
```

Each article folder contains:
- **`index.html`** — Fully styled, self-contained HTML page ready for deployment
- **`content.md`** — Markdown source with YAML front-matter (title, description, keywords, slug, og_image) for CMS integration

---

## Tech Stack

- **Pure HTML & CSS** — no build step, no JavaScript frameworks
- **CSS Custom Properties** for easy brand theming
- **Google Fonts** — Montserrat + Open Sans
- **Responsive** — mobile-first design
- **Hosted on** GitHub Pages

---

## Local Preview

Open any `index.html` in a browser — no server required. Product images load from the live site, so an internet connection is needed for full rendering.

```bash
# Or use a simple local server
python3 -m http.server 8000
# Then visit http://localhost:8000/blog/
```

---

## Deployment

The site is deployed automatically via **GitHub Pages** from the `main` branch. Any push to `main` triggers a rebuild.

---

## SEO Features

Each article includes:
- Unique `<title>` and `<meta description>`
- Targeted keyword meta tags
- Open Graph tags (`og:title`, `og:description`, `og:image`)
- Semantic HTML with structured headings (H1 → H2 → H3)
- Alt text on all images
- Internal links to product pages
- Mobile-responsive layout

---

## Contact

**Green Wheels Scooters**
Unit 6, Park Shopping Centre, Prussia Street, Dublin 7, D07K802, Ireland

- Web: [greenwheelsscooters.ie](https://greenwheelsscooters.ie)
- Email: [sales@greenwheelsscooters.ie](mailto:sales@greenwheelsscooters.ie)
- Phone: [087 100 2241](tel:0871002241)
