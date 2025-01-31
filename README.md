# Uncommon JavaScript Error: Division by Zero

This repository demonstrates a common yet easily missed JavaScript error: division by zero. The `bug.js` file contains a function that doesn't properly handle cases where the denominator is zero, leading to an error. The solution, in `bugSolution.js`, addresses this by implementing more robust error handling.

## Problem
The function `foo` in `bug.js` performs division. If the second argument (`b`) is zero, the function will throw a `ZeroDivisionError`. This can be difficult to debug, particularly in large applications.

## Solution
The `bugSolution.js` file demonstrates a better approach.  The solution includes a check to prevent division by zero, returning a defined value (in this case, `Infinity`) instead of throwing an error.  More sophisticated solutions might include throwing a custom error or using a try-catch block.  The key is preventing the application from crashing.

## How to Run
1. Clone this repository.
2. Navigate to the repository's directory.
3. Run the files using Node.js: `node bug.js` and `node bugSolution.js`

This example highlights the importance of comprehensive error handling to prevent unexpected crashes and enhance the reliability of JavaScript applications.