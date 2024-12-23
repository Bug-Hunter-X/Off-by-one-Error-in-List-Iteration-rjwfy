# Off-by-One Error in Dart List Iteration

This example demonstrates a common off-by-one error in Dart when iterating over a list using a `for` loop.  The error occurs because the loop condition `i <= numbers.length` attempts to access an index that is beyond the bounds of the list.  Lists in Dart (and most programming languages) are zero-indexed, meaning the valid indices range from 0 to `length - 1`.

The solution shows how to correctly iterate using `i < numbers.length` to avoid the error.