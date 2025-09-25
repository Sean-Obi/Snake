# 🐍 Snake Game in Python (Tkinter)

A simple, classic Snake game built using Python and the Tkinter GUI library. Control the snake using arrow keys, eat the food to grow longer, and try not to hit the wall or yourself!

---
## 🧠 Introduction

This project recreates the classic Snake game using the Python `tkinter` module. The game is rendered in a grid of square tiles, where the player controls a snake that moves around the screen, eating food to grow longer. The game ends when the snake hits the wall or itself.

---

## ✨ Features

- Classic Snake gameplay
- Keyboard controls with arrow keys
- Live score display
- Game Over and restart with spacebar
- Dynamic food placement
- Smooth movement with consistent timing

---

## 💾 Installation

1. **Clone this repository**
2. **Run the game in Python 3**

## 🕹️ Usage

Once you run the script, the game window will appear. Use the arrow keys to move the snake. Try to collect as many food items (red squares) as you can without hitting the walls or yourself.

To restart the game after a game over, press the **spacebar**.

---

## 🎮 Controls

| Key       | Action                   |
|-----------|--------------------------|
| ↑ Arrow   | Move Up                  |
| ↓ Arrow   | Move Down                |
| ← Arrow   | Move Left                |
| → Arrow   | Move Right               |
| Spacebar  | Restart after Game Over  |

---

## 📦 Dependencies

This project uses only the Python Standard Library:

- `tkinter` – for GUI  
- `random` – for random food placement

> 📝 Tkinter is usually included with standard Python installations. If not, you can install it via your system’s package manager.

---

## ⚙️ Configuration

You can customize the game grid and tile size by editing the following variables at the top of the script:

```python
ROWS = 25
COLS = 25
TILE_SIZE = 25
