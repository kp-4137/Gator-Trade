# Credentials Folder

## The purpose of this folder is to store all credentials needed to log into your server and databases. This is important for many reasons. But the two most important reasons is
    1. Grading , servers and databases will be logged into to check code and functionality of application. Not changes will be unless directed and coordinated with the team.
    2. Help. If a class TA or class CTO needs to help a team with an issue, this folder will help facilitate this giving the TA or CTO all needed info AND instructions for logging into your team's server. 


# Below is a list of items required. Missing items will cause points to be deducted from multiple milestone submissions.

1. Server URL or IP
<br>http://3.84.15.167
2. SSH username 
<br>ubuntu
3. SSH key - included in folder
4. Database URL or IP and port used.
<br>Default
    <br><strong> NOTE THIS DOES NOT MEAN YOUR DATABASE NEEDS A PUBLIC FACING PORT.</strong> But knowing the IP and port number will help with SSH tunneling into the database. The default port is more than sufficient for this class.
5. Database username 
<br>root
7. Database password 
<br>student
8. Database name (basically the name that contains all your tables)
<br>GatorTrade
10. Instructions on how to use the above information.
Using a terminal, navigate to the location where the SSH key is stored. For the first use, use the command 
chmod 400 csc648-team05.pem. Then use the command
ssh -i "csc648-team05.pem" ubuntu@ec2-3-84-15-167.compute-1.amazonaws.com to access the server
<br>To access the database navigate to the db folder (cd app/application/db) then use sudo mysql -u root -p, then paste the password

AWS Sign In:
<br>Account ID: 278286693302
<br>Username: Team05Guest
<br>Password: Team05Guest!

# Most important things to Remember
## These values need to kept update to date throughout the semester. <br>
## <strong>Failure to do so will result it points be deducted from milestone submissions.</strong><br>
## You may store most of the above in this README.md file. DO NOT Store the SSH key or any keys in this README.md file.
