# GUVI-HCL
Project Title
Internal Stack Overflow using Java and MongoDB

Description
This project implements a Java-based console application that demonstrates a fixed-capacity stack data structure and simulates internal stack overflow conditions. The application integrates MongoDB to log stack operations such as push, pop, peek, display, and overflow events, enabling persistent storage and monitoring of stack behavior.

Problem Statement

Traditional stack implementations do not provide built-in mechanisms for tracking overflow events or maintaining operation history. This makes debugging and monitoring difficult. There is a need for a system that can simulate stack overflow conditions, handle exceptions effectively, and store operational logs for analysis and diagnostics.

---
Technologies Used
Java (JDK 8 or higher)
MongoDB (NoSQL Database)
MongoDB Java Driver
Data Structures (Stack)
Exception Handling
Command Line Interface (CLI)

Methodology

1. A fixed-capacity generic stack is implemented in Java.
2. Stack operations such as push, pop, peek, and display are performed through a menu-driven interface.
3. When the stack exceeds its capacity, a custom InternalStackOverflowException is thrown.
4. All stack operations and overflow events are logged into a MongoDB collection.
5. Users can view recent log entries stored in the database for monitoring purposes.

How to Run the Project

1. Install Java JDK (version 8 or above).
2. Install and start MongoDB locally or use a cloud MongoDB service.
3. Add the MongoDB Java Driver to the project classpath.
4. Compile the Java file using javac.
5. Run the program using the java command.
6. Use the console menu to perform stack operations and view logs.

Conclusion

The Internal Stack Overflow project effectively demonstrates the integration of core data structure concepts with modern database logging techniques. By combining Java stack implementation, exception handling, and MongoDB logging, the project provides a practical learning model for understanding stack behavior, error handling, and persistent monitoring in real-world applications.

Output:
![25 op1](https://github.com/user-attachments/assets/a3ed69bb-ba49-4d8c-aaeb-decb7e709ccf)
![25 op2](https://github.com/user-attachments/assets/fd9c29a9-38b4-4d78-81a8-2ae54335944a)
![25 op3](https://github.com/user-attachments/assets/5f95343c-e752-4df5-a63c-f985688b6deb)
![25 op4](https://github.com/user-attachments/assets/bcdb3e81-8964-44ee-aaea-e795b6b49a07)




