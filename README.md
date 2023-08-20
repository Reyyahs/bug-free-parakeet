# NoSQL Challenge: Social Network API

## Description


This web-based application enables users to both access and interact with a MongoDB database, which serves as the backend for a social media platform. Through this platform, users can perform Create, Read, Update, and Delete (CRUD) operations on two main entities: users and thoughts. In addition to these core functionalities, users are also linked to friends, and thoughts can be linked to reactions. This interconnected database structure forms the foundation of the social media platform's functionality and fosters dynamic interactions among users and their thoughts.

## Installation

This application will require Node.js to use. It will also require running "npm install" to pull in the express and mongoose libraries into your environment.


## Usage

Utilize Insomnia to initiate fetch requests to various routes based on your intended actions. For accessing all users, thoughts a GET route with the format http://localhost:3003/api/option_name, where 'option_name' corresponds to users and thoughts. Moreover, to retrieve a specific item from any of these categories, input the ID number along with the following GET route: http://localhost:3003/api/option_name/ID_number.

Furthermore, employ POST, PUT, and DELETE routes to make alterations within the database.

To introduce new data, employ the POST route located at http://localhost:3003/api/option_name, along with the provision of JSON data. To modify an existing item, navigate to the PUT route at http://localhost:3003/option_name/ID_number, and submit the corresponding JSON data. For the removal of an existing item, the DELETE route at http://localhost:3003/option_name/ID_number can be employed.

When it comes to the inclusion or removal of friends from a user, utilize either a POST or DELETE route through http://localhost:3003/api/users/userId/friends/friendId. In this context, "userId" signifies the user to whom you intend to add a friend, while "friendId" represents the user's userId who is to be added as a friend.


Social Network API Video Demonstration: https://drive.google.com/file/d/1AVC-SrywFZCwAK7WFfAXX9EBB98JQxy5/view

## Reference

- UNCC-VIRT-FSF-FT-05-2023-U-LOLC Module: 18 NoSql


## Credits

N/A

## License
MIT