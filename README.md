# NoSQL - Social Network API

## Description

This is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. This is being done by using Express.js for routing. MongoDB for database, and Mongoose for ODM or Object Document Mapping.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Videos](#video)
- [Contributing](#contributing)


## Installation

In order to use this application, you will need to download MongoDB and Node. 

- Clone this repo to your machine.
- npm i
- npm init -y
- npm install express
- npm install mongoose

## Usage

When using this application, start by typing npm start in the command line. You will then utilize Insomnia Core or another application of your choice to test the following endpoints. 

User 

- Get all users: GET /api/users
- Create a user: POST /api/users
- Get user by ID: GET /api/users/:id
- Update a user: PUT /api/users/:id
- Delete a user: DELETE /api/users/:id
- Add a friend: PUT /api/users/:userId/friends/:friendId
- Delete a friend: DELETE /api/users/:userId/friends/:friendId

Thought

- Get all thoughts: GET /api/thoughts
- Create a thought: POST /api/thoughts
- Get thought by ID: GET /api/thoughts/:id
- Update a thought: PUT /api/thoughts/:id
- Delete a thought: DELETE /api/thoughts/:id

Reaction

- Add a reaction: PUT /api/thoughts/:id/reactions
- Delete a reaction: DELETE /api/thoughts/:id/reactions

Friends

- Add friend: POST /api/users/:userId/friends/:friendId
- Delete friend: DELETE /api/users/:userId/friends/:friendId

## Video

![gif of login, user, and thoughts](./assets/user-thought.gif)
![gif of reactions and friends](./assets/reactions-friends.gif)


## Contributing

Reuben Genkin and Marykate Smith both contributed to the successful of this application.   

  