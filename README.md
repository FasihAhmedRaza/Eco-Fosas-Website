# Eco Fosas — Presentation Website

English version of `LEEME.txt`.

## Getting started

Open `index.html` in a browser. Keep the `assets/` folder in the same folder as `index.html`.

## Publishing

Upload the whole folder to a static host (Netlify, Cloudflare Pages or similar) and connect the business's domain.

## WhatsApp

In `index.html`, near the end, find this line:

```js
const CONFIG = { whatsapp: '' };
```

Insert the official number with the country code 56, without the `+` sign, dashes or spaces (e.g. `'56912345678'`). Once this is set, the form opens a pre-filled message in WhatsApp, but it does **NOT** create or confirm a booking automatically.

## Real bookings

To book time slots, block out availability, receive forms without WhatsApp, send reminders or have an admin panel, connect a backend / CRM / booking platform. This demo does not include a backend.

## To complete before publishing

- Official phone number
- Business email
- Company legal name / RUT, if applicable
- Privacy policy, data handling and consent
- Confirmation of coverage, timelines, documentation, and health requirements for each case

The jobs, places and services shown come from material provided by the client.

## Photos

The photographs were provided by the user. Images with text overlaid on them have been kept unaltered. The site does not show any testimonials, accreditations or certifications that don't exist.

## Language ES / EN

The site has an ES | EN switch in the header. It remembers the visitor's choice and opens in English if their browser is set to English. Direct links: `index.html?lang=en` or `index.html?lang=es`.

The English text lives in the `const EN` block at the end of `index.html`. To change a translation, edit its line there.
