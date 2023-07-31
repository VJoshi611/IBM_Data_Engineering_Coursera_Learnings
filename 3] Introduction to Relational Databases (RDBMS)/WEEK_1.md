Introduction to Relational Databases (RDBMS) :

A relational database organizes data into tables that can be linked—or related—based on data common to each. By storing your business data in a relational database, 
you can retrieve and analyze the data to make important business decisions. There are many companies that offer relational database systems and, regardless of which 
one you use, they all share a common set of characteristics that you must be familiar with before you can move on to more advanced operations with databases. 
In this module, you will learn some basic relational database concepts and how to diagram and describe the relationships between tables in a database. 
You will also learn the different deployment topologies and architectures that are commonly used, who the typical users of databases are, and some of the features 
and benefits of some common relational database management systems including Db2, MySQL, and PostgreSQL.


### Every good relational database solution begins with a solid design and implementation strategy. A well-designed relational database ensures that the users & applications that depend on the data will know that it is:

- Accurate. Can you rely on the accuracy of the data as new information is added or it is modified? 
- Easy to access. Is the data organized in a way that makes it fast, easy, and predictable to query and maintain?
- Reliable. Can your database design ensure data integrity and maintain consistent and reliable data?
- Flexible. Can you update or expand on the design to meet future data requirements?


**Data is unorganized information, that is processed to make it meaningful. It can consist of Facts, observations, perceptions Numbers characters symbols Images Or a mix of any of these.**

- Relational databases are primarily OLTP systems, used to support day-to-day business activities such as customer transactions, human resource activities, and workflows. They can also be used to perform data analysis, for example, data from a customer relationship management system can be used to make sales projections.
- ER Model is used as a tool to design relational databases. In the ER Model, entities are objects that exist independently of any other entities in the database. It is simple to convert an ER Diagram into a collection of tables.
- Entities have attributes, which are the data elements that characterize the entity. Attributes tell us more about the entity. eg: Entity : Book, Attribute : Title, Year etc.
- Information Models are abstract, formal representations of entities that include their properties, relationships and the operations that can be performed on them.
- Data Models are defined at a more concrete level, are specific and include details. gives more information. A Data model is the blueprint of any database system.
- The Relational Model is the most used data model for databases because this model allows for logical data independence, physical data independence, and physical storage independence.

- Types of Relationships: one-to-one and many-to-many relationship**
- Relation = name of table/entity, Degree = no. of columns/attributes, and Cardinality = no. of tuples or rows.

## Introducing Relational Database Products :
**Three Tier Architecture :**
- A single-tier topology is one where the database is installed on a user’s local desktop. It is useful for small databases that only require single user access.
- In 2-tier database topologies the database resides on a remote server and users access it from client systems.
- In 3-tier database topologies the database resides on a remote server and users access it through an application server or a middle-tier.

- The main types of distributed database architectures include: Shared disk architecture(Store common storage) and shared nothing architectures(replication, or partitioning.)
- sharding: each partition has its own compute resources.
- MySQL is an object-relational database that supports many operating systems, a range of languages for client application development, relational and JSON data, multiple storage engines, and high availability and scalability options.
- PostgreSQL is an open source, object-relational database that supports a range of languages for client application development, relational, structured, and non-structured data, and replication and partitioning for high availability and scalability
