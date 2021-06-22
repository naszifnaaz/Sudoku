# Sudoku 
This is a sudoku created using Pygame in python

##Abstract

Sudoku is a logic-based, combinatorial number-placement puzzle. In classic sudoku, the objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid contains all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.

The solver is created using the backtracking algorithm, solving the puzzle recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point of time

## Requirements

+ Install [Python 3.x](https://www.python.org/download/releases/)
+ Install [Pipenv](https://pipenv.readthedocs.io/en/latest/)
+ Install [PyGame 1.9x](https://pipenv.pypa.io/en/latest/)

## How to Run ?

1. Clone the repository:

       $ git clone https://github.com/naszifnaaz/Sudoku
    or download as zip and extract.
    
2. In the root directory, run:

          $ pipenv install
          $ pipenv run python sudoku.py

## How to Play ?

+ Click a box to input a number.
+ Press [Enter] to confirm the number.
+ Press [Delete]  to remove the number.
+ To solve the sudoku automatically, press SPACE and let the algorithm do that for you.

## Future Possibilities

At the moment we only have one puzzle, we can create an external file with a number of puzzle words, which the program can access randomly.

