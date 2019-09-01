# JoyWeather

A python app that lets one view and add weathers of cities of choice

#### Date of Current Version (July 8th,2019)
#### By **Joy Wendo**
## Description
This is a Django application which allowsone to add weather for different cities


## Prerequisites
You need the following to work on the project: -
* Python version 3.6 
* Pip 
* venv 
* A text Editor(vscode preferably)
## Setup/Installation Requirements
* To start using this project use the following commands:

```
```bash
$ cd joyweather
$ cd the_weather
```
* create a virtual environment
```bash
$ python3.6 -m venv virtual
```
* navigate into the virtual environment
```bash
$ source virtual/bin/activate
```
* while in the Virtual environment install the dependencies found in the  requirements.txt file
```bash
(virtual)$ pip install -r requirements.txt
```

* migrate the database and create superuser using sqlite
```bash
(virtual)$ python manage.py migrate and python manage.py createsuperuser
```
* make migrations
```bash
(virtual)$ python3.6 manage.py makemigrations
(virtual)$ python3.6 manage.py migrate
```
* to run the project enter this command
```bash
(virtual)$ python manage.py runserver
```
* access the application on this localhost address http://127.0.0.1:8000



## Known Bugs
None known at the moment.
## Technologies Used
* HTML
* CSS
* Python
## License
MIT License
Copyright (c) 2019 Joy Wendo