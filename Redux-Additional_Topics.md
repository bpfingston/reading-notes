# Redux - Additional Topics  

## Review, Research, and Discussion  

- What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
  - useEffect

- When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
  - the reducer function, along with with action

## Vocab  

1. middleware
    - function that acts between the request and the response
2. thunk
    - middleware that allows async functions to interact with redux store.
