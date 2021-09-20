# budget-tracker

## User Story
- As an avid traveler, the user wants to be able to track their withdrawals and deposits with or without a data/internet connection, so that their account balance is accurate when they are traveling.

## About this Challenge

- Given a budget tracker without an internet connection
- When the user inputs an expense or deposit, then they will receive a notification that they have added an expense or deposit
When the user reestablishes an internet connection, then the deposits or expenses added while they were offline are added to their transaction history and their totals are updated.

## Project Description

### The following guidelines are usedto set up your models and API routes:

- For this application, webpack is not used, instead Express.js server is used. The Chrome DevTools makes it possible to test service workers on localhost in development. The Application tab is clicked, then Service Workers is selected from the menu on the left.
- The idb.js file is added to the public/js/ directory of the application.
- The service worker is added to the root of the public/ directory of the application.
- Once the the existing budget tracker is updated , it should provide the following functionality:</b>
 - The ability to enter deposits offline.
 - The ability to enter expenses offline.
- Offline entries are added to the tracker when the application is brought back online.

### Web Manifest
- Since this will be a mobile-first application, it is also needed to add a web manifest to the application with the app’s metadata, to let the users’ devices know what they’re installing and how the app should look on the home screen.

- The manifest.json file for this project will contain the following properties:
 - name
 - short_name
 - icons
 - theme_color
 - background_color
 - start_url
 - display

- For this application, the manifest.json is created manually and added to the root of the public/ directory of the application. 

## Heroku Link
https://lit-basin-74482.herokuapp.com

## GitHub Link
https://github.com/sindhu-sp/budget-tracker
 

## Technologies Used:
- Mongoose
- Express
- Javascript

#### Sindhu Pillai
