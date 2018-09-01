# PyTraffic

PyTraffic is a simple Flask traffic monitoring application.

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project to a live system.

## Prerequisites:

You need to have the following software installed to run this project

+ Python (>= v3.x)
+ virtualenv
+ Flask

Let's start by cloning the repository:
```
$ git clone https://github.com/scopeweb/pytraffic
```

Go into the pytraffic directory:
```
cd pytraffic
```

## Installation:

Start off by install virtualenv:
```
$ pip install virtualenv
```

Activate the virtual environment:
```
$ python3 virtualenv .venv
$ source .venv/bin/activate # Linux Based Systems
$ \path\to\env\Scripts\activate # Windows users

```

Now that we have the virtual environment setup, we can install Flask within it:
```
$ pip install flask
```

We also need to install the httpagentparser:
```
$ pip install httpagentparser
```

Install Pusher python library:
```
$ pip install pusher
```

## Next steps:

You'll need to have a Pusher account to be able to run this application. You can create a free account [here](https://pusher.com/)

Replace the PUSHER_APP_* keys with the values on your Pusher dashboard.

The files you want to change these in are `app.py` and `static/js/app.js`

After changing the PUSHER_APP_* keys, you can run the application:
```
$ flask run
```

Now visit [localhost](http://127.0.0.1:5000) to see the website and visit the [dashboard](http://127.0.0.1:5000/dashboard) to see the traffic monitor dashboard.

## Issues

Feel free to make a PR to make improvements or file an issue.