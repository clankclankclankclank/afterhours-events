# AFTERHOURS

[Live website](https://clankclankclankclank.github.io/afterhours-events/) · [Repository](https://github.com/clankclankclankclank/afterhours-events)

A responsive event discovery and registration website built with semantic HTML5, CSS3 and vanilla JavaScript. An editorial ivory-and-orange identity pairs immersive photography with restrained motion.

## Features
- Six illustrative events across five categories; combined live search and category filtering; date/name sorting and empty states.
- Event detail dialogs with schedule, venue, time in IST and live countdown.
- Validated name, email and international phone inputs; duplicate registration protection; confirmation and locally stored passes.
- My passes with removal, persistent dark/light theme, mobile/tablet/desktop layouts.
- Native modal focus handling, keyboard controls, visible focus indicators, labelled inputs, status messages and reduced-motion support.

## Run locally
Serve the repository root with any static server, e.g. `npx serve .`. No build step or framework is required.

## Structure
`index.html` - semantic page and modal shell. `style.css` - responsive design, themes and animation. `app.js` - event data, filtering, countdowns, form validation and storage.

## Deployment
GitHub Pages publishes the `main` branch root. For Vercel or Netlify use no build command and publish the repository root.

## Data and limitations
This is an educational front-end demo. Events are fictional, registrations remain in the current browser, and no bookings, payments or email confirmations are sent. Do not enter sensitive personal information on a shared device. Local storage can be cleared by the user and is not a production database. Real registration would require a backend, server validation, secure data storage and email delivery.

Images load from Unsplash; fonts load from Google Fonts. Network access is needed for these assets. Typography falls back to system fonts. All event times are explicitly shown in IST.

## Manual verification
Check search/category combinations, zero results, both sort options, each event dialog, Escape/close, countdown, invalid form values, duplicate registration, successful pass creation, reload persistence, removal, theme persistence, keyboard navigation and mobile widths. JavaScript syntax can be checked with `node --check app.js`.

