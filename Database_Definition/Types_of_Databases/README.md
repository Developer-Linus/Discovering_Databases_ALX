# Types of Databases
The main objective of this section is to gain a comprehensive understanding of the different types of databases available, with a focus on SQL (Relational) and NoSQL databases. Explore their fundamental characteristics, strengths, weaknesses, and typical use cases. Develop the ability to evaluate and choose the appropriate database type based on specific requirements, such as data structure, scalability needs, and performance considerations.

# Concept Overview
## Topics
- SQL - Relational Databases
- NoSQL - Non-Relational Databases
## Learning Objectives
- Understand the differences between SQL and NoSQL databases.
- Identify the characteristics, use cases, and examples of each type of database.
## SQL Databases
SQL (Structured Query Language) databases, also known as relational databases, are based on the relational model introduced by E.F. Codd in 1970. They store data in tables with predefined schema and use SQL for querying and manipulation. Data is organized into tables with rows (records) and columns (fields). Tables can be related to each other through foreign keys and join operations. <br>

SQL databases enforce a strict schema, meaning that the structure of the data (tables, columns, and data types) must be defined in advance and they use Structured Query Language (SQL) for data manipulation and retrieval. SQL databases are well-suited for applications that require complex querying, data integrity, and transactions, such as financial systems, e-commerce platforms, and content management systems.

## Characteristics:

- **Structured Data**: Data is organized into predefined structures with strict schema.
- **ACID Transactions**: SQL databases support ACID (Atomicity, Consistency, 
- **Isolation, Durability)** transactions to maintain data integrity.
- **Data Integrity**: Enforces data integrity through constraints such as primary keys, foreign keys, and unique constraints.

## Examples of Databases

- **MySQL**: An open-source relational database management system (RDBMS) widely used in web development.
- **PostgreSQL**: A powerful open-source object-relational database system known for its robustness and extensibility.
- **Oracle**: A commercial RDBMS commonly used in enterprise applications.

## NoSQL Databases
NoSQL (Not only SQL) databases are non-relational databases that store and retrieve data in a way that differs from the tabular structure used in relational databases. They are designed to handle unstructured or semi-structured data and provide flexible schemas. NoSQL databases can be categorized into different types, including key-value stores, document-oriented databases, column-family stores, and graph databases. <br>

NoSQL databases are designed to scale horizontally by distributing data across multiple servers or clusters, making them suitable for handling large volumes of data and high-traffic applications. They often sacrifice some of the ACID properties in favor of higher availability, partition tolerance, and eventual consistency.

## Characteristics:

- **Schema Flexibility**: NoSQL databases support flexible schemas, allowing for easier adaptation to evolving data models.
- **Scalability**: Designed for horizontal scalability, enabling distributed storage and processing across multiple nodes.
- **Variety of Data Models**: Support various data models such as document, key-value, columnar, and graph.

## Examples:

- **MongoDB**: A popular document-oriented NoSQL database that stores data in flexible JSON-like documents.
- **Cassandra**: A distributed NoSQL database designed for scalability and high availability, commonly used in large-scale distributed systems.
- **Redis**: An in-memory data store that supports various data structures like strings, lists, sets, and hashes.

[Youtube Video Link](https://youtu.be/ZS_kXvOeQ5Y) <br>

## Practice Exercises

Exercise 1: Identify a use case where a SQL database would be more suitable than a NoSQL database, and explain your reasoning.

Exercise 2: Discuss the trade-offs between using a SQL database and a NoSQL database in terms of scalability, data consistency, and query complexity.

## Additional Resources
[NoSQL vs SQL Databases](https://intranet.alxswe.com/rltoken/ThoY4OpLMm9J5IzA0xc0qg) <br>
[SQL vs NoSQL Databases: What’s the difference](https://intranet.alxswe.com/rltoken/F423AWCdNMAmbKJwujWoVw) <br>
[What is SQL Database](https://intranet.alxswe.com/rltoken/lokAgSHQG3SP-MXIqa1Uww)<br>
[What is NoSQL](https://intranet.alxswe.com/rltoken/bMvEtYLoSLbHo-WDlKPfRA)