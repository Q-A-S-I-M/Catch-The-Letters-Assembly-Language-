# 🎮 Catch The Letter – Assembly Language Game (MASM)

**Catch The Letter** is a fast-paced reflex game developed in **x86 Assembly Language using MASM**. Letters fall from the top of the screen, and your task is to press the matching key before it reaches the ground. Simple in concept but challenging in execution!

---

## 🕹️ Gameplay

- **Objective:** Press the correct letter key before the falling letter hits the bottom.
- **Navigation Controls:**
  - `W` – Move up in menu
  - `S` – Move down in menu
  - `Enter` – Select menu option
- **Leaderboard:**
  - Shows the **top 5 players**
  - Updates **in real time** as scores change

---

## ✨ Features

- Built with **MASM (Microsoft Macro Assembler)**
- **Impressive UI** for an Assembly-based application
- **Real-time leaderboard tracking**
- Responsive keyboard handling and interactive menus
- Custom ASCII graphics and game loop logic

---

## 🧠 Technical Notes

- **Architecture:** x86 real mode
- **Platform:** Native x86-compatible environment (e.g., Windows supporting 16-bit or real mode emulation)
- **Leaderboard Memory Behavior:**
  - Due to **direct memory access**, the leaderboard may behave **irregularly on different PCs**.
  - Memory mapping differences between systems can lead to unexpected results.

---

## ▶️ How to Run

1. Open the `debug` folder.
2. Run the executable file (e.g., `game.exe`) directly.

