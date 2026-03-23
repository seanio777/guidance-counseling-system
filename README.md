# 🏫 Guidance Counseling Appointment System

A console-based appointment scheduling system for students 
and school counselors, built in C++.

## 👥 Developers
- Francien Nicole Ausan
- Maryneil Co
- Kerstein Ashby San Pedro
- Chryzller John Suing
- Jose Antonio Verano

## 📖 About
A full-featured appointment management system that allows 
students to book, cancel, and undo counseling appointments, 
while counselors can manage, accept, and transfer sessions.

## ✨ Features
- Student appointment booking with date/time validation
- Auto-assignment to next available counselor slot
- Counselor dashboard for managing appointments
- Appointment transfer between counselors
- Conflict detection using a graph
- Undo last action using a stack
- Waiting queue for fully-booked slots
- Input validation for names, IDs, dates, and menus

## 🧠 Data Structures Used
| Structure | Usage |
|---|---|
| Vector | Storing appointments and counselors |
| Queue | Waiting list for full slots |
| Stack | Undo last book/cancel action |
| Linked List | Sequential appointment tracking |
| Binary Search Tree | Sorted appointment viewing |
| Graph | Detecting scheduling conflicts |

## ⚙️ How to Compile
```bash
g++ main.cpp -o guidance_system
./guidance_system
```

## 🎯 How to Use
1. Run the program
2. Choose Student or Counselor login
3. Students can book, view, cancel, or undo appointments
4. Counselors can manage, transfer, and accept appointments