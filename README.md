# sudoku_solver
This C++ code can solve 9x9 sudoku puzzles using Backtracking Algorithm!

![Screenshot from 2019-05-07 21-40-20](https://user-images.githubusercontent.com/36446402/57315344-04c65400-7111-11e9-939c-fce34eb7ceea.png)


## **Backtracking Algorithm**

Backtracking is a general algorithm for finding all (or some) solutions to some computational problems, that incrementally builds candidates to the solutions, and abandons each partial candidate (“backtracks”) as soon as it determines that the candidate cannot possibly be completed to a valid solution.
Abandoning a candidate typically results in visiting a previous stage of the problem-solving-process. This is what it means to “backtrack” — visit a previous stage and explore new possibilities from thereon.

Usually, apart from the original problem and the end goal, we also have a set of constraints that the solution must satisfy.

#### Sudoku Problem
Given a, possibly, partially filled grid of size 9x9, completely fill the grid with number between 1 and 9.

A fully filled grid is a solution if:

1. Each row has all numbers form 1 to 9.
2. Each column has all numbers form 1 to 9.
3. Each sub-grid (if any) has all numbers form 1 to 9.



![Sudoku_solved_by_bactracking](https://user-images.githubusercontent.com/36446402/57313700-bf545780-710d-11e9-9eb1-34979e604291.gif)
