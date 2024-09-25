# Function-and-operator-overloading

## Aim:
To study function and operator overloading

# Theory:

Function Overloading:
Function overloading is a feature in programming languages that allows you to define multiple functions with the same name but different parameters. These functions can have different types, numbers, or orders of parameters. The compiler determines which function to call based on the arguments provided during the function call.   

Key Points:

Same Name: The overloaded functions must have the same name.
Different Parameters: The functions must have different parameters in terms of their types, numbers, or orders.
Parameter Matching: The compiler matches the arguments provided in the function call with the parameters of the available overloaded functions.
Return Type: The return types of overloaded functions can be the same or different.


Operator Overloading:

Operator overloading is a feature in programming languages that allows you to redefine the behavior of built-in operators for custom data types. It enables you to customize how these operators work when applied to objects of your own classes.

Key Points:

Custom Data Types: Operator overloading is typically used to define the behavior of operators for classes that you create.
Built-in Operators: You can overload most built-in operators, such as arithmetic operators (+, -, *, /, %), comparison operators (==, !=, <, >, <=, >=), assignment operators (=), and logical operators (&&, ||).
Overloaded Functions: Operator overloading is achieved by defining functions that have specific signatures. The compiler automatically calls these functions when the corresponding operator is used with objects of your class.
Custom Behavior: You can implement any desired behavior within the overloaded functions to determine how the operator will operate on your objects.

## Algorithm: Addtion using function overloading

Addition using Function Overloading
Start

**Class Definition

1.Define a class named Addition.
Method Definitions

2.Define the following methods within the class:
Method 1: int sum(int a, int b)
Takes two integer parameters and returns their sum.
Method 2: int sum(int a, int b, int c)
Takes three integer parameters and returns their sum.
Method 3: double sum(double d, double e)
Takes two double parameters and returns their sum.


3.Main Function

4.Create an instance of the Addition class named obj.
Call obj.sum(20, 15):
This calls the first sum method (two integers).

5.Output the result.
Call obj.sum(81, 100, 10):
This calls the second sum method (three integers).

6.Output the result.
Call obj.sum(20.5, 30.5):
This calls the third sum method (two doubles).

7.Output the result.

8.End
