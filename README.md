# assignment3
1)Organization -- As programs grow in complexity, having all the code live inside the main () function becomes increasingly complicated. ...
Reusability -- Once a function is written, it can be called multiple times from within the program. ...
Testing -- Because functions reduce code redundancy, there’s less code to test in the first place

2)A function is a block of code that only runs when it is called. Python functions return a value using a return statement, if one is specified. A function can be called anywhere after the function has been declared. By itself, a function does nothing.


3)To create function def keyword is use in Python. Define a unique name for the function and in parenthesis, you can specify your parameters.
def function-name(paramenter):
  # statement
  
4)A function is a block of code that does a particular operation and returns a result. It usually accepts inputs as parameters and returns a result. The parameters are not mandatory.

E.g:
Function add(a,b)
return a+ b

A function call is the code used to pass control to a function.

E.g.:

b = add(5,6)

Now b will have the value 11.

5)Python Local and Global Variables – We can define the scope of the variable as the extent of the program within which we can access the variable.
In Python, there are two primary variable scopes:

Local variable in Python
Global variable in Python

6)A local scope is created whenever a function is called. Any variables assigned in this function exist within the local scope. When the function returns, the local scope is destroyed, and these variables are forgotten.

7)The specific value returned from a function is called the return value. When the return statement is executed, the return value is copied from the function back to the caller. This process is called return by value.
In procedures, a RETURN statement cannot contain an expression. The statement just returns control to the caller before the normal end of the procedure is reached. In functions, a RETURN statement must contain an expression, which is evaluated when the RETURN statement is executed.

8)f a function doesn't specify a return value, it returns None.

In an if/then conditional statement, None evaluates to False. So in theory you could check the return value of this function for success/failure. I say "in theory" because for the code in this question, the function does not catch or handle exceptions and may require additional hardening.


9)'global' keyword before the variable name at start of function i.e. It will make the function to refer global variable total whenever accessed.

10)None keyword is an object and is a data type of none type class.
None datatype doesn’t contain any value.
None keyword is used to define a null variable or object.
None keyword is immutable.


11)def spam():
      eggs = 99
      bacon()
   print(eggs)

  def bacon():
      ham = 101
      eggs = 0

 spam()
 When the program starts, the spam() function is called , and a local scope is created. The local variable eggs  is set to 99. Then the bacon() function is called , and a second local scope is created. Multiple local scopes can exist at the same time. In this new local scope, the local variable ham is set to 101, and a local variable eggs—which is different from the one in spam()’s local scope—is also created  and set to 0.

When bacon() returns, the local scope for that call is destroyed. The program execution continues in the spam() function to print the value of eggs , and since the local scope for the call to spam() still exists here, the eggs variable is set to 99. This is what the program prints.

12) Prevents program from crashing if an error occurs
If an error occurs in a program, we don’t want the program to unexpectedly crash on the user. Instead, error handling can be used to notify the user of why the error occurred and gracefully exit the process that caused the error.

13)The try except statement can handle exceptions. Exceptions may happen when we run a program.
Exceptions are errors that happen during execution of the program. Python won’t tell us about errors like syntax errors (grammar faults), instead it will abruptly stop.
An abrupt exit is bad for both the end user and developer.
Instead of an emergency halt, you can use a try except statement to properly deal with the problem. An emergency halt will happen if you do not properly handle exceptions.









