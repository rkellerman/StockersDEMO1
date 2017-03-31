README for DEMO 1 on how to run our application
more information on how to install at https://developer.android.com/studio/install.html
more information on how to run at https://developer.android.com/training/basics/firstapp/running-app.html

To run our code you need to have android studio installed that is updated to the newest version. 
it is located at https://developer.android.com/studio/index.html
Open the project by going to the file directory of stocker,clicking on Stockers, and pressing OK. It should open up the file and let you know if you have any errors.
Errors will possibly occur if you do not have the updated version of the gradle. The console should have a error message that tells you what you need and what the error was.
Fix the error and after its gone you can move on to the next step. 

//////////////////////////////
To run the app on a real android device: 
Set up your device as follows:
Connect your device to your development machine with a USB cable. If you're developing on Windows, you might need to install the appropriate USB driver for your device. For help installing drivers, see the OEM USB Drivers document.
Enable USB debugging on your device by going to Settings > Developer options.
Note: On Android 4.2 and newer, Developer options is hidden by default. To make it available, go to Settings > About phone and tap Build number seven times. Return to the previous screen to find Developer options.
Run the app from Android Studio as follows:
In Android Studio, click the app module in the Project window and then select Run > Run (or click Run  in the toolbar).
In the Select Deployment Target window, select your device, and click OK.
Android Studio installs the app on your connected device and starts it.
//////////////////////////////
//////////////////////////////
To run the app in the emulator: 
Before you run your app on an emulator, you need to create an Android Virtual Device (AVD) definition. An AVD definition specifies the characteristics of an Android phone, tablet, Android Wear, or Android TV device that you want to simulate in the Android Emulator.
Create an AVD Definition as follows:
Launch the Android Virtual Device Manager by selecting Tools > Android > AVD Manager, or by clicking the AVD Manager icon  in the toolbar.
In the Your Virtual Devices screen, click Create Virtual Device.
In the Select Hardware screen, select a phone device, such as Pixel, and then click Next.
In the System Image screen, click Download for one of the recommended system images. Agree to the terms to complete the download.
After the download is complete, select the system image from the list and click Next.
On the next screen, leave all the configuration settings as they are and click Finish.
Back in the Your Virtual Devices screen, select the device you just created and click Launch this AVD in the emulator  .
While the emulator starts up, close the Android Virtual Device Manager window and return to your project so you can run the app:

Once the emulator is booted up, click the app module in the Project window and then select Run > Run (or click Run  in the toolbar).
In the Select Deployment Target window, select the emulator and click OK.
Android Studio installs the app on the emulator and starts it.
//////////////////////////////

Create an android emulator using the AVD manager icon at the top with the following specs 
-Nexus 5 API 23 
-Android 6.0 

if a different emulator is used, it will still work but it might have layout issues since this app has not been tested on it.

press the run button, select the emulator, and the emulator should open up and load. This loading might take around 10 minutes so please be patient. 
Now the app should be running. Register and create a new account. when you go back to the login screen, 
email: harshpatel40
password:harsh  
in order to login. The default prefilled login will also work. Now go have fun with the app! some things might not be operational yet so they will not work 

The code will be located in all of the .java files inside stockers/app/java if you want to look at it.

In the future we will be able to send a .APK file for you to download onto an android phone and run. 