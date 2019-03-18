# Scribblr

![Scribblr](https://imgur.com/ywXCNzQ.png)

## The App
[Click here for deployed App](https://scribblerr.herokuapp.com/)

## Description
Scribblr is an app designed for today's modern writer. It is a way to share your work in a safe space and to allow other writers to read and help improve your writing. It is essentially an onine writers workshop. Inspired by writers trying to improve their craft, Scribblr will allow you to share your work with others.

## Interaction
Scribblr is a very simple app, made to be easy to follow and use. First, a user must sign up and create an account and then sign in. From there, they can create, update, and delete their Scribbls. All possible routes the user can take are easily found and simple.  

## Dependencies / Technologies
 
| Library | What it Does | 
| --- | :---: |  
| React-Select (optional) | (Used to improve functionality and styling of my search/select feature) | 
| React |
| React-Router | Used to improve site navigation |
| Express | Tie front-end to back-end |
| Sequelize | DB communication
| Nodemon | To facilitate back-end development | 
| Body-Parser | To facilitate putting user-input into the database |
| Morgan | Facilitate debugging with error messages |
| React-Bootstrap | To create consistant and flexible design |
| Bcrypt | Generates hashed passwords to ensure user security |

## Local Set up
- Fork and clone repository
- Install dependencies
```
npm install
```
- Initialize the database
```
npm run db:init
```
- Reset the database
```
npm run db:reset
```
- Seed the database information
```
npm run db:seed
```
- Start up React App and Server
```
npm run dev
```


