# PROFEX — Device Management Console

Firebase-based SMS dashboard with live device monitoring, OTP tracking, and multi-account support.

## Features

- **Multi-account Firebase management** — Add multiple Firebase projects via URL + API key
- **Live device dashboard** — Stats (Total/Online/Offline/Bank), filterable device list
- **Device detail view** — Phone number, network, SIM info, and FROM SMS data
- **Real-time SMS feed** — Simulated OTP messages with auto-refresh
- **Dark theme** — Mobile-first responsive UI

## Deploy on Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/profex-dashboard)

Or manually:

```bash
npm i -g vercel
vercel --prod
```

## Files

| File | Purpose |
|------|---------|
| `profex-dashboard.html` | Main app — single-file SPA |
| `vercel.json` | Vercel deployment config |
| `package.json` | Project metadata |

## Local Usage

```bash
npx serve .
# Open http://localhost:3000
```

> **Note:** This is a client-side demo. SMS simulation runs in-browser. Replace with real Firebase REST calls for production use.
