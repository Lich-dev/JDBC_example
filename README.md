# JDBC_example

running main will:
- make a derby database if one isn't present in the local directory
- create a table labeled "student" (will fail if already exists, remove the first batch execution to fix)
- insert a newly created student called "Jeremy" into the database
- search for all students named "Jeremy" and display everything about the first one found