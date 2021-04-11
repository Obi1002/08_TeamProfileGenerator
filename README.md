# 08_TeamProfileGenerator

* [Acceptance Criteria](#acceptancecriteria)
* [Installation](#installation)
* [Project Status](#projectstatus)
* [License](#license)
* [Deployment](#deployment)
* [Usage](#usage)
* [Preview of the App](#previewApp)

# TeamProfile_Generator

For this project, I aim to create a Node.js command-line application that takes in information about employees on a software engineering team, then generates an HTML webpage that displays summaries for each person. Additoinally, I will write a unit test for every part of the code to ensure that it passes each test. My main motivation for this project is to create a generate a detailed team profile page after all of the data has been entered. Being able to accomplish this app will maximize efficiency while minimizing the time to locate basic information about the team, which includes their emails and GitHub profiles.     

# Acceptance Criteria
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated

# Installation

Modules to install:
* [Jest](https://www.npmjs.com/package/jest) for running the unit tests.
* [Path](https:www.npmjs.com/package/path) for working with directories and file path.
* [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user.

# Project Status
This project was completed on April 8, 2021. 

# License
MIT
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/sdca/advdv)

# Deployment
[Link](https://drive.google.com/file/d/11hiw28E-KHDNBX58bvhnvr1Hp6YyPd5D/view?usp=sharing)

# Usage
When you open the terminal, you will be prompted to enter some information about your team.  Once you enter that information you will webpage will generate with the team's profile and information. This will allow a quick view of the information of each team member.  

<!-- Add screenShot -->
 # Preview of the App
* This is how the app looks
![TeamProfileGenerator Screenshot](./assets\images\teamprofilegenerator.PNG) (https://drive.google.com/file/d/11hiw28E-KHDNBX58bvhnvr1Hp6YyPd5D/view?usp=sharing)