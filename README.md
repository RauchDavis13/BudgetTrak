# BudgetTrak

## Bootcamp Challenge 19
> This challenge focusses on setting up a PWA using Express to create an app that tracks add's/delete's from a budget.  The assignment is to allow the user to continue using the app while the app is offline, when the app is online again, it will load info from a temporary database and then clear the temporary database.


* The Assignment
  Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information.

Your challenge this week is to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online. Once you’ve made these changes, you’ll deploy the application to Heroku.

### User Story
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

### Acceptance Criteria
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated


## Tech Used
* JavaScript
* Node.js
* Express.js
* MongoDB
* Mongoose
* Morgan
* Bootstrap


## Website

* Github Repository: https://github.com/RauchDavis13/BudgetTrak.git

* Heroku / MongoDB Atlas: https://afternoon-hollows-70451.herokuapp.com/

## Videos
The following video demonstrates how IndexDB is empty when the server is Online.  Once switched to Offline, as the "instances" are loaded, and then the database is refreshed, the "instances" are then listed in the budget_tracker / new_budget database.  Then, once the browser is switched again to Online, the temporay database (budget_tracker / new budget databse) is then cleared and ready for use again.

[Database storage walkthrough](https://drive.google.com/file/d/1VvVVr6QRimcE9QjLSOedA-6YwZ03klFG/view)




## Thank You So Much To:
### Instructor - Matt Kim

## TA's
- Valerie Flores
- Kris Renaldi
- Dustin Erwin, 

## Fellow Students
- Calvin Villanueva
- Robert Evanik
- K-Von Madison