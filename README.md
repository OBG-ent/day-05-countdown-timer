# ⏳ Countdown Timer

A clean, dark-themed countdown timer that counts down to anything — your birthday, New Year, a deadline. It even remembers your countdown if you close the tab.

## ✨ Features

- **Custom countdowns** — name any event and pick any future date & time
- **Quick presets** — one click to +1 hour, +24 hours, +7 days, or the next New Year
- **Persists across reloads** — your countdown is saved in `localStorage` and restored automatically
- **Live ticking** — days, hours, minutes, seconds update every second
- **Celebration state** — shows "🎉 Time's up!" when the countdown hits zero
- **Zero dependencies** — a single HTML file with embedded CSS and JavaScript

## 🚀 Run it in 30 seconds

No build tools, no installs. Either:

1. **Double-click** `index.html` — it runs straight in your browser, or
2. Serve it locally:
   ```bash
   npx serve .
   # then open http://localhost:3000
   ```

## 👀 What you'll see

A dark card-style timer with big gold digits (days · hours · minutes · seconds), your event name above it, and a control panel below: event-name input, date picker, Start/Clear buttons, and four preset buttons.

## 🧠 What this project practices

- `setInterval` for a ticking clock
- Date math: converting millisecond differences into days/hours/minutes/seconds
- `localStorage` for persistence (JSON save + restore)
- Form input validation (must be a future date)
- DOM updates and event listeners

## 🗓️ Daily coding journey

This is **Day 05 · simple build** of my daily coding journey — one small complete project every day.
