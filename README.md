# MonitorWatcher

> System monitoring and alerting with PagerDuty integration

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Go, Cron, PostgreSQL, Docker

## 🏗️ Architecture
Backend service with Go, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/monitorwatcher
cd monitorwatcher

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
