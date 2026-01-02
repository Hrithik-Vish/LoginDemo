# Login Authentication System (Advanced Java)

This project is a **simple Login, Authentication, and Logout system** built using **Advanced Java concepts** like **Servlets, JSP, Sessions, and Apache Tomcat**.

It is created as **Assignment A** for the **Advanced Java / Internship syllabus**.

---

## 🛠️ Technologies Used

- Java (JDK 8 / 11 / 17)
- Servlets
- JSP (Java Server Pages)
- Apache Tomcat 9
- Eclipse IDE

---

## 📁 Project Structure

```

LoginDemo
├── src/main/java
│   └── com.demo
│       ├── LoginServlet.java
│       └── LogoutServlet.java
│
├── src/main/webapp
│   ├── login.jsp
│   ├── welcome.jsp
│   └── WEB-INF

```

---

## ✨ Features

- User Login with username and password
- Session-based authentication
- Error message for invalid login
- Protected welcome page
- Logout functionality with session invalidation

---

## 🔐 Login Credentials (Hardcoded)

```

Username: admin
Password: 1234

```

---

## ▶️ How to Run the Project

1. Install **Eclipse IDE for Enterprise Java Developers**
2. Install and configure **Apache Tomcat 9**
3. Import this project into Eclipse
4. Run the project using:
```

Run As → Run on Server

```
5. Open browser and go to:
```

[http://localhost:8080/LoginDemo/login.jsp](http://localhost:8080/LoginDemo/login.jsp)

```

---

## 🔁 Application Flow

1. User opens `login.jsp`
2. Form submits to `LoginServlet`
3. If credentials are valid:
- Session is created
- User is forwarded to `welcome.jsp`
4. If invalid:
- Error message is shown
5. Logout:
- Session is destroyed
- User is redirected to login page

---

## 📚 Concepts Covered

- Servlet API
- JSP scripting
- HTTP Sessions
- RequestDispatcher
- Login & Logout flow

---

## ✅ Status

✔ Completed  
✔ Tested  
✔ Assignment-ready  

---

## 👤 Author

**Hrithik Vishwakarma**
