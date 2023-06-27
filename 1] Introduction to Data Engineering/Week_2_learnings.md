
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
