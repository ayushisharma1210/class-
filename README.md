# class and objects
## abstract 

Class in C++ is the building block that leads to Object-Oriented programming. It is a user-defined data type, which holds its own data members and member functions, which can be accessed and used by creating an instance of that class. A C++ class is like a blueprint for an object. 
here we used class for various purposes
to find the volume of a cube
to find properties of rectangle and cuboid
to find whether a particlar year is a leap year or not
the code demonstrates inheritance, constructor initialization, and method calls within a class hierarchy to represent people, students, and faculty members.
here is the alogrithm for these codes

                           algorithm for volume of a cube
Include the necessary header files:
#include <iostream> for input and output operations.
Declare a class called cube:
The cube class has three member variables, height, width, and length, which represent the dimensions of a cube.
The volume() method calculates and returns the volume of the cube.
Define the main function:
In the main function, an instance of the cube class, cube1, is created.
The volume of the cube is calculated by calling the volume() method of the cube1 object.
The calculated volume is then displayed on the console using cout.
This code defines a class to represent a cube and calculates its volume based on the provided dimensions. It demonstrates the use of a class, its member variables, and methods within the main function.

                       algorithm for whether the year is leap year or not
Include the necessary header files:
#include <iostream> for input and output operations.
Define a class called LeapYearChecker:
main function:
Declare an integer variable year to store the user's input year.
Prompt the user to enter a year using std::cout.
Read the input year using std::cin.
Create an instance of the LeapYearChecker class, named checker, and pass the user's input year as an argument to the constructor.
Use the isLeapYear method of the checker object to determine if the year is a leap year.
If it's a leap year, display "year is a leap year."
If it's not a leap year, display "year is not a leap year."
End the program by returning 0 from the main function.
This code allows the user to input a year, checks if it's a leap year, and provides the result.

                     algorithm of a hierarchy to represent people,students,and faculty members

Here's an algorithm for the provided C++ code, which demonstrates a simple inheritance hierarchy involving the Person, Student, and Faculty classes:
Include the necessary header files:
Define a derived class Student:
In the main function:
Create an instance of the Person class, p, and initialize it with the name "xyz."
Display the name of the person using the disp_name method.
Create an instance of the Student class, s, and initialize it with the name "John," PRN 12345, and the course "Computer Science."
Display the name and course of the student using the disp_name and disp_course methods.
Create an instance of the Faculty class, f, and initialize it with the name "Jane" and a staff ID of 56789.
Display the name and staff ID of the faculty member using the disp_name and disp_id methods.
End the program by returning 0 from the main function.

                    algorithm to find properties like area periemeter of rectangle and cuboid
Include the necessary header files:
#include <iostream> for input and output operations.
Define a base class called Rectangle:
Declare two protected member variables, length and breadth, with default values.
Create a constructor that allows you to set the length and breadth when creating a Rectangle object.
Provide methods to calculate the area and perimeter of the rectangle.
Define a derived class called Cuboid, which inherits from the Rectangle class:
Add a private member variable, height, with a default value.
Create a constructor for the Cuboid class, allowing you to set the length, breadth, and height when creating a Cuboid object.
Provide a method to calculate the volume of the cuboid.
In the main function:
Declare double variables length, breadth, and height to store the dimensions of the rectangle and cuboid.
Create an instance of the Cuboid class named cuboid and initialize it with the given dimensions.
Create an instance of the Rectangle class named rectangle and initialize it with the given dimensions.
Display the dimensions of the shapes (length, breadth, and height).
Calculate and display the area and perimeter of the rectangle using the getArea and getPerimeter methods.
Calculate and display the volume of the cuboid using the getVolume method.
End the program by returning 0 from the main function.                    


                       


