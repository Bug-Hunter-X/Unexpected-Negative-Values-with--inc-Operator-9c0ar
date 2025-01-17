# MongoDB $inc Operator Unexpected Negative Values

This repository demonstrates an uncommon bug related to the `$inc` operator in MongoDB.  Incorrectly using `$inc` to decrement values, particularly without proper concurrency control, can lead to unexpected negative results.

The `bug.js` file contains code demonstrating this problem. The solution, showcasing proper usage and error handling, is in `bugSolution.js`.