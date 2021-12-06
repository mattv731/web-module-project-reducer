# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- Computer looks into the handleClick function which calls the dispatch and "addOne"
- Uses the useReducer function on (reducer, initial state)
- reducer shows that if the case is ADD_ONE to spread state, and +1
- TotalDisplay shows the total plus 1.
