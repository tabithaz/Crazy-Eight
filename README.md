# Crazy Eights

A Python implementation of the classic card game **Crazy Eights**, where a player competes against a computer opponent. The game follows standard Crazy Eights rules, including suit changes when an eight is played, score tracking, and game-end conditions.

## Features
- **Interactive gameplay** against a computer opponent.
- **Standard Crazy Eights rules**:
  - Match the suit or rank of the up card to play.
  - Play an eight to choose a new active suit.
  - Draw a card if no legal move is available.
- **Computer AI** that:
  - Selects playable cards intelligently.
  - Chooses the most advantageous suit when playing an eight.
- **Scoring system** based on remaining cards in opponent’s hand.
- **Game loop** supports multiple rounds until the player chooses to quit.

## How to Play
1. Both player and computer start with 5 cards.
2. Match the **suit** or **rank** of the up card, or play an eight to change suits.
3. If no playable card, draw from the deck.
4. Round ends when:
   - A player runs out of cards.
   - Both players are blocked (no playable moves and no cards left in the deck).
5. Points are awarded based on opponent’s remaining card values.
6. Play multiple rounds until you choose to exit.

## Tech Stack
- Python 3
- Object-Oriented Programming (OOP) for `Card` class and deck/hand logic.
- Randomization for shuffling and card draws.

## Run the Game
```bash
python Crazy_Eights.py
