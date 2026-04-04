# Knock Knock Physio 🏥

> Professional home-based physiotherapy services — delivered to your door.

**Knock Knock Physio** is a modern, responsive web application for a mobile physiotherapy practice. It allows patients to learn about available services, read testimonials, view pricing, and book appointments — all from the comfort of their browser.

🌐 **Live Site:** [amannsyed.github.io/knock-knock-physio](https://amannsyed.github.io/knock-knock-physio)

---

## Features

- 📋 **Service Showcase** — Pain relief, post-surgical rehab, neurological therapy, elderly mobility support, and musculoskeletal treatment
- 📅 **Online Booking** — Interactive appointment booking modal with form validation
- 💬 **WhatsApp Booking** — Quick appointment requests via WhatsApp with a pre-filled message
- 💷 **Pricing Plans** — Clear, transparent pricing for all service tiers
- 🏅 **Affiliations** — Professional body memberships and accreditations
- ⭐ **Testimonials** — Patient reviews and feedback
- ❓ **FAQ** — Answers to common patient questions
- 📬 **Contact Form** — Get in touch directly from the site
- 🔐 **Admin Dashboard** — Protected admin login to manage bookings and site data

---

## Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | UI framework |
| TypeScript | Type safety |
| Vite | Build tool & dev server |
| GitHub Pages | Hosting & deployment |

---

## Run Locally

**Prerequisites:** Node.js (v18+)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/amannsyed/knock-knock-physio.git
   cd knock-knock-physio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

The app will be available at `http://localhost:5173`.

---

## Deployment

This project deploys to GitHub Pages via the `gh-pages` package.

```bash
npm run deploy
```

This runs `vite build` and publishes the `dist/` folder to the `gh-pages` branch.
