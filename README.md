# 🛠️ InnoByte Playground: Event Management Tools

This repository contains the core utilities for the **InnoByte Hackathon**. As the Dev Department, our job is to ensure the event runs smoothly using the tools we build here.

---

## 🚀 Active Projects

### 1. The Decision Wheel (Team Randomizer)
**Function:** A visual tool to decide presentation order or prize winners.
* **Requirements:** Dynamic input for Team Names, smooth CSS-based rotation, and a "Remove Winner" button to keep the rotation fair.

### 2. Smart Challenge Queue (The "Load Balancer")
**Function:** A registration system that prevents too many teams from picking the same "Problematic" (Challenge).
* **Requirements:** * Set a **Maximum Capacity** per challenge (e.g., 5 teams).
    * **Overflow Logic:** Once a challenge is "SATURATED," the UI must disable that option and force the team to choose an available one.
    * Show real-time capacity (e.g., "4/5 slots taken").

### 3. The "InnoScore" Leaderboard (New!)
**Function:** A real-time dashboard to calculate and display team rankings.
* **The Problem:** Calculating average scores from 3+ judges across different criteria (Innovation, Technicality, Presentation) is slow when done manually.
* **Requirements:**
    * **Input Form:** A simple UI for judges to enter scores (1-10) for specific teams.
    * **Weighted Logic:** Calculate a final score based on criteria weights (e.g., Technicality is 50% of the total).
    * **Live Leaderboard:** A table that automatically re-sorts itself as new scores are added.

---

## 🛠️ Tech Stack Constraints
* **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+).
* **State:** LocalStorage (for demo) or a simple JSON/Firebase backend for persistence.

---

## 📥 Contribution Workflow
1. **Fork** the repo.
2. Create a folder: `/projects/[feature-name]-[your-name]`.
3. Submit a **Pull Request**. I will be reviewing the logic—specifically how you handle the "Saturated" state in the queue and the sorting algorithm in the leaderboard.

---
**"Efficiency through code."** — *ByteCraft Dev Management*
