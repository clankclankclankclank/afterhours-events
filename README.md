# AFTERHOURS

A responsive event discovery and registration website built with semantic HTML5, CSS3 and vanilla JavaScript. An editorial ivory-and-orange identity pairs immersive photography with restrained motion.

## Features
- Six illustrative events across five categories; combined live search and category filtering; date/name sorting and empty states.
- Event detail dialogs with schedule, venue, time in IST and live countdown.
- Validated name, email and international phone inputs; duplicate registration protection; confirmation and locally stored passes.
- My passes with removal, persistent dark/light theme, mobile/tablet/desktop layouts.
- Native modal focus handling, keyboard controls, visible focus indicators, labelled inputs, status messages and reduced-motion support.

## Run locally
Serve `dist` with any static server, e.g. `npx serve dist`. No build step or framework is required.

## Structure
`dist/index.html` - semantic page and modal shell. `dist/style.css` - responsive design, themes and animation. `dist/app.js` - event data, filtering, countdowns, form validation and storage.

## Deployment
For Vercel or Netlify use no build command and set output/publish directory to `dist`. For GitHub Pages deploy the contents of `dist` using an Actions static-pages workflow.

## Data and limitations
This is an educational front-end demo. Events are fictional, registrations remain in the current browser, and no bookings, payments or email confirmations are sent. Do not enter sensitive personal information on a shared device. Local storage can be cleared by the user and is not a production database. Real registration would require a backend, server validation, secure data storage and email delivery.

Images load from Unsplash; fonts load from Google Fonts. Network access is needed for these assets. Typography falls back to system fonts. All event times are explicitly shown in IST.

## Manual verification
Check search/category combinations, zero results, both sort options, each event dialog, Escape/close, countdown, invalid form values, duplicate registration, successful pass creation, reload persistence, removal, theme persistence, keyboard navigation and mobile widths. JavaScript syntax can be checked with `node --check dist/app.js`.

