## Company Blog

This is a basic CRUD application using Python 3.7 and Flask framework.

### Install

If you don't have pipenv installed, please install it through pip.

```
pip install pipenv
```

Use pipenv install command to install all required packages.

```
pipenv install
```

Then start your virtual environement.

```
pipenv shell
```

You can set up your database through the following 3 commmands.

```
flask db init
```

```
flask db migrate
```

```
flask db upgrade
```

Now you have setup your database, you are ready to start the server.

```
pipenv run python app.py
```