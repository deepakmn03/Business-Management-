# Business Management Web Application : <br>

![home (2)](https://github.com/SuhasKamate/Business_Management_Project/assets/126138738/e8db8f17-72d6-42a0-b264-def0bf883bbf)



## Project Desc : Business Management Web Application 
  => The Business Management Web Application is a comprehensive tool designed to help businesses manage various aspects of their operations. 
          It provides a user-friendly interface for tasks like managing customer data, inventory, orders, and more.



## Features  :

- **Customer Management**: Easily add, update, and delete customer information.
- **Inventory Management**: Keep track of your inventory items, including stock levels and pricing.
- **Order Management**: Manage customer orders such as order creation .
- **User Authentication**: Secure login and authentication for admin and staff members.
- **Role-Based Access Control**: Define roles and permissions for different user types.
- **Database Integration**: Integrated with PostgreSQL for data storage.




## Technologies Used :

- Spring Boot: Backend framework for building Java-based web applications.
- pOstgreSQL: Relational database management system for data storage.
- IDE/Tool : Spring Tool Suite 4 (Eclipse)




## Installation :

1. Clone the repository : $ git clone https://github.com/deepakmn03/Business-Management.git <br>

2. Import the project inside STS/Eclipse : <br>
     - Open STS/Eclipse > file > import > maven > existing project > browse > finish . <br>
     
3. Make sure you are in the Business Management directory. <br>

4.Configure the database connection is application.properties (check the Database section for more information). <br>

5.Run the project (by running main method is BusinessProjectApplication.java) OR right clink on the project > Run As > Spring Boot App. <br>

6.Open http://localhost:2330/home in any browser. <br>

7.Now your tables will be created in the databse. <br>
   - You have to add one admin data manually to login as admin, So add one admin data. <br>
    



## Database :

PostgreSQL can be used as the database for this project. 
The database connection can be configured in the application.properties file, with the appropriate values for the following properties: <br>

spring.datasource.name=[Your Database Name] <br>
spring.datasource.url=jdbc:postgresql://localhost:5432/[Your Database Name] <br>
spring.datasource.password=[Your password] <br>
spring.datasource.username=[Your username] <br>
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver <br>
spring.jpa.hibernate.ddl-auto=update <br>
server.port=2330[Optional] <br>