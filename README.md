Project : Automation Test Engineer Capstone : Testing an Airline Booking Website


Praveen T P 

Course-end Project 3

DESCRIPTION

This project requires end-to-end development of a comprehensive QA and test environment for an airline booking website. This QA and test environment should be inclusive of the following testing layers:

Browser-based end user testing using Selenium WebDriver
Unit testing for backend elements of the website using TestNG
API testing with Postman on AWS cloud
Automating the whole testing process by creating Jenkins job
The end-deliverables will be executable scripts and modules, which can be run on demand for testing the airline booking web app.

Background of the problem statement:
Cloud Airlines is a ticket-booking portal that lets people book flights on their website. The website has the following features:

A search form in the homepage is used to enter the travel details like the date of travel, source, destination, and the number of passengers.
Based on the travel details entered, it opens a page with the available flight details and their ticket prices.
Once a person selects a flight to book, they will be taken to a register page where they must fill in their personal details. On the next page, the flight details are displayed, and the payment is done via a dummy payment gateway. On completion, a confirmation page with the details of the booking will be displayed.
The above website is already functional. The objective is to add a testing layer, which will ensure that every component of the website is passed through the QA.

Implementation requirements:

Write an automation script using page object design to store the web elements of the home page
Create Selenium scripts to test all the pages in the website
Perform unit testing for all backend classes and methods using TestNG
Add additional code to the original project to add the REST API module. This module will have two API endpoints:
           ● Retrieve the list of flights on a given date
           ● Retrieve the list of booked seats on a given flight

     5. Create Postman scripts to test the two API endpoints mentioned above
     6. Create and build Jenkins job for all the automation testing phases performed in the previous steps

The following tools must be used:

Eclipse IDE: Source code editing and modification
Selenium WebDriver: A browser testing framework for end-user black box testing
Postman: A standalone application for API testing
TestNG: A testing framework for unit testing of the backend elements of the website
Git: To connect and push files from the local system to GitHub
GitHub: To store the application code and track its versions
Specification document: Any open source document or Google Docs
The following requirements should be met:

All testing scripts and code should be pushed to your GitHub repository. You need to document the steps and write the algorithms in it.
The submission of your GitHub repository link is mandatory. In order to track your tasks, you need to share the link of the repository.
Document the step-by-step process starting from creating test cases and then executing it and recording the results.
You need to submit the final specification document, which includes:
a. Project and tester details
b. Concepts used in the project
c. Links to the GitHub repository to verify the project completion
d. Your conclusion on enhancing the application and defining the USPs (Unique Selling Points)
