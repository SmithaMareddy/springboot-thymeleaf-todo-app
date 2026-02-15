# Spring Boot To-Do Application

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

A functional CRUD web application built to manage daily tasks. This project demonstrates the integration of a Spring Boot backend with a persistent MySQL database and a responsive Thymeleaf frontend.

## 🛠 Tech Stack
* **Backend:** Java 17+, Spring Boot 3.x
* **Data Access:** Spring Data JPA (Hibernate)
* **Database:** MySQL
* **Frontend:** Thymeleaf + Bootstrap 5
* **Utility:** Lombok (for boilerplate reduction)

## ✨ Key Features
* **Full CRUD:** Create, Read, Update, and Delete tasks.
* **Persistent Storage:** Tasks are saved in a MySQL database.
* **Clean UI:** Styled with Bootstrap for a modern, responsive feel.
* **Architecture:** Follows the MVC (Model-View-Controller) design pattern.

## 📂 Project Structure
This project follows the **MVC (Model-View-Controller)** design pattern:
```text
src/main/java/com/example/todoapp/
├── controller    # Handles HTTP requests and navigation
├── model         # JPA Entities representing database tables
├── repository    # Interfaces for CRUD operations (Spring Data JPA)
├── service       # Contains Business Logic (Optional but recommended)
└── TodoAppApplication.java
```

## ⚙️ Quick Start
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/todoapp.git](https://github.com/your-username/todoapp.git)
2. **Configure Database:**
Update src/main/resources/application.properties with your MySQL username and password.

3. **Run**:
Launch the application from IntelliJ IDEA and visit http://localhost:8080.

