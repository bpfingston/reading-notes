# Advanced State with Reducers

## Review, Research, and Discussion

1. How can we ensure that an effect hook runs only once?
   - If you want to run an effect and clean it up only once (on mount and unmount), you can pass an empty array ([]) as a second argument.
2. Can useState() update more than one state variable at the same time?
   - No, but we can call useState more than once to update multiple variable.s
3. Is useState() synchronous?
   - no its Async.

## Vocab 

1. State Hook
   - A Hook is a special function that lets you “hook into” React features.
2. Component Lifecycle
   - A component’s lifecycle is broadly classified into four parts:
        - initialization
        - mounting
        - updating
        - unmounting.
