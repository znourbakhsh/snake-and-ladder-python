# 🐍 Snake and Ladder Game (Python Version)

A Python implementation of the classic **Snake and Ladder** board game with support for multiple players, dice rolling, snakes, ladders, collision handling, and graphical board visualization using Matplotlib.

---

## 🎮 Features

* Multiple players support
* Random dice rolling (1–6)
* Snakes and ladders mechanics
* Bonus turn when rolling a 6
* Player collision detection
* Winner detection
* Colored player tokens
* Graphical board visualization using Matplotlib
* Interactive round-by-round gameplay

---

## 🛠️ Technologies Used

* Python 3
* NumPy
* Matplotlib
* Colorama

---

## 📋 Requirements

Install the required packages:

```bash
pip install numpy matplotlib colorama
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/znourbakhsh/snake-and-ladder-python.git
```

2. Navigate to the project folder:

```bash
cd snake-and-ladder-python
```

3. Make sure the board image is available:

```text
board.png
```

4. Run the game:

```bash
python snake_and_ladder.py
```

---

## 🎯 Game Rules

* Players take turns rolling a dice.
* Landing on a ladder moves the player up.
* Landing on a snake moves the player down.
* Rolling a 6 grants an extra turn.
* If two players land on the same position, the previous player is sent back to the start.
* The first player to reach position 100 wins the game.

---

## 🖼️ Board Visualization

The game board is displayed using Matplotlib.

Player positions are shown as colored markers on the board and are updated after each round.

---


---

---

## 👩‍💻 Author

Created by Zahra

Related project:

🌐 Snake and Ladder Game (JavaScript Version)

A browser-based implementation of the same game is available in a separate repository.
