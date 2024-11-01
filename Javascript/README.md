# JavaScript Directory

This directory contains JavaScript code examples and utilities. Below is a brief description of each file in this directory.

## Files

### `Debounce.js`
- **Description**: A debounce function in JavaScript limits how often a given function can be called in quick succession. This is particularly useful when handling events like scroll or resize, where frequent firing can impact performance.
- **Usage**: The `debounce` function takes two arguments: the function to debounce and the delay in milliseconds. It returns a debounced version of the function.
- **Example**:
  ```javascript
  const logMessage = (message) => {
      console.log(message);
  };
  const debouncedLog = debounce(logMessage, 300);
  debouncedLog('Hello');
  debouncedLog('World');
  debouncedLog('!');
  ```

### `Throttle.js`
- **Description**: A throttle function in JavaScript limits how often a given function can be called in a given time period. This is particularly useful when handling events like scroll or resize, where frequent firing can impact performance.
- **Usage**: The `throttle` function takes two arguments: the function to throttle and the limit in milliseconds. It returns a throttled version of the function.
- **Example**:
  ```javascript
  const logMessage = (message) => {
      console.log(message);
  };
  const throttledLog = throttle(logMessage, 1000);
  throttledLog('Hello');
  throttledLog('World');
  throttledLog('!');
  ```

### `hello-world.js`
- **Description**: A simple "Hello, World!" program in JavaScript.
- **Usage**: Run the file using a JavaScript runtime like Node.js.
- **Example**:
  ```javascript
  console.log("Hello, World!");
  ```

## How to Run

To run any of the JavaScript programs in this directory, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory containing the JavaScript file you want to run.
3. Run the JavaScript file using a JavaScript runtime like Node.js. For example, to run `hello-world.js`, use the following command:

   ```bash
   node hello-world.js
   ```

## Contributing

If you have any JavaScript code examples or utilities that you would like to add to this directory, please follow the contribution guidelines in the main `README.md` file of the repository.
