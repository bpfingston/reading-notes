# Express

## Review, Research, and Discussion

   1. Whats the difference between `Put` and `Patch`?  
        -`Put` is used for creating a new resourse and replacing the old one.  
        -`Patch` is used to modify or update and resource.  
   2.Provide links to 3 services or tools that allow you to “mock” an API for development like json-server  
        1. MockServer
        2. Nock
        3. Apigee  
   3.Compare and contrast Swagger and APIDoc.js 
        - Swagger: It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation.
        - ApiDoc: it creates a documentation from API annotations in the source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated api_data.js and api_project.js as a html-page.
   4 Which HTTP status codes should be sent with each type of (un)successful API call?
        1. `400` - Bad Request
        2. `401` - Unauthorized
        3. `403` - Forbidden
        4. `404` - Not Found
        5. `405` - Method Not Allowed
        6. `409` - Conflict 
        7. `500` - internal Sever Error
        8. `503` - Service Unavailable
   5. Compare and contrast SOAP and ReST
        - SOAP: (Simple Object Access Protocol) is a standards-based web services access protocol that has been around for a long time. Originally developed by Microsoft, SOAP isn’t as simple as the acronym would suggest.
            - Works well in distributed enterprise environments
            - Standardized
            - SOAP uses XML for all messages
        - REST: (Representational State Transfer) is another standard, made in response to SOAP’s shortcomings. It seeks to fix the problems with SOAP and provide a simpler method of accessing web services.
            - REST requires use of HTTP
            - Smaller learning curve
            - Fast and Efficient
## Vocabulary Terms

   1. Terms:
        - Web Server: A web server is software and hardware that uses HTTP and other protocols to respond to client requests made over the World Wide Web.
        - Express: It is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks.
        - Routing: The process by which requests (which are specified by URL and HTTP method) are routed to code that takes care of them.
        - WRRC: Web Request/Response Cycle.


## Sources
   [PUT vs Patch](https://www.geeksforgeeks.org/difference-between-put-and-patch-request/)  
   [Apidocjs vs Swagger](https://stackshare.io/stackups/apidocjs-vs-swagger-inspector)  
   [Status Codes](https://documentation.commvault.com/11.24/essential/45599_rest_api_response_codes_and_statuses.html)  
   [SOAP vs REST](https://smartbear.com/blog/soap-vs-rest-whats-the-difference/)
