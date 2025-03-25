# 🎲 Dice Game

A simple and interactive 2-player dice game built using JavaScript, HTML, and CSS. The objective is to be the first player to reach a total score of 100. This game encourages risk and strategy—roll the dice to accumulate points, but beware of rolling a 1!

---

## 📜 Rules

1. Two players take turns.
2. On each turn, a player rolls a dice:
   - If the roll is **not 1**, the value is added to their **current score**.
   - If the roll **is 1**, the current score is lost, and the turn passes to the other player.
3. At any point during their turn, a player can **"Hold"**:
   - The current score is added to their **total score**.
   - The turn passes to the other player.
4. The first player to reach **100 points** in total wins.
5. A **"New Game"** button resets all scores and starts from scratch.

---

## 🧠 Game Flow (Based on Flowchart)

- **User rolls dice** → Generate random dice roll → Display result
  - If roll ≠ 1 → Add to current score → Display updated score
  - If roll = 1 → Current score is reset → Switch player
- **User holds score** → Add current score to total score
  - If total ≥ 100 → Player wins
  - Else → Switch player
- **User resets game** → All scores reset to 0 → Player 1 starts

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge)
- No installations required!

### Running the Game

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/dice-game.git
   ```
2. Open `index.html` in your browser.
3. Start playing!

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## 📁 Project Structure

```
Dice Game/
│
├── index.html        # Game UI
├── style.css         # Styling
├── script.js         # Game logic
└── assets/           # Dice images (if any)
```

---

## 🙌 Acknowledgments

Inspired by beginner-friendly JavaScript game ideas to strengthen DOM manipulation and event handling skills.

---

## 🧑‍💻 Author

**Karthik Kashyap R P**
