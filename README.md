🛒 Django REST E-Commerce API

A production-ready E-Commerce RESTful API built with **Django** and **Django REST Framework**.

This project focuses entirely on backend architecture and API development, including authentication, security, payment integration, and API documentation.

---

## 🚀 Live Demo

- 📚 API Documentation: https://dilsahsen.pythonanywhere.com/api/docs/

---

## 🧠 Project Overview

This project implements a complete backend system for an e-commerce platform.

It includes:

- User Authentication (JWT)
- API Key Security Layer
- Product Management
- Category Filtering & Searching
- Cart System
- Order Management
- Coupon System
- Payment Integration (Iyzico Sandbox)
- Global Error Handling
- Logging
- Throttling
- OpenAPI Documentation (drf-spectacular)
- Deployment via PythonAnywhere

---

## 🏗 Tech Stack

- Python
- Django
- Django REST Framework
- SimpleJWT
- drf-spectacular (OpenAPI/Swagger)
- django-filter
- django-cors-headers
- Iyzico Payment API
- PythonAnywhere (Deployment)

---

## 🔐 Authentication

This API uses:

- JWT (Access + Refresh tokens)
- API Key validation
- Permission-based access control

---

## 📦 Core Features

### Products
- Filtering
- Searching
- Ordering
- Pagination
- Product image upload

### Cart
- Add product
- Update quantity
- Delete item
- Clear cart

### Orders
- Create order from cart
- Apply coupon
- Process payment
- Admin status update

### Security
- Throttling
- Custom permission classes
- API Key protection
- Custom global exception handler

---
