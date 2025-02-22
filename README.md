# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The provided code attempts to access an array element beyond its valid index range, leading to a runtime exception.

## Bug Description

The `bug.java` file contains a simple Java program that initializes an integer array and then iterates through it.  The loop condition incorrectly uses `i <= arr.length`, causing an attempt to access index 5 (which is out of bounds for an array of length 5).

## Solution

The `bugSolution.java` file shows how to fix this bug by changing the loop condition to `i < arr.length`. This ensures that only valid indices are accessed.