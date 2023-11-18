# e-commerce-backend

## Description

This application was created to build the back end of an e-commerce site by modifying starter code. 

I built this project to gain a better understanding of the various node applications that can be used in back end applications. 

As mentioned above, the project creates back end code to be used with front end code at a later time. This application will allow a user to store commerce data such as products, and the various information that goes with it, in a database. Once connected to a front end application the user will be able to access and update that information as needed.

I learned quite a bit during the creation of this project. I learned more about the sequelize, dotenv, and mysql2 dependencies. I also learned more about Insomnia and how to set up folders and save my api calls so that they are readily available.

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To use this app you need to do the following:
- `git clone` this project and verify you have node installed on your computer.
- Run the following commands in the command line:
    - `npm init -y` This will initialize the node package and accept the defaults
    - `npm i dotenv` This will install the dotenv dependency used for creating global variables such as your user id and password
    - `npm i express` This will install the express dependency used to handle the different HTTP methods in the API routes.
    - `npm i mysql2` This will install the mysql2 dependency used to run mysql from the command line and interface with your database.
    - `npm i sequalize` This will install the sequelize dependency used to run sequel commands within the application versus having to log into the mysql server.
    - `node server.js` This will start the application.

## Usage

This application allows you to create a database, seed it with information, and then make api requests to and from the database. Currently the api calls allow you to view all products, categories, and tags as well as view them by id number. You can also add new products, categories, and tags. Finally, you can update and delete products, categories, and tags by id number.  

To see how this application works please visit the link below:  
https://drive.google.com/file/d/1QZnNbFHJA-BMcabMyPD0PFY9XFpxAb6E/view 

## Credits

The following website was used as reference for mysql:  
https://dev.mysql.com/doc/refman/8.2/en/

The following website was used as reference for sequelize:  
https://sequelize.org/docs/v6/

## Questions

If you would like to know more about this project or to view other projects I have worked on please visit me at [kittykatt210](https://github.com/kittykatt210).

If you have any questions about this project that aren't answered in the github repository, I can be reached at keperry30@icloud.com.

## License

Copyright (c) Kathryn Perry. All rights reserved.  
Licensed under the [MIT](https://opensource.org/licenses/MIT) license.