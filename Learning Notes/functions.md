### Functions
Some tasks need to be performed multiple times within a program. 
Rather than rewrite the same code in multiple places, a function may be defined using the def keyword. 
Function definitions may include parameters, providing data input to the function.

### Returning Multiple Values
Python functions are able to return multiple values using one return statement. 
All values that should be returned are listed after the return keyword and are separated by commas.

### The Scope of Variables
In Python, a variable defined inside a function is called a local variable. 
It cannot be used outside of the scope of the function, and attempting to do so without defining the variable outside of the function will cause an error.

### Function Parameters
Sometimes functions require input to provide data for their code. 
This input is defined using parameters.
Parameters are variables that are defined in the function definition. 
They are assigned the values which were passed as arguments when the function was called, elsewhere in the code.

### Multiple Parameters
Python functions can have multiple parameters. 
Just as you wouldn’t go to school without both a backpack and a pencil case, functions may also need more than one input to carry out their operations.

### Returning Value from Function
A return keyword is used to return a value from a Python function. 
The value returned from a function can be assigned to a variable which can then be used in the program.

### Function Indentation
Python uses indentation to identify blocks of code. Code within the same block should be indented at the same level. 
A Python function is one type of code block. All code under a function declaration should be indented to identify it as part of the function. 
There can be additional indentation within a function to handle other statements such as for and if so long as the lines are not indented less than the first line of the function code.

### Calling Functions
Python uses simple syntax to use, invoke, or call a preexisting function. A function can be called by writing the name of it, followed by parentheses.

### Global Variables
A variable that is defined outside of a function is called a global variable. It can be accessed inside the body of a function.

### Parameters as Local Variables
Function parameters behave identically to a function’s local variables. They are initialized with the values passed into the function when it was called.
Like local variables, parameters cannot be referenced from outside the scope of the function.

### Function Arguments
Parameters in python are variables — placeholders for the actual values the function needs. When the function is called, these values are passed in as arguments.

### Function Keyword Arguments
Python functions can be defined with named arguments which may have default values provided. When function arguments are passed using their names, they are referred to as keyword arguments. The use of keyword arguments when calling a function allows the arguments to be passed in any order — not just the order that they were defined in the function. If the function is invoked without a value for a specific argument, the default value will be used.
