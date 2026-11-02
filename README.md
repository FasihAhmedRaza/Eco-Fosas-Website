# Eco Fosas — Presentation Website

English version of `LEEME.txt`.

## Getting started

Open `index.html` in a browser. Keep the `assets/` folder in the same folder as `index.html`.

## Publishing

Upload the whole folder to a static host (Netlify, Cloudflare Pages or similar) and connect the business's domain.

## WhatsApp

The official number, +56 9 5767 4277, is set in `index.html` near the end:

```js
const CONFIG = { whatsapp: '56957674277' };
```

To change it, use the country code 56, without the `+` sign, dashes or spaces. The quote form opens WhatsApp with a pre-filled message, but it does **NOT** create or confirm a booking automatically. The number is also written out by hand in the "¿Prefieres hablar directo?" card and the footer.

## Real bookings

To book time slots, block out availability, receive forms without WhatsApp, send reminders or have an admin panel, connect a backend / CRM / booking platform. This demo does not include a backend.

## To complete before publishing

- Business email
- Company legal name / RUT, if applicable
- Privacy policy, data handling and consent
- Confirmation of coverage, timelines, documentation, and health requirements for each case

The jobs, places and services shown come from material provided by the client.

## Photos

The photographs were provided by the user. Images with text overlaid on them have been kept unaltered. The site does not show any testimonials, accreditations or certifications that don't exist.

The `.jpg` / `.png` files in `assets/` are the master copies; keep them. The page shows the optimized WebP copies next to them: `foto-N-480.webp` and `foto-N-800.webp` (gallery and small screens), `foto-N.webp` (1200 px: hero and lightbox) and `logo-ecofosas-240.webp`. Social previews (`og:image`) still use the JPG.

**Fonts:** Plus Jakarta Sans and Sora are self-hosted in `assets/fonts/` (latin and latin-ext files, SIL Open Font License; the license files are in the same folder). The page no longer loads anything from Google Fonts. The `@font-face` rules are at the top of the `<style>` block in `index.html`.

**Favicon:** browser tabs use `favicon-64.png`; `favicon.png` (192 px) stays for larger icons.

**Caching:** `vercel.json` tells browsers to keep everything in `assets/` (images, fonts, icons) for one year. If you replace a file, save it under a **new file name** (e.g. `foto-8-v2.webp`) and update `index.html`; reusing the old name means returning visitors keep seeing the old file.

## Language ES / EN

The site has an ES | EN switch in the header. It always opens in Spanish by default and remembers the visitor's choice if they switch. Direct links: `index.html?lang=en` or `index.html?lang=es`.

The English text lives in the `const EN` block at the end of `index.html`. To change a translation, edit its line there.
