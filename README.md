
# GCD Calculator

A simple Python program that calculates the Greatest Common Divisor (GCD) of two positive integers using the Euclidean algorithm.

## Overview

This program takes two positive integers as input and returns their GCD using an efficient iterative approach.

## How It Works

The GCD is calculated using the Euclidean algorithm:
- Repeatedly replace the larger number with the remainder of dividing the larger by the smaller
- Continue until the remainder is zero
- The last non-zero remainder is the GCD

## Usage

```bash
python gcd.py
```

Enter two positive integers when prompted.

## Example

```
Enter the first positive integer: 48
Enter the second positive integer: 18
The Greatest Common Divisor of 48 and 18 is: 6
```

## Time Complexity

**O(log(min(a, b)))** - Very efficient even for large numbers.
