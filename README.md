# BLOGAPP 🆕

## Fullstack Blog application [LIVE DEMO](https://secure-temple-73769.herokuapp.com/)

- Users 🌟
- Posts 🌟
- Authentication 🌟

This fullstack application supports user profiles, users can post and all the functionality is allowed based on authentication and authorization.

## TechStack

- Backend
  - MongoDB
  - Node
  - Express
- Frontend
  - React
  - Redux

### Using MERN stack to develop the feature set of the application

Key tools/workflows used

- Backend
  - mongoose v^5.12.13 -> ODM to communicate with mongoDB running in mongoDB atlas
  - express v^4.17.1 -> to create web-application
  - express-jwt v^6.0.0 -> for setting auth to request object
  - jsonwebtoken -> to create json tokens for users
  - bcrypt -> to generate secure passwords for users
- Frontend
  - React -> using create-react-app
  - Redux, react-redux -> for state management and hooks to update state
  - redux-thunk -> for dispatching asynchronous actions
  - Custom Hooks -> custom react hooks to manage form-data and other stateful components
  - React-Bootstrap -> for styling and ui components

## Features available

- Sign-up / Register an account
- Login/Logout
- Users
  - List all users
  - Create new user
  - Read a single user
  - Update a user
  - remove a user
- Posts
  - List all posts
  - Create new post
  - Read a single post
  - Upadte a post (like, comment)
- Auth
  - Authentication
  - Authorization
  - All actions on the site are validated based on the authentication and authorization of a user
