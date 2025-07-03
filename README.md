# API Course Project

This is a simple RESTful API project built using Laravel as part of an API development course.
The project demonstrates the basic principles of creating, reading, updating, and deleting (CRUD) resources through API endpoints.

---

## Technologies Used

- **Laravel Framework**
- **MySQL**
- **PHP**
- **Postman (for API testing)**
- **Sanctum or Passport (optional for authentication if used)**

---

## Features

- **RESTful API endpoints for managing resources (e.g., posts, users, or any entity used in the project)**
- **Supports CRUD operations:**
    - **Create new resource**
    - **Read single or multiple resources**
    - **Update existing resource**
    - **Delete resource**
- **JSON responses with appropriate HTTP status codes**
- **Validation of incoming requests**

---

## Installation and Setup

1. Clone the repository:
```
git clone https://github.com/AbdallahF44/API-Course.git
```
2. Navigate to the project folder:
```
cd API-Course
```
3. Install dependencies:
```
composer install
```
4. Copy the .env file and configure your database settings:
```
cp .env.example .env
```
5. Then edit .env and set your database credentials:
```
DB_DATABASE=your_database_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_password
```
6. Generate the application key:
```
php artisan key:generate
```
7. Run migrations:
```
php artisan migrate
```
8. (Optional) Seed the database if seeders are available:
```
php artisan db:seed
```
9. Start the development server:
```
php artisan serve
```
10. Use Postman or any API client to test the API endpoints:
```
http://localhost:8000/api/...
```

---

## API Endpoints

- *(Customize based on your actual routes)*

– **List all posts** `GET /api/posts`
– **Get a specific post** `GET /api/posts/{id}`
– **Create a new post** `POST /api/posts`
– **Update a post** `PUT /api/posts/{id}`
– **Delete a post** `DELETE /api/posts/{id}`

---

## Notes

- **The project focuses on backend API development with Laravel.**
- **You can add authentication (e.g., Laravel Sanctum) for protected routes if needed.**
- **Validation and error handling are included to ensure API robustness.**

