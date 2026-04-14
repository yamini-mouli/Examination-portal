---

# 📝 Exam Portal System

## 📌 Overview

The **Exam Portal System** is a web-based application developed using **Spring Boot** that allows users to take exams online and enables administrators to manage questions, exams, and results efficiently. The system is designed to provide a structured and user-friendly platform for conducting and evaluating online assessments.

---

## 🚀 Features

### 👤 User Module

* Register and login securely
* View available exams
* Attempt exams within a time limit
* Submit answers and view results

### 🛠 Admin Module

* Add, update, and delete questions
* Create and manage exams
* View student performance and results
* Manage users

---

## 🏗️ Tech Stack

* **Backend:** Java, Spring Boot
* **Database:** MySQL
* **ORM:** Hibernate (JPA)
* **Frontend:** Thymeleaf, HTML, CSS
* **Architecture:** MVC (Model-View-Controller)
* **Tools:** Eclipse / IntelliJ, Git

---

## ⚙️ Project Structure

```
exam-portal/
│── src/main/java/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── model/
│
│── src/main/resources/
│   ├── templates/
│   ├── application.properties
│
│── pom.xml
```

---

## 🔧 Setup Instructions

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/exam-portal.git
   ```

2. Open in IDE (Eclipse / IntelliJ)

3. Configure MySQL database in `application.properties`

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/examdb
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```

4. Run the application

   * Run the main Spring Boot class

5. Open browser

   ```
   http://localhost:8080
   ```

---

## 📊 Database Design

* **User Table** → Stores user details
* **Exam Table** → Stores exam information
* **Question Table** → Stores questions
* **Result Table** → Stores exam results

---

## 🧠 Key Learnings

* Implemented **CRUD operations** using Spring Boot
* Learned **Hibernate ORM mapping**
* Understood **MVC architecture flow**
* Gained experience in **database integration**
* Improved debugging and problem-solving skills

---

## 🔮 Future Enhancements

* Add timer-based auto submission
* Implement role-based authentication (Spring Security)
* Improve UI using React / Angular
* Add analytics dashboard

---

## 📚 References

* Spring Boot Documentation
* Hibernate Documentation
* MySQL Documentation

---

## 👩‍💻 Author

Yamini C
Harshitha S
Computer Science (Cyber Security) Students

---

