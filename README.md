# Java-Based Learning Management System (LMS)

A standalone **Learning Management System (LMS)** built with **Core Java** and **Java Swing**. This project offers a simplified, offline-friendly platform focused on student functionalities such as course enrollment, assignment submission — all without using external libraries or databases.

## Project Overview

This LMS simulates essential educational tasks found in modern online learning platforms. It is tailored to provide a clean, functional experience while demonstrating Java principles like object-oriented programming (OOP), file handling, and GUI development.

## System Users

### Students
- log in
- View courses
- View and submit assignments
- View Time table
  
> *Note: The current version focuses on student functionality only.*

## Technology Stack

| Layer       | Technology        |
|-------------|-------------------|
| Language     | Java (Core Java)  |
| GUI          | Java Swing        |
| Data Storage | Java File I/O     |
| IDE          | NetBeans          |
| Database     | None (File-based storage) |

## Key Benefits

- No external dependencies
- Data stored locally using serialized/text files
- Great for learning Java fundamentals
- Strong demonstration of OOP principles
- Operates completely offline

## Features

### 1. User Authentication & Profile Management
- Secure login with username/password
- Sign-up and session handling
- Validation rules:
  - Password must be at least 8 characters with letters and numbers

### 2. Dashboard
- View recent courses, lectures, and assignments
- Quick links to all major sections:
  - Courses
  - Assignments

### 3. Course Management
- View available courses
- Course information:
  - Course name

### 4. Assignment Management
- View current assignments
- Upload completed assignment files
- Delete assignments

## Sample Scenario

1. Student enters:
   - Email: `maro@mail.com`
   - Password: `123456789`
2. System checks stored data and:
   - ✅ If valid → Load dashboard
   - ❌ If invalid → Show error

##  Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/marwanmohamed213410/learning-management-system.git
2. Open the project in **NetBeans** or any compatible Java IDE.
3. Compile and run the application.

## Screenshots
![Screenshot 2025-05-14 093729](https://github.com/user-attachments/assets/b413471e-1733-4128-a852-74ee4535acf8)

![Screenshot 2025-06-03 220054](https://github.com/user-attachments/assets/9c8eda3a-e1e1-4ae8-8ac2-58f67e4ba432)

![Screenshot 2025-06-05 111224](https://github.com/user-attachments/assets/09e45e77-8bc0-4142-ac48-9596fd896ada)

![Screenshot 2025-06-05 111237](https://github.com/user-attachments/assets/2dd83fb5-cf18-477d-b8eb-86a370e6f5bf)

Done by: Marwan Mohamed (2nd year computer engineering students) for: Java Essentials & OOP Project Date: may 2025
