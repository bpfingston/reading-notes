# Event Driven Applications

## Review, Research, and Discussion
   1. Why is access control important?  
        - We dont want users to access data that we dont want manipulated or accessed.
   2. Describe an application that would need access control.
        - Any application that has user accounts, such as banking apps.
   3. What is a role used for?
        - To assign capabilities to a users account to manipulate or access data.
   4. Why is role based access control more scalable than discretionary or mandatory access control?
        - role based is more flexible in the sense that you can assign as much or as little access to a group of users as you want. discretionary requires individual management, so it would be hard to managage as the site scaled in size. Mandatory has a heirarchal system, and its strict in the sense that it has trouble adding roles that dont fit within the heirarchy. 

## Vocabulary
   1. Authorization
        - Different from authentication (which is essentially a service used for users to prove who they are), authorization is what access rules are for an authenticated user and either grants or refuses resource access. A user can be authenticated, but not authorized. 
   2. Role Based Access Control
        - Also considered Non-Discretionary Access Control, where access is based on a user's job function with an organization. Permissions are granted to roles rather than specific users or assets.
   3. Capabilities
        - levels of access that employees have to the network. E.g. admin, editor, writer, generic user, or which roles are able to create, read, update, or delete.