1. Basic Queries
Select Data
SELECT * FROM customers;

Select Specific Columns
SELECT name, age FROM customers;

2. Filtering Data
SELECT * FROM customers
WHERE age > 25;


Operators:

=

>

<

>=

<=

AND

OR

LIKE

3. Aggregations
SELECT COUNT(*) FROM customers;
SELECT AVG(salary) FROM employees;
SELECT SUM(sales) FROM orders;

4. GROUP BY
SELECT department, COUNT(*)
FROM employees
GROUP BY department;


Used for grouped summaries.

5. JOINS (Critical for Data Engineering)
INNER JOIN
SELECT customers.name, orders.amount
FROM customers
INNER JOIN orders
ON customers.id = orders.customer_id;

Types of Joins:

INNER JOIN

LEFT JOIN

RIGHT JOIN

FULL JOIN
