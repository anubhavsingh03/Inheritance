# Inheritance
A. Function sub class - Defines two classes, Rectangle and Cube, where Cube is derived from Rectangle Algorithm- Algorithm for Calculating Area of a Rectangle and Volume of a Cube:

Create a class named 'Rectangle': a. Declare private member variables 'width' and 'length'. b. Declare a public member function 'Area()' to calculate the area of the rectangle. c. In the constructor, prompt the user to enter the 'width' and 'length' values.

Create a class named 'Cube' derived from 'Rectangle': a. Declare a private member variable 'height'. b. Declare a public member function 'volume()' to calculate the volume of the cube. c. In the constructor, prompt the user to enter the 'height' value.

Define the 'Area()' function for the 'Rectangle' class to calculate the area as 'width * length'.

Define the 'volume()' function for the 'Cube' class to calculate the volume as 'Area() * height'.

In the 'main()' function: a. Create an instance of the 'Cube' class named 'c1'. b. Prompt the user to enter the dimensions for 'width', 'length', and 'height'. c. Call 'c1.volume()' to calculate and print the volume of the cube. d. Call 'c1.Area()' to calculate and print the area of the rectangle (inherited from the base class 'Rectangle').

End of the program.

B.function out-of class - uses class Rectangle to calculate the area of a rectangle. Algorithm - Algorithm for Calculating the Area of a Rectangle:

Create a class named 'Rectangle': a. Declare private member variables 'width' and 'length'. b. Declare a public member function 'Area()' to calculate the area of the rectangle. c. In the constructor, prompt the user to enter the 'width' and 'length' values.

Define the 'Area()' function for the 'Rectangle' class to calculate the area as 'width * length'.

In the 'main()' function: a. Create an instance of the 'Rectangle' class named 'r1'. b. Prompt the user to enter the dimensions for 'width' and 'length'. c. Call 'r1.Area()' to calculate and print the area of the rectangle.

End of the program.
