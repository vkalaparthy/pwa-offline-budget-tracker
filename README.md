# pwa-offline-budget-tracker
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Adding functionality to an existing Budget Tracker application to allow offline access without compromising on the functionality.  This budget tracker works even when the Network settings are offline. When the netork is avilable(Online), it saves the indexDB transactions into MongoDB. This app can be installed on your phone or on PC.


## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

## Installation
This application is located in GitHub at https://github.com/vkalaparthy/pwa-offline-budget-tracker and the application can be accessed from [heroku](https://vk-progressive-budget.herokuapp.com/).  When you open the Heroku app in Chrome, click the menu ⁝ at the top-right of its window and select install "OfflineBudgetTracker" and use the installed App.   
Clone the application from GitHub and run "npm install" to install all the packages and then run "npm start", open a new tab in chrome and go to the localhost:3050 (or any other port if you change the port number in server.js).

## Usage
Install the app from [Heroku ](https://vk-progressive-budget.herokuapp.com/)  and start entering your trasactions.  You will be able to use this App when Network is Online/Offline without loosing the transactions.  Since the App uses MongoDB, you need to have installed the MongoDb to store/retrieve the trasactions. 

![firstPage](./images/pbCapture.JPG)  

You can clone the app from the GitHub repository from https://github.com/vkalaparthy/pwa-offline-budget-tracke to make any improvements or Run the app in Heroku, [here](https://vk-progressive-budget.herokuapp.com/)    
  
  
Demo: Note that Budget was $120 before the Network was offline when the transactions were done (one is -75 and other one is +100)  and everything is correctly refelected after the Network goes to Online.

![demo](./images/BudgetTracker.gif) 
## License
Copyright © 2020-present, Vani Kalaparthy. Released under the MIT License.
## Contributing
## Tests
Only manual testing

## Questions
* Vani Kalaparthy
  * https://github.com/vkalaparthy
  * kalaparthy.vani@gmail.com
