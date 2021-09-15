# Readings: Passing Functions as Props

## Lists and Keys

    1.What does .map() return?  
        -  a new array  
    2.If I want to loop through an array and display each value in JSX,how do I do that in React?  
        - you put it in curley brackets{}, and run the map function to iterate through each value within the first array.  
    3.Each list item needs a unique ____.  
        - key  
    4.What is the purpose of a key?  
        - it helps React identify which items have added, changed, or been removed.  

## The Spread Operator  

    1.What is the spread operator?  
        - An ellipsis of three dots (…).  
    2.List 4 things that the spread operator can do.  
        - 4 things
            1. Copy an Array  
            2. Concatenate or combine arrays  
            3. Adds to state in React  
            4. Convert NodeList to an array  
    3.Give an example of using the spread operator to combine two arrays.
        - combining two arrays
            - var two = [1,2]
            - var arrays = [3,4]
            - var twoArrays = [...two, ...arrays]
            - console.log(twoArrays) //= [1,2,3,4]
    4.Give an example of using the spread operator to add a new item to an array.
        - adding an item into an array
            - var add = [3,4]
            - var items = [1,2, ...add]
            -console.log(items) //= [1,2,3,4]
    5.Give an example of using the spread operator to combine two objects into one.
        -cominging two objects
            - var two = {egg: "🥚"}
            - var objects = {bacon: "🥓"}
            - var twoObjects = {...two, ...objects, burrito: "🌯"}
            - console.log(twoObjects) //= {egg: "🥚", bacon: "🥓", burrito: "🌯"}

## How to Pass Functions between Components

    1.In the video, what is the first step that the developer does to pass functions between components?
        - creating the function
    2.In your own words, what does the increment function do?
        - it takes in a name that has been passed through, and checks the name against the array of people object's names, if the names match then the counter increases by 1, and returns the people object that has been selected. 
    3.How can you pass a method from a parent component into a child component?
        - props allow you to pass methods.
    4.How does the child component invoke a method that was passed to it from a parent component?
        -  by using "this.props", if the parent was called prompt
        
        this.props.prompt() would invoke the parent from the child.
