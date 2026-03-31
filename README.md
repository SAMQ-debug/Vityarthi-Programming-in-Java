
# 🎓 Campus Course & Records Manager (CCRM)

A robust console-based application for managing academic records, built with modern Java SE.

![Java](https://img.shields.io/badge/Java-21-blue?logo=openjdk)
![Status](https://img.shields.io/badge/Status-Completed-green)
![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [🚀 Getting Started](#-getting-started)
- [✨ Key Features](#-key-features)
- [🧠 Core Concepts Implemented](#-core-concepts-implemented)
- [✍️ Author](#️-author)
- [Acknowledgements](#acknowledgements)

---

## About The Project

**Campus Course & Records Manager (CCRM)** is a comprehensive, console-based application designed for academic administration. It provides a full suite of tools for managing student records, course catalogs, enrollments, and grades through a simple command-line interface (CLI).

This project showcases the power of core Java principles and modern APIs, including:

- **Object-Oriented Programming (OOP)**
- **NIO.2** for efficient file I/O
- The **Streams API** for powerful data manipulation
- The **Date/Time API**
- Key design patterns like **Singleton** and **Builder**

---

## 🚀 Getting Started

Follow these steps to get a local copy up and running.

### Prerequisites

- **Java Development Kit (JDK) version 21 or newer.**

### Installation & Execution

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Kavya-Kulshreshtha/Vityarthi-Programming-in-Java
    ```

2.  **Import into Eclipse IDE:**
    - Navigate to `File` > `Import` > `General` > `Existing Projects into Workspace`.
    - Select the cloned repository directory.

3.  **Compile the Project:**
    - Open a terminal or command prompt in the project's root directory and run:
    ```bash
    javac -d bin src/edu/ccrm/cli/Main.java
    ```

4.  **Execute the Application:**
    - Run the following command. The `-ea` flag is important as it **enables assertions** used for internal validation.
    ```bash
    java -ea -cp bin edu.ccrm.cli.Main
    ```

> **Note:** Sample data files are available in `test-data/students.csv` and `test-data/courses.csv` to get you started.

---

## ✨ Key Features

- 🧑‍🎓 **Student & Course Management**: Add, update, and remove student and course records seamlessly.
- 📝 **Enrollment Processing**: Handle student enrollments while enforcing credit limits (max 18 per semester).
- 📊 **Grade Tracking**: Assign and manage grades for students in their enrolled courses.
- 🗂️ **Data Operations**: Easily import/export data from/to CSV files and perform data backups.
- ⚙️ **Advanced Utilities**: Features an intuitive CLI, powerful search capabilities using Streams, and a utility for recursively calculating directory sizes.

---

## 🧠 Core Concepts Implemented

This project serves as a practical demonstration of several fundamental Java and software engineering concepts.

### Java Platform Editions: ME, SE, and EE

| Platform               | Description                                                        | Use Case                               | Relevance to CCRM                                        |
| ---------------------- | ------------------------------------------------------------------ | -------------------------------------- | -------------------------------------------------------- |
| **Java ME** (Micro)    | A lightweight version for resource-constrained devices.            | Older mobile phones, IoT devices.      | Not used, as it lacks features for a desktop application. |
| **Java SE** (Standard) | The core Java platform for general-purpose applications.           | Desktop software, command-line tools.  | **This is the primary platform used for CCRM.**          |
| **Java EE** (Enterprise) | Extends Java SE with APIs for large-scale enterprise servers.      | Web applications, web services.        | Not used, as CCRM is a standalone application.           |

<br/>

### JDK vs. JRE vs. JVM

- **JDK (Java Development Kit)**: The complete toolkit for Java developers. It includes the JRE, compiler (`javac`), debugger, and other tools. **You need this to compile and run CCRM.**
- **JRE (Java Runtime Environment)**: The environment required to *run* Java applications. It contains the JVM and core libraries but lacks development tools.
- **JVM (Java Virtual Machine)**: An abstract machine that runs compiled Java bytecode, enabling the "write once, run anywhere" philosophy.

<br/>

### Syllabus Topic Mapping

This table highlights where key OOP and Java concepts are implemented within the project's source code.

| Topic              | Implementation Location                |
| ------------------ | -------------------------------------- |
| Encapsulation      | `edu.ccrm.domain.Person` (private fields) |
| Inheritance        | `edu.ccrm.domain.Student` (extends Person) |
| Abstraction        | `edu.ccrm.domain.Person` (abstract class) |
| Polymorphism       | `edu.ccrm.service.TranscriptService`   |
| Streams API        | `edu.ccrm.service.CourseService`       |
| NIO.2 API          | `edu.ccrm.io.ImportExportService`      |
| Design Patterns    | `edu.ccrm.config.AppConfig` (Singleton) |
| Exception Handling | `edu.ccrm.service.EnrollmentService`   |

---

## ✍️ Author

**Kavya Kulshreshtha**

- GitHub: [@Kavya-Kulshreshtha](https://github.com/Kavya-Kulshreshtha)

---

## Acknowledgements

- [Java SE Documentation](https://docs.oracle.com/en/java/javase/21/)
- [Eclipse IDE](https://www.eclipse.org/)
- [GitHub](https://github.com/)

--- 

*Built with dedication as a part of the Vityarthi Programming in Java course.*
```
