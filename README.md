# Extended Euclidean Algorithm

This program implements the Extended Euclidean Algorithm to calculate the greatest common divisor (GCD) and find the coefficients for Bézout's identity. It also provides inverses modulo for two given integers.

## Execution Instructions

### Prerequisites
- C++ compiler
- Windows operating system (due to the use of `windows.h` for clearing console)

### How to Run
1. Clone the repository or download the source code.
2. Compile the program using a C++ compiler.
3. Execute the compiled binary.

## Usage
- Upon execution, the program will prompt for input values for `m` and `n`.
- It will then display a table showcasing the calculations and iterations involved in the Extended Euclidean Algorithm.
- Finally, it will output the GCD of `m` and `n`, along with the coefficients satisfying Bézout's identity.

## Code Overview
- The program uses the Extended Euclidean Algorithm to calculate the GCD and Bézout coefficients for two input numbers.
- It displays a table illustrating the variable changes in each iteration of the algorithm.
- Additionally, it provides information about the modular inverses if the GCD is 1.

## Sample Execution

```
// Insert a sample execution code snippet if needed
// Ensure it reflects how to use the program with input and output
// For example:
// NWD(m,n)
// M: 56
// N: 15
// Output:
// NWD(56,15) = 1
// 1 = (-4)*56 + (15)*15
// ...
```

## Note
- This program utilizes windows.h specifically for clearing the console, making it compatible with Windows systems.
