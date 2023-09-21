# Readings: Redux - Additional Topics

#### Redux Toolkit (RTK)

**1.What concerns are addressed by Redux Toolkit?**
>**Redux Toolkit is a library that tackles various concerns within Redux applications, streamlining and enhancing the development process:
Minimizing Boilerplate: It reduces the need for repetitive and boilerplate code, simplifying the setup and management of Redux.
Ensuring Immutable State: Redux Toolkit promotes the practice of immutable state updates, guarding against unintentional mutations and common errors.
Simplifying Action Creation: It streamlines the creation of actions and action creators, minimizing naming inconsistencies and typographical errors.
Handling Asynchronous Actions: Redux Toolkit seamlessly integrates with Redux Thunk middleware, facilitating the management of asynchronous actions.
Configuring DevTools: It automatically configures the Redux DevTools Extension, facilitating debugging.
Enhancing Performance: It offers memoized selectors, which can significantly boost performance.
Encouraging Encapsulation: Redux Toolkit encourages the grouping of related actions and reducers for more organized code.
Enhancing Type Safety: Leveraging TypeScript, Redux Toolkit provides improved type inference and enhances type safety.**


**2.What does configureStore() do?**
>**configureStore() is a utility function offered by Redux Toolkit, designed to streamline the creation of a Redux store within a Redux application. It bundles together multiple steps and configurations typically involved in setting up a Redux store, thereby simplifying the process for developers and ensuring that the store is initialized with sensible defaults.**

**3.How would I use createSlice()?**
>* **Import Redux Toolkit**
>* **Create a Slice**
>* **Export Actions and Reducers**
>* **Use in a Reducer File**



#### MobX

**1.What is Mobx?**
>**MobX represents a JavaScript library for managing application state, with a primary focus on state management within user interfaces. It offers an uncomplicated and effective approach to handling an application's state while ensuring seamless synchronization with the user interface. MobX derives its name from "Mobility of eXperience" and draws inspiration from the principles of reactive programming.**

**2.How does MobX make it “impossible” to produce an inconsistent state?**
>**MobX ensures the prevention of an inconsistent state by implementing rigorous guidelines for modifying state within actions, monitoring dependencies, guaranteeing immediate updates, and furnishing secure methods for observing alterations. This unwavering commitment to reactive principles serves to uphold a consistent and foreseeable application state, consequently diminishing the chances of encountering errors and unexpected behavior arising from erratic state modifications.**

**3.How would we build a reactive user interface?**
>**using MobX, we can follow these steps:**
>* **Setup MobX**
>* **Define Your Application State**
>* **Create Actions**
>* **Derive Computed Values**
>* **Build Components**
>* **Inject State**
>* **Trigger Actions**
>* **React to State Changes**
>* **Cleanup**
