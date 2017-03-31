===================================================================================
			READ ME INTEGRATION TESTING
===================================================================================

To run the integration tests, you must have downloaded all the files into android
studio as the variables that we are testing are integrated within the different
java classes. ----

When you run the application, the terminal in Android Studio will print the success 
or failure of the integrated tests.

Additionally we have provided a ManualIntegrationTest.pdf to show the grader how,
the front-end looks when we are observing the test cases.  

For the terminal to print the success or failures, the user must navigate to the
corresponding pages as the Android Studio code will only execute when the activity
is called on. Therefore the grader cannot simply run the file as the files cannot
be separated on Android Studio. 

Activities that must be called for the integrated test to run:

1. Portfolio Activity
2. Leaderboards Activity

When these pages are openend in the app, the function will be called 
to test to see if the net worth's match the profile net worth.  

Integration Tests

1. Networth on Profile matches Networth on Portfolio
	Here we are testing to see if the variable that is shared and accessed
	across the application remains constant and is displayed correctly. 
2. Networth matches the Leaderboards page.
	Additionally we will check the leaderboards page for proper rankings 
	and proper net worth being displayed.  
3. Performing a transaction reflects on thee My Portfolio Page.
	This test will first perform a buy transaction and see if the 
	stocks that were purchased were successfully displayed on the 
	Portfolio Page. Next, we will sell a different stock that was
	already owned, and observe the reflected values on the Portfolio
	page. ALL transactions take place on the "Trades Page".