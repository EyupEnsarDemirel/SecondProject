# SecondProject
This project is Task 2 for the Spring Framework Apps assignment. The goal of this task is to create
a fully functional REST API using Spring Boot. The application supports CRUD operations,
exception handling, Swagger documentation, and an in-memory H2 database.
Technologies Used
• Java
• Spring Boot
• Spring Web (REST)
• Spring Data JPA
• H2 Database
• Swagger / OpenAPI
• Maven
How to Run the Application
1. Open the project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run Project2Application.java
4. Application runs on port 8080
API Endpoints
POST /api/v1/products – create product
GET /api/v1/products/{id} – get product by id
GET /api/v1/products – get all products
PUT /api/v1/products/{id} – update product
DELETE /api/v1/products/{id} – delete product
H2 Database
URL: http://localhost:8080/console
JDBC URL: jdbc:h2:mem:testdb
User: sa
Password: (empty)
Swagger UI
URL: http://localhost:8080/swagger-ui/index.html
Application Architecture
Controller – handles HTTP requests
Service – business logic
Repository – database access using JPA
Mapper – maps request and response objects
Exception Handling
Custom exception handling is implemented using @ControllerAdvice. When a product is not found,
the API returns HTTP 404 with a descriptive error message<img width="2263" height="1421" alt="Screenshot 2025-12-22 172737" src="https://github.com/user-attachments/assets/64c5b1b2-6059-44fa-8fc4-e141f7da5cc3" />
<img width="2188" height="1333" alt="Screenshot 2025-12-22 172819" src="https://github.com/user-attachments/assets/27cc6806-f851-4ea4-b7b4-7ffb6db4c09d" />
<img width="1278" height="924" alt="Screenshot 2026-01-06 220941" src="https://github.com/user-attachments/assets/253e5a2b-d552-4c77-870a-33391d08b408" />
<img width="1245" height="878" alt="Screenshot 2026-01-06 220956" src="https://github.com/user-attachments/assets/84263e2d-42fe-4e96-a67a-7661421de3aa" />
<img width="1239" height="891" alt="Screenshot 2026-01-06 221036" src="https://github.com/user-attachments/assets/26fbd6f2-8d56-4a5d-b4e1-3c4d8492acb1" />
<img width="1377" height="782" alt="Screenshot 2026-01-06 221051" src="https://github.com/user-attachments/assets/07c27cd4-3463-4928-ba0c-2be04d4eac14" />
<img width="999" height="514" alt="Screenshot 2026-01-06 221125" src="https://github.com/user-attachments/assets/1aec78d4-bdd8-4ca4-a065-a0111ac2162f" />
<img width="1212" height="724" alt="Screenshot 2026-01-06 221145" src="https://github.com/user-attachments/assets/4fa21ebe-8bb3-4093-8f2e-d0e7c3a1de8e" />
