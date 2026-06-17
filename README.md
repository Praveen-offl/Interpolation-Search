# Interpolation Search vs Binary Search Performance Analysis

## Overview

This project implements and compares two searching algorithms:

1. Interpolation Search
2. Binary Search

The program measures:

- Execution Time (milliseconds)
- Number of Comparisons

for different array sizes and displays the performance results in a tabular format.

---

## Algorithms Used

### Binary Search

Binary Search repeatedly divides a sorted array into halves until the target element is found.

**Time Complexity:**
- Best Case: O(1)
- Average Case: O(log n)
- Worst Case: O(log n)

---

### Interpolation Search

Interpolation Search estimates the probable position of the target based on the values of the elements.

**Time Complexity:**
- Best Case: O(1)
- Average Case: O(log log n) (for uniformly distributed data)
- Worst Case: O(n)

---

## Features

- Implements Binary Search from scratch.
- Implements Interpolation Search from scratch.
- Counts the number of comparisons performed.
- Measures average execution time.
- Tests multiple input sizes.
- Displays results in a formatted table.

---

## Sample Output
