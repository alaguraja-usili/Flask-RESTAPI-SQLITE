# Flask-RESTAPI-SQLITE
Flask-RESTAPI-SQLITE


Inside Visual Sudio    install below

pipenv shell

view --> Command Pallate --> Python select interpretor --> Select virual environnment

inside virtual environment ---> install below software

1. pip install Flask
2. pip install Flask-SQLAlchemy
3. pip install flask-marshmallow
4. pip install marshmallow-sqlalchemy


Open the python terminal in your project directory and manually add a context

>>> from main import app, db
>>> app.app_context().push()
>>> db.create_all()
>>> quit()
