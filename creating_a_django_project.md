# Creating a Django Project

1. Activate your Django virtual environment.
2. Navigate to where you want the project to be saved.
3. Create a new Django project.
4. Navigate into the newly-created project directory.
5. Create a new Django app.
6. Add your newly-created app to the `INSTALLED_APPS` list in *settings.py*.
7. In the **project** directory, open *urls.py* in VS Code.
    1. Add an import for the include function.
    2. Add a path from the root route to your app-level *urls.py* file in the `urlpatterns` list.
8. In the **app** directory, open *urls.py* in VS Code.
    1. Import the path function from django.urls.
    2. Import views from the current directory.
    3. Create a new `urlpatterns` list.
    4. Add a path from the root route to a function in your *views.py* file.
9. Open *views.py* in VS Code to create that function.
    1. Import the render function from django.shortcuts.
    2. Create the function you named in step 8.4 and return a render of a template.
10. Create the template you named in step 9.2. It needs to be in a folder called templates in the **app** directory.