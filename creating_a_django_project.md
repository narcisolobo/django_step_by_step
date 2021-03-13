# Creating a Django Project

## Objectives:
- Practice the steps for creating a Django project with a single app
- Familiarize ourselves with the role of each file

---

So we've talked about modularization and MTV (and MVC), but what does that really mean? Let's go ahead and build a Django project, and then we'll review the folder structure to really see what modularization is all about.

Remember that a single application in Django (in our case, every assignment) is called a project, which contains one or more apps.

1. With our Django virtual environment activated, create a new Django project. First navigate to where you want the project to be saved (for these first few assignments, that will be the *python_stack/django/django_intro folder*). Then run this command, specifying a project name of our choosing:

`> cd python_stack/django/django_intro`\
`django_intro> django-admin startproject your_project_name_here`\

- Let's test this out:
- Navigate into the folder that was just created. A new Django project has just been created--let's run it!

`django_intro> cd your_project_name_here`\
`your_project_name_here> python manage.py runserver`\

