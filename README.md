# MongoDB $inc operator error with String
This repository demonstrates a common error when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numerical field by a specified value. However, attempting to increment a field with a string value will result in an error.

**Bug:**
The provided code incorrectly uses a string value ('1') to increment the `age` field.

**Solution:**
The solution involves using a numeric value (1) instead of a string.