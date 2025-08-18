A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables). abcd abcd_def $myfubnction

The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables. //not a global variable

function name(parameter1, parameter2, parameter3) { // code to be executed transaction process
}

Function Invocation The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button) When it is invoked (called) from JavaScript code Automatically (self invoked)