# Green Wheels Scooters - Blog Pages

## Overview

This package contains 10 fully styled blog pages for **Green Wheels Scooters** (greenwheelsscooters.ie), each focused on gifting e-scooters for a specific occasion or festival. A blog index/hub page is also included.

## Folder Structure

```
blog/
├── css/blog-styles.css           → Shared stylesheet (Green Wheels branded)
├── index.html                    → Blog listing/hub page
├── index.md                      → Markdown source for blog listing
├── christmas-escooter-gift/      → Christmas blog post
├── valentines-day-escooter-gift/ → Valentine's Day blog post
├── fathers-day-escooter-gift/    → Father's Day blog post
├── mothers-day-escooter-gift/    → Mother's Day blog post
├── birthday-escooter-gift/       → Birthday blog post
├── graduation-escooter-gift/     → Graduation blog post
├── back-to-school-escooter-gift/ → Back to School/College blog post
├── easter-escooter-gift/         → Easter blog post
├── st-patricks-day-escooter-gift/→ St. Patrick's Day blog post
├── anniversary-escooter-gift/    → Anniversary blog post
└── README.md                     → This file
```

Each post folder contains:
- `index.html` — Self-contained, fully styled HTML page
- `content.md` — Markdown source with YAML front-matter (SEO metadata)

## How to Preview Locally

1. Open any `index.html` file directly in a web browser — no server needed.
2. The CSS is linked via a relative path (`../css/blog-styles.css`), so keep the folder structure intact.
3. Product images are loaded from the live site (`https://greenwheelsscooters.ie/images/...`), so an internet connection is required for images to display.

## Integration Guide

### Option A: Direct HTML Integration
Copy each `index.html` and adapt the header/footer to match your site's existing navigation. The `<main>` content between header and footer is the blog-specific content.

### Option B: CMS/Template Integration
Use the `content.md` files as the source content. Each file includes:
- **YAML front-matter** with `title`, `description`, `keywords`, `slug`, and `og_image` fields
- **Structured headings** (H2, H3) ready for any CMS
- **Product recommendation sections** with links to product pages

### CSS Integration
- The `blog-styles.css` file is self-contained with CSS custom properties.
- Adjust the `:root` variables at the top of the file to match any brand colour updates.
- The stylesheet uses Google Fonts (Montserrat + Open Sans). If your site uses different fonts, update the `font-family` declarations.

## Image References

All product images reference the live site:
- Logo: `https://greenwheelsscooters.ie/images/logo.png`
- Products: `https://greenwheelsscooters.ie/images/product/{ProductName}/{number}.jpg`

To use local images instead, find-and-replace `https://greenwheelsscooters.ie` with your local asset path.

## SEO Checklist (Per Page)

- [ ] `<title>` tag set (included in HTML)
- [ ] `<meta name="description">` set (included in HTML)
- [ ] `<meta name="keywords">` set (included in HTML)
- [ ] Open Graph `og:title`, `og:description`, `og:image` set (included in HTML)
- [ ] Canonical URL added (update `<link rel="canonical">` with your live blog URL)
- [ ] Alt text on all images (included in HTML)
- [ ] Internal links to product pages are correct
- [ ] Page loads under 3 seconds
- [ ] Mobile responsive (handled by CSS)

## Blog Pages Overview

| # | Occasion | Recommended Products | Target Audience |
|---|----------|---------------------|-----------------|
| 1 | Christmas | G2 Pro, G2 Max, ES80 | Families, all ages |
| 2 | Valentine's Day | G2 Pro, G2 Master, T14 | Couples |
| 3 | Father's Day | G2, G2 Pro, G2 Max | Adult children → dads |
| 4 | Mother's Day | ES80, AP07, T14 | Adult children → mums |
| 5 | Birthday | ES80, G2, G2 Master | All ages |
| 6 | Graduation | ES80, D8 Pro, G2 | Graduates 18-25 |
| 7 | Back to School | ES80, AP07, D8 Pro | Students, parents |
| 8 | Easter | AP07, D8 Pro, G2 | Families, teens |
| 9 | St. Patrick's Day | G2, G2 Pro, G2 Master | Ireland enthusiasts |
| 10 | Anniversary | G2 Pro, G2 Master, M20 | Couples |

## Contact

- Website: https://greenwheelsscooters.ie
- Email: sales@greenwheelsscooters.ie
- Phone: 087 100 2241
- Address: Unit 6, Park Shopping Centre, Prussia Street, Dublin 7, D07K802, Ireland
