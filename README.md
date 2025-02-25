# Student Management System

## Description

A simple C++ console application to manage student records. Users can **add**, **view**, and **search** students by roll number. The program assigns grades based on marks.

## Features

- **Add Student** – Input roll number, name, and marks.
- **Display Students** – View all students and grades.
- **Search Student** – Find by roll number.
- **Grade Calculation** – Assigns grades automatically.
- **Exit** – Close the program.

## How to Run

1. **Compile:**
   ```sh
   g++ student_management.cpp -o student_management
   ```
2. **Run:**
   ```sh
   ./student_management
   ```
3. Follow on-screen menu options.

## Grading System

- **90-100** → A
- **75-89** → B
- **60-74** → C
- **40-59** → D
- **Below 40** → F

## Example Usage

```
1. Add Student
2. Display Students
3. Search Student
4. Exit
Choice: 1

Enter Roll No: 101
Enter Name: John Doe
Enter Marks: 85
Student added!

Choice: 2
Roll No: 101, Name: John Doe, Marks: 85, Grade: B

Choice: 3
Enter Roll No: 101
Found: John Doe, Marks: 85, Grade: B

Choice: 4
Exiting...
```

## Future Enhancements

- **File Storage** – Save/load records.
- **Sorting & Filters** – Sort by marks or name.
- **More Details** – Add age, department, etc.

## Technologies Used

- **Language:** C++
- **Compiler:** g++ / MinGW



