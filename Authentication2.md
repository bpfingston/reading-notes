# Authentication

## Review, Research, and Discussion

1.  Explain what a “Singleton” is (in Computer Science terms)
    - A singleton class is a class that can have only one instance of that class at a time.
2.  Explain how the Singleton pattern can be used with Node modules, specifically with classes
    - make function a within a class, that is then exported as an instance of that class, so that that singleton pattern can be instanciated each time with out really being called.
3.  If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
    - by creating a logger file, we can create a logger class, with a singleton class inside of it. By exporting an instance of the logger, we can then spread the singleton class wherever a new instance of the logger is called. Thereby instanciating the singleton class over and over again.

## Vocab

1.  Router Middleware
    -   code that is called after a request and before a response.
2.  Dynamic Module Loading
    -   Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
3.  Singleton Pattern
    -   A singleton class is a class that can have only one instance of that class at a time.
4.  CRUD -> REST Method Matches
    -   Create = POST, Read = GET, Update = PUT, Delete = DELETE;
5.  Mock Testing 
    -   Mocks combine the functionality of both spies and stubs, which means that they replace the target function but at the same time provide us with the ability to observe how the function was called.

### sources
1.[DynamicModuleLoading](https://en.wikipedia.org/wiki/Dynamic_loading)  
2.[Singleton](https://medium.com/@maheshkumawat_83392/node-js-design-patterns-singleton-pattern-series-1-1e0ab71e3edf)  
3.[Mock Testing](https://devopedia.org/mock-testing)  
