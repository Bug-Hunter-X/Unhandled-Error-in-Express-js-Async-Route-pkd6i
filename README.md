# Unhandled Error in Express.js Async Route

This repository demonstrates a common error in Express.js applications: unhandled errors within asynchronous route handlers.  The provided `bug.js` file showcases the issue, while `bugSolution.js` offers a solution using proper error handling techniques.

## Bug

The `bug.js` file simulates an asynchronous operation that might fail.  If the simulated operation fails, an error is thrown but not caught, resulting in the server crashing.

## Solution

The `bugSolution.js` file demonstrates the correct way to handle potential errors in asynchronous Express.js routes using a `try...catch` block.