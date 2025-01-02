# MongoDB $inc operator type error
This example demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value.  However, if you provide a string value instead of a number, it will result in an error or unexpected behavior.

The `bug.js` file contains the erroneous code, and `bugSolution.js` provides the corrected version.

## How to reproduce the bug
1. Create a MongoDB collection called 'myCollection'.
2. Insert a document with a field called 'age' which is a number.
3. Run the code in `bug.js`.  Observe the error or unexpected results.

## Solution
The solution involves changing the incremented value to a valid number, as shown in `bugSolution.js`.