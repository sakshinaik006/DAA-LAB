Aim
To implement the Quick Sort algorithm in Java and analyze its execution time for a large set of randomly generated elements.

Introduction
Quick Sort is a divide-and-conquer sorting algorithm. It works by selecting a pivot element, partitioning the array such that elements smaller than the pivot are placed on the left and larger elements on the right, and then recursively applying the same process to the subarrays. In this experiment, the execution time of Quick Sort is measured using system time functions.

Algorithm
1. Generate `n` random integer elements.
2. Choose the first element as the pivot.
3. Partition the array into two subarrays based on the pivot.
4. Recursively apply Quick Sort to the left and right subarrays.
5. Measure the execution time using `System.nanoTime()`.
6. Display the number of elements and execution time.

Source Code
The Java implementation of the Quick Sort algorithm along with execution time measurement is provided in this folder.

Input
- Number of elements: `6000`
- Randomly generated integer values
Output
- Number of elements
- Execution time in nanoseconds
- Execution time in milliseconds

Time Complexity
- Best Case: O(n log n)
- Average Case: O(n log n)
- Worst Case: O(n²)

Result
Quick Sort was successfully implemented in Java. The execution time for sorting 6000 randomly generated elements was measured and displayed accurately.
