# Oracle-SQL-Analytical-functions
This repository stores a variety of examples on how to use Oracle SQL Analytical functions for data analysis.

As per definition **"Analytic functions compute an aggregate value based on a group of rows. They differ from aggregate functions in that they return multiple rows for each group. The group of rows is called a window and is defined by the analytic_clause. For each row, a sliding window of rows is defined. The window determines the range of rows used to perform the calculations for the current row. Window sizes can be based on either a physical number of rows or a logical interval such as time."**

We will be dealing with below analytic functions :

**ROW_NUMBER:**	Assign a unique sequential integer starting from 1 to each row in a partition or in the whole result

**RANK:**	Calculate the rank of a value in a set of values

**DENSE_RANK:**	Calculate the rank of a row in an ordered set of rows with no gaps in rank values.

**NTILE:**	Divide an ordered set of rows into a number of buckets and assign an appropriate bucket number to each row.

**FIRST_VALUE:**	Get the value of the first row in a specified window frame.

**LAST_VALUE:**	Get the value of the last row in a specified window frame.

**LEAD:**	Provide access to a row at a given physical offset that follows the current row without using a self-join.

**LAG:**	Provide access to a row at a given physical offset that comes before the current row without using a self-join.

