# Inventory Management System

This project was developed using Django and it is designed to work as an inventory management system. It includes a user-friendly web interface built with Bootstrap and a REST API created with Django REST Framework, featuring JWT authentication to ensure secure access.


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Screenshots](#screenshots)

---

## Features

- **Inventory Management**: Register, update and delete suppliers, brands, categories, products, inflows and outflows.

- **User and Permission Control**: Using Django's permission system it is possible to create users with different permission levels, resulting in customized views and actions.

- **RESTful API**: API built with Django REST Framework for integrations.

- **JWT Authentication**: The API endpoints have secured access through JSON Web Tokens (JWT).

## Technologies Used

- **Backend**: Django and Django REST Framework.
- **Frontend**: HTML, CSS, Javascript, Bootstrap and Django Template Language.
- **Authentication and Permissions**: JSON Web Tokens (JWT) and Django's default permission and authentication systems.

## Installation
### Prerequisites
- Python 3.8+
- Git
- Virtualenv

### Steps
1. Clone this repository:
    ```bash
    git clone https://github.com/aguiarjv/django-ims
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Apply migrations:
    ```bash
    python manage.py migrate
    ```
6. Create a superuser for admin panel access:
    ```bash
    python manage.py createsuperuser
    ```
7. Run the server:
    ```bash
    python manage.py runserver
    ```
      
## Screenshots

### Login Page
![Login Page](/screenshots/login-screen.png?raw=true "Login Page")



