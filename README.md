# ⚔️ sistema-medicina

> *"O portal está aberto. Só você pode decidir se vai entrar."*

A Solo Leveling-inspired study tracker built for Brazilian medical school entrance exams (FUVEST / ENEM). Track daily missions, level up your stats, hit the 200-question daily goal, and count down to exam day — all in a single HTML file, no install required.

---

## ✨ Features

- **Sistema de Despertar** — on first load, the System activates and assigns your mission
- **Player card** — custom name, rank (E → S), level, XP bar
- **Daily quests** — default study missions with XP rewards and rank difficulty (C / B / A / S); add your own anytime
- **Dungeon system** — one dungeon per subject (Biologia, Química, Física, Matemática, Português, Redação, Humanas); click to log questions and grow your stats
- **200-question counter** — 200 clickable checkboxes with milestone unlocks every 25 questions and a special S-RANK notification at 200
- **Skill tree** — activate study habits (focus sessions, spaced repetition, full mock exams…) and level them up
- **Countdown timer** — live countdown to ENEM day
- **Battle log** — timestamped record of everything you do
- **Daily reset** — quests and question counter reset automatically each new day
- **Persistent state** — everything is saved to `localStorage`; your progress survives page reloads

---

## 🚀 Usage

No build step, no dependencies, no server.

```bash
git clone https://github.com/your-username/sistema-medicina.git
cd sistema-medicina
open sistema-medicina.html   # or just double-click the file
```

That's it. Open the file in any modern browser and the System activates.

---

## 🎯 Targets

| University | Course | Exam |
|---|---|---|
| USP — Universidade de São Paulo | Medicina | FUVEST |
| UFMG — Universidade Federal de Minas Gerais | Medicina | ENEM / SISU |

---

## 🗂️ Structure

```
sistema-medicina/
└── sistema-medicina.html   # entire app — HTML + CSS + JS in one file
```

---

## 🛠️ Customization

Everything lives inside the single HTML file. The state object near the top of the `<script>` block is where you can tweak defaults:

- **`quests`** — edit or add default daily missions
- **`dungeons`** — adjust subject names, ranks, and question targets
- **`skills`** — change the habit names and descriptions
- **`TARGET`** — update the countdown date to match your actual exam date
- **Stats** — initial values for each subject (0–100)

---

## 📸 Preview

```
┌─────────────────────────────────────────────┐
│  ▸ SISTEMA DE DESPERTAR ◂                   │
│                                             │
│   PROTOCOLO                                 │
│   MEDICINA                                  │
│   Academic Comeback · 2025 · S-Rank Target  │
│                                             │
│  [E] HUNTER  ████████░░░░  NV 1             │
│                                             │
│  Biologia 40  Química 35  Física 30  ...    │
│                                             │
│  ⏳ 234 : 08 : 42 : 17                      │
│     ◈ USP — MEDICINA  ◈ UFMG — MEDICINA     │
└─────────────────────────────────────────────┘
```

---

## 📄 License

MIT — use it, fork it, pass the exam.
