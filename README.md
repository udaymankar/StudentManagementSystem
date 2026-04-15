# 📚 Student Management System

A feature-rich console application for complete student record management using Core Java.  Implements CRUD operations with input validation, data persistence, and comprehensive analytics. 

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Author](#author)

## ✨ Features

### Student Management (CRUD)
- **Create**: Add new students with complete details
- **Read**: View individual or all student records
- **Update**: Modify student information, semester, status
- **Delete**: Remove student records with confirmation

### Academic Features
- **Marks Management**: Add/update marks for multiple subjects
- **Marksheet Generation**: View detailed marksheet with grades
- **Grade Calculation**:  Automatic grade assignment based on marks
- **Pass/Fail Detection**:  Automatic result calculation

### Analytics Module
- **Overall Statistics**: Total students, pass percentage, average marks
- **Grade Distribution**: Count of students in each grade
- **Course-wise Report**: Performance breakdown by course
- **Top Performers**: Rank students by performance
- **Failed Students Report**:  List students needing attention
- **Semester-wise Distribution**: Student count per semester

### Data Features
- **Persistent Storage**: Data saved using Java Serialization
- **Search Functionality**: Find students by name, ID, email, or course
- **Input Validation**: Email, phone, marks validation

## 🛠 Tech Stack

- **Language**: Java (JDK 8+)
- **Paradigm**: Object-Oriented Programming
- **Data Storage**: Java Serialization (File I/O)
- **Collections**: HashMap, ArrayList

## 📁 Project Structure

```
StudentManagementSystem/
├── src/
│   ├── Main.java
│   ├── models/
│   │   └── Student. java
│   ├── services/
│   │   ├── StudentService.java
│   │   └── AnalyticsService.java
│   └── utils/
│       ├── Constants.java
│       ├── DataStorage.java
│       └── InputValidator.java
├── data/
└── README.md
```

## 🚀 Installation & Setup

### Prerequisites
- JDK 8 or higher installed
- Any IDE (VS Code, IntelliJ, Eclipse) or Command Line

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/theworldofuday/StudentManagementSystem.git
   cd StudentManagementSystem
   ```

2. **Compile the project**
   ```bash
   cd src
   javac Main.java models/*. java services/*.java utils/*.java
   ```

3. **Run the application**
   ```bash
   java Main
   ```

## 📖 Usage

### Quick Start
1. Run the application
2. Add a new student (Option 1)
3. Add marks for the student (Option 6)
4. View marksheet (Option 7)
5. Check analytics (Option 9)

### Available Courses
- Computer Science
- Information Technology
- Electronics
- Mechanical
- Civil
- Electrical

## 🔑 Key Concepts Used

- **OOP Principles**:  Encapsulation, Single Responsibility
- **Java Collections**: HashMap for O(1) lookups, ArrayList for ordered data
- **Serialization**: Object persistence to files
- **File I/O**: Reading/writing binary data
- **Exception Handling**: Graceful error management
- **Input Validation**: Regex patterns for validation
- **Date/Time API**: LocalDate for date handling

## 👨‍💻 Author

**Uday**
- GitHub: [@udaymankar](https://github.com/udaymankar)

