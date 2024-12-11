# MongoDB $inc Operator Type Error
This example demonstrates an uncommon error related to the $inc operator in MongoDB. The error occurs when a non-numeric value is provided as an increment.  The solution highlights the correct usage of $inc with numeric values.

## Bug
The incorrect code attempts to increment the 'age' field by a string value. This will not update the document correctly and might throw an error.