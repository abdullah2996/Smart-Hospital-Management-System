# Smart Hospital Management System 🏥

A console-based **Data Structures & Algorithms (DSA)** project developed in **C++** for managing hospital operations efficiently. The system uses multiple DSA concepts such as **Hash Tables, Heaps, Graphs, Queues, Linked Lists, and Stacks** to simulate real-world hospital management functionalities.

## 📌 Project Overview

The Smart Hospital Management System helps manage:

* Patient records
* Doctor assignments
* Emergency patient handling
* Disease analytics
* Department referrals
* Action history with undo functionality

This project was developed as a university DSA project to demonstrate practical implementation of data structures in a real-world scenario.

---

# 🚀 Features

## 👨‍⚕️ Patient Management

* Add new patients
* Delete patient records
* Search patients by ID
* Display all patients
* Store patient information in files

## 🩺 Doctor Management

* Add doctors
* Assign doctors automatically using load balancing
* Manage doctor workload efficiently

## 🚑 Emergency Queue System

* Add patients to priority queue
* Treat highest severity patient first
* Display patient queue

## 📊 Disease Analytics

* Show disease frequency report
* Display critical patients based on severity

## 🔗 Referral Network

* Add department referrals
* Display referral graph
* BFS Traversal
* DFS Traversal
* Shortest referral path using Dijkstra Algorithm

## ↩️ Undo System

* View action history
* Undo last action using stack

## 💾 File Handling

The system stores data using text files:

* `patients.txt`
* `doctors.txt`
* `departments.txt`
* `referrals.txt`

---

# 🧠 Data Structures & Algorithms Used

| Concept            | Usage                       |
| ------------------ | --------------------------- |
| Linked List        | Patient storage             |
| Hash Table         | Fast patient searching      |
| Max Heap           | Emergency priority queue    |
| Min Heap           | Doctor load balancing       |
| Graph              | Department referral network |
| BFS & DFS          | Graph traversal             |
| Dijkstra Algorithm | Shortest referral path      |
| Stack              | Undo functionality          |
| File Handling      | Persistent data storage     |

---

# 🛠️ Technologies Used

* **Language:** C++
* **Concepts:** DSA, OOP
* **Compiler:** g++ / Visual Studio
* **Storage:** Text Files

---

# 📂 Project Structure

```bash
Smart Hospital Management System/
│
├── main.cpp
├── HospitalSystem.cpp
├── HospitalSystem.h
├── patients.txt
├── doctors.txt
├── departments.txt
├── referrals.txt
├── code.cpp
└── README.md
```

---

# ▶️ How to Run

## Using g++

```bash
g++ main.cpp HospitalSystem.cpp -o hospital
./hospital
```

## Using Visual Studio

1. Open the project folder
2. Build the project
3. Run the program

---

# 📋 Main Menu Options

```text
1. Add Patient
2. Delete Patient
3. Search Patient
4. Display All Patients
5. Add Doctor
6. Assign Doctor
7. Add Patient to Queue
8. Treat Next Patient
9. View Priority Queue
10. View Critical Patients
11. Disease Frequency Analytics
12. Add Department Referral
13. Display Referral Network
14. BFS Traversal
15. DFS Traversal
16. Shortest Referral Path
17. View Action History
18. Undo Last Action
19. Save and Exit
```

---

# 🎯 Learning Outcomes

Through this project, the following concepts were practiced:

* Real-world implementation of DSA
* Object-Oriented Programming in C++
* Graph traversal algorithms
* Heap operations
* File handling
* Problem solving and system design

---

# 👨‍💻 Author

**Abdullah**
BSCS Student
DSA Semester Project

---


# 📄 License

This project is developed for educational purposes only.
