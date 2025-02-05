# MongoDB $inc Operator Error: Incorrect Type
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical value, but attempting to increment by a string value results in an error.

The `bug.js` file showcases the incorrect usage. The `bugSolution.js` file provides a corrected implementation.

**Error:**
MongoDB will throw an error indicating that the value provided to `$inc` must be a number. 

**Solution:**
Ensure that the value you are incrementing by is a number.