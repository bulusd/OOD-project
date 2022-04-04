# Group-5 OOPD Project
## Summary
Group 5's work for the OOPD term project assignment.

## Dependancies
Requires:
- **Python**
    - Requires the following not-included *Python* modules:
        ```mysql-connector-python
        Pillow
        customtkinter
        ``` 
    - **SQL-based database**

## Setup
Create a database called __GYM_DATABASE__.  Configure user credentials for the Python script to use, then import the database information into a file called ```db.creds```.  The file's contents should be as follows:
```
Host_IP=<address of the database server>
Host_Port=<listening port of the database server>
Account_Username=<username of the account for using the database>
Account_Password=<password of the above user>
Database_Name=<name of the database>
Table_Name=<name of the table>
```

Once the database is all set up and the file is created, then you should be good to go! :)
