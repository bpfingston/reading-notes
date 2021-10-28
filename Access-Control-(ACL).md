# Access Control (ACL)  
  
## Review, Research, and Discussion  
  
1.When is Basic Authorization used vs. Bearer Authorization?  
    - Bearer if the user is requesting to use api controls are access controlled.  
    -Basic if the user needs to access the API with username and password credentials.  
2.What does the JSON Web Token package do?
    - authorizes the user to which is it subscribed to.  
3.What considerations should we make when creating and storing a SECRET?  
    - make sure teh SECRET is stored in a place that is not accessable by others. Like any .env file, also it is good for the secret to be at least 32 characters long.  

## Vocab

1. encryption - Encryption is the method by which information is converted into secret code that hides the information's true meaning.  
2. token - a token is a single element of a programming language. There are five categories of tokens: 1) constants, 2) identifiers, 3) operators, 4) separators, and 5) reserved words.  
3. bearer - a string with no meaning or uses but becomes important within a proper tokenization system. The server usually generates the bearer token in response to a login request and saves it in the browser or local storage.  
4. secret - provides a mechanism to hold sensitive information such as passwords, OpenShift Container Platform client configuration files, dockercfg files, private source repository credentials, and so on.  
5. JSON Web Token - JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.  

### sources:
    1.[Encryption](https://searchsecurity.techtarget.com/definition/encryption) 
    2.[Token](https://techterms.com/definition/token)  
    3.[Bearer](https://reqbin.com/req/javascript/h4rnefmw/post-json-with-bearer-token-authorization-header)4.[Secret](https://docs.openshift.com/container-platform/3.7/dev_guide/secrets.html)       
    5.[JSON Web Token](https://jwt.io/introduction)