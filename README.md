# Online/Offline-Budget-Tracker

## Project Description
Thus Budget Tracker appllication allows for offline access and functionality. Users are able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, users can populate the total when brought back online.

### Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

### User Story
```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

### Acceptance Criteria
```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```

## Deployed application
This application is deployed on Heroku:
* https://rocky-hollows-17631.herokuapp.com/

## Installation Instructions
Install the following npm packages prior to deploying application:
* compression
* express
* lite-server
* mongoose
* morgan


