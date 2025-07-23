
---

## 🎮 Color Game (`ColorGame.py`)

A fast-paced, brain-twisting typing game!
**Your mission:** Type the **color** of the word shown — not the word itself — before time runs out.

---

### 🧠 How to Play

* A color **name** will be displayed in a randomly colored **font**.
* Your goal is to type the **color of the text**, not the word (e.g., if it says `BLUE` in red color, type `red`).
* Press `Enter` to start the game and to submit answers.
* You have **30 seconds** to score as many points as possible.

---

### 📦 Requirements

* Python 3.x
* No external libraries — uses Python's built-in `tkinter`

---

### 🚀 Running the Game

1. Save the code as `ColorGame.py`
2. Run the script:

   ```bash
   python ColorGame.py
   ```

   > Use `python3` if `python` points to Python 2.x on your system.

---

### 🖼️ UI Layout

```
+--------------------------------------------+
| Type in the color of the words, not text!  |
|                 Score: 0                   |
|               Time left: 30                |
|         YELLOW  ← shown in blue font       |
|                [type here]                 |
+--------------------------------------------+
```

---

### 🧠 Game Logic

* `colors` list is shuffled randomly each turn.
* The color shown (`label`) is from `colors[0]`, but the font color is `colors[1]`.
* User's typed input is checked against the font color (`colors[1]`).
* Timer (`timeleft`) decreases every second; game ends when it hits 0.

---

### 📁 File Structure (if in same repo)

```
color-calc-games/
├── Mycalc.py        # GUI Calculator
├── ColorGame.py     # Color typing game
├── README.md
```

---
