# Redux - Asynchronous Actions

## Review, Research, and Discussion  

1. How granular should your reducers be?  
    - You would use them for each component that you need a reducer for.
2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched  
    - Con, because if its too common, you might not intend for it the reducers to fire.
3. Name a strategy for preventing the above  
    - Name your action something different

## Vocab  

1. store  
   - a function that holds your reducers
2. combined reducers
   - object that contains multiple reducers