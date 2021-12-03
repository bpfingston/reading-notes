# Context-API-Behaviors

## Review, Research, and Discussion

1. When you have multiple contexts, what component type should you use (class/function) and why?
    - Depends on the user, but if you go function you can scale back the amount of state that you are using, and if you go class, you can really be choosy about the amoutn of state.
2. What are some good use cases for using the Context API for global state?
    - Anything that can make use of globabl state(ex. any auth service)
3. How can you best test context?
    - by having a child component use it.

## Vocab 

1. context - Context provides a way to pass data through the component tree without having to pass props down manually at every level.
2. useContext() - Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. This hook allows the child component to use the context that is being passed through. 
3. static context - A static method or, block belongs to the class and these will be loaded into the memory along with the class.