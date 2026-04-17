# 🎡 Project: InnoByte Event Utils

Welcome to the **InnoByte Playground**! Instead of building a massive system, we are building a suite of **Event Utilities**—small, high-impact tools to help our Hackathon run smoothly.

## 📌 Project Goal
To create a collection of "Mini-Apps" that the ByteCraft Scientific Club can use during the Innobyte presentation day to manage teams, timing, and voting.

---

## 🛠️ The "Mini-Project" List

### 1. The Decision Wheel (Team Randomizer)
**Problem:** Teams are always nervous about who goes first.
**Task:** Build a "Spin the Wheel" web app.
* **Features:** Input a list of team names, click to spin, and land on a winner with a "confetti" effect.
* **Skills:** CSS Animations, JavaScript Math functions.

### 2. The "Pitch-Perfect" Timer
**Problem:** Presenters often go over their 5-minute limit.
**Task:** A high-visibility countdown timer.
* **Features:** Large digits, color changes (Green -> Yellow -> Red), and a buzzer sound when time is up.
* **Skills:** DOM manipulation, setInterval, Audio API.

### 3. The "InnoVote" Poll
**Problem:** Deciding the "People's Choice" award manually is slow.
**Task:** A simple real-time voting button.
* **Features:** A UI where users can click their favorite team name and see a live bar chart of the results.
* **Skills:** LocalStorage (for simple state) or Firebase (for real-time).

### 4. Team "Ice-Breaker" Generator
**Problem:** Members from different departments don't know each other yet.
**Task:** A random scientific "Would You Rather" or prompt generator.
* **Features:** A button that displays a random scientific debate topic (e.g., "Is Pluto a planet?").
* **Skills:** Array handling, JSON data fetching.

---

## 📂 Project Structure
Each project should live in its own folder within this repo:
```text
/innobyte-playground
  ├── /decision-wheel
  ├── /pitch-timer
  ├── /innovote
  └── /ice-breakers
