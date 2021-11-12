# AWS: Events

## Review, Research, and Discussion  

   1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
    - Both run CRUD within, and give you the ability to assign roles w/ authentication. 
   2. List the AWS Database offerings and talk about the pros and cons of each
    - Amazon RDS
    - Amazon DynamoDB
    - Amazon Redshift
    - AWS Database Migration Service
    - Amazon ElastiCache
   3. What’s the difference between a FIFO and a standard queue?
    - FIFO - provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.
    - Standard Queue - provide at-least-once delivery, which means that each message is delivered at least once.
   4. How can the server be assured a message was properly received?  
    - sending back a validation of the message, when an event is triggered.

## Vocab

   1. Serverless API - Creates a collection of Amazon API Gateway resources and methods that can be invoked through HTTPS endpoints.
   2. Triggers - A trigger is a special type of stored procedure that automatically runs when an event occurs in the database server. 
   3. Dynamo vs Mongo - 
    - Mongo 
        - Laptop to mainframe, on-premise to hybrid cloud to managed cloud service
        - MongoDB Atlas database as a service can be deployed on AWS, Azure and GCP
    - DynamoDB 
        - No support for on-premises deployments
        - Locked-in to a single cloud provider
   4. Dynamoose vs Mongoose
    - Dynamoose
        - Dynamoose is an Object Data Modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose.
    - Mongoose
        - Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.