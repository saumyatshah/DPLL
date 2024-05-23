# DPLL Solver

## Overview
This project involves the implementation of a Davis-Putnam-Logemann-Loveland (DPLL) algorithm in C++. The solver is designed to check the satisfiability of propositional logic formulas in Conjunctive Normal Form (CNF).

## Project Description
The DPLL Solver project focuses on developing a C++ algorithm to determine whether a given CNF logic formula is satisfiable (SAT) or unsatisfiable (UNSAT). The DPLL algorithm is a complete, backtracking-based search algorithm for deciding the satisfiability of propositional logic formulas. It enhances the basic backtracking algorithm with techniques like unit propagation and pure literal elimination to improve efficiency.

### Key Objectives
- Implement the DPLL algorithm in C++.
- Check the satisfiability of propositional logic formulas in CNF.
- Return SAT if the formula is satisfiable, otherwise return UNSAT.

## Key Features
- **DPLL Algorithm Implementation:**
  - Developed a complete implementation of the DPLL algorithm in C++.
  - Utilized unit propagation and pure literal elimination to optimize the solving process.
- **Satisfiability Check:**
  - The algorithm analyzes provided CNF logic formulas.
  - Determines and returns whether the formula is SAT or UNSAT.

## Technical Details
### Tools and Technologies
- **Programming Language:** C++

### Methods
- **Unit Propagation:** Simplifies the formula by assigning values to variables that must be true.
- **Pure Literal Elimination:** Removes literals that appear with only one polarity in the formula.
