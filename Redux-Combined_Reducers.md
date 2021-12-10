# Redux - Combined Reducers

## Review, Research, and Discussion  

1. Why choose Redux instead of the Context API for global state?  
    - It makes it easier to manage large amounts of state for larger apps, but context works just fine for smaller apps.
2. What is the purpose of a reducer?
    - It reduces a collection, and gives out single solitary state that is distributed, determined by the action given.
3. What does an action contain?
    - The logic to handle an event.
4. Why do we need to copy the state in a reducer?
    - To save initial state, and not override it.

## Vocab  

1. immutable state
    - state that is unable to be changed, and can be used to as a backup for anything that you wish to revert back too.
2. time travel in redux
    - ability to to look through different states of state.
3. action creator
    - logic that determines the action.
4. reducer
    - It reduces a collection, and gives out single solitary state that is distributed, determined by the action given.
5. dispatch
    - to execute or return an action.
