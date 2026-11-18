# WOD Log – project rules

## What it is
A **mobile-first** web app for logging CrossFit and Hyrox PRs (personal records)
and tracking progress over time.

## Rules
- **Mobile-first**: design for the phone screen first, then adapt to larger screens.
  Buttons and inputs should be large and easy to tap.
- **Data only in localStorage**: no backend, no external database, no APIs.
- **No login**: no accounts, no authentication.
- **Simple, readable code**: prefer clear solutions over clever ones;
  don't add libraries unless they're really needed. The project owner is not an experienced developer.
- **Frequent commits**: after each feature that works, propose a commit with a clear message.
- **English only**: write all documents, code comments and commit messages in English,
  even when the conversation happens in Italian.

## Stack
React + Vite + TypeScript + Tailwind CSS (v4, via `@tailwindcss/vite`).

## Useful commands
- `npm run dev` – start the app locally
- `npm run build` – type-check and build the production version
- `npm run lint` – check code quality
