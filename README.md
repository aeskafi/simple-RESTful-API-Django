# simple-RESTful-API-Django
A simple experience about RESTful API with Django.

If you want to have an experience on RESTful API with Django. This is a full guide for you.First you need to know, I did this project using a youtube video on <a href="https://www.youtube.com/watch?v=BSHRftLtPEg" target="_blank">this link</a>. Also, you can follow steps here and use the code in the repository.

# Start from here
<ol>
  <li>Download python from www.python.org</li>
  <li>Download Django web framework from www.djangoproject.com, or using pip (Python built-in package installer).</li>
  <li>Create the virtual environment using Terminal: $ python3 -m venv [name]</li>
  <li>Goninto the virtual environment using Terminal: $ source [name]/bin/activate</li>
  <li>Install Django using Terminal: $ pip install django</li>
  <li>Create a project using Terminal: $ django-admin startproject [name]</li>
  <li>Go into the folder using Terminal: $ cd [project-name]</li>
  <li>Run django using Terminal: $ python manage.py runserver</li>
  <li>Create an app in teh project folder using Terminal: $ django-admin startapp [name]</li>
  <li>Go to python_api/python_api/setting.py, add the app-name in INSTALLED_APPS. (e.g. 'myapp')</li>
  <li>In python_api/myapp/models.py add our model. you can copy from this repo.</li>
  <li>Convert the model that you made, into a SQL table using Terminal: $ python manage.py makemigrations</li>
  <li>Do the same convertation for the app too, using Terminal: $ python manage.py makemigrations myapp</li>
  <li>Finish the previous step by run this command on terminal: $ python manage.py migrate</li>
  <li>In python_api/python_api/urls.py add our api urls. you can copy from this repo.</li>
  <li>In python_api/myapp/views.py add our logic API and codes. you can copy from this repo.</li>
  <li>Now, you can test your APIs, just don't forget to run this command before testing: $ python manage.py runserver</li>
</ol>

# Notes
<ul>
  <li>At the end you will have two folder. the folder that hold our projects code titled as the name that choose for the project, and a folder as virtual environment to hold all of dependencies.</li>
  <li>The project name in this repo is python_api</li>
  <li>The app name in this repo is myapp</li>
</ul>

