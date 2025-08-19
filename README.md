# Spring Boot REST API Project

A simple Spring Boot REST API project that demonstrates the fundamentals of building RESTful web services with Spring Boot.

## 📋 Project Overview

This project serves as an educational example to understand:
- How to create RESTful APIs using Spring Boot
- Basic CRUD operations
- REST API best practices
- Spring Boot application structure
- Working with different HTTP methods (GET, POST, PUT, DELETE)
- Handling HTTP responses and status codes

## 🚀 Features

- RESTful API endpoints for student management
- Demonstrates different HTTP methods
- Proper response status codes
- Clean and organized project structure
- Built with Spring Boot 3.5.0 and Java 21

## 🛠️ Technologies Used

- **Java 21** - Programming language
- **Spring Boot 3.5.0** - Framework for building the application
- **Maven** - Dependency management
- **Spring Web** - For building RESTful web services

## 📁 Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── net/javaguides/springboot/
│   │       ├── controller/     # Contains REST controllers
│   │       │   ├── StudentController.java
│   │       │   └── HelloWorldController.java
│   │       ├── model/          # Contains entity classes
│   │       │   └── Student.java
│   │       └── SpringbootRestApiApplication.java  # Main application class
│   └── resources/
│       └── application.properties  # Application configuration
└── test/                        # Test files
```

## 🚀 Getting Started

### Prerequisites

- Java 21 JDK or later
- Maven 3.6.0 or later
- Your favorite IDE (IntelliJ IDEA, Eclipse, VS Code, etc.)

### Running the Application

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sangramjit786/simple-springboot-rest-api-project.git
   cd simple-springboot-rest-api-project
   ```

2. **Build the project**
   ```bash
   mvn clean install
   ```

3. **Run the application**
   ```bash
   mvn spring-boot:run
   ```

The application will start on `http://localhost:8080`

## 📚 API Endpoints

### Student Resource

- **GET** `/students` - Get all students
- **GET** `/students/student` - Get a single student
- **POST** `/students` - Create a new student
- **PUT** `/students/{id}` - Update a student
- **DELETE** `/students/{id}` - Delete a student

## 📝 Example Requests

### Get All Students
```http
GET http://localhost:8080/students
```

### Get Single Student
```http
GET http://localhost:8080/students/student
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Spring Framework
- Spring Boot Team
- Java Guides

---

<p align="center">
  Made with ❤️ by Your Name
</p>
