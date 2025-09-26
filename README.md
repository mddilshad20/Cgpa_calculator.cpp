# CGPA Calculator

A simple **C++ program** to calculate the **CGPA (Cumulative Grade Point Average)** based on user input for courses, credit hours, and grades.

## Features
- Input number of courses and their credit hours.  
- Enter grades for each course.  
- Calculates **GPA for individual semesters** (if structured that way).  
- Computes **overall CGPA**.  
- Simple console-based interface.  

## Requirements
- A C++ compiler (e.g., `g++`, `clang++`, or MSVC).  
- Basic terminal/command prompt access.  

## Compilation
```bash
g++ cgpa_calculator.cpp -o cgpa_calculator
```

## Usage
Run the compiled program:
```bash
./cgpa_calculator
```

The program will:
1. Ask you for the number of courses.  
2. Prompt you to enter credit hours and grade points for each course.  
3. Calculate and display your **CGPA**.  

## Example
```
Enter number of courses: 3
Enter credit hours and grade point for course 1: 3 8
Enter credit hours and grade point for course 2: 4 9
Enter credit hours and grade point for course 3: 2 7

Your CGPA is: 8.22
```

## Notes
- Make sure to enter valid numeric values for credits and grade points.  
- Grade points should follow your institution’s grading system (e.g., out of 10 or 4).  
- Modify the program as needed to match your university’s CGPA rules.  
