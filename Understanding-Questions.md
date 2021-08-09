# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The button's onClick event is fired, invoking handleAddOne
* handleAddOne dispatches to addOne
* in actions/index.js, addOne is invoked which returns the type 'ADD_ONE' and exports it to reducers/index.js
* reducer in reducers/index.js performs the ADD_ONE case, adding 1 to state.total
...

* TotalDisplay shows the total plus 1.
