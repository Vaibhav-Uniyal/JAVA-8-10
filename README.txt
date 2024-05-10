JavaFX Employee Management System
This is a simple Employee Management System built using JavaFX and JDBC. The application allows users to input employee details such as employee ID, name, age, email, and department. Users can then create an employee table, register new employees, view the list of registered employees, and update employee information based on Employee ID.

Classes and Methods
EmployeeManagementApp.java
start(Stage primaryStage): Entry point of the application. Sets up the JavaFX user interface.
createEmployeeTable(): Creates the employee table in the MySQL database.
registerEmployee(): Registers a new employee into the database.
displayEmployees(): Displays the list of registered employees.
updateEmployee(): Updates the information of an existing employee based on the Employee ID.
