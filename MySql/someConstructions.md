## IN Operator
—- Returns customers in any of these states: VA, NY, CA  

SELECT *  

FROM customers  

WHERE state IN (‘VA’, ‘NY’, ‘CA’)

## BETWEEN Operator
SELECT *  

FROM customers  

WHERE points BETWEEN 100 AND 200  
## REGEXP Operator
  
  —- Returns customers whose first name starts with a
  
  SELECT *
  
  FROM customers  
  
WHERE first_name REGEXP ‘^a’  

• ^: beginning of a string  

• $: end of a string  

• |: logical OR  

• [abc]: match any single characters  

• [a-d]: any characters from a to d
