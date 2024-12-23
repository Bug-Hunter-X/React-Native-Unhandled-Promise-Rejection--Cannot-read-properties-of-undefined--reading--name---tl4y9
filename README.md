## React Native: Handling Uninitialized State

This repository demonstrates a common error in React Native: attempting to access a state variable before it has been initialized.  This often manifests as an `Unhandled Promise Rejection` or a `Cannot read properties of undefined` error. 

The `bug.js` file showcases the problematic code. The solution, provided in `bugSolution.js`, addresses the issue by using conditional rendering to gracefully handle the scenario where the state variable is still null or undefined.