# Customer Relationships Management Web Application

## Configuration
1. Spring Boot configuration with dependencies 
[[Reference]()]
   - Spring Web
   - Thymeleaf
   - MySQL Driver
   - Spring Data JPA
   - Spring Boot DevTools (Optional)
   - Lombok (Optional)
2. Create MySQL database 
[[create-datebase.sql]()]
3. Configure database connection (JDBC) in 
[application.properties]()
4. Create Entity classes 
[[Customer]()]
5. Create Repository interfaces extends JpaRepository 
[[CustomerRepository]()]
6. Create Service interfaces 
[[CustomerService]()]
7. Create Service Implementation classes 
[[CustomerServiceRepository]()]
   - Inject Repository (prefer by constructor)
8. Create Controller 
[[CustomerController]()]





















