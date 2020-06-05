# INSTA-APP

## Description
- This is a clone of Instagram where users can users can sign up, login, view and post photos.Users can also search and follow other users.

## Features
As a user you will be able to:

- Sign in to the application to start using.
- Upload a pictures to the application.
- Search for different users using their usernames.
- See your profile with all your pictures.
- Follow other users and see their pictures on my timeline.

## BDD
| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| User visits the app and gets redirected to the login page  | User logs in | Directed to the home page where they see posted photos | 
If user has no account, they click on `sign up` | User signs up | User is redirected to the log in page |
|  Home page loads | Add comment  | Comment posted appears |
|  Homepage loads | Click `profile` | User's profile appears | 
| Homepage loads | Click `upload image` icon | User's redirected to a page where they can upload an image |  
| Homepage loads | User inputs in the search form and presses enter | Searched results show |
| A list of users displays | Click `follow` button to follow | Reloaded to the homepage|

## Technology used
1. python
2. Django
3. Bootstrap

## Running the Application
- Install virtual environment using `$ python3.7 -m venv --without-pip virtual`
- Activate virtual environment using `$ source virtual/bin/activate`
- Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
- Install all the dependencies from the requirements.txt file by running `python3.6 pip install -r requirements.txt`
- Create a database and edit the database configurations in `settings.py` to your own credentials.
- Make migrations

        $ python manage.py makemigrations instagram
        $ python3.7 manage.py migrate 

- To run the application, in your terminal:

        $ python3.7 manage.py runserver

## Testing the Application
- To run the tests for the class file:

        $ python3.7 manage.py test photos

## Known Bugs
- the search button is not functioning       

## Contacts
- For more informations or questions:
   sheilaegeidza@gmail.com
    
## License
- This project is Licensed under MIT. ©2019 Copyright.



