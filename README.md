# 🛡️ AI Insider Threat Behavioral Intelligence System

> AI-powered cybersecurity platform for detecting insider threats using behavioral analytics, machine learning, and real-time monitoring.

![Status](https://img.shields.io/badge/Status-Active-success)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688)
![React](https://img.shields.io/badge/React-Frontend-61DAFB)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

The Insider Threat Behavioral Intelligence System is an AI-powered cybersecurity platform that detects insider threats by analyzing employee behavioral patterns, login history, device usage, file access, email activity, and web browsing activity.

This project is being developed as part of the Infosys Springboard Virtual Internship.

---
## 🏗️ System Architecture

```text
                User
                  │
                  ▼
          React Frontend (Vite)
                  │
          REST API (Axios)
                  │
                  ▼
          FastAPI Backend
        ┌─────────┼─────────┐
        │         │         │
        ▼         ▼         ▼
 Authentication Employee  Activity
    Module      Module    Monitoring
        │         │         │
        └─────────┼─────────┘
                  ▼
         SQLAlchemy ORM
                  │
                  ▼
           SQLite Database
                  │
                  ▼
      CERT Insider Threat Dataset
                  │
                  ▼
      AI / ML Risk Detection (Future)
```
## 📷 Demo & Screenshots

> 🚧 Screenshots will be added as development progresses.

| Login | Dashboard |
|-------|-----------|
| Coming Soon | Coming Soon |

| Employee Management | Activity Monitoring |
|---------------------|---------------------|
| Coming Soon | Coming Soon |
## ✨ Features

- ✅ **Secure JWT Authentication** – Role-based login and protected API access.
- 👥 **Employee Management** – Add, update, delete, and manage employee records.
- 📊 **Interactive Dashboard** – Centralized overview of employee activities and security insights.
- 📈 **Behavior Monitoring** – Track login history, file access, email usage, device activity, and web browsing behavior.
- 🔐 **Role-Based Access Control (RBAC)** – Separate permissions for administrators and employees.
- 🔄 **RESTful API** – Well-structured FastAPI endpoints for frontend communication.
- 🗄️ **SQLite Database Integration** – Lightweight and efficient data persistence using SQLAlchemy ORM.
- 📂 **CERT Insider Threat Dataset** – Uses the CERT Insider Threat Dataset Release 4.2 for behavioral analysis.
- ⚡ **Modern React Frontend** – Responsive user interface built with React and Vite.
- 🚀 **FastAPI Backend** – High-performance backend with automatic OpenAPI documentation.

## Technology Stack

### Frontend
- React
- Vite
- Axios
- React Router

### Backend
- FastAPI
- SQLAlchemy
- SQLite
- JWT Authentication
- Passlib

### Dataset
- CERT Insider Threat Dataset Release 4.2

---

## Folder Structure

```
backend/
frontend/
datasets/
docs/
```

---

## APIs

### Authentication

- POST /auth/register
- POST /auth/login

### Employees

- GET /employees

### Dashboard

- GET /dashboard

### Activities

- GET /activities

---

## Milestone 1 Status

- Project Initialization
- Backend Setup
- Frontend Setup
- Authentication
- Employee Management
- Dashboard
- Activity APIs
- React Integration
- CERT Dataset Added

Status: Completed

---

## Future Enhancements

- AI Risk Scoring
- Insider Threat Detection
- Behavioral Analytics
- ML Prediction Models
- Real-time Alerts
