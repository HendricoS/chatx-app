# Application

## Project Name: ChatX

### Backend Configuration

Packages installed

1.  npm install --save-dev jest@latest babel-jest@latest @testing-library/jest-dom@latest @testing-library/react@latest jest-environment-jsdom@latest
2.  npm install --save-dev @babel/core@latest @babel/preset-env@latest @babel/preset-react@latest
3.  npm install --save react-scripts@latest react-test-renderer@latest
4.  npm install helmet - security for the app

### Frontend Framework and configuration

1.  React.js will be used as the framework to design the UI
2.  Node_modules required to run the application
3.  React-router-dom required to route components inside the application
4.  A service.js file to ensure the api's are modular (testing, debugging and reuse the code)
5.  Bootstrap - "bootstrap/dist/css/bootstrap.min.css" (css styling)
6.  Jest (React testing library for snapshot)

# React.js will be used as the framework to create the frontend (UI)

App.js will be used as the main website component:

- The following links will be added to navigate users to the different components
  ---Registration page
  ---Login page
  ---Messaging app page
  ---Password change page
  ---Admin login page
  ---Admin panel

### Backend framework and configuration

1.  Express.js will be used as the backend to create a custom server for the website
2.  MongoDB (Database) will be used as the database to store all user accounts
3.  Helmet will be used to help project the express.js server from common security threats such as Cross-site scripting (XSS) and click-jacking attacks
4.  CORS (Cross-Origin Resource Sharing) will be used as an HTTP-header based mechanism, as the website will be using bearer tokens for cross-domain API requests
5.  Mocha Chai - for backend testing (unit testing)

# Express.js will be used as the backend to create the server

All middleware, routes and models will be used in the backend server

# MongoDB will be used as the database for the application

All user accounts will be stored inside the database under users
---Admin can delete users through the admin panel

### Deploying App

1.  App to be deployed to GitHub
2.  App to be deployed to Vercel

# Planning the project

1.  Wireframes (draw.io)
2.  The UI will be created and planned using draw.io

# Frontend styling will be done using CSS an Bootstrap to ensure website responsive development

- Colors to be used
  ---Primary Color: #1c2228
  ---Secondary Color: #fee715
  ---Text Color: Whitesmoke;
  ---Root font size: 16px
