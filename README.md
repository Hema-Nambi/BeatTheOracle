# 🔮 Beat the Oracle

> **Can you out-predict Gemini AI at the FIFA World Cup 2026?**

A daily prediction duel where you go head-to-head against an AI Oracle — powered by Google Gemini 1.5 Flash — to predict FIFA World Cup 2026 match scores. Beat the Oracle and you win the **Turing Test**. Lose, and the machines have won... for today.

🎮 **[Play now →](https://hema-nambi.github.io/BeatTheOracle)**

---

## How It Works

Every day you get 5 matches — a mix of recently played games (score immediately) and upcoming fixtures (save your prediction and come back after kickoff).

The Oracle analyses real World Cup form data and makes its own prediction. You only see its reasoning **after** you've locked in yours.

| Points | Condition |
|--------|-----------|
| 🎯 3 pts | Exact scoreline match — *"Enigma Cracked!"* |
| ✅ 1 pt  | Correct result (win / draw / loss) |
| ❌ 0 pts | Miss |

Beat the Oracle's total → 🏆 **Human wins the Turing Test**  
Lose → 🤖 **The Oracle outsmarted you**

---

## Features

- **Daily challenge** — everyone predicts the same 5 matches each day (date-seeded), so scores are globally comparable
- **Live match data** — pulled from ESPN's free public API, no key needed
- **AI reasoning** — Gemini explains *why* it picked its scoreline
- **Wordle-style share card** — copy your result emoji grid and challenge friends
- **Turing tribute** — the Enigma Cracked mechanic and Turing Test framing are core to the gameplay, not decorative
- **Edit predictions** — change your mind any time before a match kicks off
- **Glassmorphism UI** — team logos, confetti, animated score counters

---

## Getting Started

1. Get a free Gemini API key from [Google AI Studio](https://aistudio.google.com) (takes 30 seconds)
2. Open the game, enter your key and a nickname
3. Start predicting!

No installation. No backend. No cost.

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Vanilla HTML / CSS / JS — single file |
| Match data | [ESPN API](https://site.api.espn.com/apis/site/v2/sports/soccer/fifa.world/scoreboard) — free, no auth |
| AI Oracle | [Gemini 1.5 Flash](https://aistudio.google.com) — free tier |
| Storage | localStorage (predictions persist between sessions) |
| Hosting | GitHub Pages |

---

## Built For

[DEV.to June Solstice Game Jam 2026](https://dev.to/challenges/june-game-jam-2026-06-03)

Prize categories targeted:
- 🌟 **Best Google AI Usage** — Gemini is the actual opponent, not a decoration
- 🤖 **Best Ode to Alan Turing** — every session is a playable Turing Test

---

## The Turing Connection

Alan Turing's 1950 paper asked *"Can machines think?"* In Beat the Oracle, you find out daily. An exact score prediction earns the **Enigma Cracked** badge — a nod to Turing's greatest achievement at Bletchley Park.

---

Made with ❤️ in Canada 🇨🇦 — a proud 2026 World Cup host nation.
