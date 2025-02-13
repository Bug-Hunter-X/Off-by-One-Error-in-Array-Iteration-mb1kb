# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java that can lead to an `ArrayIndexOutOfBoundsException`. The error occurs when iterating over an array and the loop condition is not properly checked to prevent accessing elements beyond the array's bounds.

The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version.

## How to reproduce

1. Clone this repository.
2. Compile and run `BuggyArray.java`. You will observe an `ArrayIndexOutOfBoundsException`.
3. Run `FixedArray.java` to see the corrected output.