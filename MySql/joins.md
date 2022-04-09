## Inner Joins  

SELECT *  

FROM customers c  

JOIN orders o  

 ON c.customer_id = o.customer_id  
 ## Outer Joins  
 
—- Return all customers whether they have any orders or not  

SELECT *  

FROM customers c  

LEFT JOIN orders o  

 ON c.customer_id = o.customer_id    
 
## USING Clause  

If column names are exactly the same, you can simplify the join with the USING  

clause.  

SELECT *  

FROM customers c  

JOIN orders o  

 USING (customer_id)  
 
## Cross Joins  
—- Combine every color with every size  

SELECT *  

FROM colors  
CROSS JOIN sizes
