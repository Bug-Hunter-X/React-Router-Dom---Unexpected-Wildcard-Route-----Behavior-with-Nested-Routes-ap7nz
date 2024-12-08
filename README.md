This example demonstrates a problem with unexpected route matching in React Router v6 when using nested routes in combination with a wildcard catch-all route. The wildcard route sometimes incorrectly intercepts routes that should be handled by more specific route definitions.

The `App.js` file contains the buggy code. The `AppSolution.js` file provides a solution to fix the issue. The problem can be subtle and difficult to debug, particularly in larger applications with complex route structures.