# Slot Machine (Python)

A command-line slot machine game built in Python that simulates real betting mechanics, including balance management, line-based wagering, and weighted symbol payouts.

---

## Overview

This project implements a terminal-based slot machine where users can:
- Deposit money and manage a running balance
- Place bets across multiple paylines
- Spin a randomized 3×3 slot grid
- Earn payouts based on matching symbols and predefined odds

The project focuses on applying core Python concepts to model real-world game logic in a clean, interactive CLI application.

---

## Features & Key Concepts

- Interactive command-line gameplay with validated user input
- Balance tracking with deposit limits and bet validation
- Line-based betting (1–3 horizontal paylines)
- Weighted random symbol generation using dictionaries
- Variable payouts based on symbol rarity and predefined multipliers
- Control flow using loops and conditionals to manage game logic
- State management for balance, bets, and winnings
- Modular, function-based Python program design

---

## Tech Stack

- **Language:** Python 3  
- **Libraries:** Python Standard Library (`random`)  
- **Interface:** Command Line (CLI)

---

## Getting Started

### Prerequisites
- Python 3 installed
- Terminal / Command Prompt

## How it Works 
- The user deposits an initial balance.
- The user selects:
- Number of lines to bet on (1–3)
- Bet amount per line
- The total bet is validated against the current balance.
- A 3×3 slot grid is generated using weighted symbol probabilities.
- Each selected line is checked for matching symbols.
- Winnings are calculated using symbol-specific payout multipliers.
-The user’s balance is updated after each spin until they quit.

## Symbols Odds and Payouts

| Symbol | Frequency | Payout Multiplier |
|--------|-----------|-------------------|
| A      | 2         | 5×                |
| B      | 4         | 4×                |
| C      | 6         | 3×                |
| D      | 8         | 2×                |

Lower-frequency symbols have higher payouts.

