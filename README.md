[![DynamoDB](https://www.herontechnology.co.nz/wp-content/uploads/dynamodb-logo.png)](https://aws.amazon.com/documentation/dynamodb/)

# What is DynamoDB?

Amazon DynamoDB is a fully managed [NoSQL database] service that provides fast and predictable performance with seamless scalability.

  - You can use Amazon DynamoDB to create a database table that can store and retrieve any amount of data, and serve any level of request traffic.
  
  - Amazon DynamoDB automatically spreads the data and traffic for the table over a sufficient number of servers to handle the request capacity specified by the customer and the amount of data stored.
  
  - Amazon DynamoDB will maintain consistent and fast performance.

# What is NoSQL?

NoSQL is a term used to describe high-performance, non-relational databases (the relationships between the data are not important). 
  - Non-Relational means table-less: NoSQL databases are non-relational, hence, very different from SQL databases. This means they are easier to manage and they provide a higher level of flexibility with newer data models.
 
- They are Low-Cost: The open source nature of NoSQL databases makes them an appealing solution for smaller organizations with limited budgets. The top NoSQL databases allow for rapid processing of real-time Big Data applications in ways that are affordable.
 
- Easier scalability: Elastic scalability is a major selling point of NoSQL. NoSQL databases are designed to function on full throttle even with low-cost hardware.
 
- No need to develop a detailed database model: The non-relational nature of a NoSQL database allows database architects to quickly create a database without needing to develop a detailed (fine-grained) database model. This saves a lot of development time.

A slightly better explanation about NoSQL databases:

>Different databases are designed to solve different problems. Using a single database engine for all of the requirements usually leads to non- performant solutions; storing transactional data, caching session information, traversing graph of customers and the products their friends bought are essentially different problems.” 

**Pramod J. Sadalage, NoSQL Distilled: A Brief Guide to the Emerging World of Polyglot Persistence**

# Why you should consider DynamoDB?

- There is no size limit. You can store your data and have it scale out as the need arises. 

- Since it is hosted in multiple servers, it is redundant and highly available

- DynamoDB is fully managed by Amazon, so you can set it and forget it. Amazon will handled the servers, the software and the day to day activities so you can focus on your projects, not on your hardware.

- Get started with DynamoDB for free. Many applications can operate within these free tier limits.
    * Enough throughput to handle up to 200 million requests per month
    * 25 GB of indexed data storage.
    * 2.5 million read requests per month from DynamoDB Streams. 

# How much does it cost?

|Resource Type   |  Detailts | Monthly Price  |   
|---|---|---|
| Provisioned Throughput (Write)  |   **One write capacity unit (WCU)** provides up to one write per second, enough for **2.5 million writes per month**|As low as  $0.47 per WCU   |   
| Provisioned Throughput (Read)  |  One **read capacity unit (RCU)** provides up to two reads per second, enough for **5.2 million reads per month**| As low as  $0.09 per RCU  |   
| Indexed Data Storage	  | DynamoDB charges **an hourly rate per GB of disk space** that your table consumes  | As low as  $0.25 per GB  |   

# Additional Information

- [DynamoDB Service](https://aws.amazon.com/documentation/dynamodb/)
- [NoSQL Databses](https://aws.amazon.com/nosql/)
- [Pricing](https://aws.amazon.com/dynamodb/pricing/)
- [Cost Calculator](https://calculator.s3.amazonaws.com/index.html)

### My Contact Information

Carlos Ramos
carrams@amazon.com
(954) 736-0536
