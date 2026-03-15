# AI Certs Internship Assignment

## Project Overview

This project is a **Django REST API** developed for the AI Certs Internship Assignment.
The system manages **Vendors, Products, Courses, Certifications**, and their relationships using REST APIs.

The APIs allow creating, retrieving, updating, and deleting records, along with managing mappings between entities.

---

## Technologies Used

* Python
* Django
* Django REST Framework
* Swagger (drf-yasg) for API documentation
* SQLite Database

---

## Modules Implemented

The project includes the following modules:

* Vendor
* Product
* Course
* Certification
* Vendor Product Mapping
* Product Course Mapping
* Course Certification Mapping

---

## API Features

Each module supports full **CRUD operations**:

* Create
* Read
* Update
* Delete

These operations are implemented using **Django REST Framework ViewSets**.

---

## API Documentation

Swagger documentation is available to test all APIs.

Swagger URL:

http://127.0.0.1:8000/swagger/

---

## Project Structure

```
ai_certs_project
│
├── certification
├── course
├── course_certification_mapping
├── product
├── product_course_mapping
├── vendor
├── vendor_product_mapping
│
├── screenshots
│   ├── swagger_home.png
│   ├── vendors.png
│   ├── products.png
│   ├── courses.png
│   ├── certifications.png
│   └── mappings.png
│
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

---

## Installation Steps

### 1. Clone the repository

```
git clone <repository-url>
```

### 2. Navigate to the project folder

```
cd ai_certs_project
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run database migrations

```
python manage.py migrate
```

### 5. Start the server

```
python manage.py runserver
```

---

## Access Swagger API

After running the server, open:

http://127.0.0.1:8000/swagger/

---

## Screenshots

Swagger API screenshots are included in the **screenshots** folder to demonstrate API functionality.

---

## Author

Shivpal Rathod
