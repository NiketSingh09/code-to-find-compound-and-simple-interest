# Simple & Compound Interest Calculator

A beginner-friendly C program that calculates **Simple Interest** or **Compound Interest** based on the values entered by the user.

This project was created to practice basic concepts of the C programming language such as variables, user input, conditional statements, mathematical operations, and the `math.h` library.

## Features

* Calculate Simple Interest
* Calculate Compound Interest
* Accept principal, rate, and time from the user
* Accept the number of times compound interest is calculated per year
* Simple menu-based selection

## Formulas

### Simple Interest

**SI = (P × R × T) / 100**

Where:

* `P` = Principal amount
* `R` = Rate of interest
* `T` = Time period

### Compound Interest

**A = P(1 + R/n)^(nT)**

**CI = A - P**

Where:

* `P` = Principal amount
* `R` = Annual interest rate
* `T` = Time period
* `n` = Number of times interest is compounded per year
* `A` = Final amount
* `CI` = Compound Interest

## Requirements

* A C compiler such as GCC
* Basic terminal/command-line access

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/simple-compound-interest-calculator.git
```

### 2. Navigate to the project folder

```bash
cd simple-compound-interest-calculator
```

### 3. Compile the program

```bash
gcc main.c -o interest_calculator -lm
```

The `-lm` flag links the C math library required for the `pow()` function.

### 4. Run the program

On Windows:

```bash
interest_calculator
```

On Linux/macOS:

```bash
./interest_calculator
```

## Example

```text
Enter the value of principal, rate and time period: 10000 5 2

What do you want to find?
1) Simple Interest
2) Compound Interest
Enter your choice: 1

The simple interest is: 1000.00
```

## Technologies Used

* **C**
* **stdio.h** - input and output
* **math.h** - mathematical functions such as `pow()`

## Learning Goals

This project helped practice:

* Variables and data types
* `printf()` and `scanf()`
* `if` / `else if` / `else`
* Mathematical formulas
* The `pow()` function
* Basic user input handling
* Compiling and running a C program

## Future Improvements

Some possible improvements:

* Add input validation
* Display the final amount along with the interest
* Handle invalid choices
* Add support for more financial calculations
* Improve the user interface

## Author

**DevFromZero**

A beginner C programming project created for learning and practice.
