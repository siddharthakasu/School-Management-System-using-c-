# 🎓 School Management System

A Windows Forms-based School Management System built using C# and SQL Server. This application allows administrators to manage student records efficiently — including adding, updating, deleting, and displaying student information — with a user-friendly interface.

## 📌 Features

- Add, update, delete student records
- Display all student information in a table view
- Real-time dashboard statistics:
  - Total number of students
  - Number of teachers, subjects, and entries
- Form clearing/reset functionality
- SQL Server integration using ADO.NET
- Secure data handling with parameterized queries

## 🛠️ Technologies Used

- **C#**
- **.NET Framework**
- **Windows Forms**
- **SQL Server (schooldb)**
- **ADO.NET**

## 📂 Project Structure

- `MainForm.cs`: Main UI logic
- `StudentForm.cs`: Handles student operations (Add, Update, Delete, Display)
- `Dashboard.cs`: Displays summary counts
- `Database`: SQL Server backend using `schooldb` and `studentab`, `subtab`, `teachertab`, `entab` tables

## 🖼️ Screenshots

*Include screenshots of your forms and dashboard here if available.*

## 🚀 Getting Started

### Prerequisites

- Visual Studio (2019 or later)
- SQL Server (Express or full edition)
- .NET Framework (4.7+)

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/sidhharthakasu/SchoolManagementSystem.git
