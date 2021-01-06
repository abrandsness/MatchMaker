# MatchMaker (My Contributions Below)
This is a group project for Database Management at Whitworth University

Data was gathered from a google questionnaire, and then uploaded to MySQL. Then, functions written in Python pulled the data in and put them into People and Question classes.  Each person is compared with every other person and their answers to each question are compared to calculate a match score.  The top three matches for each person are compiled and put into an email that describes the three matches, their bios, and three random questions that the pair matched on.

The questions and answers for this survey are silly, and are not meant to produce any meaningful matches, but just to demonstrate the use of MySQL and embedded SQL.

# Andrea Brandsness' Contributions:
I uploaded all the Excel data into the DBMS (MySQL) and created scripts to share this with teammates and professors.  
I wrote embedded SQL functions in Python to pull data out of MySQL as needed, then to put that data into corresponding data structures.  
I wrote the algorithms to create all instances of people and question objects.  
I also wrote the algorithms that compared each person to each other to calculate matches amongst those people, store their matched points, as well as the questions that they matched on.
I wrote the algorithm that generated an email text for any given person who had their matches calculated.
Lastly, I troubleshooted the send email function.
