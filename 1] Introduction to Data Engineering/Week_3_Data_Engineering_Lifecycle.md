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
-  Once the data you need has been gathered and imported, your next step is to make it analytics-ready. This is where the process of Data Wrangling. 

**Data Wrangling involves a whole range of transformations and cleansing activities performed on the data. Transformation of raw data includes the tasks you undertake to:**
- Structurally manipulate and combine data using Joins and Unions. 
- Normalize data, that is, clean the database of unused and redundant data.
- enormalize data, that is, combine data from multiple tables into a single table so that it can be queried faster.

**Cleansing activities include:** 

- Profiling data to uncover anomalies and quality issues.
- Visualizing data using statistical methods in order to spot outliers. 
- Fixing issues such as missing values, duplicate data, irrelevant data, inconsistent formats, syntax errors, and outliers. 

A variety of software and tools are available for the data wrangling process. Some of the popularly used ones include Excel Power Query, Spreadsheets, OpenRefine, Google DataPrep, Watson Studio Refinery, Trifacta Wrangler, Python, and R, each with their own set of features, strengths, limitations, and applications.





  
