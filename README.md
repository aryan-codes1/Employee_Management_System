# Employee Management System

![Java](https://img.shields.io/badge/Java-17%2B-blue)
![Swing](https://img.shields.io/badge/Swing-GUI-orange)
![MySQL](https://img.shields.io/badge/MySQL-Database-green)

## Overview

The Employee Management System is a Java Swing-based application designed to simplify and streamline employee record management. It leverages Java Swing for the graphical user interface and integrates with a MySQL database through JDBC for data storage and retrieval. The project is built with a strong focus on Object-Oriented Programming (OOP) principles, ensuring a robust and maintainable codebase.

## Table of Contents

- [Introduction](#Introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Database Setup](#database-setup)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The Employee Management System offers a user-friendly interface that simplifies employee record management. It serves as a comprehensive solution for organizations to perform common HR tasks efficiently. Key features include:

- **Add Employee:** Easily add new employee records to the database.
- **Search Employee:** Quickly search for employees based on the Unique ID.
- **Update Employee:** Seamlessly update existing employee information.
- **Delete Employee:** Remove employees from the database with ease.

## Features

- **User-Friendly Interface:** The application boasts an intuitive and aesthetically pleasing user interface, developed using Java Swing.
- **Database Integration:** MySQL serves as the backend database, with connectivity established through the JDBC MySQL Java Connector.
- **Object-Oriented Design:** The project adheres to OOP principles, ensuring code maintainability and scalability.

## Getting Started

### Prerequisites

Before running the Employee Management System, ensure that you have the following prerequisites installed on your system:

- Java 17 or higher
- MySQL Database
- XAMPP or a similar server environment for MySQL

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/aryan-codes1/Employee_Management_System.git
2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Build and run the project using EntryPage.java as the main entry point.

## Database Setup

To set up the MySQL database for this project, follow these steps:

1. **Install and Start Server:** Start by installing XAMPP or a similar server environment if you haven't already. Once installed, open the XAMPP Control Panel and start both the Apache and MySQL services.

2. **Access MySQL/bin folder:** Open your command prompt and cd to mySQl/bin and run the following command:
   ```bash
   mysql -u your_username -p
  - Replace username by your user name usually "root" and password if any.
  - If the provided username and password are correct, you should now be connected to the MySQL server, and you'll see a MySQL command-line prompt that looks something like this:
```sql
mysql>
```
3. **Create a Database:** Create a new database named `usermanagement`. This is where the employee data will be stored.

4. **Import Data:** To populate the database with the necessary tables and sample data, use the application to add data and create the required table.

5. A text file is provided with MySQL queries required for creation of table. Use these commands first then run the application. You can find it in `database` directory. 

## Usage

1. **Start the Application:** Launch the application by running the `EntryPage.java` class. This will open the main window of the Employee Management System.

2. **Employee Management:** You can now use the following options provided in the main window to manage your employee records:

   - **Add Employee:** Click this option to add a new employee to the database. Fill in the required information and save it to the database.

   - **Search Employee:** Use this option to search for employees based on the criteria of Unique ID.

   - **Update Employee:** Enter the unique ID to check for availability of the employee and then add the new data and click the update option to update their information.

   - **Delete Employee:** Enter the unique ID to check for availability of the employee and then click the delete option to remove them from the database.

3. Enjoy the streamlined employee management experience, and make the most of the system to efficiently manage your employee records!

## Contributing

We welcome and appreciate contributions to the Employee Management System project. Whether you want to report a bug, suggest an enhancement, or submit a code change, your input is valuable.

To contribute to this project, follow these steps:

### Reporting Issues

If you encounter a bug, have a question, or want to propose an improvement, please open an issue on our [GitHub Issues](https://github.com/aryan-codes1/Employee_Management_System/issues) page. When opening an issue, please provide as much detail as possible, including:

- A clear and descriptive title.
- A detailed description of the issue or enhancement request.
- Steps to reproduce the issue (if applicable).
- Screenshots or error messages (if relevant).
- Your environment (e.g., operating system, Java version).

### Code Contributions

If you'd like to contribute code changes or new features to the project, follow these steps:

1. Fork the repository to your GitHub account.

2. Clone the forked repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/Employee-Management-System.git
   
3. **Create a new branch:**
Create a new branch for your feature or bug fix. Choose a descriptive branch name that reflects the purpose of your changes.
```bash
  git checkout -b feature-name
```
Replace feature-name with a name that describes your change (e.g., add-new-feature, fix-bug-123).

4. **Edit and test your code:**
   Make the necessary changes to the code in your branch. Ensure that your changes address the issue or feature you're working on. Be sure to follow the coding guidelines and best practices of the project.

   *It's highly recommended to thoroughly test your changes to ensure they work as expected. This may include running unit tests, manual testing, or any other testing procedures relevant to your changes.*

5. **Commit your changes:**
   After making and testing your changes, it's time to commit them with descriptive commit messages. Each commit should have a clear and concise message that explains what the commit accomplishes.

   Use the following commands to stage and commit your changes:

   ```bash
   git add .
   git commit -m "Description of your changes"
Replace "Description of your changes" with a brief but informative message that summarizes your changes. A well-written commit message helps others understand the purpose of your changes when reviewing your pull request.

6. Create a Pull Request(PR).
   
## Creator

This Employee Management System project was created by **Aryan Gupta** and is provided for educational and non-commercial purposes. While there are no formal legal copyrights, we kindly request the following:

- Attribution: When using or sharing this project, please provide appropriate credit to the creator, **Aryan Gupta**.

- Non-Commercial Use: We appreciate that this project is used for educational and non-commercial purposes. For any commercial use, including but not limited to selling, licensing, or using it in a for-profit environment,
please use the [GitHub Issues](https://github.com/aryan-codes1/Employee_Management_System/issues) section of this repository to make inquiries or request permissions.

The creator retains the right to grant or deny permission for commercial use on a case-by-case basis. Please use the [GitHub Issues](https://github.com/aryan-codes1/Employee_Management_System/issues) section of this repository to make inquiries or request permissions.

Your cooperation and respect for these guidelines are greatly appreciated.

