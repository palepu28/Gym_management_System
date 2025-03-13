# Gym Management System

## 📌 Overview
The **Gym Management System** is a **Java-based web application** that streamlines client management and membership tracking. It provides **secure authentication, CRUD operations, and data management** for gym administrators and members. The system is built using **Spring Boot and MySQL**, ensuring scalability and efficiency.

## 🚀 Features
- **User Authentication:** Secure login/logout using **JWT (JSON Web Token)**.
- **CRUD Operations:** Manage clients, membership plans, and attendance records.
- **RESTful APIs:** Designed with **Spring Boot** for seamless communication.
- **Database Integration:** Uses **MySQL** for efficient data storage and retrieval.
- **Testing:** Implements **JUnit** for unit testing and API validation.
- **Frontend Support:** Can be integrated with **React.js or Angular** for UI.

## 🛠️ Technologies Used
- **Backend:** Java, Spring Boot, REST APIs
- **Frontend (Optional):** HTML5, CSS3, Bootstrap (Can be extended to React.js/Angular)
- **Database:** MySQL, JDBC
- **Security:** JWT Authentication
- **Tools & DevOps:** Docker, Git, Jenkins, Postman
- **Testing:** JUnit, Mockito

## ⚙️ Installation & Setup
### Prerequisites:
- Java 11+
- MySQL Database
- Maven
- Postman (for API testing)

### Steps:
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/gym-management-system.git
   cd gym-management-system
   ```
2. **Configure MySQL Database:**
   - Create a new database `gym_management`.
   - Update `application.properties` with your MySQL credentials.
3. **Run the Application:**
   ```sh
   mvn spring-boot:run
   ```
4. **Test APIs using Postman:**
   - `POST /api/auth/register` – Register a new user
   - `POST /api/auth/login` – Authenticate user with JWT
   - `GET /api/clients` – Retrieve all clients
   - `POST /api/clients` – Add new client

## 📖 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | `/api/auth/register` | User Registration |
| POST   | `/api/auth/login` | User Authentication |
| GET    | `/api/clients` | Get all clients |
| POST   | `/api/clients` | Add a new client |
| PUT    | `/api/clients/{id}` | Update client details |
| DELETE | `/api/clients/{id}` | Remove a client |

## 🏆 Future Enhancements
- Integrate **React.js/Angular** for a responsive UI.
- Implement **role-based access control (RBAC)** for different user types.
- Deploy using **Docker and Kubernetes** for scalability.
- Add **payment gateway integration** for membership fees.

## 👨‍💻 Developed By
- **Palepu Sathwik Raja**  
- **GitHub:** [palepu28](https://github.com/palepu28)  
- **LinkedIn:** [Sathwik Palepu](https://www.linkedin.com/in/sathwik-palepu-04bba120a/)

---
🚀 **This Gym Management System is built with a focus on scalability, security, and efficiency, making it ideal for modern gym businesses.**

