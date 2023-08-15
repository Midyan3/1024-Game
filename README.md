
# Project Title: "Board Management System in C++"

## Introduction
This is a remake of the classic game of 1024. The game is played on a grid, and you can choose the size when starting a new game. Each turn, you can shift the numbers on the board left, right, up, or down. When two numbers that are next to each other are the same, they merge into one, doubling their value!

## Member Functions:
### Constructor Overloads:
- **Default Constructor**
- **Constructor with one parameter (square board)**
- **Constructor with two parameters (rectangular board)**

### Destructor: 
- Frees the dynamically allocated memory.

 ### Public:
- `print()`: Prints the current state of the board.
- `selectRandomCell(int& row, int& col)`: Selects a random cell in the board.
- `noAdjacentSameValue()`: Checks for any adjacent cells with the same value.
- `pressLeft()`: Action when the left key is pressed.
- `pressRight()`: Action when the right key is pressed.
- `pressUp()`: Action when the up key is pressed.
- `pressDown()`: Action when the down key is pressed.
  
## Requirements
- **Compiler:** C++11 or higher
- **Library:** Standard C++ libraries

## License
This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
