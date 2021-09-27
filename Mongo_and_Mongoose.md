# Mongo and Mongoose

## nosql vs sql

    1. Fill in the chart below with five differences between SQL and NoSQL databases:
        - SQL
            1. SQL databases are primarily called as Relational Databases (RDBMS).  
            2. SQL databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful.  
            3. SQL databases are not best fit for hierarchical data storage.  
            4. In most typical situations, SQL databases are vertically scalable.  
            5. Excellent support are available for all SQL database from their vendors. There are also lot of independent consultations who can help you with SQL database for a very large scale deployments.  
        -NoSQL
            1. NoSQL database are primarily called as non-relational or distributed database.  
            2. In NoSQL database, queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database.  
            3. NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set.  
            4. NoSQL databases are horizontally scalable.  
            5. NoSQL database you still have to rely on community support, and only limited outside experts are available for you to setup and deploy your large scale NoSQL deployments.  

    2.  What kind of data is a good fit for an SQL database?
        - data that needs to be on a table, set out in columns and rows.
    3.  Give a real world example.
        - a Point of Sale System - POS
    4.  What kind of data is a good fit a NoSQL database?
        - data that doesnt need to adhere to a certain type of schemea
    5.  Give a real world example.
        - data mining application
    6.  Which type of database is best for hierarchical data storage?
        - NoSQL
    7.  Which type of database is best for scalability?
        - SQL - is vertically scalible. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server.
        - NoSQL - is horizontially scalible. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.
    
## sql vs nosql (Video)

    1.  What does SQL stand for?
        - Structered Query Language
    2.  What is a realational database?
        - it works with certain assumptions or certain way, and works with the SQL. Tables can work in conjunction with each other. 
    3.  What type of structure does a relational database work with?
        - a Table, and multiple of them.
    4.  What is a ‘schema’?
        - it is a set of rules that are defined by fields. 
    5.  What is a NoSQL database?
        - Its stores huge amounts of data.
    6.  How does it work?
        - it uses collections(could be called tables.)(names and ages)
            - then uses documents, that dont have to use the schema from the collections. (sometimes ages and sometime names)
    7.  What is inside of a Mongo database?
        -   a mass of data, with no relations. the data shouldnt have too much relation merging, but super fast querying. 
    8.  Which is more flexible - SQL or MongoDB? and why.
        - MongoDB, because it doesn't follow a schema, and no relation that is containing them. If you have a lot of collections this can be quite daunting.
    9.  What is the disadvantage of a NoSQL database?
        - if you have to update data, without relationtions, you have to manually update all the data that is affected by the update.
