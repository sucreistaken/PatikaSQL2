# PatikaSQL2
Homework 2
Sure, here are the query scenarios translated into English:

1.Retrieve all data from the "film" table where the values in the "replacement cost" column are greater than or equal to 12.99 and less than 16.99 using the BETWEEN - AND structure.
**SELECT * FROM film WHERE replacement_cost BETWEEN 12.99 AND 16.99;

2.Retrieve data from the "actor" table where the values in the "first_name" and "last_name" columns are either 'Penelope', 'Nick', or 'Ed' using the IN operator.
**SELECT first_name,last_name FROM actor WHERE first_name IN ('Penelope', 'Nick', 'Ed');

3.Retrieve all data from the "film" table where the values in the "rental_rate" column are 0.99, 2.99, or 4.99, and the values in the "replacement_cost" column are 12.99, 15.99, or 28.99 using the IN operator.
**SELECT * FROM film WHERE rental_rate IN (0.99,2.99,4.99) AND  replacement_cost IN (12.99,15.99,28.99);




