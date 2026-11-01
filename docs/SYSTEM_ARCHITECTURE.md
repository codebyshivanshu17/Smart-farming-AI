# System Architecture – Smart Farming AI

## 1. Introduction

Smart Farming AI follows a simple layered architecture. Each part of the application has a different responsibility, making the system easier to develop and manage.

## 2. Main Components

### 1. Frontend Layer
- Provides the user interface.
- Allows users to enter farming details.
- Displays recommendations and results.

### 2. Controller Layer
- Handles user requests.
- Connects the frontend with backend services.

### 3. Service Layer
- Contains the main application logic.
- Processes farming information.
- Generates recommendations.

### 4. Repository Layer
- Handles database operations.
- Saves and retrieves application data.

### 5. Database Layer
- Stores user details.
- Maintains soil information and farming records.

### 6. AI/ML Layer
- Helps generate crop recommendations.
- Supports fertilizer suggestions and plant disease detection through integrated models.

## 3. Working of the System

1. The user opens the application and logs in.
2. The user enters soil or farming details.
3. The frontend sends the information to the backend.
4. Spring Boot processes the request.
5. The required data is stored or retrieved from MySQL.
6. The recommendation module processes the information.
7. The result is displayed to the user.

## 4. Conclusion

The system architecture separates the frontend, backend, database, and AI modules. This makes the application easier to understand, maintain, and improve in the future.