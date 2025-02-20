# Missing Error Handling in Express.js POST Route

This repository demonstrates a common error in Express.js applications: the lack of proper error handling when processing POST requests.

The `bug.js` file shows an example of an Express.js server that processes POST requests to the `/users` route.  It directly logs the request body without any validation or error checking. If the request body is malformed, or if critical fields are missing, the application might crash or produce unexpected results.

The `bugSolution.js` file shows the corrected version, where error handling is added to gracefully handle such scenarios and provide meaningful feedback to the client.