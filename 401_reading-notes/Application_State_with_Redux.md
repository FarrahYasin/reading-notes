# Application State with Redux

#### Dan Abramov Redux Tutorials:

* 1. **What is the first principle of Redux?**
>Redux's initial principle revolves around "Single Source of Truth," highlighting that all of your application's state is consolidated within a single JavaScript object known as the "store."


* 2. **what is a store and what do we use our reducers for within that store?**
>The store serves as the central repository where your application's state is stored, while reducers are utilized within the store to dictate how state alterations should occur in response to dispatched actions. Reducers are pivotal in guaranteeing the predictability, manageability, and traceability of state modifications, ensuring the adherence to the "Single Source of Truth" concept in Redux.


* 3. **Name three Redux store methods given to us by createStore and describe their use.**
>The createStore function in Redux provides several methods to interact with the store. Here are three essential methods provided by createStore and their uses:
>
>getState():
Use: The getState() method is used to retrieve the current state of the Redux store.
>
>Description: When called, it returns the current state object, which represents the entire state tree of your application. You can access and read data from this state to display it in your components or perform any necessary operations.
dispatch(action):
>Use: The dispatch(action) method is used to dispatch actions to the Redux store.
>
>Description: Actions are plain JavaScript objects that describe changes you want to make to the state. When you call dispatch(action), Redux processes the action through your reducers and updates the state accordingly. This is how you trigger state changes in your application.
subscribe(listener):
>Use: The subscribe(listener) method is used to add listeners that will be notified whenever the state of the Redux store changes.
>
>Description: You pass a listener function to subscribe, and Redux will call this function whenever an action is dispatched and state changes occur. This allows you to react to state changes in your application, such as updating the user interface when the data in the store changes. The listener can be used to trigger re-renders in connected components.

* 4. **Explain to a non-technical recruiter what combineReducers() does and why it is useful.**
>Imagine combineReducers() as the orchestrator of your Redux state, much like a project manager assigning specific tasks to different teams (reducers) to ensure a seamless collaboration. It plays a crucial role in simplifying the development and upkeep of intricate applications using Redux.