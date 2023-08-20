## Reading: Component Based UI

>#### React Quick Start
>1. **What are the building blocks of a React app?**

>Components:
>React apps are constructed using reusable units known as components. These components are self-contained and encapsulated entities that can possess their individual state, properties (props), and methods. They come in two types: functional components (created with functions) and class components (created with classes).
>
>JSX (JavaScript XML):
>JSX is a syntax extension for JavaScript that allows you to write HTML-like code within your JavaScript code. It's used to define the structure and appearance of React components. JSX elements are compiled into React.createElement() calls.
>
>State:
>State works as a mechanism for handling and storing data that is subject to modification within a component. Class components possess their private internal state, whereas functional components can employ the useState hook to control state. Alterations made to the state initiate re-renders of the component, leading to updates in the user interface.
>
>Props (Properties):
>Props allow components to communicate with each other, Props are used to pass data from (parent) components to (child) components.Props help us create reusable and configurable components.
reparaphrase
>
>Virtual DOM (Document Object Model):
>React uses a (Virtual DOM), which is a lightweight representation of the actual DOM, when there are changes to the state or props of a component, React calculates the minimal set of changes required to update the Virtual DOM, this process is more efficient than directly manipulating the (real DOM).
>
>Reconciliation:
>this process ensures efficient updates and minimizes unnecessary re-renders, react's reconciliation process is responsible for comparing the current Virtual DOM with the previous one and determining the minimal changes needed to update the actual DOM. 
>
>Lifecycle Methods:
> Class components have a set of lifecycle methods that allow us to perform actions at specific points in a component's life cycle, such as when the component is mounted, updated, or unmounted, however, with the introduction of React hooks, many of these lifecycle methods have been replaced by hooks: like (useEffect).
>
>Hooks:
>functions that allow us to "hook into" React state and lifecycle features from functional components, they provide a way to manage state, perform side effects, and access other React features without using class components.
>
>Routing:
>routing is often a crucial part of building single-page applications (SPAs). Libraries like react-router help us manage different views and it help us navigation within our React app.
>
>Redux or (other state management libraries):
>for managing complex application states that need to be shared across components we can use Redux, Redux (or similar libraries) can be used. Redux follows a unidirectional data flow and provides a centralized store for managing state.
>

>2. **What is the difference between an HTML element and a React component?**
>While HTML elements establish the unchanging framework and content of a webpage, React components serve as versatile, reusable units that encompass both structure and functionality. This characteristic renders them highly suitable for constructing intricate and interactive user interfaces.

>3. **What is JSX and why do we use it?**
>JSX simplifies the process of constructing React components by allowing developers to blend HTML-like syntax with JavaScript, making it easier to build, understand, and maintain complex user interfaces while benefiting from React's performance optimizations.

>4. **Describe the process of embedding JavaScript expressions in JSX.**
>The process of embedding JavaScript expressions in JSX entails placing the intended JavaScript code inside curly braces {} directly within your JSX code. This enables the dynamic inclusion of variables, computations, or expression outcomes into your component's rendering. This approach facilitates the creation of dynamic content and interactive elements within your React components.

>5. **Does React or JSX have any special features for iteration or conditional logic?**
>React and JSX offer convenient features for handling iteration and conditional logic within your components. You can utilize the map function for dynamic iteration over data, rendering components accordingly. Additionally, JSX supports ternary and && operators for conditional rendering, allowing you to display content based on specific conditions.

>6. **How does React know to respond to a user’s inputs?**
>React responds to a user's inputs by capturing events, managing component states, re-rendering affected components, and efficiently updating the DOM through its Virtual DOM and reconciliation process. This methodology allows for a seamless and optimized user experience in React applications.

>7. **What word indicates that a React component manages data with a Hook?**
>useState, make the components can handle changing the data.

>8. **How can two react components share data?**
>by passing information through props, which are properties passed from parent to child components. Additionally, for more complex scenarios, a state management solution like Redux or React's Context API can be employed to share data across multiple components without direct prop passing.

>#### Render and Commit

>1. **What are the three steps of refreshing a React UI?**
>update the component's state, reconcile changes using the Virtual DOM, and efficiently update the real DOM to reflect the modifications, ensuring a responsive user interface.

>2. **How do you trigger updates to a component after the initial render?**
>making changes to a component after its initial rendering involves adjusting its state or props. React's re-rendering system identifies these alterations and efficiently updates both the Virtual DOM and the actual DOM, ensuring the user interface accurately displays the updated information or functionality.

>3. **Does React recreate DOM nodes on every rerender?**
>no, React's use of the Virtual DOM and the diffing algorithm allows it to perform targeted updates to the actual DOM without recreating DOM nodes on every rerender. This approach significantly improves the performance of React applications by reducing unnecessary DOM manipulation.

>4. **After React has updated the DOM, what still needs to happen before the user sees the change?**
>once React has applied updates to the DOM, the user can see the changes through these steps: Layout and Rendering, Painting, Compositing, Display.

