# BuyBerghia.com — waitlist page

Single static page. Deploy the whole folder to Vercel (or Netlify, or any static host).

## To go live

1. **Connect the form to Kit.** Open `index.html`, find the SIGNUP comment block.
   - Easiest: paste Kit's inline embed snippet in place of the `<form>`, keeping the `.signup` wrapper.
   - Or: set the form `action` to your Kit form's POST URL and it works as-is.
2. **Turn on the Kit welcome automation** (trigger: subscribes to form). Welcome copy is in your brief.
3. **Add a privacy policy** at `/privacy` (footer links to it). Kit and most hosts have generators.
4. **Deploy to Vercel**, point buyberghia.com at it.

## Files
- `index.html` — the page (all CSS inline, no build step)
- `logo.png` — your logo, cropped and web-sized
- `robots.txt`, `sitemap.xml` — SEO basics, already pointed at buyberghia.com

## Already done
Title tag, meta description, OpenGraph, FAQ + Organization schema, brand colors,
Playfair/Lato/Pinyon fonts, mobile-first, reduced-motion safe. No em dashes.
