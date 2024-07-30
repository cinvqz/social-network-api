# Social Network API
## Description
This Project is an API for a social network application where user's can create thoughts, share reactions and add friends.

## Technologies Used
1. Express.js
    - Used for routing
2. MongoDB
    - Used for the database
3. Mongoose
    - Used for object data modeling

## Installation
To access the project content:
   ```
    1. Use this link to the project repo
    https://github.com/cinvqz/social-network-api
   ```
    2. Use comand git clone to clone the repo
   ```
    3. Install dependencies using npm install
   ```
    4. Set up MongoDB
   ```
    5. Start the server using npm start
```
## Usage
This application can be tested using Insominia.
Here is and example of an API endpoint you can use to test it:

### Users

GET /api/users: Get all users

` Request: GET /api/users`

Response:
json

```
[
  {
    "_id": "userId",
    "username": "username",
    "email": "email",
    "thoughts": [],
    "friends": []
  }
]
```
Here is an example of the webpage's usage.

[SVG logo maker example video](https://watch.screencastify.com/v/m1dNl11ww8qBCN4UuyqW)


## Credits

[How to write a GOOD README File](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)

[Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/5281/external_tools/313)

[Chat GPT](https://chatgpt.com/)