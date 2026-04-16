# 🏥 MedSync - Hospital Management System (Microservices)

## 🚀 Overview

MedSync is a **microservices-based hospital management system** designed to manage patients, appointments, staff, beds, and notifications efficiently.

Built using **Spring Boot + Spring Cloud**, this system follows **scalable and loosely coupled architecture** used in real-world applications.

---

## 🧩 Microservices Architecture

* 🔍 **Eureka Service** → Service Discovery
* 🌐 **API Gateway** → Central entry point
* 👤 **Patient Service** → Manages patient data
* 📅 **Appointment Service** → Handles appointments
* 🛏️ **Bed Service** → Manages bed allocation
* 👨‍⚕️ **Staff Service** → Staff management
* 📩 **Notification Service** → Sends notifications

---

## ⚙️ Tech Stack

* **Backend:** Java, Spring Boot
* **Microservices:** Spring Cloud (Eureka, Gateway, OpenFeign)
* **Database:** MySQL
* **Communication:** REST + Feign Client
* **Build Tool:** Maven

---

## 🔗 System Flow

1. Client sends request → API Gateway
2. Gateway routes request using **Eureka Service Discovery**
3. Microservices communicate using **Feign Client**
4. Response is sent back via Gateway

---

## 🏗️ Project Structure

```bash
MedSync-HospitalManagementSystem/
 ├── EurekaService
 ├── GatewayService
 ├── PatientService
 ├── AppointmentService
 ├── BedService
 ├── StaffService
 ├── NotificationService
```

---

## ▶️ How to Run

1. Start **Eureka Service**
2. Start all microservices
3. Start **API Gateway**
4. Access APIs via:

```
http://localhost:8080
```

---

## 💡 Key Features

✔ Microservices Architecture
✔ Service Discovery (Eureka)
✔ API Gateway Routing
✔ Inter-service Communication using Feign
✔ Scalable & Loosely Coupled Design

---

## 🎯 Future Enhancements

* 🔐 JWT Authentication
* 🐳 Docker & Kubernetes Deployment
* 📊 Monitoring (Prometheus + Grafana)
* 🔁 Circuit Breaker (Resilience4j)

---

## 👨‍💻 Author

**Rajkumar Pichhiguntla**
