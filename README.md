
Fancode SDET Assignment Solution 📒
This is a small automation framework for ensuring that the users in Fancode city 🏙️ have completed more than 50% of their tasks📜 based on their ToDos.

Prerequisites
Before using this framework, ensure that you have following installed on you machine:

Java Development Kit (JDK) ☕
Maven Build tool
Eclipse or IntelliJ any Integrated Development Environment (IDE) 💻
Getting Started ▶️
Clone the repository on local machine
git clone git@github.com:vishwakarmaanuj/FanCodeSDETTest.git
Open the project in your preferred IDE

Build the project using Maven to resolve the dependencies

Running Test 🏃
To run the automted test, follow these steps

Right click on the testng.xml file and Click Run as Testng suite or
Navigate to src/test/java/com.assignment.fancode > FancodeTest.java > Right Click on the file and Click run as TestNG test.

Test results will be displayed in the console, including Passes, Fail and Skips and any assertions.

ExtentReport will be generated for the result with logs

About the framework
Test Data 🗃️
com.assignment.constants :

Config file in framework contains the Base URI
Constants has the constants for Longitude and Latitude
StatusCodeEnum stores the API status codes for now, later it may be implemented to add messages as well
Test Configurations 🛠️
com.assignment.core :

Client file contains the Response get method, we can implement more methods further
TestBase cotains the setUp method to set the BASE_URI
Test API Endpoints 🔗
com.assignment.endpoints: This contains all the Endpoints mentioned

Endpoints used
Get all users
  GET /users
Description
This endpoint fetches the users present in the system.
Get todo
  GET /todos
Description
This endpoint fetches all the todos in the system
Test Models 🧪
com.assignment.model : This contains the models for User and TodoResponse

Test Utlitiy Methods ⚙️
com.assignment.utils : stores all the utility and Reusbale methods

ResponseArrayUtils: converts the reponse to array.
TestHelper : Two methods present, LatituteLongitudeCheckerForUser and CalculateTaskCompletedPercentage
Test Implementation ✍🏻
Test case is implemented in the FanCodeCityTodoTest.java file in the com.assignment.fancode package. You can modify this file to add more test cases or customize the existing ones.

Test Results 🚀
Test results will be displayed in the console as well as Extent Report will be generated in Reports folder bu the name 'TestResults.html' ExtentReportspng

Tools and Technologies used 💻
Rest Assured
TestNG
Maven
Extent Reports
Eclipse
Jackson API
Java
Acknowledgements 🤝🏻
Thanks to JSONPlaceHolder for providing the API for Testing
Thanks to EmojiDb for the Emoticons
Thanks to ReadMe.so for the ReadMe Editor
Authors
@Anuj vishwakarma
