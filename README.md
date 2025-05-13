# 🗓️ Timetable Management System

## 👨‍💻 Team Members

| Name           | Roll Number | LinkedIn | GitHub |
|----------------|-------------|----------|--------|
| Haris Shahzad | 23P-0573    | [LinkedIn](https://www.linkedin.com/in/haris-shahzad-7b8746291/) | [GitHub](https://github.com/Zenvila) |
| Abdul Rafy     | 23P-0560    | [LinkedIn](https://www.linkedin.com/in/abdul-rafy-b11829315/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [GitHub](https://github.com/Abdul-Rafy2005) |
| Muhammad Taha  | 23P-0559    | [LinkedIn](https://www.linkedin.com/in/muhammad-taha-57713b247/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [GitHub](https://github.com/BoltTaha) |

---

## 🎯 Project Purpose

Managing class schedules via PDFs can be very tedious for students. Often, students have to scroll through long documents just to find their weekly class schedules. This project aims to eliminate that hassle by providing a digital, **web-based Timetable Management System**.

We propose a system with **two interfaces**:

### 👤 Student Interface
- Students can **enter their roll number** and view their personalized timetable.
- Features include:
  - Search by **Time**
  - Search by **Day**
  - Search by **Class**

### 🛠️ Admin Interface
- Admin has control over the system and can:
  - Add/Edit/Delete students
  - Manage teachers, courses, rooms, and schedules
  - Configure overall timetable data

---

## 🖥️ Dashboard Overview

The system dashboard provides quick access to the following modules:

- Manage Students  
- Manage Teachers  
- Manage Courses  
- Room Scheduling  
- View Time Table  
- Admin Settings

A **summary panel** displays:
- Total Students
- Total Teachers
- Total Courses
- Total Rooms

---

## 📊 Tables & Their Purpose

Here’s a summary of the main database tables and their functions:

| Table Name              | Purpose |
|-------------------------|---------|
| **Admins**              | Stores admin credentials for secure access. |
| **Students**            | Holds student records, roll numbers, and section IDs. |
| **Teachers**            | Contains teacher details including name, email, and department. |
| **Courses**             | Stores course data such as code, name, and credit hours. |
| **Sections**            | Groups students into logical classes (sections). |
| **Departments**         | Maintains information about academic departments. |
| **Rooms**               | Contains physical room data like capacity and type. |
| **Days**                | Represents weekdays. |
| **TimeSlots**           | Defines individual time slots for scheduling. |
| **ClassTimes**          | Binds course offerings with time, room, and slot. |
| **ClassTypes**          | Categorizes the types of classes (e.g., Lecture, Lab). |
| **CourseOfferings**     | Links courses to sections, teachers, and semesters. |
| **Semesters**           | Stores data for academic semesters. |
| **class_schedule**      | Main schedule table mapping students to teachers, courses, and timing. |
| **DeletedStudents**     | Archive table to track students removed by an admin. |
| **TeacherOfficeAssignments** | Links teachers to their assigned office rooms. |
| **TeacherOfficeRooms**  | Stores information about teacher office rooms. |

---

## 🧩 Entity Relationship Diagram (ERD)

![ERD](./timetable_erd.png)

---

## 🎓 FAST NUCES

![FAST Logo](./NU-logo.jpg)

Project developed under the Department of Computer Science at FAST National University of Computer and Emerging Sciences.

---

