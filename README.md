# Ghostly Memory — AR Nightmare

Upgraded Halloween memory game with levels, timer, scoring, and AR camera interactions.

## Quick start

1. Install dependencies:
```
npm install
```

2. Run dev server:
```
npm run dev
```

3. Open displayed local URL (usually http://localhost:5173)

## Features
- 3 difficulty levels (Easy, Medium, Nightmare)
- Timer, scoreboard, moves tracking
- AR Mode: uses webcam and TensorFlow face-landmarks to emit ghost move events that affect the game

## Notes
- TensorFlow model loads in browser; allow camera access.
- For production, consider using a server-side AI proxy for OpenAI keys (if adding AI).
