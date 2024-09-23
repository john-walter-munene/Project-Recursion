# Project: Recursion

## Overview

This project demonstrates my understanding of recursion as a problem-solving paradigm by implementing classic recursive algorithms such as Fibonacci sequence generation and Merge Sort. Through both iterative and recursive approaches, I explore the power of recursion and its application in sorting algorithms.

## Features

- **Fibonacci Sequence**: 
  - Implemented both iterative and recursive solutions for generating Fibonacci sequences.
  - Optimized iterative and recursive versions to reduce overhead and improve performance.
  
- **Merge Sort Algorithm**: 
  - Developed a recursive merge sort algorithm, which divides an unsorted array into smaller subarrays, sorts them recursively, and then merges them back together to form a sorted array.

## Algorithms Implemented

### 1. Fibonacci Sequence

The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones, starting from 0 and 1. In this project, I have implemented two approaches to generate Fibonacci sequences:

- **Iterative Approach**: This solution uses a loop to generate the Fibonacci numbers, optimized to minimize array length checks during each iteration.
  
- **Recursive Approach**: This version uses recursion to build the Fibonacci sequence. Additionally, an optimized recursive version is provided that reduces redundant function calls.

### 2. Merge Sort

Merge Sort is a classic divide-and-conquer algorithm that recursively divides an array into two halves, sorts each half, and merges them back together.

- **Recursive Merge Sort**: This implementation uses recursion to sort an array by splitting it into smaller subarrays and merging the sorted subarrays.
  
- **Alternative Merge Sort**: An alternative version that emphasizes the merging process and showcases recursion in splitting the array.

## Usage

There is no user interface (UI) for this project. The algorithms can be tested using a command line or JavaScript runtime environments like Node.js.

### Example Usage:

To test the Fibonacci sequence, you can run the following in the console:

```js
console.log(fibonacciIterativeTwo(8)); // [0, 1, 1, 2, 3, 5, 8, 13]
console.log(fibRecTwo(8)); // [0, 1, 1, 2, 3, 5, 8, 13]
```

To test the Merge Sort algorithm, you can run:

```js
console.log(alternativeMergeSort([100, 3, 2, 1, 13, 8, 5, 0, 1, 98]));
// Output: [0, 1, 1, 2, 3, 5, 8, 13, 98, 100]
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/john-walter-munene/Project-Recursion
   ```
2. Navigate to the project directory:
   ```bash
   cd project-recursion
   ```

3. Run the JavaScript file with Node.js or in a browser console:
   ```bash
   node index.js
   ```

## Lessons Learned

- **Recursion** is a powerful tool that can be used to break down complex problems into smaller, more manageable parts. However, care must be taken to handle base cases and avoid excessive memory usage with large recursion depths.
  
- **Iterative solutions** can often be optimized for performance and may be easier to understand for some problems.

- **Merge Sort** provided insight into how recursive algorithms can be used in sorting algorithms, offering an alternative to iterative approaches like Bubble Sort or Quick Sort.