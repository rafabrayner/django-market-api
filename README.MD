<h1 align="center">
    <a href="#"> A Django Market REST API </a>
</h1>

<h3 align="center">
    
</h3>


<h4 align="center"> 
	  Status: In progress 🚧
</h4>

<h2>Content</h2>

- [About](#about)
- [How it works](#how-it-works)
  - [Pre-requisites](#pre-requisites)
    - [Install](#install)
    - [How to use](#how-to-use)
- [Tech Stack](#tech-stack)
    - [**Django Market API**  (Python 3.11)](#django-market-api--python-311)


## About

This is a Django REST API for creating, updating, and deleting products from a market database

---


## How it works


### Pre-requisites

Before you begin, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Python 3.11](https://www.python.org)

If you are using Unix System, you can install the Python 3.11 by:
```bash 
$ sudo apt update
# Install the Python 3.11
$ sudo apt install python3.11
```

With Python already installed, you will need to install the ```virtualenv``` python package.
You can install this with the following command:
```bash 
$ python3.11 -m pip install virtualenv
```

In addition, it is good to have an editor to work with the code like [VSCode](https://code.visualstudio.com/) or [PyCharm Community Edition](https://www.jetbrains.com/pycharm/)


#### Install

```bash

# Clone this repository
$ git@github.com:rafabrayner/django-market-api.git

# Access the project folder in your terminal
$ cd django_market_api

# Install the virtual environment
$ python3.11 -m virtualenv venv

# Activate the virtual environment
$ . ./venv/bin/activate

# Install the dependencies
$ pip install -r requirements.txt
```

#### How to use
```bash

# Go to the project root folder
$ cd django_market_api

# Activate the virtual environment
$ . ./venv/bin/activate

# Running the project
$ python manage.py runserver

# The application will start the development server at http://127.0.0.1:8000/
```

---

## Tech Stack

The following tools were used in the construction of the project:

#### **Django Market API**  [(Python 3.11)](https://www.python.org/)

-   **[Django](https://pypi.org/project/Django/)**
-   **[Django REST framework](https://pypi.org/project/djangorestframework/)**

> See the file  [requirements.txt](https://github.com/rafabrayner/django-market-api/requirements.txt)
