# Compound Interest Calculator

This is a simple Java command-line program that calculates the amount of money accumulated after a certain number of years using compound interest.

## File

- `Main.java`: The only source file containing the program logic.

## What It Does

The program prompts the user to input:
- Initial principal amount
- Interest rate (in percentage)
- Number of times the interest is compounded per year
- Number of years the money is invested or borrowed for

It then calculates and displays the final amount after applying compound interest using the formula:
  A = P * (1 + r/n)^(nt)

Where:
- `A` is the amount after time `t`
- `P` is the principal amount
- `r` is the annual interest rate (decimal)
- `n` is the number of times the interest is compounded per year
- `t` is the number of years

## How to Run

1. Make sure you have Java installed on your system.
2. Save the code in a file named `Main.java`.
3. Open your terminal or command prompt.
4. Compile the program:
   javac Main.java
5. Run the compiled program:
   java Main

## Dependencies

- No external libraries or front-end; uses standard Java packages only.

## Notes

- This project is designed to run in the console.
- It uses `Scanner` for user input and basic `Math` functions for calculations.
