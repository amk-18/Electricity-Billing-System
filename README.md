Electricity Billing System
Project Overview
The Electricity Billing System is a Java-based desktop application developed to computerize the electricity billing process. The system automates the manual process of calculating the monthly energy consumption, generating bills, and managing customer details. It provides a convenient, efficient, and user-friendly platform for both administrators and consumers to manage billing activities and related data.

Key Features
Admin Features:
Customer Management: Admin can add, update, view, and delete customer details, including automatically assigning a unique meter number.
Meter Information: Admin can select meter location, type, and assign a bill type (Residential/Commercial).
Bill Calculation: Admin can calculate monthly bills by entering the units consumed, applying relevant taxes, penalties, and meter rent.
Tax Management: Admin can input and update tax details like service tax, GST, etc.
Deposit and Bill Details: Admin can sort and search customer bills and payment statuses based on meter number and month.
Utilities: Tools like a notepad and calculator are available for quick operations.
Customer Features:
Bill Payment: Customers can view and pay their bills online.
View and Update Information: Customers can access and update their personal details such as name, address, email, etc.
Generate Bill Slip: Customers can generate detailed breakdowns of their bills.
Utility Access: Notepad and calculator functionalities are provided for customers as well.

Software:
Operating System: Windows 10 or higher
Database: MySQL
Development Environment: Java (NetBeans IDE)
Front End: Java Swing
Back End: MySQL Database
Installation Instructions
Clone the repository:


Database Schema
The system's database consists of the following tables:

login: Stores user login credentials.
customer: Stores customer information such as name, meter number, address, and contact details.
tax: Stores tax details applied to the bill.
bill: Stores monthly consumption, total bill amount, and payment status.
meter_info: Stores details related to the installed meters.
UML Diagrams
Class Diagram: Illustrates the main classes in the system such as Admin, Customer, Bill, MeterInfo.
Use Case Diagram: Defines the interactions between the admin and customer with the system.
Normalization
The database follows the normalization rules up to Third Normal Form (3NF) to avoid redundancy and maintain efficient data storage.

Testing
Comprehensive testing has been performed, including:

Unit Testing: Testing of individual modules.
Integration Testing: Ensuring modules work together seamlessly.
System Testing: Verifying the complete functionality of the system.
Future Scope
Extensibility: The software can be extended to include remote access, additional billing features, and journaling.
Reusability: The code is modular, allowing for future enhancements without significant changes to the system.
Limitations
The system is a desktop application and cannot be accessed remotely.
A basic level of technical knowledge is required to operate the application.
Conclusion
The Electricity Billing System automates the manual billing process and enhances efficiency. It reduces the time spent on data entry, provides an easy-to-use interface, and facilitates both admins and customers in managing their billing activities.

