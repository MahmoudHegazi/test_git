# fuck gitHUb

# Coffee Shop Full Stack

### Udacity Project (Advanced Track)
!['udacity logo'](https://github.com/MahmoudHegazi/your_library_api/blob/main/download.png?raw=true)


# Introduction:

* Flask API and ionic app, following pep8 style guide, the API perfom CRUD actions , Add, Delete , read, update drinks, the app has 2 roles Mangers and Barista
* using auth0 to add layer of secuirty users can signup using Google, Facebook, Linkedin, GitHub


## how to set up the local development for FLASK API

http:localhost:5000

* ``` cd backend ```
* ``` source env/Scripts/activate```
* ```pip install -r requirements.txt```
* ```cd src```
* ```export FLASK_APP=api.py```
* ```export FLASK_ENV=development```
* ```flask run --reload```


## how to set up the local development for Ionic app

http:localhost:8100

* ``` cd frontend ```
* you have to install node.js and install ionic
* ```npm install```
* ```ionic serve```


# Errors:
* Your Library API May return 4 types of errors [404, 422, 400, 401]

# API endpoints

# GET Drinks (public)
localhost:5000/drinks
* public endpoint return the drinks menu without recipe information

# GET Drinks-detail (get:drinks-detail)
localhost:5000/drinks-detail

* endpoint return the drinks menu include recipe information used by Barista users


# PATCH Drinks (patch:drinks)
localhost:5000/drinks

* endpoint used by Manger users to edit existing drinks

# POST Drinks (post:drinks)
localhost:5000/drinks

* endpoint used by Manger users to add new drinks, it not allow duplicated drinks title

# DELETE Drinks (delete:drinks)
localhost:5000/drinks

* endpoint used by Manger users to delete existing drinks 


# POSTMAN tests 

* 20 valid test used to make sure the API run without any problems and the premssions applied


# thanks

1. udacity.com
2. stackoverflow.com
3. auth0.com

# Author

Mahmoud Hegazi (Python King)
