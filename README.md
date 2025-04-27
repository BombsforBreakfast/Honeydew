# 🍈 Honeydew

**Honeydew** is a clean, minimalist web application designed to connect people who need quick home tasks done with nearby service providers — instantly, securely, and without the hassle of professional contractor shopping.

---

## 🚀 Project Overview

- **Platform:** Next.js (React 18+)
- **Backend:** Supabase (auth, database, realtime chat)
- **Payments:** Stripe integration (MVP+)
- **Deployment:** Vercel
- **Style:** TailwindCSS + Custom Branding (Melon green theme)
- **Geolocation:** Google Maps API or Mapbox

---

## 🎯 Core Features

- Request small tasks quickly using a simple "I need..." search bar
- Providers view nearby tasks through a pulsing melon dashboard
- In-app chat system (no personal contact info shared)
- Payment system based on rounded hourly rates (+5min rounding for fairness)
- Ratings system for providers (auto removal below 3.5 stars)
- Optional tip system after task completion
- Dewdrop notification sound for new events

---

## 🛠️ Tech Stack

| Frontend | Backend | Other |
|:---------|:--------|:------|
| Next.js  | Supabase (PostgreSQL, Auth, Realtime) | Stripe (Payments) |
| TailwindCSS | Supabase Storage (for assets if needed) | Mapbox or Google Maps (Geolocation) |
| TypeScript (Recommended) | Edge Functions (optional for cron jobs later) | Vercel (Hosting & CI/CD) |

---

## 📂 Project Structure

honeydew-app/ ├── public/ │ ├── melon-icon.png │ ├── favicon.ico │ └── sounds/ │ └── dewdrop-notification.mp3 ├── src/ │ ├── app/ │ ├── components/ │ ├── lib/ │ ├── hooks/ │ └── styles/ ├── .env.local ├── next.config.js ├── tailwind.config.ts └── package.json

---

## 📈 Future Enhancements

- In-app navigation (instead of Google Maps launch)
- Provider badges/achievements
- Scheduled task posting (future update)
- Dynamic surge pricing based on local demand

---

## 🛡️ Legal / Branding

All brand names, assets, and UI/UX elements are unique to Honeydew. Honeydew is not affiliated with TaskRabbit, Handy, Uber, Thumbtack, or any other marketplace service platform.

---

Built with ❤️ for doers, movers, helpers, and growers. 🍈
