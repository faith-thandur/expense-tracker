# Personal Expense Tracker (PWA)

A lightweight, mobile-optimized Progressive Web App (PWA) designed for tracking daily income, expenses, and personal budgets. Built with client-side state management, local data storage, and offline capabilities.

Live App: [https://expense-tracker-roan-rho-96.vercel.app](https://expense-tracker-roan-rho-96.vercel.app)

---

## Features

- **Mobile-First UI:** Dark charcoal/slate interface designed specifically for mobile screens.
- **Starting Balance Adjustment:** Custom starting budget configuration with live updates.
- **Transaction Management:** Real-time logging of income and categorized expenses (Food, Bills, Shopping, Transportation, etc.).
- **Visual Analytics:** Interactive doughnut chart breakdown powered by Chart.js.
- **Local Data Persistence:** All data is stored locally on the device using browser `localStorage`—no account required.
- **Progressive Web App (PWA):**
  - Installable directly onto mobile home screens.
  - Standalone full-screen experience without browser URL bars.
  - 100% offline functionality via Service Worker caching (`sw.js`).

---

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla ES6+)
- **Icons & Visualization:** Font Awesome 6, Chart.js
- **Storage Engine:** Browser `localStorage`
- **PWA Architecture:** Web App Manifest (`manifest.json`), Service Worker (`sw.js`)
- **Deployment:** Vercel (Continuous Deployment via GitHub)

---

## Installation & Setup

### Installing as a Mobile App

#### Android (Google Chrome)
1. Open [https://expense-tracker-roan-rho-96.vercel.app](https://expense-tracker-roan-rho-96.vercel.app) in Chrome.
2. Tap the **3 dots (⋮)** menu in the top right corner.
3. Tap **Install app** or **Add to Home screen**.

#### iPhone / iOS (Safari)
1. Open [https://expense-tracker-roan-rho-96.vercel.app](https://expense-tracker-roan-rho-96.vercel.app) in Safari.
2. Tap the **Share** button (square with an up arrow).
3. Scroll down and tap **Add to Home Screen**.

---

## Local Development

To run or edit this project locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/faith-thandur/expense-tracker.git](https://github.com/faith-thandur/expense-tracker.git)
