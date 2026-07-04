# Just-Geeky-News

A CMS-style tech news app where users can create accounts, publish posts, upvote content, and comment on discussions.

## Tech Stack

![JavaScript](https://img.shields.io/badge/JavaScript-87.4%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![Handlebars](https://img.shields.io/badge/Handlebars-8.3%25-f0772b?style=for-the-badge&logo=handlebarsdotjs&logoColor=fff)
![CSS](https://img.shields.io/badge/CSS-4.3%25-1572B6?style=for-the-badge&logo=css3&logoColor=fff)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=fff)
![Express.js](https://img.shields.io/badge/Express.js-Framework-000000?style=for-the-badge&logo=express&logoColor=fff)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=fff)
![Sequelize](https://img.shields.io/badge/Sequelize-ORM-52B0E7?style=for-the-badge&logo=sequelize&logoColor=fff)
![Heroku](https://img.shields.io/badge/Heroku-Deploy-430098?style=for-the-badge&logo=heroku&logoColor=fff)

## Live Demo

https://protected-lowlands-09239.herokuapp.com/login

## Screenshot

![Just-Geeky-News Screenshot](https://karltunmoreno.github.io/My-Portfolio/assets/images/Justgeekynewspic1.jpg)

## Features

- View tech news posts in a feed
- Create an account and log in
- Stay logged in with session support
- Create, edit, and delete your own posts
- Comment on posts
- Upvote posts
- View your content from a personal dashboard

## Installation

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

4. Open the app locally at:

`http://localhost:3001/home`

## Core Packages

- **express**
- **express-session**
- **express-session-sequelize**
- **mysql2**
- **sequelize**
- **dotenv**
- **bcrypt**
- **express-handlebars**

## Project Objective

This project demonstrates:

- Express middleware and route protection
- MVC architecture organization
- Dynamic views with Handlebars templates
- Session-based authentication
- CRUD operations for post management

## User Stories

- As a user, I can view all news articles in a list.
- As a user, I can see how many upvotes and comments each article has.
- As a user, I can click on the comment count to route to a different page.
- As a user, I can visit a login page to create a new account or log into an existing account.
- As a user, I want to stay logged in even if I refresh the page or close the browser tab.
- As a user, I can click a logout button for the app to forget me.
- As a user, I can view an article's details on a separate page.
- As a logged-in user, I can add a comment to an article.
- As a logged-in user, I can upvote an article.
- As a logged-in user, I can view all of my posted articles on a separate dashboard page.
- As a logged-in user, I can create new article posts via the dashboard.
- As a logged-in user, I can edit or delete my existing articles via the dashboard.
