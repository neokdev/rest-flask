# rest-flask
> template for builing a REST API using Python Flask, SQL Alchemy and Marshmallow

## Quick Start Using Pipenv

```bash
# Install environment
$ sudo pip3 install pipenv
$ pipenv shell

# Install dependencies
$ sudo pipenv install flask flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy

# Create DB
$ python3
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhst:5000)
$ python3 app.py
```

## Endpoints
* GET    /product
* GET    /product/:id
* POST   /product
* PUT    /product/:id
* DELETE /product/:id
