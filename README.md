LOGIN PAGE
<img width="960" alt="262432786-a1307f1b-cdcd-4bb0-ace2-6f8ecbb5293b" src="https://github.com/user-attachments/assets/8a792d77-76c1-4b72-bbea-d2d76ab97c16" />

p1
HOME PAGE
<img width="959" alt="262432352-48068e0f-0690-45b0-835d-bce93286c9b2" src="https://github.com/user-attachments/assets/f36bae2f-bfa3-4110-bab3-ca7c385d42f5" />

p3
PREDICTION PAGE
<img width="959" alt="262432639-098fc02e-c7b8-45c2-b55c-610eaf925142" src="https://github.com/user-attachments/assets/3def1a2b-ecf1-462a-9388-a53bbcdfa48b" />

p7
RESULT PAGE
<img width="960" alt="262432920-5a1c3612-89e0-4122-99e1-e679b7731623" src="https://github.com/user-attachments/assets/0a02de61-6e28-422f-ace3-909c0f7cdf0f" />
<img width="960" alt="262433009-fa0dd5ce-ca60-4146-b547-bd85ff667138" src="https://github.com/user-attachments/assets/4571170a-aafc-45c3-b98e-eefc9f54c6cf" />



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
