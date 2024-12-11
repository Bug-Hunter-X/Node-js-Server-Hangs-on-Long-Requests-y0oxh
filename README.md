# Node.js Server Hang on Long Requests

This repository demonstrates a common issue in Node.js where a server can hang if a request involves a long-running synchronous operation.  The `server.js` file contains a simple HTTP server that simulates a long-running task.  This blocks the event loop, preventing other requests from being processed.

The solution provided in `serverSolution.js` addresses this using asynchronous operations and proper error handling. This example uses the `async/await` syntax for better readability.