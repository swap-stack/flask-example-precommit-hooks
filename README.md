# flask-example-with-precommit

A very simple barebones example of a Flask Application with some pre-commit hooks.

How to run:

Check files with pre-commit hooks
```
git clone https://github.com/swap-stack/flask-example.git
cd flask-example/flaskexample
pip install -r requirements.txt
pre-commit install
pre-commit run -a 
```

Run the Flask App:
```
flask run
```
