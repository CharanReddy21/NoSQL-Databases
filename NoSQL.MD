># NoSQL Databases

> ### NoSql stands for 'Non-relational or distributed database system'.


\
NoSQL databases ("not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads. NoSQL databases are horizontally scalable. This means that you handle more traffic by sharding, or adding more servers in your NoSQL database.  


<br>
<br>

>## Here are the some of NoSQL databases

\
There are so many NoSQL databases are available. MongoDB, CouchDB, CouchBase, Cassandra, HBase, Redis, Riak, Neo4J,DynamoDB are the popular NoSQL databases.

>1.MongoDB
 
MongoDB is a general purpose, document-based, distributed database built for modern application developers and for the cloud. In today’s IT industry, there are large number of companies who are using MongoDB as a database service for the applications or data storage systems. As per the survey made by Siftery on MongoDB, there are around 4000+ company confirmed that they are using MongoDB as Database. Some of the key names are :

* Castlight Health

* IBM

* Citrix

* Twitter

* T-Mobile

* Zendesk

* Sony

Companies and development teams of all sizes use MongoDB because:

* The document data model is a powerful way to store and retrieve data that allows developers to move fast.

* Enable collaboration of a large number of teams.

* Scale your data repository to a massive size.

<br>

 >2.DynamoDB

\
Amazon DynamoDB is a fully managed proprietary NoSQL database service that supports key-value and document data structures and is offered by Amazon.com as part of the Amazon Web Services portfolio.

 
Benefits of DynamoDB for Operations:

* Those who have worked in the IT industry know that scaling databases can both be difficult and risky. DynamoDB gives you the ability to auto-scale by tracking how close your usage is to the upper bounds
* DynamoDB constantly creates a backup of your data for safety purposes which allows owners to have data saved on the cloud.
* If your data objects are required to be stored in inconsistent schemas, DynamoDB can manage that.
*  Since DynamoDB is a NoSQL data model, it handles less structured data more efficiently than a relational data model, which is why it’s easier to address query volumes and offers high performance queries for item storage in inconsistent schemas.


<br>

> 3.HBase

\
HBase is an open-source non-relational distributed database.
Unlike relational database systems, HBase does not support a structured query language like SQL; in fact, HBase isn’t a relational data store at all.

An HBase system is designed to scale linearly. It comprises a set of standard tables with rows and columns, much like a traditional database. Each table must have an element defined as a primary key, and all access attempts to HBase tables must use this primary key.

* We can use this HBase feature for high-speed requirements because it offers consistent reads and writes.

* During one read or write process, all other processes are prevented from performing any read or write operations this is what we call Atomic read and write. So, HBase offers atomic read and write, on a row level. 

* In both linear and modular form, HBase supports scalability. In addition, we can say it is linearly scalable.

* For both semi-structured as well as structured data, HBase supports well

* There is no concept of fixed columns schema in HBase because it is schema-less. Hence, it defines only column families


<br>

>4.CouchBase

Couchbase Server is a NoSQL document database for interactive web applications. It has a flexible data model, is easily scalable, provides consistent high performance and is capable of serving application data with 100% uptime. 

The primary unit of data storage in Couchbase Server is a JSON document. Because application objects are modeled as documents, schema migrations do not need to be performed.

* Provides multiple data access paths to query and manage your JSON documents. App developers can pick the data access pattern that best meets their requirements. Flexible data access paths makes Couchbase useful for a wide variety of apps and use cases.

* Built-in full-text search makes it simple for developers to add intelligence to apps

* Built with a strong emphasis on reliability, high availability, and simple management, an important feature of Couchbase Server is that all operations can be done while the system remains online, without requiring modifications or interrupting running applications.


<br>

>5.ElasticSearch
<br>

Elasticsearch is a document oriented database. This NoSQL database is used if the full-text search is part of your solution. For applications that rely heavily on a search platform for the access, retrieval, and reporting of data.

*  Websites which store a lot of content find Elasticsearch a very useful tool for effective and accurate searches.

*  Another major analytics application of Elasticsearch is security analysis. Access logs and similar logs concerning system security can be analyzed with the ELK stack, providing a more complete picture of what’s going on across your systems in real-time.

Company Use Cases
 
 * Netflix 
* Ebay
* Walmart





<br>
<br>

>References

https://www.geeksforgeeks.org/difference-between-sql-and-nosql/

https://www.guru99.com/nosql-tutorial.html

https://medium.com/better-programming/5-real-life-use-cases-for-dynamodb-a152a9d152e2

https://medium.com/better-programming/5-real-life-use-cases-for-dynamodb-a152a9d152e2

https://docs.couchbase.com/server/5.0/introduction/intro.html

https://blog.eduonix.com/bigdata-and-hadoop/use-hbase-nosql-db/#:~:text=Apache%20HBase%20is%20suitable%20for,to%20get%20a%20better%20performance.

https://www.knowi.com/blog/what-is-elastic-search/#:~:text=Elasticsearch%20allows%20you%20to%20store,directly%2C%20it%20searches%20an%20index.



