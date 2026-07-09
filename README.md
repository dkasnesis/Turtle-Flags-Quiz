# 🚩 Flag Guessing Game

A fun terminal-based flag guessing game built with Python's `turtle` graphics module. Flags are drawn procedurally (no image files needed!) and the player has to identify each one by typing its name.

## How It Works

- A flag is randomly selected and drawn on screen using turtle graphics.
- You type your guess into the terminal.
- Guess correctly → you earn a point and the flag is removed from the pool.
- Guess incorrectly → you lose a life.
- Run out of lives (3 total) → game over.
- Correctly identify every flag → you win!

Your current score and remaining lives are displayed at the top of the game window and update after every round.

## Flags Included

The game currently features 12 procedurally drawn flags:

- 🇯🇵 Japan
- 🇵🇱 Poland
- 🇦🇹 Austria
- 🇮🇹 Italy
- 🇫🇷 France
- 🇳🇴 Norway
- 🇺🇦 Ukraine
- 🇩🇪 Germany
- 🇧🇸 Bahamas
- 🇹🇿 Tanzania
- 🇷🇺 Russia
- 🇰🇼 Kuwait

## Requirements

- Python 3.x
- `turtle` module (included in the standard library)

> **Note:** `turtle` requires a display environment (it won't run in a headless server or some cloud notebooks). It works fine on a standard desktop Python installation.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flag-guessing-game.git
   cd flag-guessing-game
   ```

2. Run the game:
   ```bash
   python flag_game.py
   ```

3. When prompted in the terminal, type the name of the flag shown in the turtle graphics window (lowercase, e.g. `japan`, `poland`, `italy`) and press Enter.

## Gameplay Rules

| Rule | Detail |
|---|---|
| Lives | You start with 3 lives |
| Hints | 3 hints are tracked (displayed on screen) |
| Win condition | Correctly guess all 12 flags before running out of lives |
| Lose condition | Lose all 3 lives before guessing every flag |

## Project Structure

```
.
├── flag_game.py    # Main game script
└── README.md       # This file
```

## Contributing

Contributions are welcome! Some ideas for extending the game:

- Add more countries' flags
- Implement the hint system (currently tracked but not yet functional)
- Add difficulty levels or a timer
- Refactor flag-drawing functions to reduce code duplication (e.g. a generic tricolor-flag helper)

Feel free to open an issue or submit a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).
