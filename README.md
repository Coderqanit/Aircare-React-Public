AirCare Product Requirement Document
Overview
AirCare is a company that offers AC maintenance and repair services to its customers. Currently, customers have to call or email the company to request maintenance and repair, which can be time-consuming and inconvenient. There is no efficient way to track the status of maintenance and repair requests, which makes customers frustrated. This application will provide AirCare’s customers with a convenient and efficient way to request AC maintenance and request. Customers will be able to track the status of their requests in real-time, reducing the need for follow-up calls and emails.
Success Metrics

Goal
Metric
Simplify maintenance and repair request
Number of customers that request for maintenance and repair services through the application.
Customer satisfaction score.
Seamless customer experience 
Response time to installation requests.
Number of support emails and calls.
Gross Revenue 
Total revenue gotten from maintenance and repair request on the application.



Assumptions
Customers have access to a computer or mobile device with internet connectivity.
Customers are willing to use the online maintenance and repair request forms rather than calling or emailing AirCare.
AirCare’s customer relationship management (CRM) system is capable of integrating with this application.
AirCare has the necessary resources to manage and fulfil maintenance and repair requests.
Milestone 
UI/UX Prototype 
UI/UX Prototype Acceptance
Technical Development and Documentation 
Quality Testing 
Beta Testing 
Launch
Dependencies
Integration with AirCare’s CRM system.
Training of customer service representatives to handle maintenance and repair requests efficiently.
Availability of AirCare’s installation technicians to fulfil installation requests.
User Story 1
John is an AC owner who has been using his AC for over 1 year. He browses online, clicks the AirCare website URL, and is directed to AirCare’s homepage. He then clicks on the ‘Book a Request’ button available on the view port of the homepage which directs him to the sign in page. On that page, there’s a copy below the ‘Sign in’ button that says ‘New to AirCare? Create an Account. This copy should be underlined to indicate that it is clickable.
John clicks on ‘New to AirCare? Create an Account’ and is redirected to the registration page where he enters necessary information. On clicking ‘Register’ button, John should be redirected to a page where he will enter the 6-digit code sent to his email to verify his account.
After verification, John is redirected to the Sign in page where he enters his registered ‘Email and Password’. On clicking on Sign-in button, John should be directed to his dashboard homepage.
In the dashboard side bar, John should be able to navigate to ‘Request Maintenance and Repair’, ‘Modify Request’, ‘Track Request’, ‘Notifications’ and ‘Chat with Customer Support)
Upon navigating to ‘Request Maintenance and Repair Page’, John should be able to fill all required fields and submit his request. John should receive an email and in-app notification indicating successful submission of his request and expected wait time for response to his request.
Upon navigating to ‘Modify Request Page’, John should be able to edit and update the details of his request. John should receive an email and in-app notification indicating successful update and submission of his edited request and expected wait time for response to his request.
Upon navigating to ‘Track Request Page’, John should see a visual display of his application progress from Pending to Approved. Once his request is approved, he should be able to see the details of the technician assigned to his request. John should also receive an email and in-app notification indicating approval of his request.
Requirements

Requirement
User Story
Acceptance Criteria
Customers should be able to create an account by providing the following information:

Name: 
Email: 
Password:
Confirm Password:
As a customer, I want to be able to create an account so that I can access the services provided by AirCare.
The customer should be able to see a message that indicates successful account creation on completion of the process.
Customers should be able to log in to their accounts with the correct Email and Password.
As a customer, I want to be able to log in to my account so that I can access my dashboard.
The user should be directed to their dashboard having provided the correct log in information.
Customers should be able to successfully place requests after filling the required fields.
As a customer, I want to be able to request maintenance and repair so that I can keep my AC in good working condition.
Having provided the correct required information for the request maintenance and repair, the customer should be able to send a request and receive an email and in-app 
Customers should be able to modify the details of submitted requests.
As a customer, I want to be able to modify my submitted request so that I can update my request details.
Provided the request has not been approved, customers should be able to change the details of their request. They should receive an email and in-app notification notifying them of this update.
Customers should be able to track the status of their request.
As a customer, I want to be able to track the status of my request so that I can monitor my request to completion.
Upon request approval, customers should be able to signify that the request has been fulfilled by the approved technician on the fulfilled date. Customers should receive email and in-app notification when request has been fulfilled and completed.
Customers should be able to view all requests they have made
As a customer, I want to be able to see a summary of all my requests
Each request should be clickable and should be sortable by Request Date, Request Type, and Request Status.
Customers should be able to receive and view in-app notifications.
As a customer, I want to be able to see all notifications in real time so that I can stay informed on my requests.
The notifications should have a default arrangement according to the Time Stamp. Unread notifications should be distinguishable from Read ones. Also, users should be able to filter notifications by Date,and Unread


User Interaction & Design
A design is currently being put together on Figma.
Open Questions

Question
Answer
Date Answered
How might we make customers aware of this feature?


What training will customer service representatives need to manage installation requests efficiently?




How will ABC Energy ensure that installation requests are fulfilled in a timely and efficient manner?






Out of Scope
Installation Request
Online payments 
