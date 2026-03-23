# 🧵 Untangle

**An AI thinking partner that asks you the right questions — so you can find your own answers.**

Untangle is a Socratic dialogue tool built for founders, therapists, and anyone who needs to think more clearly. Instead of giving you answers, it asks the single best question to help you get unstuck.

---

## Live

- **Landing page**: [vamsikrishnamvk.github.io/untangle](https://vamsikrishnamvk.github.io/untangle/)
- **App**: [vamsikrishnamvk.github.io/untangle/untangle-app.html](https://vamsikrishnamvk.github.io/untangle/untangle-app.html)

---

## What's in this repo

| File | Description |
|------|-------------|
| `index.html` | Marketing landing page — hero, problem, personas, how it works, pricing |
| `untangle-app.html` | The actual app — Socratic chat UI powered by Claude |
| `rubber-duck-2.jsx.txt` | Early React prototype (reference) |

---

## How it works

1. Open the app and start typing whatever's on your mind
2. Untangle asks one sharp question at a time — no advice, no answers
3. Through the dialogue, the real issue surfaces
4. After 6–8 exchanges, request a session summary

---

## Stack

- Pure HTML/CSS/JS — no build step, no dependencies
- Powered by the [Claude API](https://anthropic.com) (`claude-sonnet-4-20250514`)
- Hosted on GitHub Pages

---

## Running locally

Just open `index.html` or `untangle-app.html` directly in your browser. No server needed.

> **Note:** The app calls the Anthropic API directly from the browser. You'll need a valid API key — replace the auth header in `untangle-app.html` or set up a backend proxy before sharing publicly.
