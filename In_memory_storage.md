# In memory storage  

## Understanding the JavaScript Call Stack  

    1.  What is a ‘call’?  
        -  function invocation/ invoking a function to work
    2.  How many ‘calls’ can happen at once?  
        -  1
    3.  What does LIFO mean?  
        -  Last In, First Out
    4.  Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.  
        -   function firstFunction(){
                throw new Error('Stack Trace Error');
            }

            function secondFunction(){
                firstFunction();
            }

            function thirdFunction(){
                secondFunction();
            }

            thirdFunction();

    5.  What causes a Stack Overflow?
        -  A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

## JavaScript error messages

    1.  What is a ‘refrence error’?  
        -   When you try to use a variable that is not yet declared or you have a TDZ with a const or let, you get this type of errors.  
    2.  What is a ‘syntax error’?  
        -   This occurs when you have something that cannot be parsed in terms of syntax.  
    3.  What is a ‘range error’?  
        -   Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.  
    4.  What is a ‘type error’?  
        -   These types of errors show up when the type (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.  
    5.  What is a breakpoint?  
        -   a tool to debug your code.  
    6.  What does the word ‘debugger’ do in your code?  
        -  it causes your line to break, so you might figure out what is wrong with it.  