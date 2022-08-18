# 💻 Description

This application performs the CRUD (Create, Read, Update) of users. Also, it is possible to make a user an administrator, list users only if the user is requesting to be an administrator. All this using SOLID concepts.

# 🛠️ Features
- Create a new user with name, email
- List all users;
- View user profile;
- Make a user an administrator;

# 🔗 Routes
- GET /get → list with all users.
- POST /users → create a user.
- PATCH /users/:user_id/admin → make a user admin.
- GET /users/:user_id → displays user information.

Use
With the dependencies installed, I ran yarn dev to upload the server.

*In this challenge I was able to put my knowledge about SOLID into practice using them in typescript*