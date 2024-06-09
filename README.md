# HTML Setup for Mocha Testing

This HTML document sets up a testing environment using Mocha for JavaScript testing.

- **Meta Tags**: 
  - Sets character encoding to UTF-8.
  - Ensures proper rendering and scaling on mobile devices.
  - Specifies compatibility with the latest rendering engine for Internet Explorer.

- **Title**: 
  - Sets the title of the webpage to "Log Even Nums".

- **External Resources**:
  - Links to the Mocha CSS stylesheet for test result styling.
  - Includes Mocha and Chai JavaScript libraries for testing functionality.

- **Body Content**:
  - Contains a div with the ID "mocha" for displaying Mocha test results.
  - Configures Mocha for Behavior-Driven Development (BDD) using `mocha.setup("bdd")`.
  - Includes JavaScript files for the main script and test script.
  - Runs Mocha tests with `mocha.run()` to execute the test suite.

# JavaScript Function for Logging Even Numbers

This JavaScript code defines a function `logEvenNums` that logs even numbers up to a specified input number.

- **Function Logic**:
  - Takes a single parameter `num`.
  - Iterates through numbers from 0 to `num`.
  - Checks if each number is even using the modulo operator (`%`).
  - Logs even numbers to the console using `console.log()`.

- **Example Usage**:
  - Calls the `logEvenNums` function with an input of 6 to log even numbers up to 6.
