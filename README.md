# Javascript Closure Issue
This example demonstrates a common closure-related issue in JavaScript.  The expected output might be 0, 1, 2...9 but instead, it prints 10 ten times. This is because the `setTimeout` function uses the value of `i` that is available when the `setTimeout` callback actually executes, not when it was set.