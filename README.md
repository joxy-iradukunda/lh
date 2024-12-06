Patient Appointment System
Overview
The Patient Appointment Management System is a web application designed to streamline the scheduling and management of appointments between doctors and patients. This system eliminates the need for manual appointment booking and reduces errors, ensuring an efficient and user-friendly experience.

Technical Details
•	Backend: Spring Boot (Java)
•	Frontend: React.js
•	Database: MySQL
•	Authentication: JWT (JSON Web Tokens)
•	REST APIs: For seamless communication between frontend and backend

Business Context
This system caters to:
1.	Patients: Allowing them to find doctors, view availability, and book appointments effortlessly.
2.	Doctors: Providing an easy interface to manage their schedule and interact with patients.
3.	Admins: Ensuring smooth operations by managing doctors, patients, and appointments in a centralized dashboard.

Features
•	User Authentication: Secure signup and login for doctors, patients, and admin
•	Role-based Access:
o	Admin: Manage users, doctors, and appointments.
o	Doctor: Update availability and review appointments.
o	Patient: Book, cancel, or reschedule appointments.
•	Appointment Management:
o	Real-time availability updates.
o	Notifications for appointment confirmation.
•	User-friendly Interface: Intuitive design for seamless navigation.

Technologies Used
•	Backend:
o	Spring Boot
o	Spring Security (for authentication and role-based authorization)
•	Frontend:
o	React.js
o	Axios (for API calls)
•	Database:
o	MySQL (Relational Database)
o	JPA/Hibernate (ORM for database interactions)
•	Build Tools:
o	Maven (for backend)
o	npm (for frontend)
________________________________________
Setup and Installation
Prerequisites
•	Java Development Kit (JDK) (v11 or higher)
•	Node.js and npm
•	MySQL Server
•	Git
Backend Setup
1.	Clone the repository:
bash
git clone https://github.com/joxy-iradukunda/Joxy.git
2.	Navigate to the backend directory:
Bash
cd backend
3.	Configure the database connection in application.properties:
properties
spring.datasource.url=phegon_medical_db
spring.datasource.username=iradukundajoyeuse8@gmail.com
spring.datasource.password=
4.	Build and run the application:
bash
mvn clean install
mvn spring-boot:run
Frontend Setup
1.	Navigate to the frontend directory:
bash
cd frontend
2.	Install dependencies:
bash
npm install
3.	Start the React application:
bash
npm start
________________________________________
How to Use
Signup
1.	Visit the homepage and click on the Signup button.
2.	Fill out the required fields:
o	Username
o	Email
o	Password
o	Role (Patient, Doctor, or Admin)
3.	Click Submit to register.
4.	A confirmation message will appear upon successful registration.
Sign In
1.	Visit the homepage and click on the Sign In button.
2.	Enter your email and password.
3.	Click Login to access the dashboard.
________________________________________
Future Enhancements
•	Integration with third-party payment gateways for online consultation fees.
•	SMS and email notifications for appointment reminders.
•	Advanced analytics for admins to monitor usage and trends.
•	Support for multiple languages.

