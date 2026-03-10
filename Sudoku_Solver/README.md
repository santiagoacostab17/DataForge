# 🧩 Sudoku Solver & Generator

## 📌 Overview
**Python CLI program** to generate and solve 9x9 Sudoku puzzles.  

Demonstrates **backtracking, recursion, object-oriented programming, and logical problem-solving** in a structured workflow.

---

## ⚙️ Workflow

### 1️⃣ System Recognition
- **Domain:** Sudoku puzzle generation and solving.  
- **Goal:** Produce valid, solvable puzzles of adjustable difficulty.  
- **Constraint:** Respect Sudoku rules (unique 1–9 in rows, columns, 3x3 blocks).

### 2️⃣ Data Collection
- Initialize empty 9x9 board.  
- **User input is required** to select difficulty (number of empty cells).

### 3️⃣ Data Cleaning
- Verify initial board validity.  
- Prepare board for puzzle generation.

### 4️⃣ Exploratory Analysis
- Fill board completely using **randomized backtracking**.  
- Remove numbers according to user-selected difficulty.

### 5️⃣ Visualization
- **Console display:** readable 9x9 grid.  
- **Images:**  

**Puzzle:**  
[![Puzzle](./images/sudoku.png)](./images/sudoku.png)  

**Solved Puzzle:**  
[![Solved](./images/sudoku_solved.png)](./images/sudoku_solved.png)

> ⚠️ **Note:** Input is required for plotting. Without it, no images will be generated.

### 6️⃣ Insights / Solver Output
- Solve puzzles automatically using **recursive backtracking**.  
- Display solved board in console and save PNG.

---

## 🚀 Key Features

| Feature | Technique / Concept |
|---------|-------------------|
| Generate puzzles | Randomized backtracking |
| Solve puzzles | Recursive backtracking |
| Adjustable difficulty | 20–60 empty cells (input required) |
| Visualization | Console & PNG images |
| Modular & readable | Classes & functions |

---

## 🛠️ How to Run

```bash
python sudoku_solver_clean.py
