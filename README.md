# E-Commerce Back-End


![Badge](https://img.shields.io/badge/license-MIT-blue)
  

## Description

 In this assignment I was prompted with formulating the routes and responses that the server will send back to the client side depending on the certain type of request the front end was sending. In order to make this happen I needed to designate specific routes for each possible request inside of the API routes, then contructing the client to either:
 1) Find all of the data associated to the table.
 2) Find the data associated to the tables specific id.
 3) Update the row on a specific id with whatever the user would like to update.
 4) Delete a specific row of a table based on the user's requested id.
 
 Please have a look at the below video to see an example of how it's used:

[Video](https://drive.google.com/file/d/1GMxsg98hpDcdPEEqWxEyimr8jUTvSUKw/view?usp=sharing)



## Table of Contents

* [Installation](#installation)

* [Technology-Used](#technology-used)

* [Contribute](#contribute)

* [Tests](#tests)

* [Making](#making)

* [Questions](#questions)


## Installation

In order to run this application, you will need to run the following commands:

  First:

    - npm install

  THEN:

    - npm run seed
    - npm start

## Technology-Used

- GitHub - repository storage for the project in order to amke changes, deploy them and push to a main branch. 

- GitBash - used for written commands and communicating with the repository stored on GitHub.

- Javascript - a programming language that makes your webpage user interactive.

- Node.js - an efficient platform that runs Javascript outside of the web browser.

- Sequelize

- mySQL - a database constructor to create management systems of a bulk of data.


## Contribute 
    
In order to contribute, you will need to know the following languges:
    
  - Node, Javascript, MySQL, Sequelize, Express.Router()

## Tests

To run tests, please use the following command:

  - npm start


## Making

How was it made? Take a look here!

This is an example of a simple PUT method. This will enable the server to be updated with the information the user or front end has provided the back end with. You need to update the body on where the exact ID's match. Each category has it's own unique ID as it's primary key.

![Code-Snippet](/images/putrequest.PNG)

This is an example of a GET method by ID. This will construct the response to then send back to the front end after recieving the data from the server. A user can specify which product they would like to see and the server will find it for them by looking for a match. If there is no match, it will return the error that the category was not found.

![Code-Snippet](/images/getbyid.PNG)


## Questions

Please click the link to see my Full GitHub profile:

[GitHub](https://github.com/dnovelli1)

If you have any questions, please see the following links to best get in contact with me:

[Email Me](jakenovelli11@gmail.com)


## License

This project is currently licensed under the MIT [License](https://choosealicense.com/licenses/mit/)
  
