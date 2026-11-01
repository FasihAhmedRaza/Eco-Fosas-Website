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

## Language ES / EN

The site has an ES | EN switch in the header. It always opens in Spanish by default and remembers the visitor's choice if they switch. Direct links: `index.html?lang=en` or `index.html?lang=es`.

The English text lives in the `const EN` block at the end of `index.html`. To change a translation, edit its line there.
