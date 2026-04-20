# 📊 FinTrack

> Privacy-first Net Worth & F&O Tracker — built with React + Vite. No backend, no broker connections, all data stays on your device.

![FinTrack](https://img.shields.io/badge/React-18-61DAFB?logo=react) ![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite) ![PWA](https://img.shields.io/badge/PWA-Ready-1a6b3c)

---

## ✨ Features

- 💰 **Net Worth Tracking** — assets, liabilities, bank balances
- 🏦 **Multi-account** — Bank, Credit Card, Cash accounts with balance tracking
- 💳 **Credit Card insights** — card limit, usage bar, due date countdown
- 📈 **F&O Tracker** — log trades, track P&L, charges, capital & ROI
- 💸 **Income & Expense** tracking with category breakdowns
- 📅 **Money Insights** — calendar view, category analysis
- 🔒 **100% Private** — all data stored locally in your browser
- 📱 **PWA** — installable on Android & iOS

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/fintrack.git
cd fintrack
```

### 2. Install dependencies
```bash
npm install
```

### 3. Generate app icons (one time)
```bash
npm install canvas
node generate-icons.mjs
```

### 4. Run locally
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173)

---

## 📦 Build & Deploy

### Build for production
```bash
npm run build
```

### Deploy to Vercel (free)
```bash
npx vercel
```

### Deploy to Netlify
Drag the `dist/` folder to [netlify.com/drop](https://netlify.com/drop)

---

## 📱 Install as Android App

1. Deploy to Vercel/Netlify
2. Open the URL in **Chrome on Android**
3. Tap ⋮ → **Add to Home screen**
4. Done! FinTrack icon appears on your home screen

---

## 🗂 Project Structure

```
fintrack/
├── public/
│   ├── manifest.json       # PWA manifest
│   ├── sw.js               # Service worker (offline support)
│   ├── favicon.svg         # App icon (SVG)
│   └── icons/              # Generated PNG icons (run generate-icons.mjs)
├── src/
│   ├── App.jsx             # Main app (all components)
│   ├── main.jsx            # React entry point
│   └── index.css           # Global styles
├── generate-icons.mjs      # Icon generator script
├── index.html              # HTML entry point
├── vite.config.js          # Vite config
└── package.json
```

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| React 18 | UI framework |
| Vite 5 | Build tool |
| localStorage | Data persistence |
| Service Worker | Offline support |
| PWA Manifest | Installability |

---

## 📄 License

MIT — feel free to use, modify, and distribute.
