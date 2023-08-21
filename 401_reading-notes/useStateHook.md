# Reading: useState() Hook


> #### Thinking in React:

> **Summarize the five steps of thinking in react.**
By following these steps, you can create an organized and maintainable React application, dividing it into manageable components, structuring data flow, and maintaining a clear separation between UI and state management.

>**Step 1. Decompose into Components::**
Divide the user interface into smaller, distinct components.
Identify which parts of the UI can be encapsulated as reusable components.

>**Step 2. Construct a Static Version::**
Develop a non-interactive version of the app using these components.
Employ props to convey data and structure to render the UI.
Defer adding interactive features at this phase.

> **Step 3. Determine Essential UI State::**
Pinpoint the core data that needs to change and be remembered.
Emphasize efficiency by minimizing redundant state information.

> **Step 4. Identify State Ownership::**
Recognize components that rely on or display the state.
Establish a common parent component for components sharing related state.
Decide where to house the state within the component hierarchy.

> **Step 5. Implement Two-Way Data Flow::**
Enable interactive behavior by letting components modify shared state.
Distribute state-changing functions (typically using useState's setters) as props to child components.
Components nested deeper can trigger updates in parent components, altering shared state.

 ---

> #### State: A Component’s Memory

>1. **What is one reason a local variable isn’t sufficient for managing a React component?**

a local variable isn't sufficient for managing a React component because it lacks the ability to handle dynamic updates and changes in the component's state over time. 

>2. **What is the argument to the useState hook, and what are the two parts of its return array?**

Argument: Takes an initial value for the state variable.
Return Array: Returns a pair of elements:
State Variable: Current value of the state.
Setter Function: Updates the state variable and triggers re-render.

>3. **How can Component A access state from Component B?**
To share data between components in react we can use **props**