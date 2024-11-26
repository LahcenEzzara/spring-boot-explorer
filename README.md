# Spring Boot Explorer

A simple Spring Boot application that demonstrates a "Hello World" endpoint with a customizable message. This project is designed to be beginner-friendly and serves as a foundation for exploring Spring Boot features.

---

## 🚀 **Features**
- A RESTful `/hello` endpoint.
- Returns a friendly greeting message.
- Option to customize the greeting using a query parameter.

---

## 🛠️ **Technologies Used**
- **Java 17** (OpenJDK)
- **Spring Boot** (Latest version)
- **Maven** (Build tool)
- **IntelliJ IDEA** (Development environment)

---

## 📂 **Project Structure**
```plaintext
src/main/java/com/lahcencodes/springbootexplorer/
├── SpringBootExplorerApplication.java  # Main application file
```

---

## 🌐 **Endpoints**

### **Hello Endpoint**
- **URL:** `http://localhost:8080/hello`
- **Method:** `GET`
- **Description:** Returns a greeting message.
- **Query Parameter:**
    - `name` (optional): Customize the name in the greeting message.

#### Example Requests:
1. Default greeting:
   ```bash
   curl http://localhost:8080/hello
   ```
   **Response:**
   ```json
   Hello World!
   ```

2. Custom greeting:
   ```bash
   curl http://localhost:8080/hello?name=Lahcen
   ```
   **Response:**
   ```json
   Hello Lahcen!
   ```

---

## ⚡ **Getting Started**

### Prerequisites
Ensure you have the following installed:
1. **Java 17** (OpenJDK 17)
2. **Maven** (for building the project)
3. **Git** (for cloning the repository)

---

### **Steps to Run**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/LahcenEzzara/spring-boot-explorer.git
   cd spring-boot-explorer
   ```

2. **Build the Application**
   ```bash
   ./mvnw clean install
   ```

3. **Run the Application**
   ```bash
   ./mvnw spring-boot:run
   ```

4. Open your browser or API testing tool and navigate to:
    - [http://localhost:8080/hello](http://localhost:8080/hello)

---

## 🧪 **Testing the Application**

### Using `curl`
1. Default greeting:
   ```bash
   curl http://localhost:8080/hello
   ```

2. Custom greeting:
   ```bash
   curl http://localhost:8080/hello?name=LahcenCodes
   ```

### Using Postman
1. Create a new GET request.
2. Enter the URL: `http://localhost:8080/hello`.
3. Add a query parameter (optional): `name=LahcenCodes`.
4. Send the request.

---

## 🔧 **Stopping the Server**

1. **If running in the foreground**:
   Press **`Ctrl + C`** to terminate the application.

2. **If running in the background**:
   Find the process:
   ```bash
   ps aux | grep java
   ```
   Kill the process:
   ```bash
   kill <PID>
   ```

---

## 📜 **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🛡️ **Support**
If you have any questions or need help, feel free to contact me via [GitHub](https://github.com/LahcenEzzara).

Happy coding! 🎉