# Comprehensive-SQL-Project-for-CSIS1550

PROJECT
REQUIREMENTS
Part 1 (20% of the project grade)
• E-R diagram that shows how these five tables should be related identifying the correct
relationships (one-to-one, one-to-many, many-to-many) along with identifying the primary key
and foreign key in each relationship.
NOTE: Draw and submit a clear ER Diagram USING LUCID CHART
(https://www.lucidchart.com/) if you like you an use a TEMPLATE .Or Submit a clear snapshot if
you are hand drawing the E-R diagram (please draw it neatly using a ruler).
Part 2 (40% of the project grade)
• Create the MOVIES Database and tables using the provided MovieDatabaseTableData.txt
file (need to edit that to create the database and tables) and import it to the server. Take a
screenshot for submission.
NOTE: The .txt file you can also save it as .sql file for submission.
• For each table, complete the table definition including the table name, field names with data
type, primary key identification. Write the statements consistent with the MySQL syntax of
creating a table with the necessary field definition.
• Create a MySQL log file with the name lastname_firstname_MovieDBTables.txt that contains all
the required table definitions AND a record of LOADING THE DATA into ALL THE TABLES.
Submit the completed log file and screenshot using the Assignment (Comprehensive Programming
Project) tool in Canvas (You can create a zip file to submit all the files together).
NOTE: In order to decide the appropriate data types, review the file
MovieDatabaseTableData.txt which is also attached in this Module.
This is a critical part of the project because the accuracy of your query solutions will depend on the
accuracy of your data definition. The raw data provided will not load correctly if your table properties
are not defined correctly.
Part 3 (40% of the project grade)
Write MySQL query statements for the questions below including the output that proves the accuracy of
your solution. Your questions and answers should be stored in a text file that captures your interaction
with MySQL. Be sure to include the question numbers alone with the questions so that I can identify
which question you are answering. BE SURE TO EDIT OUT SQL ERROR MESSAGES.
NOTE: Create a log file of your work with the name lastname_firstname_MovieDBQueries.txt that
contains the MySQL codes and the output for each question (be sure to include the question number
using MysQL commenting technique). Submit the completed log file using the Assignment
(ComprehensiveProgrammingProject) tool in Canvas.
1. Find the movieID, title, year and DVDPrice of all movies where the DVD-Price is equal
to the discountPrice.
2. Find the actorID, lastName, firstName, middleName, and suffix of all actors whose
middleName is not NULL.
3. Suppose you remember a movie quote as “Play it again, Sam.” However, when you write a query
to find this quote, you get no results. Write a query that will find the text of all movie quotes that
begin with the word “Play.”
4. Suppose you remember the role of Joker in one of the Batman movies, but when you write a
query to find this role, you get no results. Write a query that will find the roleID and roleName
of any role where Joker appears as part of the role name.
5. Find the movieID, title, year, and totalNoms of all movies that were nominated for more than
five Awards and were released before 1950.
6. Find the movieID, title, year, and awardsWon of all movies that either won more than five
Awards or were released after 1990.
7. Find the movieID, title, year, and discountPrice of all movies with discount prices between
$15.00 and $20.00 inclusive.
8. Find the movieID, title, and year of all movies, along with the difference between totalNoms
and awardsWon. For the column heading of the calculated column, use “nominated but not
won.”
9. Suppose you have a special membership at a store that qualifies you for 10% off all of your
purchases, including discount prices. Find the movieID, title, and year of all movies, along with
the discount price minus 10% of the discount price. For the column heading of the calculated
column, use “my price.”
10. Find the gender and the count (of all rows of that gender) in the Actor table, grouped by gender.
11. Find the totalNoms and the maximum number of awardsWon in the Movie table,
grouped by totalNoms and ordered by the maximum number of awardsWon.
12. Find the company, year, and sum of awardsWon for movies, grouped by company and year.
13. Find the actorID, lastName, firstName, middleName,suffix, and birthdate of rows in the Actor
table where the gender is F. Order the results by the actor’s date of birth.
14. Find the movieID, title, year, DVDPrice, and half of the DVDPrice (the price for a half-off
sale) of movies that have a DVDPrice of at least $20.00.
15. 
