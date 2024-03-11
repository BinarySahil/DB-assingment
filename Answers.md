# DB-assingment
Q1.
The relationship between Product and Product in this e-commerce is a one-to-many relationship. This means that one item can be in one category, but a category can contain many items. For example, "T-Shirts" might be in the "Clothing" category, but the "Clothing" category also includes "Pants," "Sweater," and "Hat." Therefore, a group can have many products, creating variety and integration for customers to browse different products


Q2.
We can use Foreign key constraints and Data Validation to ensure the "Product" table has valid category assigned.
Foreign key constraints:You can create foreign key constraints on the "category_id" field in the "Item" table. This parameter will refer to the primary key ("id") of the "product_category" table. This will prevent products with incorrect Category ID from being added to the Product List.
 Data validation: Data validation can be used on the application side to ensure that only category IDs are entered for new products. This can be done from the drop-down menu or from the list of valid categories. 
