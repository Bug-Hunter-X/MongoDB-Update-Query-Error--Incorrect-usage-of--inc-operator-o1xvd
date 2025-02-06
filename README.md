# MongoDB Update Query Error: Incorrect usage of $inc operator
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error arises from providing a string value instead of a numerical value to the `$inc` operator, which expects a number to increment the field.

## Bug
The `bug.js` file contains the incorrect usage of the `$inc` operator, which results in an error when executed against a MongoDB database.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator, showing how to provide a numerical value to increment the field correctly.
