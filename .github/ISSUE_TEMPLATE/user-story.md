## Title
User Login

## Description
As a registered user,  
I need to log in to my account,  
So that I can access my personal dashboard.

## Acceptance Criteria

### Scenario 1: Successful login
Given the user is on the login page
When the user enters valid credentials and clicks "Login"
Then the user is redirected to the dashboard

### Scenario 2: Incorrect password
Given the user is on the login page
When the user enters an invalid password and clicks "Login"
Then an error message is displayed and the user stays on the login page

### Scenario 3: Empty input
Given the user is on the login page
When the user submits without entering username or password
Then an error message is displayed prompting the user to fill in the required fields
