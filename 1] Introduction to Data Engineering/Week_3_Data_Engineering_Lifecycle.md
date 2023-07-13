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

# 3] Querying Data, Performance Tuning, and Troubleshooting :
- In order for raw data to become analytics-ready, a number of transformation & cleansing tasks need to be performed on raw data. And that requires you to understand 
  your dataset from multiple perspectives. One of the ways in which you can explore your dataset is to query it. 

- Basic querying techniques can help you explore your data, such as, counting and aggregating a dataset, identifying extreme values, slicing data, sorting data, 
  filtering patterns, and grouping data.

- In a data engineering lifecycle, the performance of data pipelines, platforms, databases, applications, tools, queries, and scheduled jobs, need to be constantly 
  monitored for performance and availability. 

- The performance of a data pipeline can get impacted if the workload increases significantly, or there are application failures, or a scheduled job does not work as 
  expected, or some of the tools in the pipeline run into compatibility issues. 

- Databases are susceptible to outages, capacity overutilization, application slowdown, and conflicting activities and queries being executed simultaneously. 

- Monitoring and alerting systems collect quantitative data in real time to give visibility into the performance of data pipelines, platforms, databases, applications, 
  tools, queries, scheduled jobs, and more.

- Time-based and condition-based maintenance schedules generate data that helps identify systems and procedures responsible for faults and low availability.

# 4] Governance and Compliance :
- Data Governance is a collection of principles, practices, and processes that help maintain the security, privacy, and integrity of data through its lifecycle.
- Personal Information and Sensitive Personal Information, that is, data that can be traced back to an individual or can be used to identify or cause harm to an individual, needs to be protected through governance regulations. 
- General Data Protection Regulation, or GDPR, is one such regulation that protects the personal data and privacy of EU citizens for transactions that occur within EU member states. 
Regulations, such as HIPAA (Health Insurance Portability and Accountability Act) for Healthcare, PCI DSS (Payment Card Industry Data Security Standard) for retail, and SOX (Sarbanes Oxley) for financial data are some of the industry-specific regulations. 

- Compliance covers the processes and procedures through which an organization adheres to regulations and conducts its operations in a legal and ethical manner.

- Compliance requires organizations to maintain an auditable trail of personal data through its lifecycle, which includes acquisition, processing, storage, sharing, retention, and disposal of data.

**Tools and technologies play a critical role in the implementation of a governance framework, offering features such as:**
- Authentication and Access Control.
- Encryption and Data Masking.
- Hosting options that comply with requirements and restrictions for international data transfers.
- Monitoring and Alerting functionalities.
- Data erasure tools that ensure deleted data cannot be retrieved.


  
