# Inventory Manager

A lightweight, web-based inventory management system built using Java Spring Boot and Thymeleaf. This project helps small to medium-sized organizations streamline inventory tracking, stock control, and item issuance, replacing traditional paper-based processes with a digital system.

## Features

- Add, update, and delete inventory items
- Organize items by category
- Track item issuance and returns
- Role-based access for administrators and staff
- Responsive front-end using Thymeleaf templates and Bootstrap

## Tech Stack

- Java 11
- Spring Boot (Web, Data JPA, Security)
- Hibernate ORM
- Thymeleaf
- MySQL
- Bootstrap

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/inventory-manager.git
   ```
2. Configure MySQL database in `application.properties`
3. Build and run the app:
   ```bash
   ./mvnw spring-boot:run
   ```
4. Open your browser and go to `http://localhost:8080`

## Database

The system uses a MySQL database with the following core entities:
- `Item`
- `Category`
- `Transaction`
- `User`

## Folder Structure

```
src/
├── main/
│   ├── java/
│   ├── resources/
│   │   ├── templates/
│   │   └── static/
```

## 📝 License

This project is provided for personal portfolio and educational use. You are free to modify and reuse it.


