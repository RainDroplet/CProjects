# CProjects - Week 1
**Lecture: Introduction to C/C++ Programming**

Slide 1:
- Welcome to Week 1 of our course, Introduction to C/C++ Programming!
- Today, we'll embark on our journey to explore the basics of C/C++ and understand their significance in the programming world.

Slide 2:
- C/C++: A Brief Overview
  - C and C++ are powerful and widely-used programming languages.
  - C is a procedural language known for its efficiency and low-level control.
  - C++ is an extension of C, adding object-oriented programming features.

Slide 3:
- Why Learn C/C++?
  - C/C++ are used extensively in various domains, including systems programming, embedded systems, game development, and more.
  - They provide a solid foundation for understanding programming concepts and transitioning to other languages.

Slide 4:
- Setting up a Development Environment
  - We'll begin by installing an IDE (Integrated Development Environment) and configuring a C/C++ compiler.
  - Code::Blocks and Visual Studio are popular options that provide a user-friendly interface and powerful tools.

Slide 5:
- Basic Syntax, Data Types, Variables, and Operators
  - Syntax: C/C++ has a specific set of rules for writing code. Let's start with a simple program that displays "Hello, World!".

  ```c
  #include <iostream>

  int main() {
      std::cout << "Hello, World!" << std::endl;
      return 0;
  }
  ```

  - Data Types: We'll explore various data types, including integers, floating-point numbers, characters, and booleans.

  ```c
  int age = 25;
  float pi = 3.14;
  char grade = 'A';
  bool isStudent = true;
  ```

  - Variables: Learn how to declare variables and assign values to them.

  ```c
  int x, y;
  x = 5;
  y = 10;
  ```

  - Operators: Understand arithmetic, assignment, comparison, and logical operators.

  ```c
  int sum = x + y;
  int difference = x - y;
  int product = x * y;
  int division = x / y;
  bool isGreaterThan = x > y;
  ```

Slide 6:
- Control Flow and Decision-Making Structures
  - Control flow structures allow us to control the execution of code.
  - Decision-Making Structures:
    - If-else statements: Execute code based on a condition.

  ```c
  int num = 10;

  if (num > 0) {
      std::cout << "The number is positive." << std::endl;
  } else {
      std::cout << "The number is zero or negative." << std::endl;
  }
  ```

    - Switch-case statements: Select code to execute based on a given value.

  ```c
  int choice = 2;

  switch (choice) {
      case 1:
          std::cout << "You chose Option 1." << std::endl;
          break;
      case 2:
          std::cout << "You chose Option 2." << std::endl;
          break;
      default:
          std::cout << "Invalid choice." << std::endl;
          break;
  }
  ```

  - Looping Structures:
    - For loop: Execute code repeatedly for a specific number of times.

  ```c
  for (int i = 1; i <= 5; i++) {
      std::cout << i << " ";
  }


  ```

    - While loop: Execute code repeatedly as long as a condition is true.

  ```c
  int count = 1;

  while (count <= 5) {
      std::cout << count << " ";
      count++;
  }
  ```

Slide 7:
- Recap: Assignments for Week 1
  - Assignment 1: Basic Calculator
    - Create a command-line calculator program in C/C++.
    - Implement functions for basic arithmetic operations (addition, subtraction, multiplication, division).
    - Prompt the user to enter two numbers and choose an operation.
    - Perform the selected operation and display the result.
  - Assignment 2: Grade Calculator
    - Develop a program in C/C++ that calculates grades based on given marks.
    - Design a structure to store student details such as name, ID, and marks for different subjects.
    - Implement functions to calculate the average grade and display the grade along with student information.
    - Read student data from a file and process the grades accordingly.

Slide 8:
- Conclusion
  - Today, we covered an introduction to C/C++ programming and its importance in the programming world.
  - In the upcoming lectures, we'll dive deeper into the fundamentals and explore more advanced concepts.
  - Remember to complete the assignments and ask questions whenever needed.

