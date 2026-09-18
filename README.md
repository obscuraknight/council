# Council

A workroom where **Grok, Claude, ChatGPT, Gemini, and Llama** share one transcript and take turns — useful when you want models to design, implement, and review the same piece of code instead of living in five tabs.

## What it does

- One group thread. Every bot sees what the others just said.
- Modes: **Code workshop**, **Debate**, **Relay**, **Free talk**.
- Per-bot roles: Architect, Implementer, Reviewer, Researcher, Challenger, Synthesizer.
- **Bring your own keys.** OpenRouter (one key for all models) or direct xAI / OpenAI / Anthropic / Google / Groq keys.
- Works in **demo mode** with no keys so you can click around the UI.

Keys are stored in `localStorage` and sent only to this app’s `/api/chat` proxy.

## Run it

```bash
npm install
npm run dev
```

Open http://localhost:3000.

1. Click **API keys** and paste an OpenRouter key (simplest) or provider-specific keys.
2. Keep Code workshop on, with Grok / ChatGPT / Claude in the room.
3. Send a task, then **Run one round** (or Auto 3 rounds).

## Deploy

Import the repo on Vercel. No extra config required.
