# Authorization/Authentication

## Review, Research, and Discussion
    1.  What header(s) are used in authentication and authorization?
        -   Basic and Bearer respectively
    2.  What is safe to put into a JWT
        -   a secret, a token, username, and password.
    3.  How are JWTs validated
        -   Formatting is checked (headers) ;
        -   Signature is verified ;
        -   Check standard claims  ;

## Vocab
    1.  RBAC - Role-based access control (RBAC) is a method of regulating access to computer or network resources based on the roles of individual users within your organization.  
    2.  User Roles - User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.  
    3.  JWT Token - JSON web token (JWT), pronounced "jot", is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

## sources

  1.[RBAC](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)  
  2.[User Roles](https://central.smarsh.com/s/article/What-are-User-Roles)  
  3.[JWT Token](https://auth0.com/docs/security/tokens/json-web-tokens)  
