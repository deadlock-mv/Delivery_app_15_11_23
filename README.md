# Delivery_app_15_11_23
This app has the features of maintaining or managing restarunt orders and deliveries with two roles namely user and a manager.

Setup Prerequisites - Python 3.11, node 18, Mysql engine

Clone the repo using git options in VS Studio or git command - $ git clone https://github.com/deadlock-mv/Delivery_app_15_11_23/new/main?readme=1

Setting the Backend - 
  1. Create virtual env using - $ python3 -m venv <virtual_env_name>
  2. Activate the venv using - $ source <virtual_env_name>/bin/activate
  3. Open the terminal in the FDMS directory and run the command to install requirements using - $ pip install -r requirements.txt
  4. Creating a database for use -
     I. Open the Mysql Workbench and create an instance with specified database settings from 'settings.py' file
     II. Create a database named FDMS2.
  6. We need to migrate the models into the database, we do it using - $ python3 manage.py migrate
  7. Run the server in the same directory using - $ python3 manage.py runserver
    
Setting the Frontend -
  1. Open the terminal in Frontend directory and run the command to install packages using - $ npm i
  2. Run the server in the same directory using - $ npm start
  
