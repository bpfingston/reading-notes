# CRUD

## Status Codes Based On REST Methods
    1.  In your own words, describe what each group of status code represents:
        -   100’s = the initial request has been recieved and accepted, and the client should continue with the rest of it.
        -   200’s = valid request, and succeeded in validating.(not necessarily processed.)
        -   300’s = redirecting the client to a new loction due to the requested address not being accessable. 
        -   400’s = invalid request(timeouts, or wrong uri)
        -   500’s = server error code, such as being overwhelmed with data.
    2.  What is a status code 202?
        - the request has been accepted for processing.
    3.  What is a status code 308?
        - the resource requested has been definitively moved to the URI given.
    4.  What code would you use if an update didn’t return data to a client?
        - 204 No content
    5.  What code would you use if a resource used to exist but no longer does?
        - 410 Gone
    6.  What is the ‘Forbidden’ status code?
        - 403 Forbidden

## Build A REST API With Node.js, Express, & MongoDB - Quick 
    1.  Why do we need to pull our MongoDB database string out of our server and put it into our .env?
        - so we dont use our local host.
    2.  What is middleware?
        - code that runs when our server gets a request, but before it gets passed to our routes.
    3.  What does app.use(express.json()) do?
        - it allows our code to accept JSON as a body instead of a post element.
    4.  What does the /:id mean in a route?
        - a parameter, whatever is put in after the first slash.
    5.  What is the difference beween PUT and PATCH?
        - Patch - whatever the user passes us.
        - Put - it updates all information at once, rather than just what gets passed.
    6.  How do you make a default value in a schema?
        - by typing default: within the value section of the attribute of the schema.
    7.  What does a 500 error status code mean?
        - there is an error on your server. its our fault.
    8.  What is the difference between a status 200 and a status 201?
        - 201 - successfully created an object
        - 200 - everything was successful.