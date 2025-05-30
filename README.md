# MiniBase
## Create Table & Insert into Command:

![This is an image](https://github.com/Kavan510/DBMS-in-CPP/blob/main/Presentation/img1.png)


## Select Command:

![This is an image](https://github.com/Kavan510/DBMS-in-CPP/blob/main/Presentation/img2.png)


## Update Command with Where Clause:

![This is an image](https://github.com/Kavan510/DBMS-in-CPP/blob/main/Presentation/img3.png)


## Delete From Command with Where Clause:

![This is an image](https://github.com/Kavan510/DBMS-in-CPP/blob/main/Presentation/img4.png)


## Help Command & Describe Command:

![This is an image](https://github.com/Kavan510/DBMS-in-CPP/blob/main/Presentation/img5.png)

##


Developed a CLI(Command Line) application named - **`MiniBase`**.

MinBase is a lite clone of a real DataBase Management System.

Users get the result in the same way as they would if the query was executed in a real DataBase Management System.


### Commands MinBase handles - 
- create table
- drop table
- insert into 
- select
- update
- delete from
- describe table
- help

### How MinBase work?

- User types the query in the command-line interface.
- The query which is in string datatype is parsed and stored in a vector of strings called Tokens.
- Then SQL keywords (like create, delete, describe, etc) are handled so that the applications works in case-insensitive mode.
- Then, the Tokens are checked for any kind of errors and if any, corresponding error messages are printed.
- If no errors, then corresponding function calls are made.
- Thus query gets executed and success message is printed accordingly.

### Features of MinBase : 
-  A very lightweight program
-  Is `case-insensitive` but only for keywords in SQL
-  A `Schema File` which is a text file is maintained that contains information of attributes of all the tables.
-  Different text files are created for storing tuples of different tables.
-  Also works fine with `where clause in select, update, delete from`
    
### Assumptions made : 
- Defining primary key while creating table is mandatory, else error will be raised.
    
