# Employee-Management-System-

The Employee Management System (EMS) is an admin-based application designed to manage employee information and track company resources. 
I used Java as programming language and MySQL as the database for storing the data related to employee details, project details, department details. 
I used JDBC (Java Database Connectivity) driver for connecting Java to MySQL, which is a set of classes and interfaces in the Java programming language that defines how a client may access a database. Here are the general steps to connect to MySQL using JDBC:
1.	Import the JDBC packages: The first step is to include the required JDBC packages in your Java program. These packages are typically provided by the database vendor and include the necessary classes and interfaces for establishing a connection.
2.	Load the JDBC driver: In order to use JDBC to connect to a MySQL database, you need to load the MySQL JDBC driver into your program. This is done using the Class.forName() method, which loads the driver class dynamically.
3.	Establish a connection: After loading the JDBC driver, you can use the DriverManager.getConnection() method to establish a connection to the MySQL database. This method takes a URL string that specifies the location of the database and the credentials needed to connect to it.
4.	Create a statement: Once you have established a connection, you can create a Statement object that will be used to execute SQL statements.
5.	Execute SQL statements: You can execute SQL statements using the Statement object you created. The results of these statements are returned as a ResultSet object, which can be used to retrieve and manipulate data.
6.	Close the connection: After you are done using the database, you should close the connection to free up any resources that were allocated.

Java Swing is a GUI (Graphical User Interface) toolkit for Java. It provides a set of graphical components like buttons, text fields, labels, and more that can be used to create a rich user interface for desktop applications.
It is a Java Swing GUI application for an Employee Management System. It contains a main window with four buttons that allow the user to navigate to different functionalities of the system such as managing projects, registering employees, managing departments, and assigning employees to projects. 

I designed an object-oriented architecture that enabled easy scalability and extensibility. Additionally, I leveraged MySQL's relational database management system to ensure data consistency and integrity. One of the key features I implemented was the ability to perform CRUD operations on various tables in the database, which allowed admins to easily add, modify, and remove records. I pursued this project as a means of improving my coding and database skills, and it has helped me gain a deeper understanding of how to design user-friendly, reliable, and extensible applications
