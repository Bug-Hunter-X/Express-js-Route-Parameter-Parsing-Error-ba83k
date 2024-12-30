# Express.js Route Parameter Parsing Error

This repository demonstrates a common error in Express.js routes where parameters are not properly validated or handled, leading to unexpected behavior or crashes.  The bug occurs when the route parameter `:id` is not a valid number, causing `parseInt(userId)` to return `NaN`, which leads to the `find` function not correctly finding the user.