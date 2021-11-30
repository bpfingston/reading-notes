# Component Lifecycle / useEffect() Hook

## Review, Research, and Discussion

   1. Why do we not need more .html pages in a multi-page React app?
     -  We dont need more than a single page because we use routes to cover the multiple different pages that we might need to use.
   2. If we wanted a component to show up on every page, where would we put it and why?
     - Inside the <BrowserRouter />, outside a <Route />

   3. What does routing do with the components that were rendered when a new route is requested?
     - they become unmounted and are store the info within a react history object.
   4. What does props.children contain?
     - the props carried down from the parent.
   5. How do useState() and this.setState() differ?
     - useState is a hook that uses functions instead of classes.
     - this.setState is used to change the state of a class component.

## Vocab

  1. State Hook
    - lets a developer add state without having to convert a function to a class.
  2. Mounting and Un-Mounting
    - Mounting: setting the route and all state involved within its components to be rendered on the screen.
    - Un-mounting: removing the route and all state involved within its components, so that it isnt rendered anymore.