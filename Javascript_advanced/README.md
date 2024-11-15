JavaScript Advanced - Master README
Overview
This project focuses on mastering advanced JavaScript concepts and programming techniques. Topics covered include lexical scoping, closures, call stack management, binding, and callbacks. These concepts are crucial for understanding the inner workings of JavaScript, creating more efficient code, and developing sophisticated applications.

Project Directory: Javascript_advanced
Tasks
0. Lexical Scoping and Welcome Message
File: 0-welcome.js
Description: Create a function welcome that demonstrates lexical scoping. It should alert a welcome message using a nested function.
Testing: Run welcome('Holberton', 'School'); in the browser console.

1. Closure Scope Chain
File: 1-nested_functions.js
Description: Create a series of nested functions that demonstrate closure and alert messages sequentially.
Testing: Ensure alerts display messages in the correct order: "Welcome", "Welcome Holberton", and "Welcome Holberton!".

2. Closure
File: 2-function_me.js
Description: Create a closure welcomeMessage and test with multiple calls for different names.
Testing: Run guillaume(), alex(), fred() in the console to check for proper alert messages.

3. Closure and Loops
File: 3-classrooms.js
Description: Implement a closure createClassRoom that returns seat numbers using a loop and closure.
Testing: Run tests in the browser console to check for the correct seat numbers.

4. Complex Closure
File: 4-math.js
Description: Write functions that return closures to add and divide numbers.
Testing: Use the console to ensure correct mathematical operations and outputs.

5. Changing DOM with Closure
File: 5-mode.js
Description: Use closure to modify the DOM's CSS when specific buttons are clicked.
Testing: Ensure the page's appearance changes correctly when each button is clicked.

6. Private Methods with Closure
File: 6-hogwarts.js
Description: Create a class studentHogwarts with private methods and variables using closures.
Testing: Verify proper functionality for rewarding and penalizing students.

7. Stack Order and setTimeout
File: 7-timeout.js
Description: Demonstrate the execution order using loops and setTimeout.
Testing: Ensure console logs appear in the expected sequence.

8. Stack Order in Functions
File: 8-payments.js
Description: Implement processOrder and processPayment to manage order processing and log messages in sequence.
Testing: Verify the console logs all steps correctly for multiple orders.

9. Prime Numbers & Timing Execution
File: 9-prime.js
Description: Write a function to count prime numbers and measure execution time using the performance API.
Testing: Ensure execution time is logged correctly.

10. Execution Stack & Timing Execution
File: 10-prime.js
Description: Execute countPrimeNumbers 100 times and measure execution time.
Testing: Confirm that execution time is logged in the console.

11. Changing Stack Order Using setTimeout
File: 11-prime.js
Description: Modify the execution order of countPrimeNumbers using setTimeout.
Testing: Check that calculations are delayed as expected and time is logged.

12. Binding
File: 12-room_area.js
Description: Bind a function to an object roomDimensions and calculate the area.
Testing: Ensure boundGetArea returns the correct area.

13. Binding + Closure
File: 13-bind_user.js
Description: Create a user object and use bind() to personalize a welcome message.
Testing: Test with various welcome strings in the console.

14. Simple Callback
File: 14-wikipedia.js
Description: Use a callback function with XMLHttpRequest to fetch data and modify the DOM.
Testing: Ensure the paragraph element is correctly added to the page.

Usage
Clone the repository: git clone https://github.com/omda3310/holbertonschool-web_front_end.git
Navigate to the project directory: cd Javascript_advanced
Open the desired JavaScript file in your editor to make changes and test in your browser console.