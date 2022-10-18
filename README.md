# sql_fuggvenyek



/*
USE northwind;
SELECT AVG(standard_cost) FROM products;
SELECT AVG(standard_cost) FROM products WHERE list_price < 30;
SELECT AVG(standard_cost) FROM products WHERE category = "Sauces";
*/



/*
USE northwind;
SELECT SUM(standard_cost) FROM products;
SELECT SUM(standard_cost) FROM products WHERE list_price > 20 AND list_price < 50;
SELECT SUM(standard_cost) FROM products WHERE category != "Sauces";
*/

/*
USE northwind;
SELECT COUNT(id) FROM employees WHERE city = "Seattle";
SELECT COUNT(id) FROM employees WHERE job_title = "Sales Representative";
SELECT COUNT(id) FROM employees WHERE first_name LIKE "A%";
*/


USE northwind;
SELECT MIN(standard_cost) FROM products;
SELECT MAX(standard_cost) FROM products;
SELECT MAX(standard_cost) FROM products WHERE list_price >= 30;
SELECT MAX(standard_cost) FROM products WHERE product_code LIKE "%CO%";


