# Java ArrayIndexOutOfBoundsException

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`.  The example shows a simple `for` loop that iterates one element past the end of an array, causing the exception.  The solution shows how to correct the loop condition to avoid this error.

## Bug Description
The provided Java code attempts to access an array element beyond its valid index range.  The code uses a loop that iterates until `i <= array.length`, resulting in an attempt to access `array[5]` when the array is of size 5.  This leads to an `ArrayIndexOutOfBoundsException`.

## Bug Solution
The solution modifies the loop's condition to `i < array.length`, ensuring that the loop correctly iterates from 0 to 4 (array.length - 1), thereby avoiding the out-of-bounds access. 