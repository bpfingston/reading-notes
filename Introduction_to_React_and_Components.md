# Introduction to React and Components

## Component Based Archetecture

    1.What is a component
        - it is a software object that is intended to interact with other components, which encapsulates certain functionality or a set of functionalities. 
    2.What are the charactersitics of a component?
        - **Reusability** - while some may be used for certain tasks, a majority of them are designed to be able to be reused.
        - **Replacability** - they are able to be replaced with other similarliy functioning components.
        - **Not Context Specific** - a component is able to work in a variety of ways and contexts.
        - **Extensible** - a component is able to be extended from old components, giving new behavior.
        - **Encapsulated** - it allows the caller to use its functionality wihtout it exposing its inner workings.
        - **Independent** -  they are designed to not have to depend on any other component.
    3.What are the advantages of using compent based architecture?
        - Ease of deployment - it gives ease to replacing old components and implementing the new ones.
        - Reduced cost - allows the spread of the cost of development and maintenance.
        - Ease of development - allow interfaces to provide defined funcationality and allowing development without impacting other parts of the system.
        - Reusable - allows you to again spread the maintence and development cost among other apps and systems, as you reuse them.
        - Modification of tech complexity - a component modifies the complexity through the use of a component container and its services.
        - reliability - the system becomes more reliable due to the reliability of the individual components.
        - System maintenance and evolution - ease to implement new components and swapping out old ones, without affecting the rest of the system.
        - Independent - while they don't depend on each other, components then give the system to be ablility to upgrade, without worrying about affecting the rest of the system. It also allows producitivity to continue without having to worry future devs working on the software screwing up code due to changing a component. 

## What is Props and How to Use it in React

    1.What is props short for?
        - it stands for properties
    2.How are props used in React?
        - to pass data from one component to another. w3schools say that props are arguments that are passed into React components.
    3.What is the flow of props?
        - uni-directional flow (one way from parent to child)
