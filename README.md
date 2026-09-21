# Pulse

A one-page store for heart rate monitors: device matching based on fitness level, plus Garmin, Polar, and Suunto models.

Includes section layout, responsive design, lead forms, modal windows, and a tabbed catalog.

## What’s on the page

- **Promo** — headline, benefits (fast matching, free delivery, consultation), and request buttons
- **Advantages** — team experience, health, running coaching
- **Consultation form** — name, phone, email
- **Slider** — Polar watch cards
- **Catalog** — tabs for fitness, running, and triathlon, with product cards (description and price)
- **Customer reviews**
- **Modals** — consultation and order for the selected model

## Stack

- HTML, SCSS (BEM blocks in `src/sass`)
- Gulp: style build, HTML minification, asset copy, BrowserSync
- jQuery, Slick, Animate.css, Wow.js
- jQuery Validate and a phone input mask
- PHPMailer for form submissions

## Structure

```
src/          source files
  index.html
  sass/       styles (blocks, variables, media)
  js/         scripts and plugins
  img/        images
  icons/      icons
  mailer/     email sending
dist/         built site (served locally)
gulpfile.js   build tasks
```

## Getting started

You need Node.js and npm.

```bash
npm install
npx gulp
```

After that, a local server starts from the `dist` folder. Changes in `src` are picked up automatically.
