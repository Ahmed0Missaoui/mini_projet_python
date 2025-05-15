# Student Management System

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.0-green)](https://spring.io/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.110.0-blue)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/Next.js-14.1.0-blue)](https://nextjs.org/)
[![Angular](https://img.shields.io/badge/Angular-17.0.0-red)](https://angular.io/)

A full-stack student management system with microservices architecture, combining Spring Boot and FastAPI backends with modern frontend frameworks.

## 📋 Features

### Student Features
- 🧑🎓 Student registration & JWT authentication
- 📚 Course enrollment and management
- 🔖 Bookmark system for courses/materials
- 🤖 AI-generated book summaries (Groq LLM)
- 🔍 Advanced book recommendations

### Admin Features
- 📊 Dashboard with real-time statistics
- 🏫 Department management
- 📈 Student performance analytics
- 🛠️ System configuration
- 📦 Bulk data operations

## 🛠️ Tech Stack

| Category       | Technologies                                                                 |
|----------------|------------------------------------------------------------------------------|
| **Frontend**   | Next.js (React), Angular, TypeScript, Tailwind CSS, Chart.js                 |
| **Backend**    | Spring Boot (Java 17), FastAPI (Python 3.11), Groq SDK                      |
| **Databases**  | MongoDB (Student Data), PostgreSQL (Book Recommendations), Redis (Caching) |
| **DevOps**     | Docker, GitHub Actions, Prometheus, Grafana                                  |
| **APIs**       | Swagger/OpenAPI, REST, WebSocket                                             |

## 🚀 Getting Started

### Prerequisites
- Docker 24.0+ & Docker Compose 2.20+
- Node.js 18.x+
- Java 17 JDK
- Python 3.11

### Installation
```bash
# Clone repository
git clone https://github.com/your-repo/student-management-system.git
cd student-management-system

# Set up environment variables
cp .env.example .env

# Build and start containers
docker compose up --build -d


🌐 API Documentation
Spring Boot: http://localhost:8080/swagger-ui.html

FastAPI: http://localhost:8000/docs

🖥️ Frontend Access
Student Portal (Next.js): http://localhost:3000

Admin Dashboard (Angular): http://localhost:4200

