# Class 00

[Journal Home](README.md)

Current Readings:

1. [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
2. [Higher order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

## Reading Notes

### React Docs - Thinking in React

1. Each component or function has one job to execute, which allows for a more modular approach to programming. This approach makes the code easier to follow for other developers and allows for the code to be reused in other contexts.
2. Static suggests that the application is just displaying the basic components of the website in their default mode. Therefore, if the user does input information, the application will not respond. It's a basic proof of life step.
3. Data flow and the functionality of state. This allows for props to pass information down to children and provides functionality.
4. The following are questions for determining state:

  -First: is it passed from the parent via props -> then no
  -Second: Does it change? -> if so, then yes
  -Third: Can it be computed with state or props -> if so, then no

5. State should exist as the lowest node that is commonly shared and need to update if the state changes.

### Higher order functions

1. A higher order function uses more primitive code it their definition to allow for developers to use these higher level functions to work with concepts less granularly.
2. greaterThan takes in an input and uses it to define a new function, then returns that function. The author then defines a new function which which will have an input that goes in the place of m in the greaterThan function. The output of greaterThan10 has an output of true or false.
3. The map method iterates through an array-like object and creates a new array that has element that are transformed outputs of the original array elements.

### Things I want to know more about

I would like to know more about why the greaterThan output function has an obvious return value of either true or false. `m => m > n`: why does this have an output of true when m is greater than n. I guess, why is this the default logic and not null.

&copy; 2022, NoMichi
