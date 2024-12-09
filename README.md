# Unhandled 'undefined' Values in JavaScript Function

This repository demonstrates a common JavaScript bug involving the improper handling of `undefined` values in function parameters. The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version.

## Bug Description
The original function checks for `null` values but omits a check for `undefined`. This can lead to unexpected errors or incorrect results when the function is called with `undefined` arguments.

## Solution
The solution explicitly checks for both `null` and `undefined` values to ensure robust handling of unexpected inputs.