# Kedur website

Source for **https://www.kedur.co.uk** — a Jekyll site hosted free on GitHub Pages.

## Pages
- `index.html` — Home
- `products-services.html` — Products & Services (`/products-services/`)
- `contact.html` — Contact Us with enquiry form (`/contact/`)

## Editing content
- **Products & Services sections:** `_data/solutions.yml` (one entry per service; `id` is the page anchor)
- **Parts we supply cards:** `_data/products.yml`
- **Industries:** `_data/services.yml`
- **Email, site description, form endpoint:** `_config.yml`
- **Colours and fonts:** top of `assets/css/style.css`

## Connecting the contact form (Formspree)
1. Create a form at formspree.io with calvin.fernandes@kedur.co.uk.
2. Copy its endpoint (looks like `https://formspree.io/f/abcdwxyz`).
3. In `_config.yml`, replace the `formspree_endpoint` value with it and commit.
Until then, the form opens the visitor's email app with the enquiry filled in.

Commit a change on GitHub and the site rebuilds automatically within a minute or two.

## Do not delete
- `CNAME` — tells GitHub Pages to serve the site on www.kedur.co.uk.
