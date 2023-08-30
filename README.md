# Flask_Auth_App
How to add authentication to your app with flask-login

# In a terminal, you can set the FLASK_APP and FLASK_DEBUG values:

# Linux :

export FLASK_APP=project
export FLASK_DEBUG=1

# Windows :

set FLASK_APP=project
set FLASK_DEBUG=1

#To Initialize db 

#If using the Python interpreter is new to you, you can consult the official documentation.
 
from project import db, create_app, models
db.create_all(app=create_app()) # pass the create_app result so Flask-SQLAlchemy gets the configuration.