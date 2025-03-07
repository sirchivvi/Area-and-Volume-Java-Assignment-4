Shape Calculator Program

Overview

This Java program is a menu-driven application that calculates the area, perimeter, and volume of different shapes. The program follows Object-Oriented Programming (OOP) principles, using abstract classes and interfaces to define shape properties and behaviors.

Features

- Uses an abstract class (Shape) to define the general behavior of all shapes.
- Implements an interface (Volume) for shapes that have a volume.
- Supports multiple shapes, including:
  - Circle
  - Rectangle
  - Square
  - Sphere
  - Cylinder
  - Equilateral Pyramid (Square Base)
- Allows users to input measurements for calculations.
- Uses separate Java files for each class to ensure modularity and maintainability.
- Follows best coding practices, including comments and structured code organization.

Class Structure

1. Shape (Abstract Class)
- Contains a constructor (Shape(String shape)) to initialize shape names.
- Defines two abstract methods:
  - calculateArea()
  - calculatePerimeter()

2. Volume (Interface)
- Contains an abstract method:
  - calculateVolume()

3. Shape Classes

Each shape class extends Shape and implements Volume where applicable.

Circle
- Implements calculateArea()
- Implements calculatePerimeter()

Rectangle
- Implements calculateArea()
- Implements calculatePerimeter()

Square
- Implements calculateArea()
- Implements calculatePerimeter()

Sphere (Implements Volume)
- Implements calculateArea()
- Implements calculateVolume()

Cylinder (Implements Volume)
- Implements calculateArea()
- Implements calculatePerimeter()
- Implements calculateVolume()

Equilateral Pyramid (Square Base) (Implements Volume)
- Implements calculateArea()
- Implements calculateVolume()

How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Shape.git
2. Compile the Java files:

javac *.java
3. Run the main program:

java Main
