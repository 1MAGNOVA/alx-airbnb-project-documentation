# Backend Requirements for ALX-Airbnb Project

This document specifies the technical and functional requirements for the backend features.

---

## 1. User Authentication

### API Endpoints
- **POST /api/v1/auth/register**
  - Registers a new user
- **POST /api/v1/auth/login**
  - Logs in a user and returns an access token
- **GET /api/v1/auth/logout**
  - Logs out the user

### Input/Output
- **Register Input:**  
  ```json
  { "username": "john_doe", "email": "john@example.com", "password": "StrongPass123" }


  Property Management

## 2, Property Management


Endpoints:

POST /properties → add property

GET /properties/{id} → view property

PUT /properties/{id} → update property

DELETE /properties/{id} → delete property


##  3,  Booking System

Endpoints:

POST /bookings → create booking

GET /bookings/{id} → view booking

PUT /bookings/{id}/cancel → cancel booking
