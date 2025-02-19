# Express.js JSON Body Parsing Bug

This repository demonstrates a common issue encountered when using Express.js to parse JSON data from POST requests.  The problem arises when the request body is empty or contains invalid JSON data.

## Bug Description

The Express.js application fails to handle empty or invalid JSON POST requests gracefully.  Instead of returning an appropriate error response, it either throws an error or behaves unexpectedly.

## Solution

The solution involves adding error handling middleware to catch JSON parsing errors and respond appropriately.

## Setup

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `node bug.js` to start the server with the bug.
4. Run `node bugSolution.js` to start the server with the fix.
