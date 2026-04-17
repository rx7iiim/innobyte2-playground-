# 🚀 InnoByte Event Utils

A suite of four browser-based mini-apps to help the ByteCraft Scientific Club run the InnoByte Hackathon smoothly — no server or build step required.

## 📂 Project Structure

```
innobyte-playground/
├── index.html            ← Hub dashboard (start here!)
├── decision-wheel/       ← 🎡 Spin-the-Wheel team randomiser
│   └── index.html
├── pitch-timer/          ← ⏱️ Countdown timer with buzzer
│   └── index.html
├── innovote/             ← 🗳️ Live voting poll with bar chart
│   └── index.html
└── ice-breakers/         ← 🧊 Scientific debate prompt generator
    └── index.html
```

## 🛠️ Mini-Apps

### 1. 🎡 Decision Wheel (`/decision-wheel`)
A canvas-based "Spin the Wheel" app that randomly selects a team.
- Add / remove team names
- Smooth easing spin animation
- Confetti explosion on the winner

### 2. ⏱️ Pitch-Perfect Timer (`/pitch-timer`)
A high-visibility countdown timer for keeping presenters on time.
- Large digits, circular progress ring
- Colour shifts: **Green → Yellow → Red**
- Web Audio API buzzer when time is up
- Configurable presets (3 / 5 / 7 / 10 min) and custom duration

### 3. 🗳️ InnoVote Poll (`/innovote`)
A live voting dashboard for the People's Choice award.
- Add any number of teams
- One-click voting with animated bar chart
- Vote counts persisted in LocalStorage
- Reset all votes at any time

### 4. 🧊 Ice-Breaker Generator (`/ice-breakers`)
A random scientific debate / "Would You Rather" prompt generator.
- 35+ prompts across 5 categories (Space, Biology, Tech, Physics, Would You Rather)
- Flip card animation between prompts
- Save favourite prompts (persisted in LocalStorage)

## 🚀 How to Run

Open `index.html` in any modern browser — no installation needed.

```bash
# Optional: serve with a local HTTP server
python3 -m http.server 8080
# then open http://localhost:8080
```
