
## Types of Data :
- Data that follows a rigid format and can be organized neatly into rows and columns is structured data. Eg: databases and spreadsheets.
- Semi-structured data is a mix of data that has consistent characteristics and data that doesn’t conform to a rigid structure.
   Eg: email has a mix of structured data, such as the name of the sender and recipient, but also has the contents of the email, which is unstructured data.
- Unstructured data—data that is complex, and mostly qualitative information that is impossible to reduce to rows and columns.
  Eg: photos, videos, text files, PDFs, and social media content.

## Data Repositories Types :—
1] Transactional systems, also known as Online Transaction Processing (or OLTP) systems, are designed to store high-volume day-to-day operational data. Such as online 
   banking transactions, ATM transactions, and airline bookings. While OLTP databases are typically relational, they can also be non-relational.

2] Analytical systems, also known as Online Analytical Processing (OLAP) systems, are optimized for conducting complex data analytics.
   These include relational andnon-relational databases, data warehouses, data marts, data lakes, and big data stores.


## Basic points about data format :
- Whereas XML was widely popular like a decade ago, especially with the SOAP protocol of the web applications. However, soon the web developers and corporations
  discovered that it can be a resource intensive, especially memory, because it has both the starting and ending tags.
- So then JSON came into the picture. They got it off the ending tags and just looked like a key-value pairs and it saved some resources.
   And it is now widely used as part of the RESTful APIs. And then even newer versions of the data format such as Apache Avro are gaining wide popularity because
  of the efficiency on how they store the data.
- relational databases struggle a little bit with heavy write intensive applications such as IoT or sensor data, social media data 
   because the B-tree data structures that drive, or power, these relational databases

### Idenifying data source :
- structure of the data, nature of the application, and the volume at which the data is getting ingested into your database.

- data validations Load is the step where processed data is transported to a destination system or data repository. It could be: Initial loading, that is, populating all the data in the repository; Incremental loading, that is, applying ongoing updates and modifications as needed periodically; or Full refresh, that is, erasing contents of one or more tables and reloading with fresh data Load verification—which includes data checks for missing or null values, server performance, and monitoring load failures, are important parts of this process step.

- Big Data refers to the dynamic, large and disparate volumes of data being created by people, tools, and machines. It requires new, innovative, and scalable technology to collect, host, and analytically process the vast amount of data gathered in order to derive real-time business insights that relate to consumers, risk, profit, performance, productivity management, and enhanced shareholder value.”

- Hive is based on Hadoop, queries have very high latency—which means Hive is less appropriate for applications that need very fast response times. Also, Hive is read-based, and therefore not suitable for transaction processing that typically involves a high percentage of write operations. Hive is better suited for data warehousing tasks such as ETL, reporting, and data analysis and includes tools that enable easy access to data via SQL

## Data Platforms, Data Stores, and Security

- Data Repository : 
It can be a small or large database infrastructure with one or more databases that collect, manage, and store data sets.
Different types of repositories your data might reside in, such as databases, data warehouses, and big data stores,

-  Data mart is to : provide users' data that is most relevant to them when they need it, accelerate business processes by providing efficient
   response times, provide a cost and time-efficient way in which data-driven decisions can be taken, improve end-user response time; and provide secure access and control.

- A Data Lake is a data repository that can store large amounts of structured, semi-structured, and unstructured data in their native format. While a data warehouse
   stores data that has been cleaned, processed, and transformed for a specific need, you do not need to define the structure and schema of data before loading into 
   the data lake. A data lake exists as a repository of raw data in its native format, straight from the source, to be transformed based on the use case for which it 
   needs to be analyzed. 

# RDBMS Use Case :
- well suited for IOT and Data Warehouse(OLAP).
- Does not work well with structured and semi-structured data. migration is only possible if identical schema and data type of both RDBMS.

## Summary and Highlights

The architecture of a data platform can be seen as a set of layers, or functional components, each one performing a set of specific tasks. These layers include:

- Data Ingestion or Data Collection Layer, responsible for bringing data from source systems into the data platform.
- Data Storage and Integration Layer, responsible for storing and merging extracted data.
- Data Processing Layer, responsible for validating, transforming, and applying business rules to data.
- Analysis and User Interface Layer, responsible for delivering processed data to data consumers.
- Data Pipeline Layer, responsible for implementing and maintaining a continuously flowing data pipeline.

A well-designed data repository is essential for building a system that is scalable and capable of performing during high workloads. 

The choice or design of a data store is influenced by the type and volume of data that needs to be stored, the intended use of data, and storage considerations. 
The privacy, security, and governance needs of your organization also influence this choice.

The CIA, or Confidentiality, Integrity, and Availability triad are three key components of an effective strategy for information security. 
The CIA triad is applicable to all facets of security, be it infrastructure, network, application, or data security.

## Practice Quiz

### Question 1
Which one of these steps is an intrinsic part of the “Data Storage and Integration Layer” of a data platform?
- **Transform and merge extracted data, either logically or physically**

The Storage and Integration layer in a data platform stores, transforms, and merges extracted data to make it available for data processing.

### Question 2
Systems that are used for capturing high-volume transactional data need to be designed for faster response times to complex queries.
- **False**

Systems that are used for capturing high-volume transactional data need to be designed for high-speed read, write, and update operations.

### Question 3
What is the role of “Intrusion Detection” and “Intrusion Prevention” in the area of network security?
- **Inspect incoming network traffic for intrusion attempts and vulnerabilities**

Intrusion Detection and Intrusion Prevention systems inspect network vulnerabilities and intrusion attempts and prevent them from happening.

## Graded Quiz
### Question 1
Which one of these steps is an intrinsic part of the “Data Processing Layer” of a data platform?
- **Read data in batch or streaming modes from storage and apply transformations**

### Question 2
Systems that are used for capturing high-volume transactional data need to be designed for high-speed read, write, and update operations.
- **True**

High-speed read, write, and update operations are essential for systems that need to capture large volumes of transactional data.

### Question 3
What is the role of “Network Access Control” systems in the area of network security?
- **To ensure endpoint security by allowing only authorized devices to connect to the network**

This is achieved with the help of Network Access Control systems. 

### Question 4
____________ ensures that users access information based on their roles and the privileges assigned to their roles.
- **Authorization**

One of the primary controls for data security is to enable access to data through a system of Authorization. It allows access to information based on a user’s role and role-based privileges. 

### Question 5
Security Monitoring and Intelligence systems:
- **Create an audit history for triage and compliance purposes**

Security Monitoring and Intelligence systems create an audit trail and provide reports and alerts that help enterprises react to security violations in time.

# ****Data Collection and Data Wrangling****

## **Summary and Highlights**

Depending on where the data must be sourced from, there are a number of methods and tools available for gathering data. These include query languages for extracting data from databases, APIs, Web Scraping, Data Streams, RSS Feeds, and Data Exchanges.

Once the data you need has been gathered and imported, your next step is to make it analytics-ready. This is where the process of Data Wrangling, or Data Munging, comes in. 

Data Wrangling involves a whole range of transformations and cleansing activities performed on the data. Transformation of raw data includes the tasks you undertake to:

- Structurally manipulate and combine data using Joins and Unions.
- Normalize data, that is, clean the database of unused and redundant data.
- Denormalize data, that is, combine data from multiple tables into a single table so that it can be queried faster.

Cleansing activities include:

- Profiling data to uncover anomalies and quality issues.
- Visualizing data using statistical methods in order to spot outliers.
- Fixing issues such as missing values, duplicate data, irrelevant data, inconsistent formats, syntax errors, and outliers.

A variety of software and tools are available for the data wrangling process. Some of the popularly used ones include Excel Power Query, Spreadsheets, OpenRefine, Google DataPrep, Watson Studio Refinery, Trifacta Wrangler, Python, and R, each with their own set of features, strengths, limitations, and applications.

## Practice Quiz

### Question 1
How is data gathered using Application Programming Interfaces, or APIs?
- **APIs are invoked from applications to access databases, web services, data marketplaces and other such data endpoints for gathering data**

### Question 2
What is one of the common structural transformations used for combining data from one or more tables?
- **Joins**

### Question 3
What tool allows you to discover, cleanse, and transform data with built-in operations?
- **Watson Studio Refinery**

Watson Studio Refinery has built-in features that allow you to discover, cleanse, and transform data. 

## Graded Quiz

### Question 1
Web scraping is used to extract what type of data?
- **Text, videos, and images**

### Question 2
___________ focuses on cleaning the database of unused data and reducing redundancy and inconsistency.
- **Normalization**

Normalization cleanses the database of unused data and inconsistencies in data that is coming from multiple sources. 

### Question 3
OpenRefine is an open-source tool that allows you to:
- **Transform data into a variety of formats such as TSV, CSV, XLS, XML, and JSON**

### Question 4
When you’re combining rows of data from multiple source tables into a single table, what kind of data transformation are you performing?
- **Unions**

Unions are a common structural transformation used for combining rows of data from multiple source tables. 

### Question 5
When you detect a value in your data set that is vastly different from other observations in the same data set, what would you report that as?
- **Outlier**

Outliers are values in your data set that may be vastly different from other values in the same data field. 

# ****Querying Data, Performance Tuning, and Troubleshooting****

## **Summary and Highlights**

- In order for raw data to become analytics-ready, a number of transformation and cleansing tasks need to be performed on raw data. And that requires you to understand your dataset from multiple perspectives. One of the ways in which you can explore your dataset is to query it.
- Basic querying techniques can help you explore your data, such as, counting and aggregating a dataset, identifying extreme values, slicing data, sorting data, filtering patterns, and grouping data.
- In a data engineering lifecycle, the performance of data pipelines, platforms, databases, applications, tools, queries, and scheduled jobs, need to be constantly monitored for performance and availability.
- The performance of a data pipeline can get impacted if the workload increases significantly, or there are application failures, or a scheduled job does not work as expected, or some of the tools in the pipeline run into compatibility issues.
- Databases are susceptible to outages, capacity overutilization, application slowdown, and conflicting activities and queries being executed simultaneously.
- Monitoring and alerting systems collect quantitative data in real time to give visibility into the performance of data pipelines, platforms, databases, applications, tools, queries, scheduled jobs, and more.
- Time-based and condition-based maintenance schedules generate data that helps identify systems and procedures responsible for faults and low availability.

## **Practice Quiz**

### Question 1

In the video, we used a query function to see how spread out the values in the “Sale Amount” field are. What function did we use?
- **Standard Deviation**

### Question 2
______________ helps you assess if the size of a workload is slowing down the system.
- **Monitoring the amount of data being processed through a data pipeline**

# ****Governance and Compliance****

## **Summary and Highlights**

Data Governance is a collection of principles, practices, and processes that help maintain the security, privacy, and integrity of data through its lifecycle.

Personal Information and Sensitive Personal Information, that is, data that can be traced back to an individual or can be used to identify or cause harm to an individual, needs to be protected through governance regulations.

General Data Protection Regulation, or GDPR, is one such regulation that protects the personal data and privacy of EU citizens for transactions that occur within EU member states. 
Regulations, such as HIPAA (Health Insurance Portability and Accountability Act) for Healthcare, PCI DSS (Payment Card Industry Data Security Standard) for retail, and SOX (Sarbanes Oxley) for financial data are some of the industry-specific regulations.

Compliance covers the processes and procedures through which an organization adheres to regulations and conducts its operations in a legal and ethical manner.

Compliance requires organizations to maintain an auditable trail of personal data through its lifecycle, which includes acquisition, processing, storage, sharing, retention, and disposal of data.

Tools and technologies play a critical role in the implementation of a governance framework, offering features such as:

- Authentication and Access Control.
- Encryption and Data Masking.
- Hosting options that comply with requirements and restrictions for international data transfers.
- Monitoring and Alerting functionalities.
- Data erasure tools that ensure deleted data cannot be retrieved.

## **Practice Quiz**

At what stage of the data lifecycle would you establish which third-party vendors in your supply chain will have access to the data you are collecting?
- **Data Sharing**

It is in the Data Sharing phase of the data lifecycle that you establish which third-party vendors will have access to your data, and how they will be held accountable to the same regulations you are liable for.

## **Graded Quiz**
### Question 1
In which phase of the data lifecycle do you establish the data you need, the amount of data you need, and how you intend to use the data you are collecting.
- **Data Acquisition**

In the Data Acquisition phase, you establish the data you need to collect, the amount of data you need, and its intended use. 

### Question 2
The process of _____________ abstracts the presentation layer without changing the data in the database physically.
- **Anonymization**

Using Anonymization, the presentation layer is abstracted without changing the data in the database itself. 

# Quiz

## Practice Quiz
### Question 1
Automated tools, frameworks, and processes for all stages of the data analytics process are part of the Data Engineer’s ecosystem. What role do data integration tools play in this ecosystem?
- Store high-volume day-to-day operational data in data repositories
- Cover the entire journey of data from source to destination
- **Combine data from multiple sources into a unified view that is accessed by data consumers to query and manipulate data**
- Conduct complex data analytics

### Question 2
Which of these data sources is an example of semi-structured data?
- Documents
- Social media feeds
- **Emails**
- Network and web logs

### Question 3
Which one of the provided file formats is commonly used by APIs and Web Services to return data?
- XML
- Delimited file
- **JSON**
- XLS

### Question 4
What is one example of the relational databases
discussed in the video?
- Spreadsheet
- XML
- Flat files
- **SQL Server**

### Question 5
Which of the following languages is one of the most popular querying languages in use today?
- R
- **SQL**
- Java
- Python

## Graded Quiz

### Question 1
There are two main types of data repositories – Transactional and Analytical. For high-volume day-to-day operational data such as banking transactions, Transactional, or OLTP, systems are the ideal choice.
- **True**
- False

Transactional, or OLTP, systems are designed and optimized for handling high-volume transactions.

### Question 2
Which of the following is an example of unstructured data?
- Zipped files
- **Video and Audio files**
- XML
- Spreadsheets

### Question 3
Which one of these file formats is independent of software, hardware, and operating systems, and can be viewed the same way on any device?
- XML
- XLSX
- **PDF**
- Delimited text file

PDF format is independent of software, hardware, and operating systems, and can be viewed the same way on any device. 

### Question 4
Which data source can return data in plain text, XML, HTML, or JSON among others?
- **APIs**
- Delimited text file
- XML
- PDF

APIs can return data in a wide variety of formats such as plain text, XML, HTML, or JSON among others. 

### Question 5
In the data engineer’s ecosystem, languages are classified by type. What are shell and scripting languages most commonly used for?
- Manipulating data
- Building apps
- **Automating repetitive operational tasks**
- Querying data
