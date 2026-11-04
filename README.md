# Tasbeeh Dashboard — React

A single-page React + Vite project with responsive light/dark themes, four dhikr choices, preset/custom targets, keyboard counting, undo, session reset, daily progress and history.

## Run locally

Use Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Production

```bash
npm run build
npm run preview
```

Deploy the generated `dist` directory. A Netlify build configuration is included.

## Files

- `src/App.jsx`: React components and counter logic.
- `src/styles.css`: responsive styles and theme variables.
- `src/main.jsx`: React entry point.

Personal counts and settings are saved in this browser's localStorage. There is no account authentication or cross-device sync. Worldwide totals and participant counts are clearly labeled demo data; connect a backend to provide live worldwide contributions. Google Fonts require an internet connection; fallback fonts work offline.

A completed session is recorded when its target is reached. The next tap starts a new session. Reset preserves history; undo reverses the last count or reset.
