Advanced JavaScript Project - Exploring Closures and DOM Manipulation
Welcome to my Advanced JavaScript Project! This project is designed to deepen my understanding of JavaScript's powerful features, such as closures, lexical scoping, execution stack, and DOM manipulation. Each task here builds on the previous one, allowing me to explore different aspects of JavaScript’s advanced functionality.

Project Overview
Through this project, I aim to:

Understand closures and how JavaScript manages variable scope and data privacy.
Control the execution stack order with JavaScript's asynchronous features.
Manipulate the DOM using JavaScript closures to change webpage styles and interactivity.
Develop a solid foundation in lexical scoping, execution stack order, binding, callbacks, and private methods.
Table of Contents
Learning Objectives
Requirements
Project Tasks
Task 0: Lexical Scoping and Welcome Message
Task 1: Closure Scope Chain
Task 2: Closure
Task 3: Closure and Loops
Task 4: Complex Closure
Task 5: Changing DOM with Closure
Task 6: Private Methods with Closure
Task 7: Stack Order and setTimeout
Task 8: Stack Order in Functions
Task 9: Prime Numbers & Timing Execution
Task 10: Execution Stack & Timing Execution
Task 11: Changing Stack Order using setTimeout
Installation
Usage
License
Learning Objectives
The objectives of this project are:

To develop a clear understanding of lexical scoping in JavaScript.
To explore closures and use them for creating private variables and methods.
To understand the execution stack order and how to manipulate it for optimal performance.
To apply closures and timing functions to dynamically update the DOM and handle interactive elements.
To experiment with setTimeout and callbacks for controlled timing operations in JavaScript.
Requirements
To work on this project, I need:

A text editor (e.g., Visual Studio Code, Atom, or Sublime Text).
The JavaScript files should end with a .js extension.
A README.md file (this file) documenting the project.
Project Tasks
Task 0: Lexical Scoping and Welcome Message
File: 0-welcome.js

This task is about creating a welcome function that forms a greeting by combining a first and last name. It demonstrates lexical scoping by allowing a nested function to access variables in the outer scope.

Task 1: Closure Scope Chain
File: 1-nested_functions.js

Here, I’ll create nested functions that access variables from outer scopes, displaying three pop-up alerts. This task shows how closures preserve the scope chain.

Task 2: Closure
File: 2-function_me.js

This task practices creating closures with a welcomeMessage function that outputs a welcome alert for specific names like Guillaume, Alex, and Fred.

Task 3: Closure and Loops
File: 3-classrooms.js

In this task, I’ll use closures within a loop to dynamically assign seats, demonstrating how closures capture each loop's data. This helps me learn how to avoid common pitfalls with closures in loops.

Task 4: Complex Closure
File: 4-math.js

This task involves using closures to create functions for addition and division operations. I’ll create specific functions like addBy100, addBy1000, and divideBy10 to demonstrate reusable functions with closures.

Task 5: Changing DOM with Closure
File: 5-mode.js

This task is about changing the DOM using closures. I’ll create buttons (e.g., "Spooky," "Dark Mode") that, when clicked, update the webpage's style, allowing me to see closures applied to interactive elements.

Task 6: Private Methods with Closure
File: 6-hogwarts.js

Here, I’ll create a studentHogwarts module that uses closures to manage private methods and variables. This exercise is key to understanding data privacy in JavaScript.

Task 7: Stack Order and setTimeout
File: 7-timeout.js

This task is an introduction to the execution stack order. I’ll log messages to the console using setTimeout to see how asynchronous calls affect stack order.

Task 8: Stack Order in Functions
File: 8-payments.js

This task involves simulating a payment system to observe the order in which JavaScript functions are executed. It will deepen my understanding of stack order management in complex workflows.

Task 9: Prime Numbers & Timing Execution
File: 9-prime.js

This task involves creating a function to count prime numbers from 2 to 100 and measuring execution time. It highlights performance testing and the need for efficiency in JavaScript.

Task 10: Execution Stack & Timing Execution
File: 10-prime.js

In this task, I’ll rerun the prime counting function 100 times, recording the time taken for each run. It’s a deeper dive into performance analysis and timing execution.

Task 11: Changing Stack Order using setTimeout
File: 11-timeout.js

Here, I’ll use setTimeout to change the stack order, delaying calculations until the end of the stack. This task helps me explore JavaScript's asynchronous features and event loop.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/alu-web_front_end.git
Navigate into the project directory:
bash
Copy code
cd alu-web_front_end/Javascript_advanced
Usage
Each .js file can be tested in a JavaScript environment, such as the browser console or Node.js. Detailed instructions are included in each file’s comments.

Example for Running 0-welcome.js
Open the browser console or a Node.js environment.
Copy and paste the code from 0-welcome.js.
Call welcome('First', 'Last') to see the greeting message output.
License
This project is open-source under the MIT License. See the LICENSE file for more information.
