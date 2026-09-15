# 💰 Business Finance Tracker

A lightweight, offline-first web app for tracking daily income, expenses, and profit across **four business categories**:

- ⛏️ **Mining** — buy/sell mineral transactions
- 🚗 **Bolt** — daily vehicle trip income
- 🎯 **Betting** — ticket staking and payouts
- 🧾 **Personal Expenses** — everyday spending

Built as a single-page Progressive Web App (PWA). Runs entirely in the browser. No server, no login, no cost.

**Live URL:** https://akandeaka.github.io/finance-tracker/

---

## ✨ Features

### Mining Business
- Track every mineral transaction by type (Tin, Columbite, Zircon, Monazite, etc.)
- Auto-calculates profit: `Selling Amount − Purchase Cost − Other Expenses`
- Supports unsold stock (leave selling amount blank)

### Bolt Business
- Record fuel cost, trips, and other expenses per day
- Auto-calculates daily profit: `Total Passenger Income − Fuel Cost − Other Expenses`

### Betting Investment
- Log each ticket: stake, odds, status, payout
- Auto-calculates: `Profit/Loss = Payout − Stake`
- Tracks total invested, total won, total lost

### Personal Expenses
- Categorized spending (Food, Transport, Phone/Data, Household, Utilities, Health, Rent, Other)

### Dashboard
- **Daily / Weekly / Monthly** summary views
- Profit-by-business chart
- 7-day net trend line
- Monthly projection based on recorded days
- Smart insights (best-performing business, reinvestment suggestion, overspend warnings)

### Data Safety
- All data stored in your browser's `localStorage`
- JSON backup export/import
- Works fully offline once installed

---

## 📱 How to Install (PWA)

### Android
1. Open the URL in **Chrome**
2. Tap ⋮ menu → **Install app** or **Add to Home screen**
3. Confirm → the app appears with its own icon

### iPhone
1. Open the URL in **Safari**
2. Tap **Share** → **Add to Home Screen**

### Desktop (Chrome / Edge)
1. Open the URL
2. Click the **install (⊕)** icon in the address bar

After installing, the app **works fully offline** — no internet needed for daily use.

---

## ⚠️ Important: Network / VPN Note

**GitHub Pages (`akandeaka.github.io`) is intermittently blocked or throttled by some Nigerian ISPs** (MTN, Airtel, Glo, Spectranet). Symptoms:

- Browser shows `ERR_CONNECTION_TIMED_OUT`
- The URL works one minute, times out the next
- Works fine on mobile data but not WiFi (or vice versa)

### Workaround
If you can't reach the URL:

1. **Turn on a VPN** and reload
2. Once the app loads, **install it as a PWA** (see above)
3. After installation, the app runs from cache — **VPN no longer needed** for daily use
4. Only use VPN when you need to update the app from GitHub

This is a network issue, **not a problem with the app itself**.

---

## 💾 Data Backup — Do This Weekly

Your data lives **only in this browser on this device**. It is not synced to any server.

**Every Sunday, do this:**

1. Open the app → **⚙️ Data** tab
2. Click **⬇️ Export JSON Backup**
3. Save the file and send it to yourself on WhatsApp / Google Drive / email

**To restore:**
1. Open the app → **⚙️ Data**
2. Click **⬆️ Import Backup**
3. Select your JSON file → done

Keep the last 4 weekly backups in case of emergency.

---

## 🗂️ Project Files
