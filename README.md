## Catalog Application
This is a catalog app that lists different gear items categorized by sport type. 

#### Implementation
The application allows you to do CRUD operations to the catalog and get json items list using apis.

#### How to build
You can install the required applications from requirements.txt via pip. It is best to do this using a virtual environment.

0. Clone project from this github location and save the code in a folder. eg proj/folder
1. Install virtualenv
2. Go to project folder and create a virtual environment.
	> cd proj/folder
	> virtualenv venv 
	> source venv/Scripts/activate (Windows)
	> pip install -r requirements.txt
	> pip list to confirm
3. To populate the app with test data, you will first need to ran database_setup.py to create the tables and database in sqlite. 
	> python database_setup.py
4. Then ran sports_items.py to populate with content. 
	> python sports_items.py
5. Lastly, ran application.py to start the server and there are instructions on how to access the site on your browser. 
	> python application.py
6. Note, to get Google login to work, use 'localhost' instead of '0.0.0.0' as the instruction says.
	> To access the application, in your browser, go to http://localhost:8000/

#### Requirements
Libraries listed under requirements.txt The main ones are Flask (Application), SQLAlchemy(Database), oauth2client(Google Authentication) and requests (APIs), the rest are dependencies for those libraries. Below is a full list of requirements from pip list.

Package         Version
--------------- --------
certifi         2019.3.9
chardet         3.0.4
Click           7.0
Flask           1.0.3
httplib2        0.12.3
idna            2.8
itsdangerous    1.1.0
Jinja2          2.10.1
MarkupSafe      1.1.1
oauth2client    4.1.3
pip             19.1.1
psycopg2-binary 2.8.2
pyasn1          0.4.5
pyasn1-modules  0.2.5
requests        2.22.0
rsa             4.0
setuptools      41.0.1
six             1.12.0
SQLAlchemy      1.3.4
urllib3         1.25.3
Werkzeug        0.15.4
wheel           0.33.4

