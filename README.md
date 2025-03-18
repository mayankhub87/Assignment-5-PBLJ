# Assignment-5-PBLJ
ava Programming Assignment 🚀
This repository contains Java programs that demonstrate the use of autoboxing, serialization, file handling, and efficient data processing and management. The assignment is divided into three levels of difficulty: Easy, Medium, and Hard. 🎯

Easy Level 🟢
Problem Statement
Write a Java program to calculate the sum of a list of integers using autoboxing and unboxing. Include methods to parse strings into their respective wrapper classes (e.g., Integer.parseInt()).

Requirements:
Use a list of integers and calculate their sum. ➕

Demonstrate autoboxing and unboxing. 📦

Parse strings into integers using wrapper class methods. 🔢

Example:
java
Copy
Input: List<String> numbers = {"1", "2", "3", "4", "5"};
Output: Sum = 15
Medium Level 🟡
Problem Statement
Create a Java program to serialize and deserialize a Student object. The program should:

Serialize a Student object (containing id, name, and GPA) and save it to a file. 💾

Deserialize the object from the file and display the student details. 📄

Handle FileNotFoundException, IOException, and ClassNotFoundException using exception handling. ⚠️

Requirements:
Define a Student class with attributes: id, name, and GPA. 🎓

Implement serialization and deserialization methods. 🔄

Handle exceptions appropriately. 🛠️

Example:
java
Copy
Student Object: id = 101, name = "John Doe", GPA = 3.8
Serialized to file: student.ser
Deserialized from file: Student{id=101, name='John Doe', GPA=3.8}
Hard Level 🔴
Problem Statement
Create a menu-based Java application with the following options:

Add an Employee: Gather details of the employee (employee name, employee id, designation, and salary) and store it in a file. 📝

Display All: Display all the employee details from the file. 📋

Exit: Exit the application. 🚪

Requirements:
Use file handling to store and retrieve employee details. 📂

Implement a menu-driven interface. 🖥️

Ensure the program handles file operations efficiently. ⚡

Example:
Copy
Menu:
1. Add an Employee
2. Display All
3. Exit

Enter your choice: 1
Enter Employee Name: Jane Doe
Enter Employee ID: 102
Enter Designation: Software Engineer
Enter Salary: 75000
Employee added successfully! ✅

Enter your choice: 2
Employee Details:
1. Name: Jane Doe, ID: 102, Designation: Software Engineer, Salary: 75000

Enter your choice: 3
Exiting the application... 👋
How to Run the Programs 🛠️
Clone this repository to your local machine. 📥

Navigate to the respective program directory (Easy, Medium, or Hard). 📁

Compile and run the Java programs using the following commands:

bash
Copy
javac ProgramName.java
java ProgramName
Submission Guidelines 📄
Create a separate folder for each level (Easy, Medium, Hard). 📂

Include the Java source code files (.java) and any necessary resources (e.g., serialized files, employee data files). 📄

Update the README.md file with any additional instructions or notes. 📝

Happy Coding! 🎉👨‍💻👩‍💻
