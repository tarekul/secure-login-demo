Simulated SQL Injection
How this browser simulation was built.
Built using HTML, Javascript, and SQL.js(lightweight file-based SQL db engine that runs on browser)

Hint to login without password or incorrect password
username is admin
use -- to bypass password validation. In SQL -- starts a comment and anything after it becomes a comment.
How can we utlize the -- to make the query string to be SELECT _ FROM users WHERE username = 'admin'?
With SELECT _ FROM users WHERE username = 'admin' we get the result without a password
