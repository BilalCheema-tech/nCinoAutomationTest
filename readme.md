# nCino QA Automation Test

## Pre-Requisites
	1. Programming Language: Java
	2. Java 1.7 installed and configured
	3. JUnit installed and configured on the selected IDE. 
	4. Maven installed and configured on the selected IDE.
	5. TestNg installed and configured on the selected IDE.
	6. Install TestNG in Eclipse to run the tests with TestNG.
	7. Install Selenium and configure it in your System.
	

## End to End Automation Test
	1. Framework: Selenium
	2. Feature: http://todomvc.com/
		1. Load the Website
		2. Click within the JavaScript Tab
		3. Select the polymer link
		4. Add two todo items
		5. Edit the content of the second todoItem

	3. Design Pattern: Page Object Model (src/main/java/pageobjets)
	4. Browsers configured
		1. ChromeDriver (For both MAC and Windows)
		2. FirefoxDriver (For both MAC and Windows)
	5. Location of drivers --> external/webdrivers
	6. Dependencies: pom.xml
	
*Note: I have verified chromedriver and firefoxdriver for MAC*
*Note: If you are using MAC OS, please comment out the relevant path of the data.properties file for uniterrupted execution*
		
## Execution Details
	1. Unzip the Project (GitProjects)
	2. Import maven project in Eclipse or any other IDE. 
	
	### For End to End Automation Tests
		1. Navigate to project
		2. Open “data.properties” file to view the test data
		3. Default browser is set to Google Chrome.
		4. Navigate to src/test/java/com.mycompany.app
		5. Right click on HomePage.java and Run as ‘TestNg Test’
		6. If you want to run on firefox change the browser to firefox in "data.properties” file


