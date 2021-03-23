# budget-tracker


## User Story

AS AN avid traveller,<br />
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection,<br />
SO THAT my account balance is accurate when I am traveling.

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

## Description

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:
  * Enter deposits offline
  * Enter expenses offline

When brought back online:
  * Offline entries should be added to tracker.

## Acceptance Criteria

GIVEN a user is on Budget App without an internet connection,<br />
WHEN the user inputs a withdrawal or deposit,<br />
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

## Demo

<img src="./assets/images/budget-tracker.gif" />

## Deploying the App

This app should be deployed using Heroku and MongoDB Atlas.

***

HEROKU LINK: https://whispering-dawn-63893.herokuapp.com/

https://github.com/tracy80s2003/budget-tracker

https://tracy80s2003.github.io/budget-tracker/