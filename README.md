# Django-School-Management-System

This app is meant to be used by school manager to manage their school records:
student data
staff
results and
finances.

It currently doesn't allow students/staff to login.
Solely, it's expected to be used on a single machine or online for managers only.

# Features Of This Django School Management System Project
    - Academy Management - Manage Session , Terms, Subjects, Classes.
    - Student Management -  Add Student , Bulk Add Student,  Fees Details Check , View Profile.
    - Employee Management - Add Employee, Edit Employee, View Employee.
    - Fees Management -  Add Fees , Delete Fees, Pay fee , Fees Structure , customize fee Structure.
    - Result Management -  Add Result , Edit Result , Manage Result.

# Technology Used in Django School Management System Project
    - We have developed this project using the below technology
    - HTML : Page layout has been designed in HTML
    - CSS : CSS has been used for all the desigining part
    - JavaScript : All the validation task and animations has been developed by JavaScript
    - Python : All the business logic has been implemented in Python
    - SQLite : SQLite database has been used as database for the project
    - Django : Project has been developed over the Django Framework
    - Supported Operating System
    - We can configure this project on following operating system.
    - Windows : This project can easily be configured on windows operating system. For running this project on - - Windows system, you will have to install
    - Python 3.7, PIP, Django.
    - Linux : We can run this project also on all versions of Linux operating systemMac : We can also easily - - - configured this project on Mac operating system.

    username: admin
    password: admin123
```


Run

```python
pip install -r requirements.txt #install required packages
python manage.py migrate # run first migration
python manage.py runserver # run the server
```
Then locate http://172.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin123
```

## Roadmap
To build a fully fledged open source school management.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Coding Standards
```bash
isort .
black .
```

## Test
```base
python manage.py test
```
# Installation Steps :-
    Install Python 3.7
    Install all dependencies cmd -python -m pip install –-user -r requirements.txt
    Finally run cmd - python manage.py runserver
    Admin User Name - admin
    Admin Password - admin123
