# ParkSmart — Smart Parking System

Live Demo: https://praveenkumar21122006.github.io/smart-parking-system/

Modern single-page web app for smart parking management.

## Features
- 3 floors × 32 slots (96 total) — Standard / EV / Accessible / VIP
- Real-time availability, occupancy stats & charts
- Interactive parking grid — click to book / check-in / release
- Booking with plate, name, duration, payment & price calculation ($2.50–$5.00/hr, $35 cap)
- Filters (floor, search, status, type) + live activity feed
- Dark/Light theme, responsive, localStorage persistence

## Run Locally
```bash
python3 -m http.server 8001
# open http://localhost:8001
```
No build step — just `index.html`.

## Deploy (GitHub Pages)
Push to `main` — Pages serves from root. Enabled via branch `main` / `/ (root)`.

## Tech Stack
- HTML5 + Tailwind CSS (CDN) + Vanilla JS
- Font Awesome, Google Fonts (Inter)
- localStorage for persistence
