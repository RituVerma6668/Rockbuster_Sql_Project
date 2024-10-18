# Rockbuster_Sql_Project
Rockbuster Stealth LLC This is a data dictionary for Rockbuster Stealth LLC from the PostgreSQL server database. Rockbuster Stealth LLC is a movie rental company that plans to launch an online video rental serivce. The company has a large and complex database that contains information on films, customers, payments, rentals, and more.

A bootcamp project that required writing SQL queries to join tables and retrieve required data, then visualizing the data in Tableau Public.
## Rockbuster_Data has 2 tables 1. Fact_tables 2. Dimension_tables

**1. Fact_tables**
<ul style="list-style-type:circle;">
  <li>Payment</li>
  <li>Rental</li>
</ul>
     
**2. Dimension_tables**
<ul style="list-style-type:circle;">
  <li>Actor</li>
  <li>Address</li>
     <li>Category</li>
  <li>City</li>
     <li>Country</li>
  <li>Customer</li>
     <li>Film</li>
     <li>Film Actor</li>
      <li>Film Category</li>
     <li>Inventory</li>
  <li>Language</li>
    <li>Staff</li>
    <li>Store</li>
</ul>

 #  Project Description
 ---
For this project, I was provided a relational database and used PgAdmin 4 from Postgres to query this database. Here is a short list of some of the things I learned while completeing this project:
---
- How to use DBVisualizer to to build an entity relationship diagram

- The effects of constraints on how data can be input into a relational database

- Grouping and cleaning data in SQL

- Finding and displaying max, min, averages of data using SQL queries

- Writing relatively complex queries involving joins, subqueries and Common Table Expressions.

---
I was given a list of questions that hypothetical executives and managers at Rockbuster wanted answered, and had to write my own SQL queries to retrieve the data needed to answer them. The main areas if interest were:

- Basic statistical summaries of sales information
    
- Finding which countries on Earth produced the most sales
    
- Determing the top cities within those countries
    
- Finding the top five customers within those cities

 ---
 ## Sample queries can be found in the files of this repository.

Since most if this data exists on different tables, the main difficulty was in finding the correct keys and methods to use to join and filter those tables correctly and efficiently.

In the end, the data we retrieved and organized was exported into CSV files and further visualized in Tableau. Here is a link to my final project, and here is a picture of the database ERD for reference:
---
![image](https://github.com/user-attachments/assets/ba7971da-a694-4940-9ff1-2a768f50f17b)

---


   
   
   
   
   
   
