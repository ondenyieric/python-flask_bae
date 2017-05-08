#create a directory
$ mkdir Flask

cd Flask

#create your virtual environment in your directory

$ virtualenv  venv

#activate your virtual environment
$ source venv/bin/activate

#define variables to intergrate during development
$ export FLASK_APP="run.py"

#DATABASE
$ mysql -u ----- -p

$ CREATE DATABASE myflaskapp;

$ SHOW DATABASE;

$ USE myflaskapp;

#TABLES

CREATE TABLE users(id INT(11) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100),email VARCHAR(100), username VARCHAR(30),password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);


#flask connector

$ pip install flask-mysqldb

#FORMS
pip install flask-WTF

#PASSWORD

pip install passlib

