# parking_lot_system #


#1. Required#

Database：SQL SERVER (Create the db with the ldf and mdf files, which are in the database folder.)

#2. Run the program#

Run the LoginFrame.java, which is the entry of the program. Use the username and password that are already in the db to login.

#3. Structure of the code#

There are four folders of the code(We can focus on the DB, Objects and UI).

In the DB, this is the part to contect the database, which will do the jobs of search, delete and update... Every command that will require the info from database should call the functions in here to access the database.

In the Objects, there are charger, park, sit_infor and users files, which also correspond to four tables in the database. They contain all the functions that each object can use in the program.

In the UI, obviously, these are the design for the whole UI of the program.
