#Employee Management System

#HOW TO RUN THIS PROJECT?#
###FROM THE IDE:###
1. Open the project in an IDE like Eclipse.
2. You can run the DBScript provided in MySQL to create database and tables with basic values. 
	(Creating database is necessary since hibernate- update option is used : "spring.jpa.hibernate.ddl-auto = update")
3. In case you do not want to run file, you can change the line "spring.jpa.hibernate.ddl-auto = update"  to  "spring.jpa.hibernate.ddl-auto = create-drop"
	in src/main/resources/application.properties file.
4. Check your database connection in src/main/resources/application.properties file and change if needed.
5. Go to com.employee.management
6. Right Click on class Application.
7. Hit "Run As Java Application" in the IDE.
8. Check if localhost server has started.
9. Open Postman client service on Google chrome.
10. Hit url : "http://localhost:8080/employees" and url : "http://localhost:8080/departments"

    

#TECHNOLOGY STACK#
1. Java
2. Eclipse Neon 4.6.0
3. MySQL Workbench
4. Postman for Chrome: Version 4.10.5




### Ease of extending the program ###
1. You can add useraccount table and assign username and password details for the employee.
2. You can also create a system account who handles all the creation and deleting of employee and department.
