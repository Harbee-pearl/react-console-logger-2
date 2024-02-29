# React Console Logger 2

React Console Logger 2 is a simple and efficient React npm package designed to facilitate logging items in the console for debugging purposes within your React applications.

## Installation

You can install React Console Logger 2 via npm:

```bash
npm install react-console-logger-2
```

or using yarn:

```bash
yarn add react-console-logger-2
```

# Usage

Using react-console-logger-2 is straightforward. Simply import the logger function and place it within your React component or functions, passing the items you wish to log as an argument.

# Props

react-console-logger-2 accepts the following props:

value: (required) The item or data you wish to log in the console.

# Example

Here's an example of how you can use React Console Logger 2 in your React application:

```bash
import { logger } from 'react-console-logger-2';

const App = () => {

  const data = { name: 'Alice', age: 25, city: 'New York' };
  const data2 = "Hello World"


  return (
    <div>
      <h1>My App</h1>
     <button onClick={()=>logger(data)}>Log </button>
    </div>
  );
};

export default App;

```

# License

React Console Logger 2 is licensed under the MIT License.
