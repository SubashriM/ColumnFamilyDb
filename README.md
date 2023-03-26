STUDENT MANAGEMENT
This project uses HBase, a distributed, non-relational database management system, for storing and accessing data. The project creates three tables - STUDENT, STAFF, and MARK- and inserts data into them. It then read data from the tables.

TABLES
STUDENT:
     The customer table has the following columns:
          Row Key
          Name
          Regno
          Department
          
STAFF:
     The car table has the following columns:
          Row Key
          Id
          Name
          Department
          Position
          Salary
          
MARKS:
      The staff table has the following columns:
         Row Key
         Name
         Regno
         Mark1
         Mark2
         CGPA
In this project, HBase is used as a distributed NoSQL database to store and retrieve large amounts of data. Some of the common HBase commands used in this project are:
      
     CREATE - used to create a new table in HBase.

     PUT- used to insert data into a specific row and column of a table .All the values for the attributes of the tables are given using this command.This command also used to update the values for the attributes in the table.
     
     SCAN - used to retrieve data from multiple rows and columns of a table.
     
     DELETE - used to delete a specific row or column from a table .

These commands can be executed through the HBase shell or through client APIs in programming languages such as Java or Python.
