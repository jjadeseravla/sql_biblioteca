# SQL Biblioteca Database

The Biblioteca Database


## About
Inserting data and querying data using select to practice some of the concepts from Intro to SQL by answering some questions regarding a dataset from Biblioteca.
Using SQLite for the exercise.


## Setup
To set up SQLite and the Biblioteca database
Go to the SQLite downloads page and get the appropriate binary for your operating system/platform
 Use your operating system’s package manager to install it
Use your operating system’s package manager to extract the contents to a location such as /Users/<username>/Development/Tools/sqlite-tools
Change directory to the location you extracted the zip in
Run the following in your terminal to confirm your installation:
$ sqlite3 test.db
sqlite > create table test(id);
sqlite> .quit
Check that test.db exists in that directory. If it does, you have successfully set up
Remove test.db from the directory
Download biblioteca.sqlite. You will be using this database in the exercise.

## Questions
1.  Who checked out the book 'The Hobbit’?
2.  How many people have not checked out anything?
3.  What books and movies aren't checked out?
4.  Add the book 'The Pragmatic Programmer', and add yourself as a member. Check out 'The Pragmatic Programmer'. Use your query from question 1 to verify that you have checked it out. Also, provide the SQL used to update the database.
5. Who has checked out more that 1 item?
Tip: Research the GROUP BY syntax.


Text file containing the answers to the questions listed above as well as the SQL statements that written to obtain those answers.
