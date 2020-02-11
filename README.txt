# SQLProject
This project was designed and implemented using the 2018-2019 NBA Season data from basketball-reference.com. This package consists of documentation, datasets, and SQL code files, in order to develop our database system.


We used the LSU class server to develop our project. First, you will need to connect to the server using a username and password provided by our instructor. Once you have logged into the server, you should create a new directory called SQLProject to hold all the files ($ mkdir SQLProject). Then, add each file in this folder to that directory.

To run a demo of the project, run the SQLTABLES.txt file by typing the command
  mysql --local-infile -ucs4402xx -pzzzzzz cs4402xx < SQLTABLES.txt
into the terminal, zzzzzz is the database server password and xx is the account ID that was given by the instructor. This command only needs to be run once and the tables will be created.
Next, run the SQL queries by typing the command
  mysql --local-infile -ucs4402xx -pzzzzzz cs4402xx < sql_code.txt
with the same information that was given above and you will see the different unique records that were resulted from the written queries.
