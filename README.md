# Social Network API


## Description

This is the API and back-end data store for a simple Social Network application, which accommodates Users, their associated Friends, their Thoughts, and Reactions to those thoughts by other Users.

It was built using Express, MongoDB, and the Mongoose ORM.


## Installation

To use this program on your computer, follow these steps:

1 - Ensure Node.js is installed on your local computer.

2 - Using VS Code, pull the GitHub repo into a directory on your local computer

3 - In VS Code, right-click on that directory and select "Open in Integrated Terminal".

4 - On the command line, type "npm init" and then hit Enter.



## Usage

After completing the installation steps above, to start the API listening, follow these steps:

1 - On the command line, type "npm ruin start" and then hit Enter.

2 - Use Insomnia or another RESTful API tool to see each of the API's CRUD operations in action. The following is a list of each of those operations, the appropriate API request method to use, and their corresponding API URL endpoints:

* GET all users
http://localhost:3001/api/users

* GET single user by userId
http://localhost:3001/api/users/:userId

* POST new user
http://localhost:3001/api/user

* PUT update a user by userId
http://localhost:3001/api/users/:userId

* DELETE a user by userId
http://localhost:3001/api/users/:userId

* PUT new friend by userId
http://localhost:3001/api/users/:userId/friends

* POST a new thought
http://localhost:3001/api/thoughts/

* GET single thought by thoughtId
http://localhost:3001/api/thoughts/:thoughtId

* POST a new thought
http://localhost:3001/api/thoughts/

* PUT update a thought by thoughtId
http://localhost:3001/api/thoughts/:thoughtId

* DELETE a thought by thoughtId
http://localhost:3001/api/thoughts/:thoughtId

* POST a reaction to a thought by thoughtId
http://localhost:3001/api/thoughts/:thoughtId/reactions

* DELETE a reaction to a thought by thoughtId and reactionId
http://localhost:3001/api/thoughts/:thoughtId/reactions/:reactionId



## Appearance

Visit the following Google Drive link to watch a walk-through video of this API's functionality:

https://drive.google.com/file/d/1b6oF6OWKZjemwLxvpV29wBN-aQnwHHMA/view



## License

MIT License

Copyright (c) 2023 Peej D

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
