# Northwind_Traders_import-export_data_preparation

Scenario/ Challenge
Your Role: Sales Executive
You are a sales executive of an import-export company called "Northwind Traders", which imports and exports specialty foods from around the world. The Enteprise Resource Planning (ERP) software you are in charge of, contains a database with several tables for customers, orders, inventory, purchasing, suppliers, shipping, employees, and single-entry accounting.



Your Task
1. Delete duplicate rows of QuantityPerUnit in the products table with a CTE and ROW_NUMBER() function.
2. Use a case statement that creates a variable called WhentoRestock that says 'Restock Now' when UnitsOnOrder > 50 and when UnitslnStock < 20 as well.
3. Use a case statement that creates a variable called WhentoRestock in the Products table that says 'Restock Now' when UnitsOnOrder > 50 and when UnitslnStock < 20 as well,
4. that says 'Restock Next Week' when UnitsOnOrder between 30 and 40 and UnitslnStock < 50,
5. 'Restock Next Month' when UnitsOnOrder < 30 and UnitslnStock < 50
6. and 'Restock in 6 Months' when UnitsOnOrder < 5 and UnitslnStock >= 50.
7. Otherwise, WhentoRestock = 'Ask Manager'.
8. Select CustomerlD, ContactNa me, City, Region and Fax from the customer table, replace Fax with 'No Fax Specified' when Fax in NULL in the table Customers, and select only those rows with the label Fax = 'No Fax Specified' using a common table expression.

