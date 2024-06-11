# Change Calculator

This is a simple C program that calculates the minimum number of coins needed to make change for a given amount of cents. It breaks down the amount into quarters, dimes, nickels, and pennies.

## Table of Contents

- [Overview](#overview)
- [How It Works](#how-it-works)
- [Functions](#functions)
- [Usage](#usage)
- [Compiling and Running](#compiling-and-running)
- [Example](#example)

## Overview

The program prompts the user to enter the amount of cents owed and calculates the number of quarters, dimes, nickels, and pennies required to make that amount. It then prints the total number of coins needed.

## How It Works

1. The user is prompted to input the number of cents.
2. The program calculates the number of quarters, dimes, nickels, and pennies needed.
3. It subtracts the value of these coins from the total amount of cents.
4. The program prints the total number of each type of coin and the total number of coins.

## Functions

- `int get_cents(void)`: Prompts the user to enter a positive integer for the amount of cents.
- `int calculate_quarters(int cents)`: Calculates and returns the number of quarters needed.
- `int calculate_dimes(int cents)`: Calculates and returns the number of dimes needed.
- `int calculate_nickels(int cents)`: Calculates and returns the number of nickels needed.
- `int calculate_pennies(int cents)`: Calculates and returns the number of pennies needed.

## Usage

1. Clone or download the program files.
2. Compile the program using a C compiler (e.g., GCC).
3. Run the compiled executable.
4. Enter the number of cents when prompted.

## Compiling and Running

To compile and run the program, use the following commands in your terminal:

```sh
gcc -o change_calculator change_calculator.c -lcs50
./change_calculator
```

## Example

```sh
$ ./change_calculator
Enter how many cents the customer is owed: 87
Total number of Quarters: 3
Total number of Dimes: 1
Total number of Nickels: 0
Total number of Pennies: 2
Total Coins to be returned: 6
```

In this example, the user inputs 87 cents, and the program calculates that the change should include 3 quarters, 1 dime, 0 nickels, and 2 pennies, totaling 6 coins.
