# JamalAndMisagh.com

Website for Misagh & Jamal's 20th Wedding Anniversary celebration — Dec 27–29, 2026 at the Bear & Bison Inn, Canmore.

Plain static site (no build step), hosted on GitHub Pages at <https://jamalandmisagh.com>.

- `index.html` — invitation, itinerary, RSVP
- `style.css` — styles
- `images/og-preview.jpg` — link-preview thumbnail (WhatsApp, iMessage, etc.)
- `images/twenty.svg` — the hand-lettered "twenty", traced from the printed invitation
- `CNAME` — custom domain for GitHub Pages (don't delete)

## Local preview

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>.

## Deploying

Push to `main`; GitHub Pages redeploys automatically in a minute or two.
