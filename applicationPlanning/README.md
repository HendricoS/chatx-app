# Software Requirements Documentation

---

# \*\*\* System Architecture \*\*\*

## Frontend Architecture

- The frontend of the application will be developed using React.js, a popular JavaScript library for building user interfaces.
- The choice of React.js is motivated by its component-based architecture, which allows for modular and reusable code.
- The application will use React Router for navigation between different components, providing a seamless user experience.
- Bootstrap will be utilized for CSS styling, ensuring a responsive design.

### Frontend Components

- App.js: Main component handling website routing and navigation.
- Registration Page: Allows users to register with a valid Gmail address and password.
- Login Page: Provides a login interface for registered users.
- Messaging App Page: The main page where users can send and receive messages.
- Password Change Page: Allows users to change their passwords after logging in.
- Admin Login Page: Admin user login page.
- Admin Panel: Interface for admin users to delete other user accounts.

## Backend Architecture

- The backend is powered by Express.js, serving as a custom server handling API requests and responses.
- MongoDB is used as the database to store user accounts.
- Helmet middleware enhances security against common web vulnerabilities, while CORS middleware enables secure cross-origin API requests.

### Backend Components

- Express.js Server: Custom server handling API requests and responses.
- MongoDB Database: Stores user accounts, accessible through backend routes.
- Helmet Middleware: Enhances security by protecting against common web vulnerabilities.
- CORS Middleware: Enables secure cross-origin API requests.

### Deployment

- The application will be deployed to GitHub for version control and collaboration.
- Vercel will be used for hosting the frontend, ensuring ease of deployment and automatic CI/CD.

---

# \*\*\* System Requirements Specification \*\*\*

## Functional Requirements

### User Registration

- Users should register with a valid Gmail address and a password of at least 6 characters.
- Duplicate registrations with the same email address should be prevented.

### User Authentication

- Registered users can log in using their credentials.
- Admin users have a separate login page for authentication.

### Messaging

- Logged-in users can send and receive messages.
- Users can delete messages from the chat.

### Password Change

- Users can change their passwords after logging in.

### Admin Panel

- Admin users can log in and access an admin panel.
- Admin users can delete other user accounts from the admin panel.

## Non-Functional Requirements

### Security

- The application should use HTTPS to encrypt data during transmission.
- User passwords should be securely stored using industry best practices.

### Performance

- The application should handle concurrent user connections efficiently.
- Response times for API requests should be optimized.

### Scalability

- The system should be scalable to accommodate an increasing number of users.

### Usability

- The UI should be responsive and user-friendly.
- User interactions should be intuitive.

---

# \*\*\* User Stories \*\*\*

- As a new user, I want to register with my Gmail address and a secure password.
- As a registered user, I want to log-in to access the messaging app.
- As a user, I want to send and receive messages from other users.
- As a user, I want to change my password for security reasons.
- As an admin user, I want to log in to access the admin panel.
- As an admin user, I want to delete user accounts from the admin panel.

---

# \*\*\* Comparison with Existing Solutions \*\*\*

- While various messaging applications exist, this application is tailored for organizational use, providing a simple and secure platform for team communication.
- The admin panel feature distinguishes it, allowing for user management within the application.
- This messaging app focuses on essential features, ensuring a streamlined user experience and efficient communication within a team or organization.

## More information

- This is a message application app that allows several users to login and send messages to other users
- All logged-users will be able to see and receive all user messages
- The app will mainly be used for example a company. Whereby all team members can login to the app and send, receive and delete messages

---

# \*\*\* How to Use the App \*\*\*

## Explanation of How to Use the App

- The app facilitates communication between users.
- After registering and logging in, users can access the messaging app to send, receive, and delete messages.
- Admin users can additionally log in to the admin panel to manage user accounts.

## Instructions for Local Installation:

### Clone the GitHub repository:

- git clone https://github.com/HendricoS/ChatX.git

### Navigate to the frontend directory:

- cd ChatX/client

### Install dependencies:

- npm install

### Start the frontend development server:

- npm start

### Open a new terminal and navigate to the backend directory:

- cd ../server

### Install backend dependencies:

- npm install

### Start the backend server:

- npm start or nodemon

### Modify MongoDB URIs or API keys as needed

# \*\*\* Security Measures \*\*\*

- The app employs Helmet middleware and CORS to enhance security.
- User passwords are securely stored using industry best practices.

### Third-Party APIs:

- MongoDB is used as the database for the backend.

### Deployment Information:

- The frontend is deployed on Vercel, and the backend is hosted on ?????.
- Frontend and backend are deployed separately for ease of maintenance and scalability.

## GitHub Link

https://github.com/HendricoS/chatx-app.git

## Vercel Link

https://chatx-app.vercel.app/
