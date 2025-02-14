# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB updates. The error arises from providing a string value instead of a number to the `$inc` operator, leading to an update failure. The solution shows the correct way to increment a counter using `$inc` with a numerical value.

## Bug
The initial code attempts to increment a counter field using a string value ('1') instead of a numerical value (1). This results in an error during the update operation.  The provided script shows the incorrect usage which will throw an error.

## Solution
The solution demonstrates the correct way to use the `$inc` operator. The code uses a numeric value (1) to increment the counter field, ensuring that the update operation executes successfully.