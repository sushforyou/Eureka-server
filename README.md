# 🔎 Eureka Discovery Server

**Eureka Server** is a service registry used in microservices architectures to allow services to **register themselves** and **discover other services** dynamically.  
It acts as the central hub for all microservices to communicate in a scalable way.

---

## 🚀 Features

- Service registration and discovery for microservices  
- Provides a web dashboard to view all registered services  
- Supports Spring Boot applications out-of-the-box  
- Lightweight and easy to configure  

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Spring Boot 3+, Java 17 |
| Service Discovery | Eureka Server |
| Build Tool | Maven |
| Dashboard | Web UI |

---

## ⚙️ Configuration

### `application.yml`
```yaml
server:
  port: 8761

eureka:
  client:
    fetch-registry: false
    register-with-eureka: false
