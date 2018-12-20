# ActivityTrackerProject
Activity Tracker Project 

************Activity Tracker*************

Steps to run the Activity Tracker program.

1] Install the dependancies which we are included in package.JSON using the below command.
	
	npm install
	
2] Execute the seed file to populate some sample data to test the application using the below command.
	(Note: Sometimes the seeding may not terminate automatically. Please press "CTRL + C" to terminate if this happens.
	 Note: The passwords stored in the database by seed file are hashed. We have mentioned the actual passwords in the seed.js file 
		next to the hashed password field in the comments. Please use those passwords for logging in.)
	
	npm run seed

3] To start the server, please execute the below command.

	npm start
