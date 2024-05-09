Spring Boot Security Framework Demo
This is a demo project showcasing a Spring Boot application with security features implemented using Spring Security.

Prerequisites
Before running this application, ensure you have the following installed:

IntelliJ IDEA
Java Development Kit (JDK) 17 or higher
Gradle
Getting Started

1. Clone the repository to your local machine:
   https://github.com/SITE-ADA/as1-spring-boot-logging-and-security-GunelD.git
2. Navigate to the project directory:
cd spring-boot-security-framework-demo
3. Build the project using Gradle:
   gradle build
4. Run the application

   The application will start on http://localhost:8080.

Usage

Accessing the Application
Open a web browser and go to http://localhost:8080 to access the home page.
If you're not logged in, you'll be prompted to log in or sign up.


User Authentication
Click on "Login" to access the login page.
Use the provided username and password to log in.
Upon successful login, you'll be redirected to the courses page.


Course Management (Admin Role)
To access course management features, log in as an administrator (ADMIN role).
Admin users can view, update, delete existing courses, and add new courses.

Signing Up (User Registration)
If you don't have an account, click on "Sign Up" to register.
Fill in the required details and submit the form.
After successful registration, you can log in using your new credentials.

Additional Information
The application uses in-memory authentication for demo purposes. In a production environment, configure a database-backed authentication provider.
Ensure proper security configurations based on your requirements before deploying to a production environment.

   


Link to video: https://youtu.be/8hTqKUxxkPI 
