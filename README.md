# World Cup_database

This is the second project under freecodecamp's Relational Database Certification.

It has 3 files
- worldcup.sql containing the worldcup database
- insert_data.sh for inserting data into the database
- queries.sh for querying the database.

### Description:

worldcup.sql

It contains two tables. A "teams" table listing the names of all teams that participated in the world cup games and a "games" table.
The "games" table contains details of the 2014 and 2018 world cup games and all rounds played upto the finals along with the goals scored. The winners and opponents in this table are denoted as FOREIGN KEYS, both referencing the PRIMARY KEY from the teams table.

insert_data.sh

The second file contains the bash script for inserting data into each of the above tables in PostgreSQL.

queries.sh

This file contains all the queries to get the required statistics from the database.

### Learning Experience:

Through this project I learnt how to do the following:

- Set 2 FOREIGN KEYS and connect two tables using both foreign keys
- Give EXECUTABLE PERMISSIONS to the script file in the bash terminal
- Use 'cat'(concatenate) command in bash to read data from the games file and give its contents as ouput
- Add comments in bash using '#'
- Create a 'while' loop in bash
- Use the IF statements in bash to query and insert values into the tables
- Use 'echo' in bash to print all arguments in the bash terminal
- TRUNCATE tables
- ALTER SEQUENCE of PRIMARY KEY making it restart with 1
- Use advanced PostgreSQL commands such as WHERE, LIKE, SUM, AVG, MAX, ROUND, COUNT, JOINS (INNER & RIGHT), DISTINCT, ORDER BY and UNION to query the database in bash 
- Split terminals to use both PostgreSQL and bash
- Run the bash script and get the desired output


