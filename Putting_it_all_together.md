# Readings: Putting it all together  

## Thinking in React
    1.What is the single responsibility principle and how does it apply to components?  
        - A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.  
    2.What does it mean to build a ‘static’ version of your application?  
        - There is no interactivity, instead of using state, you would use props since the data doesnt need to change.  
    3.Once you have a static application, what do you need to add?
        - you need to add ReactDom.render so that the UI will update.  
    4.What are the three questions you can ask to determine if something is state?  
        - 3 questions:   
            1.Is it passed in from a parent via props?  
            2.Does it remain unchanged over time?  
            3.Can you compute it based on any other state or props in your component?  
        - if yes at any time, you aren't in state.  
    5.How can you identify where state needs to live?  
        - by identifying a common component that owns a piece of state in the other components. If you can't decide on one, then make a component to do so.  

## Higher-Order Functions  

    1.What is a “higher-order function”?  
        - Functions that operate on other functions, either by taking them as arguments or by returning them.  
    2.Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?  
        -  they are return 'm' which is defined as 'm' being greater than 'n.'
    3.Explain how either map or reduce operates, with regards to higher-order functions.  
        -  map that applies a given function(or transforms) to each element of a function(or container/list/s.)
