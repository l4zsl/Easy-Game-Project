# 🎮 Easy Game Project

A simple 2D survival game built with **Python and Tkinter**. Dodge incoming obstacles, manage your health, and survive as long as possible to beat your personal high score.

## ✨ Features

- **Player Movement** — Move freely around the game area using keyboard controls.
- **Sprint System** — Hold Shift to move faster.
- **Dynamic Obstacles** — Survive two alternating obstacle patterns:
  - 🔴 **Rain** — Incoming projectiles approach from different directions.
  - ▰ **Moving Barriers** — Horizontal obstacles move downward with shifting gaps.
- **Health System** — Start with 100 HP. Each collision reduces health by 20.
- **Survival Timer** — Track how long you can stay alive.
- **High Score System** — Automatically saves your best survival time using JSON, so your record persists between sessions.
- **Replay System** — Start another round immediately after Game Over.

## 🕹️ Controls

| Key | Action |
|:---:|---|
| `W` / `↑` | Move Up |
| `A` / `←` | Move Left |
| `S` / `↓` | Move Down |
| `D` / `→` | Move Right |
| `Shift` | Sprint |

## 🛠️ Built With

- **Language:** Python 3.10+
- **GUI Framework:** Tkinter
- **Data Storage:** JSON
- **Standard Libraries:**
  - `random` — Random obstacle generation
  - `time` — Survival time tracking
  - `json` — High score storage
  - `pathlib` — File path management

No additional third-party packages are required.

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/l4zsl/Easy-Game-Project.git
```

### 2. Navigate to the project directory

```bash
cd Easy-Game-Project
```

### 3. Run the game

```bash
python main.py
```

## 📁 Project Structure

```text
Easy-Game-Project/
├── main.py         # Main game implementation
├── highscore.json  # Persistent high score data
└── README.md       # Project documentation
```

`highscore.json` stores your best survival time and is created or updated automatically.

## 🎯 Objective

Survive for as long as possible while avoiding incoming obstacles. Every collision costs 20 HP, and the game ends when your health reaches zero.

**How long can you survive?**

## 👨‍💻 Developer

**กณวรรธน์ แมทต้า**

GitHub: [@l4zsl](https://github.com/l4zsl)
