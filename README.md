# 📝 Blog App - Microservices Architecture

🔥 In this project, we build a **Real-World Blog Application** using a production-ready **Microservices Architecture** powered by **RabbitMQ, Redis, PostgreSQL, MongoDB, Docker, and Google OAuth**.  

This app demonstrates **scalable service communication, event-driven cache invalidation, optimized database usage, and deployment to AWS EC2**.  

---

## ✅ What You'll Learn
- Microservices communication with **RabbitMQ**
- **Redis caching** & smart cache invalidation
- **PostgreSQL + MongoDB integration** for optimized data use
- **Google Authentication (OAuth 2.0)**
- Dockerizing services & deploying on **AWS EC2**
- Frontend built with **Next.js** and deployed on **Vercel**

---

## 📌 Technologies
- **Backend:** Node.js, Express, RabbitMQ, Redis  
- **Databases:** PostgreSQL, MongoDB  
- **Authentication:** Google OAuth 2.0  
- **Containerization & Deployment:** Docker, AWS EC2  
- **Frontend:** Next.js (deployed on Vercel)  

---



---

## 📂 Project Structure

- **User Service** → Handles user registration, login, and authentication using **Google OAuth 2.0**.  
- **Author Service** → Manages author details, profiles, and their relationship with blog posts.  
- **Blog Service** → Core service for creating, updating, and managing blog posts, categories, and comments.  
- **Song Service** → A demo service showing how easily new microservices can be integrated into the architecture.  
- **Redis** → Provides caching for faster responses and includes **event-driven cache invalidation** using RabbitMQ.  
- **RabbitMQ** → Message broker enabling communication between microservices (publish-subscribe model).  
- **PostgreSQL** → Used for relational data storage (structured blog/author relationships).  
- **MongoDB** → Used for unstructured or flexible data storage (blog content, metadata, etc.).  
- **Frontend (Next.js)** → Modern React-based frontend for users, deployed on **Vercel**.  
- **Docker & Docker Compose** → Containerizes all services for easy setup, scaling, and deployment.  
- **AWS EC2** → Cloud hosting for microservices, RabbitMQ, and Redis.  

---

## 🛠️ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Navneetpatel05/blog-microservice-project-2025.git
cd blog-microservice-project-2025
