# she-codes-crowdfunding-api-project-Isabellam123


About this project:
This is a very basic structure for a crowdfunding website built using DRF and the intention is to build upon this using React. 
The concept behind it (yet to be fleshed out) is a crowdfunding website for local Aus documentary and impact film projects. 

This has been deployed to Heroku and Insomnia is currently being used to POST, GET, PUT content on this website.

To GET a pledge list, please find this at; https://she-codes-backend-izzy.herokuapp.com/pledges/
To GET a project list, please find this at; https://she-codes-backend-izzy.herokuapp.com/projects/
To GET a user list, please find this at; https://she-codes-backend-izzy.herokuapp.com/users/

To run this locally:
  cd crowdfunding
  python3 manage.py runserver
  open http://localhost:8000/projects/ for a projects list
  open http://localhost:8000/pledges/ for a pledges list
  open http://localhost:8000/users/ for a user list


These are the dependencies/ requirements.txt
  Django==4.0.2
  djangorestframework==3.13.1
  gunicorn==20.1.0
  dj-database-url==0.5.0
  psycopg2==2.9.3
  whitenoise==5.3.0
  django-cors-headers==3.11.0
