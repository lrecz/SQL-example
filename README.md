# SQL-example
SQL: SELECT title, first_name,last_name FROM film_actor 
INNER JOIN actor 
ON film_actor.actor_id = actor.actor_id 
INNER JOINfilm 
ON film_actor.film_id = film.film_id 
WHERE first_name = 'Nick' 
AND last_name = 'Wahlberg'  
/* Syntax as Follows  command (SELECT) [table column1], [table column2], 
command (FROM) [table] Intersection of tables (Inner Join) [Table] 
ON [table1].[column1] = [table2].[column1] (These columns contain the same values) Intersection of tables (Inner Join) [Table] 
ON [table1].[column2] = [table2].[column2] (These columns contain the same values) filtering of values--command (WHERE) [first value to filter on] = 'Value1' 
AND [second value to filter on] = 'Value2'
