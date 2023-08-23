# Sample Python Okta Login

## Pre-reqs

* Python 3
* Pip
* optional: virtualenv

## Setup
Using virtual env:

1. If you haven't setup the environment: python3 -m venv okta1
2. (Windows) env/Scripts/activate
3. Install dependencies: pip install -r requirements.txt

Setup client_secrets.json file:

1. copy client_secrets.json.dist to client_secrets.json
2. replace domain, client id, secrets, etc

Don't commit the secrets to source control!

## Run

1. python app.py

## References

* https://learnpython.com/blog/python-requirements-file/
* https://developer.okta.com/code/python/#get-started-with-python-flask-okta
* https://learnpython.com/blog/python-requirements-file/