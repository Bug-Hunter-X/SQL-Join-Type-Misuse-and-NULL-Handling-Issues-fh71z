# SQL Bugs: Join Type Errors and NULL Value Handling

This repository demonstrates two common SQL errors: incorrect use of join types (LEFT JOIN vs. INNER JOIN) and issues handling NULL values.

The `bug.sql` file contains SQL code showcasing these errors.  The `bugSolution.sql` file provides corrected versions of the queries.

## Bug 1: Incorrect Join Type
The original query uses a LEFT JOIN where an INNER JOIN is needed, leading to incorrect data inclusion.

## Bug 2: NULL Value Handling
The original query fails to account for NULL values in a comparison, potentially resulting in unexpected results.

## Solutions
The corrected queries in `bugSolution.sql` demonstrate the correct use of join types and proper handling of NULL values.