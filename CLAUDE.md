# WOD Log – regole del progetto

## Cos'è
App web **mobile-first** per registrare i PR (personal record) di CrossFit e Hyrox
e vedere i progressi nel tempo.

## Regole
- **Mobile-first**: progetta prima per lo schermo del telefono, poi adatta a schermi più grandi.
  Pulsanti e campi grandi e facili da toccare.
- **Dati solo in localStorage**: nessun backend, nessun database esterno, nessuna API.
- **Niente login**: nessun account, nessuna autenticazione.
- **Codice semplice e leggibile**: preferisci soluzioni chiare a soluzioni furbe;
  niente librerie in più se non servono davvero. Chi legge il codice non è uno sviluppatore esperto.
- **Commit frequenti**: dopo ogni funzione che funziona, proponi un commit con un messaggio chiaro.

## Stack
React + Vite + TypeScript + Tailwind CSS (v4, tramite `@tailwindcss/vite`).

## Comandi utili
- `npm run dev` – avvia l'app in locale
- `npm run build` – controlla i tipi e crea la versione di produzione
- `npm run lint` – controlla la qualità del codice
