# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value. However, providing a string value to `$inc` will result in an error or unexpected behavior.

## Bug
The `bug.js` file contains code that attempts to increment a counter field using a string value. This leads to an error because `$inc` expects a numerical value.

## Solution
The `bugSolution.js` file shows the corrected code where the counter is incremented using a numerical value.  This fixes the issue and correctly updates the document.