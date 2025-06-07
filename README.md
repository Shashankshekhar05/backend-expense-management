# 💰 Expense Management System

A Spring Boot web application for managing and tracking enterprise-level expenses with user authentication and role-based access.

---

## 🔧 Tech Stack

- **Backend:** Java, Spring Boot, Spring Security
- **Database:** MySQL
- **Frontend:** HTML, CSS (basic UI, or integrated with Thymeleaf)
- **Tools:** Postman,  Git

---

## ✨ Features

- User Registration & Login (Spring Security + JWT)
- Add / Edit / Delete Expenses
- View Reports and Filter by Date/Category
- Admin Dashboard
- Swagger API Documentation

---

## 📸 Screenshots

![Screenshot 2025-06-07 160903](https://github.com/user-attachments/assets/d5c20234-fd54-4e98-b2e3-851653f5b136)
![Screenshot 2025-06-07 171827](https://github.com/user-attachments/assets/d217190e-5ce2-4038-ba00-c9be5d04aec4)




---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Shashankshekhar05/backend-expense-management.git
2. Configure Database
Update the MySQL connection details in src/main/resources/application.properties:

ini
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/expense_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
3. Build and Run the Application
Using Maven:

bash
Copy
Edit
mvn clean install
mvn spring-boot:run
4. Access the Application
Backend REST API will be available at:
http://localhost:8080/api/



🚀 API Endpoints Summary
Endpoint	Method	Description
/api/auth/register	POST	Register new user
/api/auth/login	POST	User login, returns JWT token
/api/expenses	GET	Get all expenses (auth required)
/api/expenses	POST	Create new expense
/api/expenses/{id}	GET	Get expense by ID
/api/expenses/{id}	PUT	Update expense by ID
/api/expenses/{id}	DELETE	Delete expense by ID

Note: Include JWT token in the Authorization header for protected endpoints.

🛠 Usage
Use Postman or any REST client to test endpoints.

Register a user and login to receive the JWT token.

Use the token for subsequent requests with this header:

makefile
Copy
Edit
Authorization: Bearer <your_jwt_token_here>
🤝 Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

📄 License
This project is licensed under the MIT License.

📫 Contact
GitHub: Shashankshekhar05

LinkedIn: shashankshekhar05

⭐ Thanks for checking out the Expense Management System!

