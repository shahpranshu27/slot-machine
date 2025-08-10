# 🎰 Slot Machine Game

A simple **terminal-based slot machine game** built in Python.  
Deposit money, place bets, spin the reels, and see if you hit the jackpot!

---

## Features
- Bet on **1 to 3 lines**. (adjust lines as per your choice)
- Adjustable bet per line.
- Randomized symbols with different probabilities.
- Winnings calculated based on symbol rarity.
- Play until you run out of balance or quit.

---

## How to Play
1. **Clone the repository**:
   ```bash
   git clone https://github.com/shahpranshu27/slot-machine.git
   cd slot-machine


2. **Run the game**:

   ```bash
   python3 main.py
   ```

3. **Gameplay Flow**:

   * Deposit your starting balance.
   * Choose how many lines to bet on (`1-3`).
   * Set your bet amount per line.
   * Spin the slot machine and see your winnings!
   * Repeat until you quit.

---

## Example Game

```
What would you like to deposit? $50
Enter the number of lines to bet on (1-3)? 3
What would you like to bet on each line? $5
You are betting $5 on 3 lines. Total bet is equal to: $15
C | B | C
D | A | D
B | C | D
You won $10.
You won on lines: 2
Current balance is $45
Press enter to play (q to quit).
```

---

## Game Rules

* The slot machine is **3x3** (3 rows × 3 columns) [adjust this as per your choice].
* Winning occurs when **all symbols match** on a line.
* Symbol probabilities and payouts:

| Symbol | Count (Probability) | Value (Multiplier) |
| ------ | ------------------- | ------------------ |
| A      | 2                   | 5×                 |
| B      | 4                   | 4×                 |
| C      | 6                   | 3×                 |
| D      | 8                   | 2×                 |

---

## Requirements

* Python 3.x
* No external libraries required (uses `random`)

---