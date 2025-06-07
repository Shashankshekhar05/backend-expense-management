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

![![Screenshot 2025-06-07 174615](https://github.com/user-attachments/assets/25d4cdbd-4fd7-4d05-b6b4-e46cae2f6122)
)
![![Screenshot 2025-06-07 174631](https://github.com/user-attachments/assets/803c7517-0702-4239-9e53-8bacb4b4a455)
)
![![Screenshot 2025-06-07 174734](https://github.com/user-attachments/assets/42e0ba64-1645-4dcd-9271-5348a5c682c3)
)
![![Screenshot 2025-06-07 175010](https://github.com/user-attachments/assets/7747d9b5-dd45-4f5c-955f-6033d6b55d3a)
)
![![Screenshot 2025-06-07 175042](https://github.com/user-attachments/assets/d8bba7fd-1499-4d6b-ae68-b84c9a8c9747)
)
![![Screenshot 2025-06-07 175118](https://github.com/user-attachments/assets/b3094f6f-76c5-43e9-aab9-f1a05c70f6a4)
)












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

