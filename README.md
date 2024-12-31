# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its valid index range. This results in a runtime exception. The `bugSolution.java` file provides a corrected version.

## How to reproduce

1. Clone this repository.
2. Compile `bug.java` using a Java compiler (e.g., `javac bug.java`).
3. Run the compiled code (e.g., `java bug`).

You will see the `ArrayIndexOutOfBoundsException`.

## Solution

The issue is resolved in `bugSolution.java` by modifying the loop condition to `i < arr.length`.