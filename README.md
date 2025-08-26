# 🛒 E-Commerce Web Application
📌 Project Synopsis

The objective of this project is to develop a dynamic and scalable e-commerce web application with essential features such as:

User registration & login

Product browsing & search

Cart management

Secure checkout process

Additionally, the Admin Panel provides functionalities for:

Product management (Add, Update, Delete)

Order management for efficient operations

The project ensures robust authentication and authorization using Spring Security and provides a responsive UI with Thymeleaf and Bootstrap.

## ⚙️ Technologies Used

Backend: Java, Spring Boot, Spring Security

Frontend: HTML, CSS, JavaScript, Bootstrap, Thymeleaf

Database: MySQL

Architecture: MVC (Model-View-Controller)

IDE: Spring Tool Suite (STS)

## 🚀 Features
User Module

Register, login, and manage profile

Browse products with search & filter options

Add/remove items to cart

Secure checkout & order placement

Admin Module

Manage product catalog (CRUD operations)

View and manage customer orders

Role-based authentication & authorization

## 🛠️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/ecommerce-app.git
cd ecommerce-app


Configure the MySQL database:

Create a database ecommerce_db.

Update application.properties with your DB credentials.

spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update


Run the Spring Boot application:

mvn spring-boot:run


Access the application:

User Portal: http://localhost:8080/

Admin Panel: http://localhost:8080/admin

## 📂 Project Structure
ecommerce-app/
 ├── src/main/java/com/ecommerce
 │    ├── controller    # Web controllers
 │    ├── model         # Entity classes
 │    ├── repository    # JPA repositories
 │    ├── service       # Business logic
 │    └── EcommerceApplication.java
 ├── src/main/resources
 │    ├── templates     # Thymeleaf templates
 │    ├── static        # CSS, JS, Images
 │    └── application.properties
 ├── pom.xml            # Dependencies

## 🔒 Security

Implemented using Spring Security

Role-based access (ROLE_USER, ROLE_ADMIN)

Passwords encrypted using BCrypt

## 📈 Future Enhancements

Product recommendation system (ML-based)

Payment gateway integration

Order tracking system

Review & rating system

👨‍💻 Author

Developed by Samrudh KU – Passionate Java Full Stack Developer.
