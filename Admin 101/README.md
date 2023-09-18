# Admin 101
This is a CTF named Admin 101

This CTf is mainly based on Web development. It will cover the basic concept of how webpages works and connect to form a bigger one. This include frontend, API, backend, and database. The database for this project is MongoDB. The reason of using MongoDB is because MongoDB can prevent sql injection which I would not like to cover it in this project. Moreover, this project will need gobuster to search for the rest of the webpages, as we know most of the webpages are hidden by admin to prevent any malicious intention. The CTF will start with a basic templates and you need to figure out the rest of it.

Files and folders for this project:
- Flag - This folder will cover how to capture the flag for this project
- static - This folder contain all static files useb by this project such as pictures, css design for webpages, and text files
- templates - This folder contain all the webpages for this project
- app.py - This is the backend server for this project using flask
- requirement.txt - This will inform you the basic requirement you need to run this project
- README.md - This contain the metadata of this project

For your information, the database this connected might be closed, feel free to create another new one and connect it through app.py. 
You can easily change the link in app.py > def db_connect() > client = MongoClient("your_link" , server_api=ServerApi('1')


##PREVIEW OF ADMIN 101##
![login](https://github.com/717U5/CTF/assets/145121989/3bc5ff3a-c799-4e74-8b4d-87f54c00863c)


![start](https://github.com/717U5/CTF/assets/145121989/e46b96cd-c0aa-473c-8fac-4be89af5f626)
