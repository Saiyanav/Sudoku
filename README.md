A simple Python script that solves Sudoku puzzles using backtracking.

📌 **Features**

    Solves any valid 9x9 Sudoku puzzle

    Uses a backtracking algorithm

    Easy-to-read console output

🛠️ **Requirements**

    Python 3.x

No additional dependencies required.


🚀 **How to Use**

Clone the repository:

    git clone https://github.com/Saiyanav/Sudoku.git
    cd Sudoku

Run the solver:

    python sudoku_solver.py

Edit the puzzle inside the script if needed (look for the board variable).


🧠 **Algorithm**

The solver uses a classic backtracking approach:

    Try filling each empty cell with a valid number

    Recursively move forward

    Backtrack if no valid number leads to a solution


📄 **Example**

Given this input:

    5 3 0 | 0 7 0 | 0 0 0
    6 0 0 | 1 9 5 | 0 0 0

The script will output the completed board.


📬 **License**

This project is open-source and available under the MIT License.
