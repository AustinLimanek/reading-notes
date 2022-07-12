# Class 02

[Journal Home](README.md)

Current Readings:

1. [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
2. [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

## Reading Notes

### React Lifecycle

1. Based on the React Lifecycle Events diagram render occurs before the componentDidMount. The 'render' is above the 'componentDidMount' in the diagram.
2. Mounting is the first phase of the React lifecycle. 
3. Events in order: `constructor`, `render`, `react updates`, `componentDidMount`, `componentWillUnmount`.
4. `componentDidMount` is used if the DOM needs to be initialized in some way.

### React State Vs Props

1. You can pass props into components and they can act as initialization for a process or for basic information as titles, subtitles, description, etc.
2. State is local, and used only in the component. Props are used more globally, and in particular between parent and child.
3. If the props are changed then the component will re-render the component with the updated props. When the state changes, the application will also re-render. If the state somewhere else in the program has their state shared as props in another portion will also cause the program to re-render as the local state is changed from the new prop influencing the new state. State -> re-render -> state -> prop -> newState -> re-render. There appears to be two re-renders whenever a state is passed as a prop and back into an additional component that uses the passed prop as a new state.
4. State is the variable that holds a working input or changing value that needs to be updated for the user to better experience the UI. For example, when the user types information, feedback on spelling and grammar can help guide the writer to improve on the go. This is in contrast to only checking grammar and spelling at some given time. The current string is the state of the input variable. The components that react depending on information on the state appear during appropriate situations.

### Things I want to know more about

I now have a better understanding of the usefulness of state and props, however, I don't know how to actually code these concepts into the code. Hopefully I can glean understanding from reading number one.

&copy; 2022, NoMichi
