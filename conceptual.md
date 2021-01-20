### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  - An open source object relational database management system

- What is the difference between SQL and PostgreSQL?
  - PostgreSQL is an advanced version of SQL which provides support to different functions of SQL like foreign keys, subqueries, triggers, and different user-defined types and functions.

- In `psql`, how do you connect to a database?
  $ psql db_name

- What is the difference between `HAVING` and `WHERE`?
  - WHERE filters row given a condition. HAVING filters a group (GROUP BY) give a condition.

- What is the difference between an `INNER` and `OUTER` join?
  - INNER join returns only the rows that match a given condition in both tables whereas OUTER joins can return non-matching rows as well.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  - LEFT OUTER returns all rows from the first table as well as rows from the second table that match the given condition. RIGHT OUTER returns all rows from the second table as well as rows from the first table that match the given condition.

- What is an ORM? What do they do?
  - An ORM is a library for object relational mapping that allows you to interact with a database like PostgreSQL in your language of choice such as Python.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  - Server side works with APIs that have a same-origin policy.
  - Server side keeps information like API keys, passwords and other sensitive data from being exposed to the browser and end-user.

- What is CSRF? What is the purpose of the CSRF token?
  - Cross-Site Request Forgery. CSRF tokens prevent attackers from spoofing a form on their own website that makes an HTTP request to your server as if it came from your form/webiste.

- What is the purpose of `form.hidden_tag()`?
  - Allows you to render multiple hidden form fields in one block in Flask-WTF
