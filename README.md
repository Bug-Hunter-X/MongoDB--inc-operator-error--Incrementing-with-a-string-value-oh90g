# MongoDB $inc Operator Error: Incrementing with a String

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations: providing a string value instead of a number.  The incorrect use of `$inc` can lead to unexpected behavior and data corruption.

## Problem

The provided `bug.js` example shows an incorrect usage of the `$inc` operator. The `count` field is attempted to be incremented by the string '1' rather than the number 1.

## Solution

The `bugSolution.js` file corrects the issue. The correct increment operation uses a numerical value for incrementing the field.

## How to reproduce

1.  Ensure you have a MongoDB instance running.
2.  Execute `bug.js`. Observe the result, likely an error or unexpected behavior.
3.  Execute `bugSolution.js`. Observe the correct increment operation.
