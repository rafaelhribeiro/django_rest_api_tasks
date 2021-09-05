# REST API Tasks

Back-end code for the the Tasks API.

## Requirements

* Python 3.6+
* Django 4+
* Django REST Framework 3.13+

## Install dependencies

You can install all the required dependencies by running

    python3 -m pip install -r requirements.txt

## Structure

| Endpoint      | Method  |  Result             |
|---------------|---------|---------------------|
| `/tasks`      |   GET   | List all tasks      |
| `/tasks`      | POST    | Create a new task   |
| `/tasks/:id`  | PUT     | Update a task `:id` |
| `/tasks/:id`  | DELETE  | Delete a task `:id` |


## Use

First, we have to start up Django's development server.

    python manage.py runserver

