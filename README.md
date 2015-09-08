Edited README.md

# Overview of updated class file
The updated program now computes the area of a 3D triangle based off of the coordinates input by the user. The 3D Point class has 3 private variables, x, y and z which all store the coordiates of the point. All are double variables initialized to 0.0. There are the standard accessor and mutator functions which allow for the manipulation of the coordinate values. There has been an additional function added, double distanceTo(Point &); which computes the distance between the point calling the function and the point in the function's argument. The original class was designed around 2D objects so with the addition of the third point, z, for a 3D object, an additional constructor, accesor and mutator function was added to reflect these changes.

# Other changes
## pa1.cpp
In this file, code was added to take input from the user in order to create three points. The inputs were stored into variables for the x, y and z coordinates of the points and then a new Point class is made based off of these variables. After the new class object is made, the variables are set to 0 in order to be reused by the next round of inputs. After three points have been created, a function is called to compute the area of the triangle/object made up of these three points and the value returned by the function is stored in a variable. The program then outputs the area with a precision of two decimal places.

## Point.cpp
The changes made here reflect the changes made to the Point class file. Implementations for the new accessor and mutator files were added as well as the implementation of the new member function distanceTo.

# Compiler
I used WinGW to compile my code.
