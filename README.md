
# Insta
# Description
Insta_Lite is a photo sharing app which allows users to assign filters to photos and share them with followers. ... 
Insta_Liters can sync their photo sharing to other social networks,
so Instagram photos can be posted directly to Facebook, Tumblr, Twitter, Flickr, and Foursquare.. 
Visit the live site on https://eid-insta.herokuapp.com/

# Author
Eid Abdullahi
# Features
As a user of the web application you will be able to:

Sign up and log in
View photos posted by other users
Follow other users
Comment on photos
Edit your profile
Specifications

# Behavior	Input	Output
User visits the app and gets redirected to the login page	User logs in	Directed to the home page where they see posted photos
If user has no account, they click on sign up	User signs up	User is redirected to the log in page
Home page loads	Add comment	Comment posted appears
Homepage loads	Click profile	User's profile appears
Homepage loads	Click upload image icon	User's redirected to a page where they can upload an image
Homepage loads	Click settings icon	A modal appears where one can change their password or logout
Homepage loads	User inputs in the search form and presses enter	Searched results show

# Getting started
Prerequisites
python3.6
virtual environment
pip
Cloning
In your terminal:

  $ git clone https://github.com/EidAbdullahi/eid-instagram/tree/master
  $ cd insta

#Running the Application
Install virtual environment using $ python3.8 -m venv --without-pip virtual

Activate virtual environment using $ source virtual/bin/activate

Download pip in our environment using $ curl https://bootstrap.pypa.io/get-pip.py | python

Install all the dependencies from the requirements.txt file by running python3.6 pip install -r requirements.txt

Create a database and edit the database configurations in settings.py to your own credentials.

Make migrations

  $ python manage.py makemigrations instagram
  $ python manage.py migrate 
To run the application, in your terminal:

  $ python manage.py runserver
Testing the Application
To run the tests for the class file:

  $ python manage.py test instagram
Technologies Used
Python3.8
Django
HTML
Bootstrap
This application is developed using Python3.8, Django, HTML and Bootstrap

# LICENSE AND COPY RIGHT INFO.
MIT License

Copyright (c) 2021 Insta_lite Eid

