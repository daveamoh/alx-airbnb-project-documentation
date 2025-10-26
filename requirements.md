# Airbnb Clone Backend — Requirement Specifications

## 📘 Overview
This document outlines the **technical and functional requirements** for the key backend features of the Airbnb Clone project.  
It covers the design of the **User Authentication**, **Property Management**, and **Booking System** modules — defining APIs, data validation rules, and performance criteria.

---

## 🧩 1. User Authentication Module

### 🎯 Objective
Enable users (guests, hosts, and admins) to securely register, log in, and manage authentication sessions using JSON Web Tokens (JWT).

### 🔑 Functional Requirements
1. Users can register an account with valid credentials.
2. Users can log in and receive an authentication token.
3. Passwords are hashed using a secure algorithm (e.g., bcrypt).
4. Duplicate email registrations are not allowed.
5. Users can retrieve and update their profiles.
6. Sessions expire automatically after a set period.

### ⚙️ API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| `POST` | `/api/auth/register` | Register a new user |
| `POST` | `/api/auth/login` | Log in an existing user |
| `GET` | `/api/users/:id` | Retrieve user details |
| `PUT` | `/api/users/:id` | Update user profile |
| `POST` | `/api/auth/logout` | Log out user session |

### 🧾 Input/Output Specifications

#### **POST /api/auth/register**
**Input:**
```json
{
  "first_name": "John",
  "last_name": "Doe",
  "email": "john@example.com",
  "password": "StrongPass123",
  "role": "guest"
}
