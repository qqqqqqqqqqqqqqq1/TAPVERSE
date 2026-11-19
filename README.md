# TAPVERSE — Telegram Mini App

TAPVERSE is a mobile-first Telegram Web App prototype with skill-based mini-games, RPG progression, daily quests and a neon game dashboard.

## Run locally
Open `index.html` in a browser, or run a static server from this folder:
`npx serve .`

## Current prototype
- Neon game dashboard inspired by the supplied concept
- Tap-to-earn demo: coins, XP, levels, energy
- Daily missions, reward screen, invite/share flow
- Telegram Web Apps SDK bootstrap
- Local browser storage for prototype progress

## Before public launch
1. Deploy this folder to an HTTPS host (GitHub Pages, Vercel, etc.).
2. Set the deployed HTTPS URL as the Web App URL for @TapversePlayBot via @BotFather.
3. Add a backend/database; current balances and claims are local demo state and are not secure or synced.
4. Validate Telegram initData on the backend before trusting user identity.
5. Configure bot menu button / Main Mini App and test inside Telegram.

Never commit bot tokens or secrets to this repository.
