# PaymentsWorkshop_Postman

Project Name: Square Payments API

URL: https://developer.squareup.com/explorer/square

#Purpose of the Project:

The purpose of the project is to create a collection of API's to execute positive and negative scenarios, with the habilitty to generate a report after each execution and monitoring the collection so the tester knows the status of each API.

The QAs responsability on the project is to create test scripts in Postman or asserts for the APIs.

---------------------------------------------------------------

How-to: Pre-requisites

#Pre-requisites for installation:

Installation:
+ Visual Studio Code
	- https://code.visualstudio.com/
+ Node Js | TestCafe
	- https://nodejs.org/en/
+ Adding Javascript as language once Visual Studio Code is installed
+ Postman Installation 
	- https://www.postman.com/downloads/
	
Language of development: N/A

Step #1: go to the following url: https://github.com/echarly/PaymentsWorkshop_Postman
	Expected: The GitHub page is displayed and the following project is shown: 
	echarly/SauceDemoWorkshopVisualStudio
	
Step #2: Click on the green button that says "Code" with an arrow pointing down.
	Expected: Two options will be displayed:
				- Open with GitHub Desktop
				- Download Zip File

Step #3: Click the option that says "Download Zip file"
	Expected: a Zip file named "SauceDemo-main.zip" will be downloaded in your "downloads" folder.
	
Step #4: UnZip the Zip file named in the previous step. 
	Expected: a set of folders and files will be unzipped into a folder with 13 files.
	
Step #5: Open Visual Studo Code application and click "Open Folder" or press "ctr + O".

Step #6: Navigate to the "PaymentsWorkshop_Postman" folder which was unzipped 

Step #7: Click "View" in the navigation bar on the top of Visual Studio Code and select 
		 "Terminal" to view the terminal on the bottom. 
     
---------------------------------------------------------------

How-to: Execute the test scenarios

To execute the tests type the following:

+ In the Terminal enter the following text:

---> 
npx newman run c:\PaymentsWorkshop\YOUR_APP\API\collection\PaymentWorkshop.postman_collection.json -e c:\PaymentsWorkshop\YOUR_APP\API\envVariables\PaymentEnvironment.postman_environment.json
	
---------------------------------------------------------------
How-to: The two projects

PaymentsWorkshop_Postman
The solution is divided into two sections which are: 
	+ Collection
	+ envVariables 
	
The difference between them is very simple: 
	+ Collection contains the APIs, headers and test scripts
	+ envVariables contains the environment variables used to execute the APIs
		
---------------------------------------------------------------

For any comments or questions please contact: charlyh@gmail.com

Have fun! 
