# sql_patika_odev_10   www.patika.dev
patika.dev odev 10 sql
--answer 1
SELECT city,country FROM city
LEFT JOIN country ON city.country_id = country.country_id;
--answer 2
SELECT payment_id,first_name,last_name FROM customer
RIGHT JOIN payment ON payment.customer_id = customer.customer_id;
-- answer3 
SELECT rental_id,first_name,last_name FROM customer
FULL JOIN rental ON rental.customer_id = customer.customer_id;
