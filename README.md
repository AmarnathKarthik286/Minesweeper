# 💣 Terminal Minesweeper in C++

A **terminal-based Minesweeper game** built in C++ with colored console output for a more interactive experience. Choose difficulty, reveal safe spots, flag mines, and avoid triggering them!

## 🧩 Features

- ✅ Easy, Medium, and Hard difficulty levels
- ✅ First move is always safe
- ✅ Colored cell numbers using ANSI escape codes
- ✅ Recursive reveal for empty cells
- ✅ Flag and unflag cells
- ✅ Input validation
- ✅ Win/loss detection

## 🎮 How to Play

1. **Compile the code:**

   ```bash
   g++ -o minesweeper minesweeper.cpp
   ```

2. **Run the game:**

   ```bash
   ./minesweeper
   ```

3. **Commands:**

   - Input format: `row column command`
     - `R` to Reveal
     - `F` to Flag/Unflag
   - Example:
     ```
     3 4 R
     ```
     Reveals the cell at row 3, column 4.

4. **Goal:**
   - Reveal all non-mine cells to win.
   - If you reveal a mine, the game is over.

## 🎨 Color Legend

| Cell | Meaning        | Color     |
|------|----------------|-----------|
| `*`  | Hidden Cell    | Default   |
| `F`  | Flag           | Red       |
| `0`  | Empty Cell     | White (dot `.`) |
| `1`  | 1 adjacent mine| Blue      |
| `2`  | 2 adjacent mines | Green    |
| `3`  | 3 adjacent mines | Red     |
| `4`  | 4 adjacent mines | Magenta |
| `5`  | 5 adjacent mines | Yellow  |
| `6`  | 6 adjacent mines | Cyan    |
| `7`  | 7 adjacent mines | White   |
| `8`  | 8 adjacent mines | Gray    |

> Colors may vary slightly depending on terminal.

## 📁 Files

```
minesweeper.cpp   # Main game source
README.md         # Project info
```

## ⚙️ Requirements

- C++11 or above
- A terminal that supports ANSI escape codes
  - ✅ Linux/macOS terminals
  - ⚠️ On Windows, use WSL or a compatible terminal like Git Bash

## 🚀 Future Ideas

- Add a timer
- Custom board size and mine count
- GUI version using SFML or Qt

## 📜 License

This project is open-source and available under the **MIT License**.
