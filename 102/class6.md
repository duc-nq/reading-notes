# What are variables in JavaScript?

Variables are containers for storing data (storing data values).

In this example, x, y, and z, are variables, declared with the var keyword:

# What does it mean to `declare` a variable?


• Helps ensure that the variable is defined before you try to use it. This avoids undefined variable errors.

• Specifies the scope of the variable - declares where the variable can be accessed in your code. Globally declared variables can be accessed anywhere, locally declared variables only in that scope.

• Specifies the data type. Variables in JS are dynamically typed, but we can hint the data type in the declaration.

• Prevents unintended variable creations. Without a declaration, simply assigning a value to an "undeclared" variable will create it implicitly. Explicit declarations help catch typos.

• Useful for debugger/tools. The declaration allows better tooling/debugging support as the tools know the variables in each scope.

# What is an “assignment” operator, and what does it do?

The assignment operator in JavaScript is =.

It assigns a value to a variable.

The basic syntax is:

variable = value;

For example:

let x = 5; // Assigns 5 to variable x
let y = 'Hello'; // Assigns string 'Hello' to variable y
let z = x + y; // Assigns the value of x + y to z

# What is information received from the user called?

In JavaScript, information received from the user is typically called:

• Input - A general term for any data received from the user.

• User input - Also a general term.

• Form data - Specifically refers to data submitted from HTML forms.

• Query string data - Data from the query string in a URL.

• Event data - Data associated with user events (clicks, touches, etc).