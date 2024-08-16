### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
React is used to create clean UI's using HTML syntax within JavaScript code. This lets devs create usable components and write more efficient code. Some useful features include code reusability, code stability, streamlined debugging, and a virtual DOM. React can be used to build business websites and portfolios, forums, art gelleries, music streaming platofrms, and just about anything that might require sophisticated user interactions.

- What is Babel?
Babel is a JavaScript compiler that converts JavaScript into ES5 JavaScript, so that it can run in any browsers, incluiding those of which are outdated.

- What is JSX?
JSX is JavaScript XML, which is a syntax extension for JavaScript that lets us write HTML directly in React within JavaScript code.

- How is a Component created in React?
In React, a component is created by using the React.createClass() method. For the full progression, you would export the component, define the function, and then add some markup if applicable.

- What are some difference between state and props? 
If the data will change, use State. If the data won't change, use Props. For example, when creating a gameBoard - for the Score and the Display Text After game, we use state since it could change. For the numRows and numColumns on the game board, we use Props because they are static. For state, data is specific to a component. For props, data is passed to a component.

- What does "downward data flow" refer to in React?
Downward data flow refers to the passage of data from the top-level component to the leaves.

- What is a controlled component?
Controlled Components rely on React state to manage form data

- What is an uncontrolled component?
Uncontrolled Components rely on the DOM itself to manage form data

- What is the purpose of the `key` prop when rendering a list of components?
Keys identify which items in a ist have been modified. They give an identity to the elements in the list.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?
Arrays are often modified with .push(), .pop(), or any other reordering modifications. Props are immutable, and it is easy for an array to be changed.

- Describe useEffect.  What use cases is it used for in React components?
useEffect runs after the first render, runs after all rerenders by default, accepts a callback function as its first argument, and returns undefined or a function. You can place dependencies in an array as its second argument. If somevalues haven't changed, you can tell React to skip applying an effect.

- What does useRef do?  Does a change to a ref value cause a rerender of a component?
useRef returns a mutable object within a key of current, whose value is equal to the initial value passed into the hook. The object persists across renders. Mutating the object does not trigger a re-render.

- When would you use a ref? When wouldn't you use one?
We use a ref when accessing an underlying DOM element or when we are setting up & clearing timers. We don't use it to control the state of the DOM.

- What is a custom hook in React? When would you want to write one?
A function that has reusable logic, which lets it be shared across different functional components. It lets you share stateful logic, but not the state itself. Each call to a Hook is independent from every other call to the same Hook. You write one if you have on or multiple React Hooks that will be used in multiple locations in a code.
