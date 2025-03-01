LOGIN PAGE

p1
HOME PAGE

p3
PREDICTION PAGE

p7
RESULT PAGE

p9 p10
PAST HISTORY PAGE

p8
************ Database Creation ************

initially to connect the database and program localhost="root" password="********"

CREATE DATABASE................................................... mysql> create database patient;

mysql> use patient; Database changed

CREATE USER TABLE.................................................

mysql> create table USER (id INT AUTO_INCREMENT,name VARCHAR(20),user VARCHAR(20),pass VARCHAR(20),PRIMARY KEY(id));

CREATE PATIENT DATA STORING........................................

mysql> create table data (date DATETIME,id INT AUTO_INCREMENT,username VARCHAR(20), glucose INT,bp INT,weight INT,height INT,age INT,pregnancy INT,predict VARCHAR(15),PRIMARY KEY(id));

SHOW TABLE COMMENT............ mysql> show tables;

TO SEE THE DATA FROM THE TABLE... mysql> select * from data;

TABLE STRUCTURE........ mysql> describe data;
