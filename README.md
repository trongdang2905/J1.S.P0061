
LAB211 AssignmentType:Short AssignmentCode:J1.S.P0061LOC:42Slot(s):1
Title
  	Create a program to calculate perimeter and area. 
Background 
       N/A
Program Specifications
Create a program to calculate the perimeter and the area of ??a Circle, a Rectangle and a Triangle. 

Function details: 
Function 1: Display GUI And Input Data.
* Users run the program. The program prompts users for the input Data.
* Auto next Function 2.
Function 2: Perform function
* The program calculates the area and the perimeter of the input circle, the rectangle and the triangle
* Display the information on the screen and Exit the program. 
Expectation of User interface:



Guidelines
       Student must implement the methods
- getPerimeter
- getArea
- printResult
       in startup code.
Example: 
- Create an abstract class Shape contains three methods printResult, getPerimeter and getArea.
- Create classes Triangle, Rectangle, Circle that extend from class Shape.
-  Construct the shapes that consists the properties of a circle (radius), a rectangle (width, length), a triangle (sideA, sideB, sideC) and generate their getter and setter methods. 
- Override the methods of the Shape class. 
- Calculate the area of ??a circle using the formula Heron: 

	Use Math.sqrt()
- Calculate the area of ??a circle with Pi = Math.PI 
Function 1: Calculate the perimeter 
o Must create function: public double getPerimeter () 
* Return: the perimeter of the shape. 
Function 2: Calculate the area. 
o Must create function: public double getArea () 
* Return: The area of ??the shape. 
Function 3: Display the shape information. 
o Must create the function: public void printResult () 
* Return: void. 
       
