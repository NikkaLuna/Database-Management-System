
# SQL Database Management System

## Project Overview

For this project, I created an entity-relationship (ER) model, databases, tables, and queries for two fictional small businesses. I used SQL to test and run the database application.



<div style="text-align: center;">
  <img src="https://github.com/NikkaLuna/SQL_Database_Management_System/assets/94496219/6df488c3-5f77-42c9-a5b8-452ddb02197b alt="Image">
</div>


Project Overview
----------------

This project comprises two main components:

1.  **Jaunty Coffee Co. Database Creation:** Designing and implementing a relational database to manage coffee shop operations.
2.  **Nora's Bagel Bin Database Normalization:** Developing a normalized database model to streamline the ordering process.

* * * * *

Jaunty Coffee Co. Database Implementation
-----------------------------------------

### Database Design

The database for **Jaunty Coffee Co.** includes four primary tables:

-   **coffee_shop:** Information about each coffee shop location.
-   **employee:** Details of employees working at each coffee shop.
-   **supplier:** Information about coffee bean suppliers.
-   **coffee:** Details of different coffee types offered, including their suppliers and pricing.

### Implementation Steps

1.  **Create Tables:** Established the necessary tables with appropriate fields and defined primary and foreign keys to maintain relationships and data integrity.

2.  **Populate Tables:** Inserted initial data into each table to provide a foundation for database operations and testing.

3.  **Create Views:** Developed a view (`employee_info`) that consolidates employee information by combining first and last names into a full name for easier data access and reporting.

4.  **Create Indexes:** Implemented an index (`coffee_index`) on the `coffee_name` field to enhance query performance and speed up data retrieval processes.

5.  **Develop Queries:**

    -   **SFW Query:** Created a query to retrieve employee records based on specific hire dates, enabling targeted data analysis.
    -   **Table Joins Query:** Constructed a query to combine data from multiple tables (`coffee_shop`, `supplier`, and `coffee`) to provide comprehensive information across different aspects of the business.

### Testing

To ensure the database functions correctly:

-   **Table Creation:** Verified that all tables were created without errors.
-   **Data Insertion:** Confirmed that data was accurately inserted and could be retrieved as expected.
-   **Views and Indexes:** Tested the view and index to ensure they provided the intended performance benefits and data representations.
-   **Queries:** Executed the developed queries to validate that they returned accurate and relevant results based on the inserted data.

* * * * *

Nora's Bagel Bin Database Normalization
---------------------------------------

### Second Normal Form (2NF)

**Attribute Assignment:**

-   Separated the initial table into distinct tables to eliminate partial dependencies, ensuring that each table contains attributes fully dependent on its primary key.

**Relationships and Cardinality:**

-   Defined one-to-many and one-to-one relationships between the newly created tables to maintain logical data associations and integrity.

**Explanation:**

-   By decomposing the tables, redundancy was minimized, and data consistency was enhanced, ensuring that each piece of information is stored only once and linked appropriately.

### Third Normal Form (3NF)

**Attribute Assignment:**

-   Further refined the tables to eliminate transitive dependencies by creating a separate `CUSTOMER` table, ensuring that non-key attributes depend solely on the primary key.

**Table Naming:**

-   Assigned clear and descriptive names to each table to reflect their contents accurately.

**Key Linking:**

-   Introduced foreign keys to establish relationships between tables, enabling efficient data retrieval and maintaining referential integrity.

**Relationships and Cardinality:**

-   Defined many-to-one relationships to accurately represent how orders relate to customers and how order items relate to specific bagels.

**Explanation:**

-   This normalization step ensured that all data dependencies are logical and that the database structure supports efficient data management without redundancy.

### Final Physical Database Model

**Table Structure:**

-   Finalized the table structures with appropriate data types assigned to each attribute, ensuring data integrity and optimizing storage.

**Relationships:**

-   Clearly defined relationships between tables to facilitate seamless data interactions and maintain consistency across the database.

* * * * *

Conclusion
----------

This project successfully achieved two key objectives:

1.  **Jaunty Coffee Co. Database Creation:** Developed a robust relational database that effectively manages coffee shop operations, employee details, supplier information, and product offerings. The implementation ensures data integrity, optimized performance, and scalability for future growth.

2.  **Nora's Bagel Bin Database Normalization:** Created a normalized database model that streamlines the ordering process by eliminating data redundancy and ensuring logical data dependencies. The normalization to 3NF enhances data integrity and simplifies data management.

Both databases are designed to support efficient data management, ensuring that Jaunty Coffee Co. and Nora's Bagel Bin can operate smoothly and scale effectively as their business needs evolve.
## Authors

- [@NikkaLuna](https://github.com/NikkaLuna)


## 🚀 About Me
I'm a Software Engineer with an emphasis on Java, Python, SQL, and AWS.  


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrea-hayes-msml/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/AHayes_Ninja_)
[![art portfolio](https://img.shields.io/badge/my_art-888?style=for-the-badge&logo=ko-fi&logoColor=white)](https://andreachristinehayes.wixsite.com/andreahayesart/)
