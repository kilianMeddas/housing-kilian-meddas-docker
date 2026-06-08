# 🏠 Housing Data API – Flask & PostgreSQL

A containerized backend API built with Flask and PostgreSQL to manage and serve structured housing data.

This project demonstrates **backend engineering, database design, and Dockerized deployment** in a production-like environment.

---

## 🚀 Project Overview

The goal of this project is to build a **scalable backend system** capable of:

- Storing structured housing data
- Managing database migrations
- Exposing a REST API
- Running fully in a Dockerized environment

It simulates a real-world backend service used in data-driven applications.

---

## ⚙️ Features

### 📊 Data Management
- PostgreSQL database integration
- Structured housing dataset storage
- CRUD operations via API

### 🌐 REST API
- `GET /houses` → retrieve all records
- `POST /houses` → insert new data

### 🗄️ Database Migrations
- Flask-Migrate integration
- Automated schema creation
- Version-controlled database structure

### 🐳 DevOps / Containerization
- Dockerized Flask application
- Docker Compose orchestration
- PostgreSQL service container

---

## 🧰 Tech Stack

- Python
- Flask
- PostgreSQL
- Flask-Migrate
- psycopg2
- Docker
- Docker Compose

---

## 🏗 Architecture

```

Client → Flask API → PostgreSQL Database
↓
Docker Compose

````

The system runs as a **multi-container architecture**:

- API service (Flask)
- Database service (PostgreSQL)
- Initialization service (DB setup)

---

## 📡 API Endpoints

### GET /houses
Retrieve all housing records.

### POST /houses
Add a new housing entry.

---

## 🐳 Deployment

The entire system runs using Docker:

```bash
docker-compose up --build
````

This automatically:

* builds the API
* starts PostgreSQL
* initializes database schema

---

## 🎯 What I Learned

* Designing REST APIs with Flask
* Working with relational databases (PostgreSQL)
* Database migrations (Flask-Migrate)
* Containerization with Docker
* Multi-service architecture design
* Backend system structuring

---

## 👨‍💻 Purpose

This project simulates a **production-ready backend service for data storage and retrieval**, similar to systems used in real-world data engineering pipelines.

---

## 📌 Author

* Kilian Meddas

```
