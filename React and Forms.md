# Readings: React and Forms  

## Forms  

    1.What is a ‘Controlled Component’?  
        -An input form element whose value is controlled by React.
    2.Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.  
        -it should update on its own, but updating the state with their responses as soon as they enter them, because thats how React(Controlled Components) handles it.
    3.How do we target what the user is entering if we have an event handler on an input field?  
        - event.target.value

## The Conditional (Ternary) Operator Explained

    1.Why would we use a ternary operator?  
        -  its used as an alternative conditional to "if" statements, because its shorter.
    2.Rewrite the following statement using a ternary statement:  
        - x === y ? 'true' : 'false'