# API's

## API Design Best Practices  

    1.  What does REST stand for?  
        - Representational State Transfer - it uses open standards, and does not bind the implementation of the API or the client applications to any specific implementation.  
    2.  REST APIs are designed around a ____.  
        - resource  
    3.  What is an identifer of a resource? Give an example.  
        - an identifier is a URI that uniquely identifies that resource.  
            -EX. https://github.com/orders/1  
    4.  What are the most common HTTP verbs?   
        -  GET, POST, PUT, PATCH, and DELETE  
    5.  What should the URIs be based on?  
        - Nouns  
    6.  Give an example of a good URI.  
        - https://adventure-works.com/orders  
    7.  What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
        - it may require a client application to send multiple requests to find all of the data that it requires. bad thing, because it overloads the server.  
    8.  What status code does a successful GET request return?  
        - HTTP status code 200(OK).  
    9.  What status code does an unsuccessful GET request return?  
        - HTTP status code 404(Not Found).  
    10. What status code does a successful POST request return?  
        - HTTP status code 200(Created).  
    11. What status code does a successful DELETE request return?  
        - HTTP status code 204(No Content).  

## RegExr

    1.  How would you match your name using RegEx?  
        -/^Bryce$|^Daniel$|^Pfingston$([A-Z][a-z]*) (the asterisk repeats the code before it unlimited times to match whatever string you are passing.)  
