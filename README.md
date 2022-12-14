# ****🎥Cinema Application**** #
### 📋 Description:
This application is simple simulator of cinema service.It is possible to register visitors.
They will be able to buy tickets for a certain time in the selected hall.

* Written using Spring and Hibernate frameworks.
* Includes authentication/authorization,REST

### 🚀  Project structure:
**Application has an N-Tier Architecture**
* Data access layer (DAO). This layer is responsible for accessing the database.
* Application layer (service). This layer of architecture is responsible for processing the data received from the DAO level.
* Presentation layer(controller). This level allows the user to work with this application.

### 🔎 Model structure:
![](img.png)

### 💡 Features:
- Registration
- Authentication
- Login / Logout
- Set role for users (by default USER)
- ADMIN can create and delete movies and movie sessions
- USER can buy a ticket for the movie session

### ⚙ Technologies:
- Java 11
- Maven
- MySQL
- Tomcat 9.0.50
- Hibernate
- Spring Web/Security
- REST

### 👀 INSTRUCTIONS FOR LAUNCHING THE PROJECT:
1. Fork this repository
2. Create new project from Version Control
3. Edit resources/db.properties - set the necessary parameters
``` java
    db.driver=YOUR_DRIVER
    db.url=YOUR_URL
    db.user=YOUR_USERNAME
    db.password=YOUR_PASSWORD
```
4. Create the necessary name of DB
5. Install Tomcat
6. Add Tomcat server to configuration and Fix it.
7. Run project

### 👀 For testing, you can use ready-made profiles:
1. ROLE_ADMIN
* Login: admin@adm.ua
* Password: admin12345

2. ROLE_USER
* Login: ivan@uk.ua
* Password: user1234
