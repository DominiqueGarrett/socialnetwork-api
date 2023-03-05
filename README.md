# socialnetwork-api
Module 18 Challenge Assignment: NoSQL Challenge: Social Network API


## Badges
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Table of Contents
  * [License](#license)
  * [Description](#description)
  * [User Story](#user-story)
  * [Acceptance Criteria](#user-story)
  * [Installation](#installation)
  * [Setup](#setup)
  * [Usage](#usage)
  * [Screenshots of Application in Use](#screenshots-of-application-in-use)
  * [Technologies](#technologies)
  * [How to Contribute](#how-to-contribute)
  * [Tests](#tests)
  * [Questions?](#questions)


## License
  Read more about MIT here:
  [MIT](https://opensource.org/licenses/MIT)


## Description

An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

## User Story
```
    AS A social media startup
    I WANT an API for my social network that uses a NoSQL database
    SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria 
```
    GIVEN a social network API
    WHEN I enter the command to invoke the application
    THEN my server is started and the Mongoose models are synced to the MongoDB database
    WHEN I open API GET routes in Insomnia for users and thoughts
    THEN the data for each of these routes is displayed in a formatted JSON
    WHEN I test API POST, PUT, and DELETE routes in Insomnia
    THEN I am able to successfully create, update, and delete users and thoughts in my database
    WHEN I test API POST and DELETE routes in Insomnia
    THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
    

## Installation
 
---------INSERT INSTALLATION--------

## Setup

---------INSERT SETUP--------

## Usage

After following the instructions in installation: 
1. Open the "index.js" file in your integrated terminal.
2. Run command "npm run seed" to seed users into your database.
3. Run command "npm run start" (or "node server.js"). Alternatively, if you have Nodemon installed, run "npm run watch" (or "nodemon server.js"). 
4. Open insomnia and type in "localhost:3001/api/_" in the address bar. Check out the following routes: <br><br>
User + Friends <br>
- `/api/users` to get all users or create user
- `/api/users/:userId` to get one user, update and delete user
- `/api/users/:userId/friends/:friendId` to add or delete a friend <br><br>
Thought + Reactions <br>
- `/api/thoughts` to get all thoughts or create thought
- `/api/thoughts/:thoughtId` to get one thought, update or delete. 
- `/api/thoughts/:thoughtId/reactions` to create reaction 
- `/api/thoughts/:thoughtId/reactions?reactionId=` to delete reaction 
5. When finished, run CONTROL-C in terminal to end and trash the session. 

<br>
Please check out this [video] (https://drive.google.com/file/d/1opY3BH_J3iSpYGSwvKnSIj8PnLTplf--/view) to view a demonstration of how to use this program. 
<br>

## Screenshots of Application in Use

---------INSERT SCREENSHOTS--------



## Technologies

---------INSERT TECHNOLOGIES--------

  ## How to Contribute
  [Contributor Covenant](https://www.contributor-covenant.org/)  


  ## Questions?
  ### Reach me here: 
  [DominiqueGarrett](https://github.com/DominiqueGarrett)  
  Dominique.garrett1212@yahoo.com
