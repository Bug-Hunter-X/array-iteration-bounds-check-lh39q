# Off-by-One Error in Java Array Iteration
This repository demonstrates a common off-by-one error in Java that can lead to an `ArrayIndexOutOfBoundsException`.  The error stems from an incorrect loop condition when iterating over an array. 

## The Bug
The `Bug.java` file contains code that attempts to initialize an array and populate it. The for loop has an incorrect upper bound, leading to an attempt to access an index that is out of bounds. 

## The Solution
The `BugSolution.java` file provides the corrected code with a modified for loop to avoid the index out of bounds issue. The loop condition is changed to iterate up to (but not including) the array's length, thus correctly addressing the off-by-one error. 

## How to Reproduce
1. Compile and run `Bug.java`. Observe the resulting exception.
2. Compile and run `BugSolution.java`. Observe the correct output.