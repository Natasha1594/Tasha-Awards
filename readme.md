Tasha Awardss

## Description
The application will allows a user to post a project he/she has created and get it reviewed by his/her peers.

As a user of the web application you will be able to:

1. Sign up and log in
2. View projects posted by other users
3. Post projects
4. Rate a project
5. Edit your profile
6. Generate APIs
7. Review a project


* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.6 manage.py runserver`
* Access the live site using the local host provided



## Getting started

### Prerequisites
* python3.6
* virtual environment
* pip

#### Create and activate the virtual environment
```bash
python3 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```

#
#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash

python manage.py makemigrations projects
python manage.py migrate
```

#### Run the app
```bash
python manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)



## Testing the Application
`python manage.py test insta`
        
## Built With

* [Python3.6](https://docs.python.org/3/)
* Django 3.1
* Postgresql 
* Boostrap
* HTML
* CSS

