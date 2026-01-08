# Login Authentication System (Advanced Java + JDBC)

This project is a **Login, Authentication, and Logout system** built using **Advanced Java concepts** such as **Servlets, JSP, Sessions, JDBC, and Apache Tomcat**.

It uses **JDBC with an SQL database** to validate user credentials instead of hardcoded values.

This project is created as **Assignment A** for the **Advanced Java / Internship syllabus**.

---

## 🛠️ Technologies Used

- Java (JDK 8 / 11 / 17)
- Servlets
- JSP (Java Server Pages)
- JDBC
- SQL (MySQL / any relational DB)
- Apache Tomcat 9
- Eclipse IDE

---

## 📁 Project Structure

```

LoginDemo
├── src/main/java
│   └── com.demo
│       ├── LoginServlet.java
│       ├── LogoutServlet.java
│       └── DBConnection.java
│
├── src/main/webapp
│   ├── login.jsp
│   ├── welcome.jsp
│   └── WEB-INF

````

---

## ✨ Features

- User login using **database-stored credentials**
- JDBC-based authentication
- Session-based login system
- Error message for invalid username/password
- Protected welcome page
- Secure logout with session invalidation

---

## 🗄️ Database Details

### Example Table Structure

```sql
CREATE TABLE users (
    id INT PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR(50),
    password VARCHAR(50)
);
````

### Sample Data

```sql
INSERT INTO users (username, password)
VALUES ('admin', '1234');
```

> ⚠️ Passwords are stored in plain text for learning purposes only.

---

## ▶️ How to Run the Project

1. Install **Eclipse IDE for Enterprise Java Developers**
2. Install and configure **Apache Tomcat 9**
3. Create a database and table as shown above
4. Update database credentials in `DBConnection.java`
5. Import this project into Eclipse
6. Run the project using:

```
Run As → Run on Server
```

7. Open browser and go to:

```
http://localhost:8080/LoginDemo/login.jsp
```

---

## 🔁 Application Flow

1. User opens `login.jsp`
2. Login form submits to `LoginServlet`
3. Servlet connects to database using JDBC
4. Credentials are validated from `users` table
5. If valid:

   * Session is created
   * User is forwarded to `welcome.jsp`
6. If invalid:

   * Error message is displayed
7. Logout:

   * Session is destroyed
   * User is redirected to login page

---

## 📚 Concepts Covered

* Servlet API
* JSP scripting
* JDBC & SQL
* Database connectivity
* HTTP Sessions
* RequestDispatcher
* Login & Logout flow

---

## ✅ Status

✔ Completed
✔ JDBC Integrated
✔ Tested
✔ Assignment-ready

---

## 👤 Author

**Hrithik Vishwakarma**
just tell me 👍
```
