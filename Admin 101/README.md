# Admin 101
This is a CTF named Admin 101

This CTf is mainly based on Web development. It will cover the basic concept of how webpages works and connect to form a bigger one. This include frontend, API, backend, and database. The database for this project is MongoDB. The reason of using MongoDB is because MongoDB can prevent sql injection which I would not like to cover it in this project. Moreover, this project will need gobuster to search for the rest of the webpages, as we know most of the webpages are hidden by admin to prevent any malicious intention. The CTF will start with a basic templates and you need to figure out the rest of it.

For your information, the database this connected might be closed, feel free to create another new one and connect it through app.py. 
You can easily change the link in app.py > def db_connect() > client = MongoClient("your_link" , server_api=ServerApi('1')
