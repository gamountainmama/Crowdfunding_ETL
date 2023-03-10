# Crowdfunding_ETL

Create the Category and Subcategory DataFrames

    1. Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame that has the following columns:

        - A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories

        - A "category" column that contains only the category titles

    2. Export the category DataFrame as category.csv and save it to your GitHub repository.
   
    3. Extract and transform the crowdfunding.xlsx Excel data to create a subcategory DataFrame that has the following columns:

        - A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories

        - A "subcategory" column that contains only the subcategory titles
        
        - Export the subcategory DataFrame as subcategory.csv and save it to your GitHub repository.

Create the Campaign DataFrame

    1. Extract and transform the crowdfunding.xlsx Excel data to create a campaign
   
    2. Export the campaign DataFrame as campaign.csv and save it to your GitHub repository.
    
Create the Contacts DataFrame

    Use regular expressions for extracting and transforming the data from the contacts.xlsx Excel data:
         
        - Import the contacts.xlsx file into a DataFrame.
        
        - Extract the "contact_id", "name", and "email" columns by using regular expressions.
    
        - Create a new DataFrame with the extracted data.
    
        - Convert the "contact_id" column to the integer type.
    
        - Split each "name" column value into a first and a last name, and place each in a new column.
   
        - Clean and then export the DataFrame as contacts.csv and save it to your GitHub repository.
  
Create the Crowdfunding Database

    1. Inspect the four CSV files, and then sketch an ERD of the tables by using QuickDBD.

    2. Use the information from the ERD to create a table schema for each CSV file. Note: Remember to specify the data types, primary keys, foreign keys, and other constraints.

    3. Save the database schema as a Postgres file named crowdfunding_db_schema.sql, and save it to your GitHub repository.

    4. Create a new Postgres database, named crowdfunding_db.

    5. Using the database schema, create the tables in the correct order to handle the foreign keys.

    6. Verify the table creation by running a SELECT statement for each table.

    7. Import each CSV file into its corresponding SQL table.

    8. Verify that each table has the correct data by running a SELECT statement for each.




