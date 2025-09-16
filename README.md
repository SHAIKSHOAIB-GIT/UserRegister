📘 User Registration Project (Servlet + JSP + Oracle DB)
🔹 Overview

This project demonstrates a User Registration Web Application using:

Java Servlet + JSP

Oracle Database 10g XE

Apache Tomcat 8.5 --> change port no to 9999

JDBC (Oracle ojdbc6.jar)

Intallation guide
                
        [All SW](https://drive.google.com/drive/folders/1ZwTOro69JwQb5HQEwQFZfuihdYrfNsyY)

Users can register by filling out a form. The data is stored securely in an Oracle DB, and the app redirects to a success or failure page.

    UserReg/
     ├── src/
     │   └── com/servlet/
     │       └── RegisterServlet.java
     │
     ├── WebContent/
     │   ├── register.jsp
     │   ├── success.jsp
     │   ├── failure.jsp
     │   └── WEB-INF/
     │       ├── lib/
     │       │   └── ojdbc6.jar   <-- (manually copy here)
     │       └── web.xml
     │
     └── README.md

 🔹 Steps to Run in Eclipse

    Create Project
    
    File → New → Dynamic Web Project → Name: UserReg.
    
    Target Runtime: Tomcat 8.5.
    
    Dynamic Web Module: 3.1.
    
    Add Files
    
    Copy all Java files to src/com/example/...
    
    Copy JSP files (register.jsp, success.jsp, failure.jsp) into WebContent/.
    
    Copy web.xml into WebContent/WEB-INF/.
    
    Place ojdbc6.jar inside WebContent/WEB-INF/lib/.
    
    Run on Tomcat
    
    Right-click project → Run As → Run on Server → select Tomcat 8.5.
    
