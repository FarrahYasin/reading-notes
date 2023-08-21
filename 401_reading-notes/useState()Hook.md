# Reading: useState() Hook


> #### Thinking in React:

> **Summarize the five steps of thinking in react.**
By follow these steps, you can systematically build responsive and modular user interfaces using React. This method emphasizes organization, reusability, and maintaining a clear data flow throughout the application.

>**Step 1. Deconstruct the UI into Components:**
Divide the user interface into smaller, reusable building blocks called components. Each component should have a specific purpose, handling a particular function or visual aspect.

>**Step 2. Construct a Static Representation:**
Develop a non-interactive version of the UI using React components, excluding any dynamic behavior or state management. This step helps in visualizing the layout and arrangement of components.

> **Step 3. Identify the Essential UI State:**
Determine the core set of data that your app needs to manage. Focus on the data that will change and drive component behavior.

> **Step 4. Plan the Component Hierarchy:**
Decide how components should be organized and interconnected. Establish how data flows between parent and child components, aiming to lift state to higher levels when possible.

> **Step 5. Integrate State Management:**
Incorporate state management into React components, following the minimal state defined earlier. Update components to utilize state data and define responses to user actions. This stage involves linking event handlers, passing properties, and managing state changes.

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