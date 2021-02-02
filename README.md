# DjangoProjectBasicCommands
Basic Commands for Develop Django Project

1. Installing Virtualenv 
    
    ```
    pip install virtualenv
    ```
    
2. Create Virtualenv
    ```
    virtualenv (environment name)
    ```
    
3. Activate Environment::**(environment name)\Scripts\activate**  (windows)
4. Deactivate Environment::**venv\Scripts\deactivate.bat** (windows)
5. Install django:: **pip install django**
6. Start Django Project::**django-admin startproject (project name)**
7. Run Django Project::**python manage.py runserver**
8. Create app::**django-admin startapp (app name)**
9. Migrating the Model(Step-1)::**python manage.py makemigrations**
10. Migrating the Model(Step-2)::**python manage.py migrate**
11. Translated into SQL statements::**python manage.py sqlmigrate (migrationfilename)** 
12. Activating Python Shell::**python manage.py shell**
