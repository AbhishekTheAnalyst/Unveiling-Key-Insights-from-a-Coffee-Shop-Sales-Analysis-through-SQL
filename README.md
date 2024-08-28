# Unveiling-Key-Insights-from-a-Coffee-Shop-Sales-Analysis-through-SQL

Leveraged SQL to extract valuable insights to fuel data-driven business strategies.

**Tasks**
--------------------------------------------------------------------------------------------------------------------------

1.) What is the total Sales?



**Analysis**
--------------------------------------------------------------------------------------------------------------------------

1.)	**What is the total Sales?** 

--Calculating the total sales by joining  the 'transactions' and 'products' table.

**SELECT SUM**(p.unit_price * t.transaction_qty) **AS** Total_Sales

**FROM** product p

**JOIN** transactions t **ON** t.product_id = p.product_id

![image](https://github.com/user-attachments/assets/c4e5f6ce-ecef-4f91-a9c6-7c3951dae43e)
