# Gabriela's Premier Pet Care

Marketing website for Gabriela's Premier Pet Care — trusted dog sitting, dog walking, drop-in visits, and overnight pet care in Orlando, FL.

## Stack
Plain HTML + CSS. No build step. Just open `index.html` in a browser.

## Pages
- `index.html` — Home
- `about.html` — About Gabriela
- `services.html` — Services & pricing
- `book.html` — Book appointment (placeholder until scheduler is live)
- `contact.html` — Contact form

## Deploy
Hosted on Vercel as a static site. Push to `main` → Vercel auto-deploys.

## Local preview
Just open `index.html` in your browser, or run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## TODO / follow-ups
- Hook the contact form up to Formspree or Netlify Forms (currently a placeholder alert).
- Replace the Book Appointment placeholder with the real scheduler embed (Calendly, Acuity, or Squarespace Scheduling).
- Swap CDN image URLs for locally-hosted images so the site doesn't depend on Squarespace.
- Add custom domain.
