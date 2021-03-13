# Creating a new Django Virtal Environment

Let's create a new virtual environment for our Django projects. We'll need to do this just once. Create and navigate to a folder named *my_environments* and run the appropriate commands to create a virtual environment and then install Django:

Create your environment:
`
Mac/Linux: | python3 -m venv djangoPy3Env
Windows (command prompt): | python -m venv djangoPy3Env
`

Activate your environment:



1. Activate your Django virtual environment (use your preferred method, or follow these steps).
    1. Change directory (cd) into your environments directory.
    2. Once there, activate your Django virtual environment:
        - Mac/Linux: source py3Env/bin/activate
        - Windows: call py3Env\Scripts\activate
        
cd to your desired directory.
django-admin startproject <project_name>.
cd <project_name>.
python manage.py startapp <app_name>.