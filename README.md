# 💻 Student Information System (Java – Intermediate Project)




A Student Information System built in Java using Object-Oriented Programming (OOP) principles and Data Structures like Linked List and Binary Search Tree (BST) for efficient data storage, retrieval, and management.

This project demonstrates clean OOP design, encapsulation, and menu-driven console interaction for practical learning.



## 🚀 Features

✨ CRUD operations for managing student records

⚡ Fast searching with BST (optimized lookup by ID)

📑 Ordered record maintenance with Linked List

🧩 Encapsulation with getters/setters for data safety

🖥️ Interactive console menu system


## 🛠️ Tech Stack

Language: Java

Core Concepts:

Object-Oriented Programming (Encapsulation, Classes, Objects)

Data Structures: Linked List, Binary Search Tree



## 📊 Example Input / Output

Student Information System
1. Add Student
2. View All Students
3. Search Student by ID (LinkedList)
4. Search Student by ID (BST)
5. Exit

## Example Input

1

Enter Student ID: 101

Enter Student Name: Alice

Enter Department: CSE

Enter Grade: 8.5

## Example Output

Student added successfully!

Searching Student (LinkedList)

## Input:

3

Enter Student ID to search (LinkedList): 101


## Output:

ID: 101, Name: Alice, Department: CSE, Grade: 8.5

Searching Student (BST)

## Input:

4

Enter Student ID to search (BST): 101


## Output:

ID: 101, Name: Alice, Department: CSE, Grade: 8.5



<img width="456" height="460" alt="image" src="https://github.com/user-attachments/assets/5bb9b4e0-dfba-456c-be09-01e3ce5ddb4f" />


---

## 📌 Future Improvements

🟢 Add update & delete functionality for student records

🟢 Store data in files or database for persistence

🟢 Search students by name, department, or grade

🟢 Build a GUI version using JavaFX or Swing

## 👤 Author

**Rupam Ghosh**

🔗 GitHub https://github.com/codebyrupam

---

## 📊 UML Class Diagram

```mermaid
classDiagram
    class Student {
        - int id
        - String name
        - String department
        - double grade
        + getId()
        + getName()
        + getDepartment()
        + getGrade()
        + displayStudentDetails()
    }

    class StudentLinkedList {
        + addStudent(Student)
        + viewAllStudents()
        + searchStudentById(int)
    }

    class StudentBST {
        + insert(Student)
        + search(int)
    }

    StudentLinkedList --> Student
    StudentBST --> Student





