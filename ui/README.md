# Interviewer UI

A Vite + React interface for Interviewer's adaptive technical-interview agent.

## Run locally

```bash
cd ui
npm install
npm run dev
```

Open [http://127.0.0.1:4173](http://127.0.0.1:4173).

## Product surface

- **Practice** — a GPT-style list of interview sessions and a unified agent chat
- **Notes** — user notes plus notes saved by Interviewer when requested in chat
- **Profile** — basic learner and interview-target details

Code editors and system-design whiteboards are rendered as interactive artifacts
inside the chat when the user requests them.

## Production build

```bash
npm run build
npm run preview
```

The optimized build is written to `dist/`.
