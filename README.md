# -DB-Assignment

Ans 1

The relationship between "Product" and "Product_Category" in this schema is a one-to-many relationships
where a product can belong to only 1 category, it is made applicable by the help of foreign key contained in the “Product” table The ‘Category_id’ column in the "Product" table references the primary key (id) of the "Product_Category" table.
There's no limit on how many products can have the same “Category_id” in the "Product" table.
While the schema suggests a product belongs to only one category, majorly e-commerce systems allow for many-to-many relationships between products and categories


Ans 2 

With the help of foreign key we can ensure that each product in the product table has a valid category assigned to it, When a foreign key constraint is set up on the “Category_id” column in the "Product" table referencing the id (primary key) of the "Product_Category" table, the database itself will enforce data integrity.
This means any attempt to insert a product with a non-existent  “Category_id” will be rejected by the database. There has to be a “Category_id” to move forward.
