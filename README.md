# 🧠 Sudoku Generator & Solver

A complete Sudoku generator, puzzle creator, and solver built with Python using Jupyter Notebook. This project creates a valid filled 9x9 Sudoku board, removes a configurable number of cells to form a playable puzzle, displays it in a readable format, and optionally solves it.

## 📌 Features

- ✅ Generates a fully valid Sudoku solution  
- 🧩 Creates playable puzzles by removing numbers  
- 🔁 Solves puzzles using backtracking algorithm  
- 🎨 Pretty-printed grid with subgrid separation  
- 💡 Adjustable difficulty by setting number of holes  

---

## 🛠️ Setup

```bash
git clone https://github.com/CauaMaia/Sudoku-Generator-and-Solver.git     
cd Sudoku-Generator-and-Solver      
```

> Make sure you have **Python 3.7+** installed.  
> If you're using **Visual Studio Code**, install the official [Jupyter extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) to run and interact with `.ipynb` files seamlessly.

---

## 🔎 Usage

1. Open the notebook:

```bash
jupyter notebook sudoku.ipynb
```

2. Run the cells in order:
   - The notebook will generate a full Sudoku solution
   - Create a puzzle by removing cells
   - Display the board
   - Optionally solve it using backtracking

---

## 🧪 Example Output

```
🧩 Sudoku Puzzle:
7 . . | . 9 1 | 4 8 .
. 9 3 | 7 . . | . . 2
. 1 . | . . 8 | . 7 3
---------------------
4 . 7 | 5 3 . | . . .
. 3 . | . . . | . 6 .
. . . | . 4 2 | 8 1 9
---------------------
3 4 9 | 2 . . | . 5 .
2 . . | . . 4 | 3 9 .
. 7 8 | 9 1 . | . . 6
```

---

## ⚙️ Configuration

To change the difficulty of the puzzle, modify this line in the notebook:

```python
puzzle_grid = make_puzzle(full_grid, num_holes=40)
```

Suggested values:

- `num_holes = 30` → Easy  
- `num_holes = 40` → Medium  
- `num_holes = 50+` → Hard  

---

## 📂 Project Structure

```
Sudoku-Generator-and-Solver/
├── sudoku.ipynb       # Main notebook
├── README.md          # Project documentation
```

---

## 🧠 Algorithms Used

- **Backtracking** for solving the board  
- **Randomized shuffling** to generate unique boards  
- **Grid validation** using subgrid, row, and column constraints  

---

## 👨‍💻 Author

Made by [Cauã Maia](https://github.com/CauaMaia)
