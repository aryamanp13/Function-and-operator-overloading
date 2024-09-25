# Function-and-operator-overloading

## Aim:
To study function and operator overloading

# Theory:

Function Overloading:
Function overloading is a feature in C++ that allows you to define multiple functions with the same name but with different parameters.
The compiler differentiates these functions based on the number and/or type of their parameters.

Operator Overloading
Operator overloading is a feature in C++ that allows developers to redefine the way operators work for user-defined types (such as classes).
This enables you to use operators like +, -, *, and others with objects of your classes in a way that is intuitive and similar to built-in types.

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
