# SpringBootWithThymeleaf



# 🌿 Spring Boot with Thymeleaf

This project demonstrates a **Spring Boot** application integrated with **Thymeleaf** as the template engine.  
It covers various **Thymeleaf features** such as conditional rendering, looping, and profile-based data display.

---

## 📂 Project Structure

SpringBootWithThymeleaf
│
├── src/main/java
│ └── com.example
│ ├── SpringBootWithThymeleafApplication.java # Main Spring Boot entry point
│ └── controller
│ └── MyController.java # Controller handling web requests
│
├── src/main/resources
│ ├── static
│ │ └── index.html # Static landing page
│ ├── templates
│ │ ├── conditional.html # Conditional rendering example
│ │ ├── looping.html # Looping through collections
│ │ └── profile.html # Profile data display
│ └── application.properties # Spring Boot configuration
│
├── pom.xml # Maven dependencies
└── README.md # Project documentation





---

## 🚀 Features

- **Thymeleaf Template Engine**
- **Spring Boot MVC Integration**
- Dynamic HTML rendering with:
  - Conditional statements (`th:if`, `th:unless`)
  - Loops (`th:each`)
  - Data binding (`th:text`, `th:href`)
- Static resource handling (`/static` folder)
- Controller-to-template data passing

---

## 🛠️ Technologies Used

| Technology       | Purpose |
|------------------|---------|
| Java 17          | Programming language |
| Spring Boot 3.x  | Framework |
| Thymeleaf        | Template engine |
| Maven            | Build tool |
| HTML5 / CSS3     | Frontend UI |

---

## 📦 Maven Dependencies

Add to your `pom.xml`:

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>




⚙️ Configuration
application.properties


spring.application.name=SpringBootWithThymeleaf
server.port=8080



▶️ How to Run
Clone the repository


git clone https://github.com/your-username/SpringBootWithThymeleaf.git
cd SpringBootWithThymeleaf




Build and run the application


mvn spring-boot:run


Access the application


http://localhost:8080



👨‍💻 Author
Your Name
📧 Email: sharanyanemade123@gmail.com
🔗 GitHub: SharanyaNemade



📚 Learning Outcomes

Understanding how Spring MVC integrates with Thymeleaf
Using Model objects to pass dynamic data to templates
Creating dynamic and conditional HTML rendering
Structuring a Spring Boot web application with Thymeleaf best practices






📜 License
This project is licensed under the MIT License.



MIT License

Copyright (c) 2025 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy of this software 
and associated documentation files (the "Software"), to deal in the Software without restriction, 
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, 
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial 
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT 
NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE 
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
