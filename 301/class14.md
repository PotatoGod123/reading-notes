# Javascript

## SQL database normalization 

Essentially you are checking to see if your database can occur anomalies with its current row and column structure and see if you are able to seperate it into seperate forms or other table with forgein keys referring to it.  
    
    First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
    Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
    Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key

Here are some situation in which you would need to add normalization   

Insert Anomaly


There are facts we cannot record until we know information for the entire row.  In our example we cannot record a new sales office until we also know the sales person.  Why?  Because in order to create the record, we need provide a primary key.  In our case this is the EmployeeID.  

Update Anomaly

In this case we have the same information in several rows. For instance if the office number changes, then there are multiple updates that need to be made.  If we don’t update all rows, then inconsistencies appear.  

Deletion Anomaly

Deletion of a row causes removal of more than one set of facts.  For instance, if John Hunt retires, then deleting that row cause us to lose information about the New York office.  


Search and Sort Issues

The last reason we’ll consider is making it easier to search and sort your data.  In the SalesStaff table if you want to search for a specific customer such as Ford, you would have to write a query like



[<==Back](../README.md)