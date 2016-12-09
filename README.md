# Heroku - Flask (Python 3) Sample
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Deployment Setup
* 'virtualenv venv'
* 'source venv/bin/activate'
* 'pip install -r requirements.txt'

## Procfile
This file is not necessary. Heroku automatically detects the project language and starts a proper web server. But in this project, we use gunicorn.

## Runtime.txt
Heroku supports Python 2.7.12 (default) and Python 3.5.2. If you want to specify version of Python, you have to create runtime.txt file.