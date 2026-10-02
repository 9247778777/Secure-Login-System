Project: Secure Login System

Technology Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Python Flask
* Database: SQLite
* Password security: bcrypt
* Security: Input validation, parameterized SQL queries, sessions and logout

Main Features

1. User Registration
    * User creates an account with username and password.
    * Password is hashed using bcrypt before storing it.
    * The original password is never stored in the database.
2. Secure Login
    * User enters username and password.
    * bcrypt verifies the password against the stored hash.
3. SQL Injection Protection
    * Database queries use parameterized statements instead of directly inserting user input into SQL.
4. Session Management
    * Successful login creates a session.
    * Only authenticated users can access the dashboard.
    * Logout destroys the session.
5. Input Validation
    * Checks that required fields are provided.
    * Password requirements can be enforced.
6. Optional 2FA
    * A second verification step can be added using an authenticator application.
  
Expected Outcome :

The completed application demonstrates how secure authentication works in a web application. It protects user passwords through hashing, reduces SQL-injection risk through parameterized queries, and uses sessions to control access to authenticated pages.
