# Employee_Form-
The employee form was developed using the Python Django Web Framework and Bootstrap 4 b using Pycharm ID

This is a simple and fully functional example of CRUD functionality. The frontend is developed using the Bootstrap 4, and backend is on Python Django Web Framework. 

Important:

The main project and the wokring must be parent. Otherwise, the VIEWS file will not wokring, and the URLs. py won't be able to locate the functions created inside the view.py file. 
After installing the Django Framework by the command "pip install django" we must add the Django Package into the project to use the complete libraries of the Django.
The {% csrf_token %} is important to keep form secure from any hacker attempts. Where we use the form method "POST"
The "template" folder is the child of app folder. and this contain all the frontend files such as HTML, CSS ,JS and others

Model.py

model.py file is use to create the columns for the table which will store our data in the database SQL lite3 (by default) 
After creating the models we need to migrate whole file to create the DB. 

Views.py:

This is the main file where we acutally declare all the CRUD operation functioanlity. 

Urls.py:

Urls file is basically the routing file of Django and this file display the page we want the viewer to see.

