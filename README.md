<div align="center">

<img src="[HWG.png](https://avatars.githubusercontent.com/u/281136396?s=400&u=fa7fb9e2eca25fe5e3e4c80d287295235002221d&v=4)" alt="HereWeGo Logo" width="140"/>

# HereWeGo Unit Monitoring

### *Your units. Your guests. Your profits. All in one tab.*

[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-ff69b4?style=for-the-badge)](#)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=for-the-badge)](#)
[![No Server Needed](https://img.shields.io/badge/Server-None%20Required-blue?style=for-the-badge)](#)
[![Open Source](https://img.shields.io/badge/Open-Source-orange?style=for-the-badge)](#)

**[🌐 Live Demo](https://your-username.github.io/herewego-unit-monitoring)** · **[📥 Download](../../releases)** · **[🐛 Report Bug](../../issues)** · **[💡 Request Feature](../../issues)**

---

</div>

## 🤔 What is HereWeGo?

**HereWeGo Unit Monitoring** is a **single HTML file** that turns any browser into a full-featured property management system — purpose-built for short-term rental operators managing condo units.

No app store. No subscription. No server to maintain. No internet required after the first load. Just **one file**, and you're running a professional-grade unit management dashboard.

> 💡 *Perfect for Airbnb hosts, condo suite operators, and transient accommodation managers who want powerful tools without the enterprise price tag.*

---

## ✨ Feature Highlights

### 📅 Visual Booking Calendar
A full month-at-a-glance calendar where every guest gets their own color. See **check-ins**, **check-outs**, and **active stays** for individual units or all units at once — no more squinting at spreadsheets.

### 🔒 Smart Double-Booking Prevention
Try to book an occupied unit and the system **hard-blocks** the save — immediately. No silent overwrites, no accidental conflicts. It even accounts for the exact schedule: **2:00 PM check-in** and **12:00 PM check-out**, so back-to-back bookings on the same date work perfectly.

### 💰 Intelligent Rate Logic
Rates are automatically calculated based on your actual pricing rules:
- **Weekday stays** (Monday–Friday) → ₱3,000/day, always
- **Single-night weekend** (Saturday or Sunday) → ₱3,500
- **Multi-night stays** (2 days+, even if weekends are included) → ₱3,000/day flat
- All rates are **fully customizable** per unit

### 🧾 Guest Receipts — Print-Ready
Generate a professional receipt for any booking in one click. Includes guest name, unit details, stay breakdown, extras, and total — formatted and ready to hand over or save as PDF.

### 🖨️ One-Page Print Report
Hit Print and get a **beautifully designed letter-size report** — all on one page — with:
- Stats summary (bookings, nights, revenue, profit)
- Full calendar view for the month
- Bookings table with status badges
- Finance breakdown (expenses vs. revenue vs. net profit)

### 📊 Finance Dashboard
Track everything that affects your bottom line:
- Monthly revenue vs. rent vs. expenses vs. production costs
- Net profit per unit or across all units
- Charts for occupancy and income trends
- ROI calculation baked in

### 🌙 Dark Mode / Light Mode
Polished gold-cream light theme and a deep navy dark theme — both fully readable, no eyestrain.

### 📱 Mobile-Responsive
The calendar and all panels **auto-resize** for any screen. Fluid cell sizing using `clamp()` so it looks sharp from a 320px phone to a 4K monitor.

### 🎨 Custom Branding
Click the logo to upload your own image, set your suite's name and tagline. Your brand, not ours. Logo shows up in the header and in every printed report.

### ➕ Multi-Unit Support
Add as many units as you manage. Switch between them in one click. The dashboard, calendar, bookings table, and finances all filter instantly per unit.

### 💾 Offline-First, Local Storage
All data lives in your browser's `localStorage`. **No account needed. No cloud sync. No data ever leaves your device.** It works offline — perfect for property managers in the field.

---

## 🚀 Deployment — GitHub Pages (60 Seconds)

> No build step. No npm install. No Dockerfile. Seriously.

**Step 1 — Fork this repo**

Click the **Fork** button at the top right of this page.

**Step 2 — Enable GitHub Pages**

Go to your fork → `Settings` → `Pages` → under **Source**, select `main` branch and `/ (root)` → click **Save**.

**Step 3 — You're live 🎉**

GitHub will give you a URL like:
```
https://your-username.github.io/herewego-unit-monitoring
```

That's it. Share the link. Bookmark it. Your property management dashboard is now live on the internet — for free, forever.

---

## 💻 Local Usage (Even Simpler)

Don't need a live URL? Just:

```bash
# Clone or download
git clone https://github.com/your-username/herewego-unit-monitoring.git

# Open the file
open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

Or just double-click the file. Done.

---

## 📂 Project Structure

```
herewego-unit-monitoring/
│
├── index.html          ← The entire application (yep, just this one file)
└── README.md           ← You're reading it
```

That's the whole repo. One HTML file. The CSS, JavaScript, fonts, icons, and logic are all self-contained inside it.

---

## 🎮 How to Use

| Action | How |
|---|---|
| **Add a unit** | Click `＋ Unit` in the top-right header |
| **New booking** | Click any date on the calendar OR the `✦ New Booking` button |
| **Edit a booking** | Click a guest chip on the calendar or a row in the Bookings tab |
| **Cancel a booking** | Open the booking → click `Cancel Booking` |
| **Print report** | Click `🖨 Print` in the header |
| **Generate receipt** | Open any booking → click `🧾 Receipt` |
| **Switch units** | Click a unit pill in the header (`All Units`, `Unit 3016`, etc.) |
| **Change your logo** | Click your agency name/logo in the header |
| **Toggle dark mode** | Click the `🌙` button |
| **Set rates & extras** | Go to `⚙️ Settings` tab |

---

## 📋 Pricing Rules (Built-In)

| Scenario | Rate Applied |
|---|---|
| Any weekday booking (1 day or more) | ₱3,000 / night |
| 1-night stay on Saturday or Sunday | ₱3,500 / night |
| 2+ nights (even if weekend nights included) | ₱3,000 / night flat |

> All base rates are configurable per unit in Settings.

**Available Extras (add-ons per booking):**
Parking 🚗 · Extra Bed 🛏️ · Extra Access Card 💳 · Extra Pax 👥 · Laundry 👕 · Mineral Water 💧 · Wine Glass 🍷 · Extra Towel 🛁 · Netflix 📺 · Guest Kit 🧴

---

## 🛡️ Privacy — Read This

> Your data **never leaves your browser.**

HereWeGo stores everything in `localStorage` — the same way your browser remembers your preferences on websites. There is no server, no database, no analytics, no tracking, and no account system. Nobody else can see your bookings.

**This also means:** if you clear your browser data, your bookings go with it. Export/backup functionality is on the roadmap. In the meantime, don't clear site data if you want to keep your records.

---

## 🗺️ Roadmap

- [ ] 📤 Export bookings to CSV / Excel
- [ ] 💾 Manual JSON backup & restore
- [ ] 📲 PWA support (install as an app on mobile)
- [ ] 📧 Guest email confirmation template generator
- [ ] 🗓️ iCal / Google Calendar sync
- [ ] 🌐 Multi-device sync via optional cloud backend

Got a feature idea? [Open an issue](../../issues) — all suggestions welcome.

---

## 🤝 Contributing

Pull requests are open! Whether it's a bug fix, a new feature, or even a typo correction — contributions are always appreciated.

```bash
# Fork → Clone → Edit index.html → Commit → Pull Request
```

Please keep the "one file" philosophy intact — all code should stay inside `index.html`.

---

## 📄 License

Released under the **MIT License** — free to use, fork, modify, and deploy for personal or commercial projects. A mention or a ⭐ star on the repo is always appreciated but never required.

---

<div align="center">

**Built with 🖤 for suite operators who deserve better tools.**

*If HereWeGo saves you time or money, consider giving it a ⭐ star on GitHub — it helps others find it.*

---

`HereWeGo Unit Monitoring` · *One file to rule them all* · Made in 🇵🇭

</div>
