# Guess Fruit Game (Rust CLI)

A simple command-line fruit guessing game built using Rust.  
The player tries to guess the correct fruit chosen randomly by the program.

---

## Features

- Random fruit selection
- Interactive CLI gameplay
- Unlimited attempts (until correct guess)
- Input validation
- Clean and beginner-friendly Rust code

---

## Built With

- Rust
- Standard Library
- rand crate (for random selection)

---

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/guess-fruit-game-using-rust.git
cd guess-fruit-game-using-rust
```

### 2. Add dependency (if not already included)

Make sure your `Cargo.toml` contains:

```toml
[dependencies]
rand = "0.8"
```

### 3. Run the project

```bash
cargo run
```

---

## How to Play

- The program randomly selects a fruit.
- You type your guess in the terminal.
- The game will tell you if your guess is correct or not.
- Keep guessing until you find the correct fruit.

Example:

```
Guess the fruit: apple
Wrong guess! Try again.

Guess the fruit: mango
Correct! You guessed the fruit
```

---

## Project Structure

```
guess-fruit-game-using-rust/
│
├── src/
│   └── main.rs
│
├── Cargo.toml
└── README.md
```

---

## Concepts Used

- Random number generation
- Vectors and Strings
- User input handling
- Conditional statements
- Loop control
- Error handling with Result

---

## Future Improvements

- Add difficulty levels
- Add hints system
- Limit number of attempts
- Track score
- Add replay option

---

## Contributing

Pull requests are welcome.  
Feel free to fork and improve the project.
