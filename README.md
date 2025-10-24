**Employee Payroll System**
A simple Java-based console application that models an employee payroll system using object-oriented principles. It supports full-time and part-time employees, calculates their salaries, and manages employee records.

**Features**
Abstract Employee class with polymorphic behavior

Two employee types:

FullTimeEmployee with fixed monthly salary

PartTimeEmployee with hourly rate and hours worked

PayrollSystem class to:

Add and remove employees

Display employee details with calculated salary

Demonstration via Main class

Technologies Used
Java (JDK 8+)

Object-Oriented Programming (OOP)

ArrayList for dynamic employee storage

**Project Structure**
Code
EmployeePayrollSystem/
├── Main.java
├── Employee.java
├── FullTimeEmployee.java
├── PartTimeEmployee.java
└── PayrollSystem.java
**How to Run**

Clone the repository:
git clone https://github.com/your-username/EmployeePayrollSystem.git
cd EmployeePayrollSystem

Compile the code:
javac Main.java
Run the application:
java Main

**Sample Output**
Code
initail Employee Details: 
Employee [name=Vikas,id=1, salary=70000.0]
Employee [name=Alexander,id=2, salary=4000.0]

Removing Employee
Remaining Employee Details: 
Employee [name=Vikas,id=1, salary=70000.0]
📚 Concepts Demonstrated
Abstraction: Employee is an abstract class with a common interface.

Inheritance: FullTimeEmployee and PartTimeEmployee extend Employee.

Polymorphism: calculateSalary() is overridden in subclasses.

Encapsulation: Private fields with public getters.

Dynamic Data Management: Employees stored in an ArrayList.

**Author**
Made by Abhay Shaw
