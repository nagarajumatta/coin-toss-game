# Coin Toss Game

Welcome to the Coin Toss Game! This project is a simple simulation of a coin toss, where users can interactively toss a coin and view the results.

## Project Structure

```
coin-toss-game
├── src
│   ├── main.py          # Entry point of the game
│   ├── game
│   │   ├── __init__.py  # Game module initialization
│   │   └── coin_toss.py # Contains the CoinToss class
│   └── utils
│       ├── __init__.py  # Utilities module initialization
│       └── statistics.py # Contains functions for calculating statistics
├── tests
│   ├── __init__.py      # Tests module initialization
│   └── test_coin_toss.py # Unit tests for the CoinToss class
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

## How to Run the Game

1. **Clone the repository:**
   ```
   git clone https://github.com/nagarajumatta/coin-toss-game.git
   cd coin-toss-game
   ```

2. **Install the required dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Run the game:**
   ```
   python src/main.py
   ```

## Features

- Toss a coin and get a random result (Heads or Tails).
- View the results of previous tosses.
- Calculate and display statistics related to the toss results.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements for the project!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.