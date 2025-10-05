# 🎓 University Management System – Java & MySQL

A **Java-based University Management System** designed to efficiently manage student, faculty, and administrative information.  
All records are stored in a **centralized MySQL database**, allowing users to **Add, View, Update, and Manage** university data seamlessly.

---

## ✅ Features & Modules

| Module / Class                | Description |
|------------------------------|-------------|
| `Login`, `Splash`            | User authentication and startup screen |
| `AddStudent`, `AddTeacher`   | Add new student or faculty records |
| `UpdateStudent`, `UpdateTeacher` | Edit existing information |
| `StudentDetails`, `TeacherDetails` | View complete profiles |
| `EnterMarks`, `Marks`        | Record and view academic performance |
| `ExaminationDetails`         | Manage exam schedules and data |
| `StudentLeave`, `TeacherLeave` | Leave application forms |
| `StudentLeaveDetails`, `TeacherLeaveDetails` | Leave tracking |
| `StudentFeeForm`, `FeeStructure` | Fee management |
| `Project`, `About`           | Project overview section |
| `Conn`                       | Database connection class |

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **Java (Swing/AWT/Core Java)** | Frontend Interface & Logic |
| **MySQL** | Data Storage |
| **JDBC** | Database Connectivity |

---

## 📂 Project Structure

## 📂 Project Structure

```
UniversityManagementSystem/
│── src/
│   ├── Login.java
│   ├── Splash.java
│   ├── AddStudent.java
│   ├── AddTeacher.java
│   ├── UpdateStudent.java
│   ├── UpdateTeacher.java
│   ├── StudentDetails.java
│   ├── TeacherDetails.java
│   ├── EnterMarks.java
│   ├── Marks.java
│   ├── ExaminationDetails.java
│   ├── StudentLeave.java
│   ├── TeacherLeave.java
│   ├── StudentLeaveDetails.java
│   ├── TeacherLeaveDetails.java
│   ├── StudentFeeForm.java
│   ├── FeeStructure.java
│   ├── About.java
│   ├── Project.java
│   ├── Conn.java
│── README.md
```
## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/UniversityManagementSystem.git
   ```
2. **Open the project in any Java IDE**
   - IntelliJ IDEA / Eclipse / NetBeans
3. **Configure Database Connection in `Conn.java`**
   ```java
   String url = "jdbc:mysql://localhost:3306/university";
   String username = "root";
   String password = "your_password";
   ```
4. **Import `database.sql` into MySQL**

5. **Run `Splash.java` to start the application**
