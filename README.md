# MatchMaker
This project was done as a group project for Database Management at Whitworth University

This project uses MySQL to find 'matches' among friends who answered a silly survey.  The matches are calculated based on weighted questions, and emails are generated to send to each participant, informing them of their top three matches.

Data was gathered from a google questionnaire, and then uploaded to MySQL. Then, functions written in Python pulled the data in and put them into People and Question classes.  Each person is compared with every other person and their answers to each question are compared to calculate a match score.  The top three matches for each person are compiled and put into an email that describes the three matches, their bios, and three random questions that the pair matched on.
