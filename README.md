# 🃏 Blackjack Game in Python

A simple **Blackjack game** implemented in Python, where the player competes against a virtual dealer.
The game simulates basic rules, handles card decks, and provides player and dealer decision-making logic.

## ✨ Features
- 🌀 **Deck of Cards**: The deck is shuffled at the start of each game.
- 🎯 **Player Decision**: The player can choose to:
  - 🃏 "Hit" (get another card).
  - ✋ "Stand" (keep the current hand).
- 🔢 **Score Calculation**: Scores are calculated based on the value of the cards:
  - Aces can count as either **1** or **11**.
- 🛡 **Dealer Logic**: The dealer hits until reaching a score of **17** or higher.

---

## 🛠 Explanation
### 🎴 Classes:
- **🂠 Card Class**: Represents individual cards, including their rank and suit.
- **🃏 Deck Class**: Handles the deck of cards, shuffling, and dealing cards.
- **✋ Hand Class**: Represents the player's or dealer's hand and computes the total score, accounting for Aces that can be **1** or **11**.

### 🔄 Gameplay Flow:
1. Both the **player** and the **dealer** are dealt two cards.
2. The player can choose to:
   - 🃏 **Hit**: Draw a card.
   - ✋ **Stand**: End their turn.
3. The dealer hits until their score is **17** or higher.
4. Compare the player’s and dealer’s final scores to determine the winner.

## 🎮 Sample Gameplay

Welcome to Blackjack!

Player's hand: 8 of Spades, 5 of Hearts
Player's score: 13

Dealer's hand: 10 of Diamonds and a hidden card

Do you want to 'hit' or 'stand'? hit

Player's hand: 8 of Spades, 5 of Hearts, 7 of Clubs
Player's score: 20

Dealer's hand: 10 of Diamonds and a hidden card

Do you want to 'hit' or 'stand'? stand

Dealer hits.
Dealer's hand: 10 of Diamonds, 6 of Hearts
Dealer's score: 16

Dealer hits.
Dealer's hand: 10 of Diamonds, 6 of Hearts, 9 of Spades
Dealer's score: 25
Dealer busted! You win!
```

## 📋 Features Overview
- 🔄 *Card Shuffling*: Deck is shuffled at the start of each game.
- 🎯 *Player Choices: Decide to **hit* or *stand*.
- 🛡 *Dealer Rules: Dealer hits until they have **17* or more points.
- 🔢 *Score Handling: Aces count as **11* or *1*, depending on the total score.

## 🚀 Future Enhancements
- 💰 *Betting System*: Add a betting feature to make the game more engaging.
- ♻ *Multiple Rounds*: Play multiple rounds in one session.
- 🖥 *GUI*: Use libraries like tkinter to build a graphical interface.

