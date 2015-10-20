\#nofilter [![Build Status](https://travis-ci.org/7091lapS/instagram-challenge.svg?branch=master)](https://travis-ci.org/7091lapS/instagram-challenge)
===================

This is an instagram clone I made for one of the weekend challenges at Makers Academy. Bulding this project hugely improved my understanding of Rails, MVC, relational databases associations and AWS.
The project was built using BDD.

The website is hosted [here](https://instagram-clone7091.herokuapp.com)
Functionalities
-----
The website has some of the functionalities of the early versions of Instagram:
- Users can sign up, view and upload photos to the photo stream
- Users can comment photos
- Users can like photos

Technologies
-----
- Rspec/Capybara, FactoryGirl, and Poltergeist to test drive the project
- ImageMagick for photo uploads
- Ruby on Rails to build MVC
- PostgreSQL database with ActiveRecord
- Amazon Web Services S3 for photo hosting
- Javascript/JQuery to update likes without having to refresh pages
- Foundation for styling
- Heroku for cloud deployment

Installation
-----
Make sure you have ImageMagick and PostgreSQL installed locally. You also need Poltergeist to run the javascript tests.
```
git clone https://github.com/7091lapS/instagram-challenge/
#cd to directory
bundle install
#to run the server
rails s
#to run the tests
rspec
```
To implement in future versions
-----
- Facebook sing-in
- Edit and delete photos
- Add a route to see all photos by one user
