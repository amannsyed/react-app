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
| [React 19](https://reactjs.org/) | UI framework |
| TypeScript | Type safety |
| [Vite](https://vitejs.dev/) | Build tool & dev server |
| [GitHub Pages](https://pages.github.com/) | Hosting & deployment |

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

## Build for Production

```bash
npm run build
npm run preview
```

---

## Deployment

This project deploys to GitHub Pages via the `gh-pages` package.

```bash
npm run deploy
```

This runs `vite build` and publishes the `dist/` folder to the `gh-pages` branch.

---

## 📁 Project Structure

```text
knock-knock-physio/
├── src/
│   ├── components/      # Reusable React UI components
│   ├── App.tsx           # Root application component
│   ├── main.tsx          # React DOM entry point
│   └── index.css         # Global styles
├── public/               # Static assets (images, icons)
├── package.json
├── tsconfig.json
└── vite.config.ts
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## 📝 License

MIT
