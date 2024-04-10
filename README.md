# django-template

## Starting a django Project
1. create a virtual environment- for this case am calling my env virtual
`python -m venv virtual`
2. create a .gitignore file and hide the virtual environment.
3. activate the environment
`source virtual/bin/activate`
4. Install Django
` python -m pip install django`
5. Create a project inside the virtual environment
`django-admin startproject project_name .` 
6. Test out the project by running this command
`python3 manage.py runserver`
7. Create the app, run the following command:
`python manage.py startapp app_name`
8. Once you’ve created the app, you need to install it in your project, the INSTALLED_APPS list in settings.py.

- From here we keep rolling now:
10. Lets add a route

11. Now we have included the urls but remember our app has no file `app.urls`. We need to create a file urls.py in  our app
`touch app/urls.py`
12. To organize our templates , lets create a templates folder and have all our templates.
13. 



