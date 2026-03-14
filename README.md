# HR & Payroll Management System - Backend (Django SaaS MVP)

## Overview
This is the backend for a **HR & Payroll Management System** built with Django. It centralizes employee management, payroll validation, leave requests, and reporting in a structured and maintainable architecture.

## Features
- REST API endpoints for employee management and payroll
- Generate PDF payslips
- Approve leave requests
- Monitor payroll and employee status
- Secure authentication and authorization
- Optimized database schema for performance

## Technology Stack
- Python 3.x
- Django
- Django REST Framework
- PostgreSQL (or MySQL)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/DanielMbe/hr-payroll-backend.git
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
