# Countdown ⏳

**🔗 Live Demo: https://linling856.github.io/countdown/**

A pure front-end countdown web app. Mobile-first, bilingual (中文 / English), no backend, no build step.

## Features

- ⏱ Multiple parallel countdowns — target date mode or custom duration (days + hours + minutes)
- 📅 Month calendar — target days and check-in days highlighted, tap a day for details
- ✅ Daily check-in — streak counter, tasks light up the calendar
- 🔔 Custom reminders — lead days (0–30), daily or last-day-only (works while the page is open)
- 💾 localStorage persistence + JSON export / import
- 📱 PWA — add to home screen, offline static cache
- 🌐 中文 / English toggle

## Run

Serve over HTTPS or localhost (required for notifications & service worker), e.g.:

```bash
npx serve .
```

or deploy to GitHub Pages as-is. Pure HTML/CSS/JS — just open `index.html`.

## License

[MIT](LICENSE)
