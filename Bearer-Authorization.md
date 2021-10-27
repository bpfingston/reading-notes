# Bearer Authorization

## Review, Research, and Discussion
1. Write the following steps in the correct order:
    1. Register your application to get a client_id and client_secret  
    2. Ask the client if they want to sign in via a third party  
    3. Redirect to a third party authentication endpoint  
    4. Receive authorization code  
    5. Make a request to the access token endpoint  
    6. Receive access token  
    7. Make a request to a third-party API endpoint  

2. What can you do with an authorization code?
    - The authorization code is a special password that authorizes the user to manipulate data within a security protected space.  
3. What can you do with an access token?
    - The token authorizes the user within a specific app, to access certain data.  
4. What’s a benefit of using OAuth instead of your own basic authentication?
    - Less liability, as it is relayed to OAuth, and generally Oauth is more secure than basic authentication.  

## Vocab
1. Client ID - is an identifier associated with an application that assists, with client APIs.  
2. Client Secret - a secret known only to the app and auth server.  
3. Authentication Endpoint -  an endpoint that is called to obtain an access token which can then be used in the subsequent password update callouts.  
4. Access Token Endpoint - where apps make a request to get an access token for a user  
5. API Endpoint - a point at which an API connects with the software program.  
6. Authorization Code - is a temp code that a client will exchange for an access token.  
7. Access Token - The token authorizes the user within a specific app, to access certain data.  
