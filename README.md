## Student Database Management System (Java + MySQL)

### Overview
This Java-based project implements a simple student database management system with operations such as adding, displaying, searching, updating, and deleting student records. The system connects to a MySQL database and uses JDBC for interaction.

---

## List of Variables

| Variable Name   | Data Type     | Purpose                                                                 |
|-----------------|---------------|-------------------------------------------------------------------------|
| `name`          | `String`      | Stores the student's full name                                          |
| `prn`           | `String`      | Stores the student's PRN (Permanent Registration Number)                |
| `dob`           | `String`      | Stores the date of birth of the student                                 |
| `marks`         | `int`         | Stores the student's marks                                              |
| `studentList`   | `List<Student>`| Stores the list of student objects for in-memory operations             |
| `conn`          | `Connection`  | Used to establish a connection with the MySQL database                  |
| `scanner`       | `Scanner`     | Used to read user inputs from the console                               |

---

## List of Functions

| Function Name               | Return Type    | Purpose                                                                 |
|----------------------------|----------------|-------------------------------------------------------------------------|
| `getConnection()`          | `Connection`   | Establishes and returns the JDBC connection to the MySQL database       |
| `addStudent()`             | `void`         | Accepts user input and inserts a new student record into the database   |
| `displayStudents()`        | `void`         | Retrieves and displays all student records from the database            |
| `searchByPRN(String prn)`  | `void`         | Searches for a student using PRN                                        |
| `searchByName(String name)`| `void`         | Searches for students by name                                           |
| `searchByPosition(int pos)`| `void`         | Searches for a student by position in the result set                    |
| `updateStudent()`          | `void`         | Updates student record based on PRN                                     |
| `deleteStudent()`          | `void`         | Deletes a student record from the database using PRN                    |
| `main(String[] args)`      | `void`         | Entry point of the program with a menu to trigger all operations        |

---

