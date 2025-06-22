##   Project: Feedback Collection System

A web-based application for collecting, viewing, and managing user feedback. Built using Java Servlets and JSP, this project allows users to submit their feedback, and enables an admin to review or delete entries. Feedback is stored in a local JSON file using Gson.

--------------------------------------------

##  Tech Stack

1. Frontend: JSP, HTML, CSS
2. Backend: Java Servlets
3. Storage: JSON File (`feedback.json`)
4. Library: Gson (for JSON serialization)
5. Server: Apache Tomcat 9+
6. IDE: Eclipse or IntelliJ IDEA

--------------------------------------------

## Setup Instructions

Requirements

1- Java JDK 8 or above  
2- Eclipse IDE (EE) or IntelliJ IDEA  
3- Apache Tomcat 9+  
4- Gson library ('gson-2.x.jar')

--------------------------------------------

###  How to Run the Project

1. Clone or Download the Project
   - Clone from GitHub or extract the ZIP.

2. Import into Eclipse
   - Go to File > Import > Existing Projects into Workspace
   - Select the root folder.

3. Add Gson JAR
   - Download from: [https://mvnrepository.com/artifact/com.google.code.gson/gson](https://mvnrepository.com/artifact/com.google.code.gson/gson)
   - Create folder: WebContent/WEB-INF/lib/
   - Place JAR file inside.
   - Add to build path:  
     Right-click project → Build Path > Configure Build Path > Add JARs.

4. Run on Apache Tomcat
   - Configure Tomcat in Eclipse.
   - Right-click project → 'Run As > Run on Server'.

5. Access the Application
   - Visit:  
     'http://localhost:8080/FeedbackCollectionSystem/home.jsp'

----------------------------------------

##  Admin Login

Use the following credentials to log in as admin:

- Username: 'admin'  
- Password: 'admin123'


