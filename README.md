# ✈️ InfyGo – Flight Booking System

A **flight booking backend system** built using **Java & Spring Boot**, designed to handle **flight search, booking management, payments, and secure authentication**.  
The project follows a **clean layered architecture** and is built to be **scalable, secure, and integration-ready**.



## 🚀 Key Features
- 👤 User authentication with **JWT security**
- 🔍 Flight search by source & destination
- 🧾 Flight booking management
- 💳 Payment processing support
- 💺 Seat management
- 🔐 Secure REST APIs
- 🧩 Modular and scalable architecture



## 🛠 Tech Stack
- ☕ Java 17  
- 🌱 Spring Boot  
- 🔐 Spring Security + JWT  
- 🗄 Spring Data JPA  
- 🐬 MySQL  
- 📦 Maven  



## 📁 Project Structure
```
infygo-flight-booking-system
│
├── src/main/java/com/infygo
│   ├── InfyGoApplication.java
│   ├── controller
│   ├── service
│   ├── repository
│   ├── model
│   ├── dto
│   ├── security
│   ├── exception
│   └── config
│
├── src/main/resources
│   ├── application.yml
│   └── data.sql
│
├── pom.xml
└── README.md
```


## 🔐 Security (JWT)
- 🔑 Token-based authentication
- 🛡 API protection using Spring Security
- 🔓 Public access only for authentication endpoints



## 🔗 REST API Overview

### 🧾 Authentication
- `POST /api/auth/login` → Generate JWT token

### ✈️ Flights
- `GET /api/flights` → Fetch available flights

### 📖 Booking
- `POST /api/bookings` → Book a flight

### 💳 Payments
- `POST /api/payments` → Process payment



## ⚙️ Setup & Run
1. 📥 Clone or download the repository  
2. 🗄 Create MySQL database: `infygo_db`  
3. 🔧 Update database credentials in `application.yml`  
4. ▶️ Run `InfyGoApplication`  
5. 🌐 Server runs on `http://localhost:8081`  


## 🧪 Testing
- 🧰 Use **Postman** for API testing  
- 🔑 Pass JWT token in request header:
```
Authorization: Bearer <JWT_TOKEN>
```
