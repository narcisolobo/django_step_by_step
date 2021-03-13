# Creating a Django Project

## Objectives:
- Practice the steps for creating a Django project with a single app
- Familiarize ourselves with the role of each file

---

So we've talked about modularization and MTV (and MVC), but what does that really mean? Let's go ahead and build a Django project, and then we'll review the folder structure to really see what modularization is all about.

Remember that a single application in Django (in our case, every assignment) is called a project, which contains one or more apps.

1. With our Django virtual environment activated, create a new Django project. First navigate to where you want the project to be saved (for these first few assignments, that will be the *python_stack/django/django_intro folder*). Then run this command, specifying a project name of our choosing:

`> cd python_stack/django/django_intro`\
`django_intro> django-admin startproject your_project_name_here`

- Let's test this out. Navigate into the folder that was just created. A new Django project has just been created--let's run it!

`django_intro> cd your_project_name_here`\
`your_project_name_here> python manage.py runserver`

Open `localhost:8000` in a browser window. Hooray for CLIs (command-line interfaces)!

(Don't worry about the warning about unapplied migrations. It won't affect us for now, and we'll address it soon enough.)

Press `ctrl-c` to stop the server. Open up the project folder in your text editor. (Take note of the folder structure so far!) We'll be updating some of these files shortly.

2. For every app we want to add to our project, we'll do the following:
    1. `your_project_name_here> python manage.py startapp your_app_name_here`\
    **The apps in a project CANNOT have the same name as the project.**
    2. In the text editor, find the `settings.py` file. It should be in a folder with the same name as our project. Find the variable *INSTALLED_APPS*, and let's add our newly created app:
    
    **your_project_name_here/your_project_name_here/settings.py**
