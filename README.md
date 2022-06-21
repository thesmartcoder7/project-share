# Project Watch

![Project Image](projects/static/projects/images/readme-image.png)

### By: Samuel Martins

## Table of Content

- [Description](#description)
- [Installation Requirement](#usage)
- [Technology Used](#technologies)
- [Licence](#licence)
- [Authors Info](#author-info)

## Description

This is a project developed for other developers to share their work. One can be able to upload their projects and other users get to rate them. With that, developers can get as many eyeballs on their projects as possible. [live site]()

# Note:

This project is by no means complete. Therefore, don't be alarmed when you encounter bugs in any form. Development is ongoing

## Behaviour Driven Development

The user is able to;

- Sign in to the application to start using it

- Upload projects for global sharing

- View projects posted by others

- Rate projects based on design, usability, content

- Search for projects

- View a project's rating including the overall score

- View their profile page

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

These are the things you need to install the software and how to install them

```
virtual enviroment:

$ pipenv shell

or

$ python3 -m venv virtual ( or your selected virtual enviroment name )
```

### 1. Local Repository

- Make sure you have a stable internet to have the ability to clone the repository.
- Type the following command in your terminal to clone this repository

```
git clone https://github.com/thesmartcoder7/project-watch.git

```

If you are using SSH, use the following command

```
git clone git@github.com:thesmartcoder7/project-watch.git
```

When you run the commands successfully, you should have a local version of this repository.

### 2. Online Repository

- Make sure you have a stable internet for forking this repository.
- According to the license, you can fork this project. You need to click on the forking icon and it will be added as one of your repositories

Feel free to fork the project and have fun with it. Happy coding!

### Installing

To get a development env running, you simply need the install all the packages reguired from either a requirements.txt file or a pipfile. First you need to activate your virtual environment

```
$pipenv shell

of

$ source virtualenvname/bin/activate
```

after that, install all the required depencencies

```
$ pipenv install //pretty much takes care of installing all depencies for you
```

Now that all your dependencies are installed, you need to create a local database for your project and run migrations, or use the database that django comes with by default. The Make file has instructions for this.

```
$ make migrate
```

After this, you can run the application using the commands that come in the make file. for this case, it is either of the following:

```
$ make

or

$ make run

or

$ python manage.py runserver

```

## Running the tests

If you want to run tests for the entire project, you need only run this command:

```
$ make test

or

$ python manage.py test
```

## API Endpoints

User Profiles:

```
https://project-re-views.herokuapp.com/api/profiles
```

All Projects:

```
https://project-re-views.herokuapp.com/api/projects
```

## Technologies

- HTML5
- SCSS
- JavaScript
- Django
- Postgres

## Licence

Copyright (c) Samuel Martins - [MIT Licence](LICENSE)

## Author Info

- Twitter - [@thesmartcoder7](https://twitter.com/thesmartcoder7)
- Linkedin - [Samuel Martins](https://www.linkedin.com/in/samuel-martins-09839b115/)
- Website - [Samuel Martins](https://smart-code.dev)
- blog - [Samuel Martins](https://samuel-martins.medium.com/)
