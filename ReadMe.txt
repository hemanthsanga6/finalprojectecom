Hello Welcome!!!

STEP 1: Create and Activate the Environment
	1.python3 -m venv /path/to/new/virtual/environment
	Go to the final project directory
	2.virtualenv env	
        3.cd env       (click enter)
        4.Scripts/activate
        5.cd..                (click enter)
        6.cd finalproject                (click enter)
        

STEP 2: Install the the required software
        1.py -m pip install -r requirements.txt         (click enter)

        (NOTE: better to use Python 3.8.0  to 3.9.0 versions)

Step 3: Enert the Project folder
        1. cd finalproject                 (click enter)

Step 4:Run the server
        1. python manage.py runserver   (click enter)
	
	Once the server is up and running visit http://127.0.0.1:8000/
        It is a simple e commerce website created using django framework
        We can view the products add them to cart and store the orders in a database
        http://127.0.0.1:8000/admin will open the admin panel where we can view and access the database 
