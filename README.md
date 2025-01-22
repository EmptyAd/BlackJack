# 🃏 Blackjack Game

A command-line implementation of the classic card game **Blackjack**! Test your luck and strategy by playing against the computer in this Python-based game.

---

## 📜 How It Works

1. Each player (you and the computer) starts with two cards.
2. You can choose to "hit" (draw another card) or "stand" (end your turn).
3. The goal is to get as close to 21 as possible without exceeding it.
4. The computer follows fixed rules:
   - Draw cards until its score is 17 or higher.
   - Automatically stops at or above 17 unless it has Blackjack.
5. The winner is decided based on the following:
   - A score of **21** with two cards is a **Blackjack** (highest priority).
   - Scores exceeding **21** result in a **bust** and a loss.
   - Otherwise, the closest score to 21 wins.

---

## 🛠️ Features

- **Dynamic Gameplay:** Randomized card dealing ensures an engaging experience.
- **Blackjack Detection:** Automatic handling of special rules for Blackjack.
- **Clear Outcome Messages:** Displays results with explanations (e.g., "You win," "Opponent went over").
- **Replay Option:** Restart the game easily.

---

## 🚀 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blackjack-game.git
   cd blackjack-game
   ```
2. Ensure Python is installed on your system.
3. Run the game:
   ```bash
   python main.py
   ```

---

## 🖥️ Demo

```
If you want to play BlackJack, type 'y' or 'n': y
 Your cards: [9, 7], current score: 16
 Computer's First card: 6
Type 'y' to add another card, type 'n' to pass: y
 Your cards: [9, 7, 4], current score: 20
 Computer final hand: [6, 9, 5], final score: 20
Draw
```

---

## 📂 Code Features

- **Card Dealing:** Randomly selects cards from a standard deck.
- **Score Calculation:** Handles rules like:
  - Ace can count as **1** or **11**.
  - Automatic handling of Blackjack and bust scenarios.
- **Comparison Logic:** Determines the game outcome based on scores.

---

## 🎮 Controls

- **'y':** Draw another card (hit).  
- **'n':** End your turn (stand).  

---
