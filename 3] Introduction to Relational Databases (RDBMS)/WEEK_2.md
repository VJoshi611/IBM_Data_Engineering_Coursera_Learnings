
-  Data Definition Language (or DDL) statements are used to define, change, or drop database objects such as tables. Common DDL statement types include CREATE, ALTER, TRUNCATE, and DROP.
-  Data Manipulation Language (or DML) statements are used to read and modify data in tables. These are also sometimes referred to as CRUD operations, that is, Create, Read, Update and Delete rows in a table.  Common DML statement types include INSERT, SELECT, UPDATE, and DELETE.

**Creating Table:**
- Define Schema
- Table name
- column name
- data types
- check duplicates, null values

**Data Movement Utilities:**
- Data engineers and database administrators will often need to move data into an out of an existing database. This could be for several reasons such as: initially populating the entire database and all objects with it such as tables; creating a working copy of the database for development and testing purposes, creating a snapshot of the state of the database at particular instant in time for the purposes of disaster recovery creating a new table (or a set of tables) from data that has been extracted from external data sources or files adding or appending data into one or more existing tables
- One method for moving data between databases is to perform a backup and restore. The backup operation creates a file (or a set of files) that encapsulates all of the database objects and their data. The restore operation creates an exact copy of the original database from the backup files. Backup and restore operations preserve all objects in the database, including schemas, tables, views, user defined data types, functions, stored procedures, table constraints, triggers, security settings, relationship between objects and of course the data in all the tables. Backups are often taken on a periodic basis to preserve copies of production database for disaster recovery purposes. Backup and restore operations can also be performed for creating additional copies of the database for development and test purposes.
- The Import operation reads data from a file and performs a series of INSERT statements against the target table. The Export operation selects data from the specified table and saves it into a target file.

**DATABASE HIERARCHY:**
- Instance
- Database
- Schema
- Database objects : Tables,Constraints,Indexes, Views, Aliases.

**Indexes**
- By default, when you create a primary key on a table an index is automatically created on that key, but you can also create your own indexes on regularly searched columns.
- Advantages : 1] Improved performance of SELECT queries when searching on an indexed column,  2] results are returned quicker than when it has to check every row in the table,  3] uniqueness of rows
- Disadvantages :  1] uses more spaces,  2] decreases performance of INSERT, UPDATE, DELETE queries.
- use case : For example, on a table that rarely has rows inserted or updated, but is regularly used in SELECT queries and WHERE clauses.

- **Normalization** reduces redundancy and increases consistency of data
- In first normal form (1NF), each row must be unique, and each cell must contain only a single item.
- In second normal form (2NF), you must create separate tables for sets of values that apply to multiple records.
- In third normal form (3NF), eliminate any columns that do not depend on the key.

**Constraints:**
- Entity Integrity Constraint ensures primary key is a unique value that identifies each tuple (or row)
- Referential integrity constraint defines relationships between tables
- Semantic Integrity Constraint refers to the correctness of the meaning of the data
- Domain Constraint specifies the permissible values for a given attribute
- Null Constraint specifies that attribute values cannot be null
- Check Constraint limits the values that are accepted by an attribute.
