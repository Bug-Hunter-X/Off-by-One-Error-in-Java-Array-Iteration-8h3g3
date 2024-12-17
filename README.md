# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The code attempts to sum the elements of an array, but due to an incorrect loop condition, it throws an `ArrayIndexOutOfBoundsException`.  The solution demonstrates the correct way to iterate using the `<` operator instead of `<=`.

The bug and solution are provided in separate Java files, `Bug.java` and `BugSolution.java` respectively.  The `Bug.java` file contains the code with the error, while `BugSolution.java` provides the corrected code.