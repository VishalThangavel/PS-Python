# Python Practice Question Bank

A collection of 41 practice problems for coding assessments, grouped by topic. Duplicates from the original list have been merged.

## Contents

1. [Math and Number Theory](#1-math-and-number-theory)
2. [Number and Format Conversion](#2-number-and-format-conversion)
3. [Strings](#3-strings)
4. [Arrays, Lists and Matrices](#4-arrays-lists-and-matrices)
5. [DP, Greedy and Heap](#5-dp-greedy-and-heap)
6. [Dictionaries and Simulation](#6-dictionaries-and-simulation)

---

## 1. Math and Number Theory

| # | Question | Sample / Notes |
|---|---|---|
| 1 | Circular prime | |
| 2 | Prime factors of N (with repeats) | `56` → `[2, 2, 2, 3, 7]` |
| 3 | Prime numbers in a given range | Two inputs |
| 4 | Combinations nCr = n! / (r!(n−r)!) | |
| 5 | Maximum digit sum of pairwise products | `8 6 7` → products 48, 56, 42 → digit sums 12, 11, 6 → **12** |
| 6 | Quadratic equation solver | |
| 7 | Middle number identification | |
| 8 | Separate primes, composites and negatives (negatives sorted) | `2 3 4 5 -3 -2 -7` → `[2,3,5]`, `[4]`, `[-2,-3,-7]` |
| 9 | Maximum product of three numbers | `[-10,-3,5,6,-20]` → **1200** |
| 10 | Product of all numbers in an input string | `2,3.5,4,5.5,2,3,4,56` → float product |
| 11 | Area of circle, triangle and rectangle | Use `math.pi` |
| 12 | Volume of cylinder and sphere, area of triangle | Use `math.pi` |
| 13 | Fibonacci series (iterative, as a list) | |
| 14 | Print integers from N to -1 | `-5` → `-4 -3 -2 -1` |

## 2. Number and Format Conversion

| # | Question | Sample / Notes |
|---|---|---|
| 15 | Decimal to binary (integer and fractional parts) | `25.75` → `11001.11`, `15` → `1111` |
| 16 | Decimal to binary with 7-digit precision | Learn exception handling |
| 17 | 12-hour ↔ 24-hour time | |
| 18 | Integer to English Words | LeetCode |

## 3. Strings

| # | Question | Sample / Notes |
|---|---|---|
| 19 | Replace characters in a string with other characters or symbols | |
| 20 | Print the longest word | `programming python` → `programming` |
| 21 | Check for more than 3 consecutive consonants | `banana` → yes, `strength` → no |
| 22 | Check for no 3 consecutive consonants | `apple` → NO, `banana` → YES |
| 23 | Interleave two strings (recursive) | `ab`, `cd` → `abcd acbd acdb cabd cadb cdab` |
| 24 | Keyboard Row | LeetCode |
| 25 | Maximum Product of Word Lengths | LeetCode |
| 26 | Permutation in String | LeetCode |

## 4. Arrays, Lists and Matrices

| # | Question | Sample / Notes |
|---|---|---|
| 27 | Tuples of numbers and their squares in a range | `2 4` → `[(2,4),(3,9),(4,16)]`; `101 99` → Invalid Range; `101 101` → Equal range |
| 28 | Two Out of Three (result sorted ascending) | LeetCode |
| 29 | Intersection of Two Arrays | LeetCode |
| 30 | Minimum element shared by both arrays | |
| 31 | Matrix multiplication | |
| 32 | Special Discount (subtract the first smaller-or-equal price to the right) | `8 4 6 2 3` → `4 2 4 2 3` |
| 33 | Last Visited Integers | LeetCode |
| 34 | Poisoned Duration | `[2,4,6]`, `2` → `7` |

## 5. DP, Greedy and Heap

| # | Question | Sample / Notes |
|---|---|---|
| 35 | [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/description/) | LeetCode |
| 36 | [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/description/) | LeetCode |
| 37 | House Robber | Use memoization and recursion |
| 38 | Last Stone Weight | LeetCode |
| 39 | Minimum Amount of Time to Fill Cups | LeetCode |

## 6. Dictionaries and Simulation

| # | Question | Sample / Notes |
|---|---|---|
| 40 | Depth of a nested dictionary | |
| 41 | ATM program | Convert a single input into a list of withdrawal amounts, take the ATM balance, and pass both to a function that reports whether each withdrawal is possible, updating the balance |