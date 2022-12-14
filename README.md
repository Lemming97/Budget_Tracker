# Budget_Tracker
19. Progressive Web Applications (PWA) Challenge: Budget Tracker



## Description 

The purpose is to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online. Once you’ve made these changes, you’ll deploy the application to Heroku.

## Table of Contents
* [Installation](#installation)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Screenshots](#screenshots)
* [Link](#link)
* [Usage](#usage)



## Installation 


1. Clone the repository from GitHub
1. Install `node.js`
1. Install `MongoDB`
1. Run `npm install` to install dependencies. 
1.  Dependencies include Express.js for routing, a MongoDB database, Morgan, and Compression. 
1. Run `npm start` to start the web server and connect


This package assumes there is a MongoDB server running on localhost:27017. If your server is running somewhere else, you can edit server.js to reflect that.

## User Story

```md
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

## Acceptance Criteria

```md
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```

## Screenshots 

<img width="840" alt="Screen Shot 2022-08-03 at 12 33 08 AM" src="https://user-images.githubusercontent.com/49573760/182552706-8140500e-e30d-48a8-94f7-24534e3f3d01.png">


## Link 

<a href="https://mighty-ridge-71933.herokuapp.com/">Click Here</a>


## Usage 

Gives users a fast and easy way to track their money, but allows them to access that information at any time is even more important. 
