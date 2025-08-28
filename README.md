# DataSystems
This is a collection of projects on Data Management System and Engineering

```sql
--The Correct Query
SELECT 
    order_id, product_name, amount
FROM orders
WHERE location = 'Manchester'
  AND (
       (order_date >= '2024-05-01' AND order_date <= '2024-05-31')
    OR (order_date >= '2024-07-01' AND order_date <= '2024-07-31')
  );
```
