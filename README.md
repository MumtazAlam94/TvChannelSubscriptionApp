# TvChannelSubscriptionApp
A TvChannelSubscription Managment Project Based on Spring Boot,Spring Security,Java Collection, JavaScript etc

This is beginner level project of Tv Channels Subscription Managment Project,

**Workflow**
Hibernate configuration added( database and tables automatically create when run the project)
Service classes provide & updated
Controller Classes Provided and updated
dao classes interact with database
bug fixed 
support in both eclipse & intellij ide
disclaimer: currently working on this branch so there may be some bug related to endpoint.

**Quickstart**
Clone the repository
Open the project in your IDE: Eclipse or IntelliJ IDEA
recognizes the project as a Spring Boot project. Also, you must change the working directory of the project so that the views 
Configure the database connection in application.properties file (check the Database section below for more info)
Run the project 


**Database**
MySQL can be used as the database for this project. The database connection can be configured in the application.properties file, with the appropriate values for the following properties:

   spring.datasource.url = jdbc:mysql://localhost:3306/demo?useSSL=false
   spring.datasource.username = root
   spring.datasource.password = root
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

Having done that, you must create some base data in the database. You can do that by running the basedata.sql script on the database. Check out Google for how to do that, because it depends on what tool you are using to access said database.


**Controller**
control the endpoint and also send data to view
 
**Models**
represent data as entity and relationship among them.

**View**
receive data from controller and show with frontend.
