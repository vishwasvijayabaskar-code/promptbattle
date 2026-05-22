# PromptBattle ⚔️

> Compare LLM responses side-by-side. One HTML file. No backend. Bring your own API keys.

![Demo](https://img.shields.io/badge/demo-open%20index.html-6366f1?style=for-the-badge)

## What is this?

A single HTML file that lets you send the same prompt to two LLMs simultaneously and compare their responses in real-time with streaming.

**Supported models:**
- OpenAI: GPT-4o, GPT-4o Mini
- Anthropic: Claude Sonnet 4, Claude Haiku 4
- Google: Gemini 2.5 Flash, Gemini 2.5 Pro

## Quick Start

```bash
# Just open the file
open index.html

# Or serve it
npx serve .
```

1. Enter your API keys (stored in localStorage, never leaves your browser)
2. Pick two models to compare
3. Type your prompt
4. Hit **Battle** (or Ctrl+Enter)
5. Watch responses stream in side-by-side

## Features

- **Single HTML file** — no build step, no dependencies, no framework
- **Real-time streaming** — both models stream simultaneously
- **Timing** — see how long each model takes
- **Privacy-first** — API keys stay in your browser's localStorage
- **Dark theme** — easy on the eyes
- **Mobile responsive** — stacks vertically on small screens
- **Persistent config** — model selections and keys survive refresh

## Privacy

Your API keys are stored in `localStorage` and sent directly to each provider's API. **No data passes through any intermediary server.** This is a static HTML file — there is no backend.

## Use Cases

- Compare response quality across models
- Test prompts before committing to a provider
- Find the cheapest model that gives good enough results
- Evaluate coding ability, reasoning, creativity side-by-side
- Quick A/B testing for prompt engineering

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Ctrl+Enter` / `Cmd+Enter` | Send prompt |

## Self-Hosting

It's one file. Copy `index.html` anywhere. Done.

```bash
# GitHub Pages
cp index.html docs/index.html
# Deploy to Vercel, Netlify, or anywhere that serves static files
```

## Also By Me

- [oneshot](https://github.com/vishwasvijayabaskar-code/oneshot) — One command, any LLM, instant answers from terminal
- [gitgenius](https://github.com/vishwasvijayabaskar-code/gitgenius) — AI-powered git commits, PR descriptions, changelogs
- [aiterm](https://github.com/vishwasvijayabaskar-code/aiterm) — AI terminal assistant, auto-explain errors
- [awesome-ai-agents](https://github.com/vishwasvijayabaskar-code/awesome-ai-agents) — Curated list of AI agent frameworks
- [ai-system-design-primer](https://github.com/vishwasvijayabaskar-code/ai-system-design-primer) — System design for AI systems

## License

MIT
