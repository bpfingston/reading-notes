# Express REST API

## Review, Research, and Discussion

    1.  Name 3 real world use cases where you’d want to change the request with custom middleware
        -   logging
        -   validating data
        -   Time stamping request
    2.  True or false: The route handler is middleware?
        -   False
    3.  In what ways can a middleware function end the process and send data to the browser?
        -   `res.end`, `res.send`, `next()`
    4.  At what point in the request lifecycle can you “inject” middleware?
        -   After the request is made, but before the response is returned.
    5.  What can cause express to error with “Request headers sent twice, cannot start a second response”
        - When a function tries to call a callback twice, or making a request of the same path more than once.

## Vocabulary

    -   Middleware - software that acts as abridge between an operating system or database and applications, especially on a network.
    -   Request Object - Defines the resource that you wish to fetch.
    -   Response Object - An object definig a body for the response.
    -   Application Middleware - Middleware thats applicable to the entire application itself. Sends requests to the server by using app.use(), app.get(), etc
    -   Routing Middleware - This is middleware that is supplied to a specific route. It will only be executed on that route and will be chained in order depending on where it's passed in to the route.
    -   Test Driven Development - “Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing, and design.
    -   Behavioral Testing - a testing process for inputs and outputs in which you aren't writing the application.