# Incorrect use of $inc operator in MongoDB

This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, if you provide a string value instead of a number, the operation will fail.  The solution shows the correct way to increment a field.

## Bug
The bug lies in the incorrect type passed to `$inc`. Passing a string instead of a number leads to an error in the MongoDB query.

## Solution
The solution shows the correct way to increment a field using `$inc`, ensuring a numerical value is passed for incrementing the field.