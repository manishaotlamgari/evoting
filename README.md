# EVOTING
A simple project demonstrating eVoting system using php allows users to register as voter/admin with a unique username.
During login based on their role will be redirected to admin/voter panel.
Admins can create elections with an access key, add candidates, delete elections and can view results.
Admins can specify start and end date of elections.

Only ongoing elections are displayed to the voters. 
Voters can select an election and should enter the access key provided by the admin to vote the candidates. 
Each voter can vote only once in each election.

# Usage 
Extract the folder in htdocs folder

   - Open Xammp control panel
   - Start server and Mysql
   - Open MySQL Admin (In browser-> localhost/phpmyadmin) and create a database named "evotingdb". Open it and import the sql file present in database schema folder.
   - All the tables with primary key, foreign key constraints will be created.
   - In browser type-> localhost/eVoting/index.php
