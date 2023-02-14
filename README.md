# SQL-11
1. (SELECT first_name FROM actor)
UNION ALL
(SELECT first_name FROM customer);
2. (SELECT first_name FROM actor)
INTERSECT
(SELECT first_name FROM customer);
3. (SELECT first_name FROM actor)
EXCEPT
(SELECT first_name FROM customer);
4. 
* (SELECT last_name FROM actor)
UNION ALL
(SELECT last_name FROM customer);
* (SELECT last_name FROM actor)
INTERSECT
(SELECT last_name FROM customer);
* (SELECT last_name FROM actor)
EXCEPT
(SELECT last_name FROM customer);
* (SELECT last_update FROM actor)
UNION ALL
(SELECT last_update FROM customer);
* (SELECT last_update FROM actor)
INTERSECT
(SELECT last_update FROM customer);
* (SELECT last_update FROM actor)
EXCEPT
(SELECT last_update FROM customer);
