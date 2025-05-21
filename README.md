A Java Swing-based desktop application designed to manage key operations of a hospital, such as patient records, staff management, room allocation, and more. Built with Java and MySQL using JDBC for database connectivity, this project offers a comprehensive system to handle administrative tasks efficiently.

🚀 Features
🔐 User Login & Authentication

Secure login system to authenticate users and restrict unauthorized access.

🧍‍♂️ Patient Management

Add, update, delete, and view patient records with complete medical history.

👨‍⚕️ Employee Information

Manage hospital staff data including doctors, nurses, and admin personnel.

🏥 Department Management

Maintain various hospital departments like Cardiology, Emergency, Neurology, etc.

🚑 Ambulance Management

Register and track ambulance services and driver details.

🛏️ Room Management

Manage room allocations with real-time status updates for ICU, General, and Private rooms.

🔍 Search Functionality

Search available rooms by room type, status, or other parameters.

🛠️ Tech Stack
Layer	Technology
Frontend	Java Swing
Backend	Java
Database	MySQL (Workbench)
Connectivity	JDBC (Java Database Connectivity)

📦 Installation
Clone the repository:

Use Eclipse, IntelliJ IDEA, or NetBeans.

Set up the database:

Import the provided .sql file (if available) into MySQL Workbench.

Update the Connection settings in your Java files (host, username, password, database name).

Run the application:

Compile and run the main file (e.g., Main.java or Login.java).

📂 Folder Structure
/hospital-management-system
│
├── src/
│   ├── Login.java
│   ├── Patient.java
│   ├── Employee.java
│   ├── Department.java
│   ├── Room.java
│   ├── Ambulance.java
│   └── DBConnection.java
├── README.md
└── database/
    └── hospital_schema.sql
🙌 Contributing
Contributions are welcome! Feel free to fork the repository and open a pull request with enhancements, features, or bug fixes.

📧 Contact
Have questions or suggestions? Feel free to connect with me on LinkedIn or open an issue on this repository.

Let me know if you'd like help generating the .sql file, adding screenshots, or organizing the code files into packages!
