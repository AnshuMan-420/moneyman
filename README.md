# MoneyMan

A private, local-first money tracker, budget planner, and calendar — all in one `index.html` file.

![MoneyMan](https://img.shields.io/badge/single--file-no%20build-8b5cf6)

## Features

- Expense and income tracking with categories and notes
- Separate **Lena** (to get) and **Dena** (to pay) ledgers, with per-person balances
- Monthly budget with an 85% warning and a clear over-budget state
- Category donut chart and six-month cashflow chart
- Calendar with events, reminders, special days, and birthday wishes
- Password gate before every money change
- In-app Back buttons, plus browser/Android Back that closes a modal or returns to the previous tab instead of leaving the app
- Local profile photo, only after explicit permission
- JSON backup / restore (Replace All or Merge with duplicate protection)
- UTF-8 CSV export for the selected month
- Mobile bottom navigation, dark glass UI, and home-screen metadata
- No server, no build step, no account, no tracking

## Run it

Open `index.html` in any modern browser. That is the whole app.

Your profile and records are stored in `localStorage`. Nothing is uploaded anywhere.

## Deploy

This repository is ready for GitHub Pages:

1. Open **Settings → Pages**
2. Choose **Deploy from a branch**
3. Select `main` and `/ (root)`
4. Save

The app will be available at:

`https://anshuman-420.github.io/moneyman/`

## Notes

- The profile photo is cropped and resized locally, then saved as a data URL.
- Backups deliberately exclude the profile and password.
- Browser notifications work only where the browser grants permission; in-app reminders always work.
- A full home-screen install needs the app to be served over HTTPS.
