# Data Engineering Lifecycle :

# 1] Data Platforms, Data Stores, and Security : 

A layer represents functional components that perform a specific set of tasks in the data platform.
- Data Ingestion or Data Collection Layer,
- Data Storage and Integration Layer : responsible for storing and merging extracted data
- Data Processing Layer, and Analysis 
- User Interface Layer : responsible for delivering processed data to data consumers.
- Data Pipeline Layer, which overlays multiple layers.

#### # primary considerations for designing a data store: 
- The type of data you want to store
- Volume of data
- Intended use of data
- Storage considerations
- Privacy, security, and governance needs of your organization.

#### # when not to use :
- If you're looking to run complex search queries and multi-operation transactions, for example, a document-based database may not be the best option for you. 
- you would not opt for a graph-based database if you need to process high-volume transactions because graph-based databases are not optimized for large-volume 
  analytics queries.
- When you require to store large volumes of raw data in its native format, straight from its source, a data lake would be the appropriate choice for you. With a data 
  lake, you can store both relational and non-relational data at scale without defining the data's structure and schema.
-  when you're dealing with Big Data, that is data that is not only high-volume but also high-velocity, of diverse types, and needs distributed processing for fast 
   analytics, then a big data repository would be an option you would explore. Big data stores split large files across multiple computers allowing parallel access to 
   them. Computations run in parallel on each node where data is stored.


# 2] Data Collection and Data Wrangling :








  
