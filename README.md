# hotel-booking-server--spring-boot

Setup Instructions

Backend (Spring Boot) Setup

Clone the Repository

git clone https://github.com/your-username/hotel-booking-backend.git
cd hotel-booking-backend

Configure the Database

Update application.yml (or application.properties) in the src/main/resources/ directory:

spring:
  datasource:
    url: jdbc:mysql://localhost:3306/hotel_db
    username: root
    password: Admin@123
  jpa:
    hibernate:
      ddl-auto: update

Build and Run the Backend

./mvnw spring-boot:run  # If using Maven

OR

./gradlew bootRun  # If using Gradle

Verify API is Running
Open Postman or your browser and check:

http://localhost:8080/api/hotels

The server should respond with available hotels.

Frontend (React) Setup

Clone the Frontend Repository

git clone https://github.com/your-username/hotel-booking-frontend.git
cd hotel-booking-frontend

Install Dependencies

npm install  # or yarn install

Configure API Base URL
Update src/config.js:

export const API_BASE_URL = "http://localhost:8080/api";
Start the React App

npm start  # or yarn start

Access the Application
Open your browser and go to:

http://localhost:3000
Deployment
#for frontend follow the below link
<a href="https://drive.google.com/file/d/1L--CP7AaZ8F4J8KEnKTKaKwxenzmmss-/view?usp=sharing">click for frontend</a>
