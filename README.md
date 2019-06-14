## Catalog Application
This is a catalog app that lists different gear items categorized by sport type. 

#### Implementation
The application allows you to do CRUD operations to the catalog and get json items list using apis.

#### How to build
You can use the Vagrant file included here to build and ran using vagrant or install the required applications from requirements.txt via pip. To populate the app with test data, you will first need to ran database_setup.py to create the tables and database in sqlite. Then ran sports_items.py to populate with content. Lastly, ran application.py to start the server and there are instructions on how to access the site on your browser. Note, to get Google login to work, use localhost instead of 0.0.0.0

#### Requirements
Libraries listed under requirements.txt