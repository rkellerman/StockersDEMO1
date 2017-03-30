%%%%%%%%%%%%%%%
README4.txt
%%%%%%%%%%%%%%%

This folder contains all the php scripts used for proper function of our applicaiton in demo 1.  These files exist on our server at Awardspace.com, and exist on a subdomain known as http://stockers.atwebpages.com.  There is no need to run these files on their own, they cannot perform the neccessary functions unless they are accessed through an HTTP POST request, which is done automatically through the Backgroundworker class within the application.  Each Backgroundworker object has all the neccessary URLs to access in order to get the data that the object needs at any given time, and it will call a specific set of scripts in a very specific order to get the data from our database (which also exists on the server on host pdb9.awardspace.net) and then return this data to the application in order to populate the tables that exist within each activity.  The URLs are shown here:

"http://stockers.atwebpages.com/login.php"
	- this script establishes the initial datanase connection and handles the login event
"http://stockers.atwebpages.com/register.php"
	- this script handles the register event
"http://stockers.atwebpages.com/viewPrices.php"
	- this script is not used in the application, but serves as a tool used during development
"http://stockers.atwebpages.com/purchase.php"
	- this script hanldes the purchase even
"http://stockers.atwebpages.com/sell.php"
	- this script handles the sell event
"http://stockers.atwebpages.com/yahoostock.php"
	- this script connects to the Yahoo! Finance API and populates the associated table in the database
"http://stockers.atwebpages.com/portfolio.php"
	- this script populates the portfolio tables on the portfolio screen
"http://stockers.atwebpages.com/leaderboard.php"
	- this scipt populates the leaderboard table on the leaderboard page
"http://stockers.atwebpages.com/price.php"
	- this script handles the price search event
"http://stockers.atwebpages.com/class.yahoostock.php"
	- this script serves as a model for the yahoostock object that is created in the yahoostock.php script, it is never called directly and does not appear in the application code, but is called by yahoostock.php
