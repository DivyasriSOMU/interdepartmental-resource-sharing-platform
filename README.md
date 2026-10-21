# Interdepartmental Planning & Resource Sharing Platform

## Project Description

The Interdepartmental Planning & Resource Sharing Platform is a web-based application developed using the MERN stack to simplify resource sharing and management between departments in an educational institution.

The platform allows students to log in, view available departments and resources, and submit resource booking requests. Administrators can manage departments and resources, review booking requests, and approve or reject pending requests.

The system also includes booking conflict detection to identify overlapping requests and suggests alternative resources when conflicts are detected. Role-based access control helps ensure that administrative operations are restricted to authorized users.

## Key Features

- User authentication for students and administrators
- Role-based access control
- Department management
- Resource management
- Resource booking requests
- Booking conflict detection
- Alternative resource suggestions
- Admin approval and rejection of booking requests
- Secure password hashing

## Technologies Used

- **Frontend:** React.js, Vite
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Token (JWT)
- **Password Security:** bcrypt

## Project Objective

The main objective of this project is to provide a centralized platform for managing and sharing institutional resources, improving coordination between departments and reducing scheduling conflicts.

## Running the Project

1. Install Node.js, npm, and MongoDB.
2. Configure the backend environment variables in `server/.env`.
3. Start the backend using the command configured in `server/package.json`.
4. Start the frontend by running `npm run dev` inside the `client` folder.
5. Open the local URL provided by Vite in your browser.

## Author

**Name:** [Divyasri S]

**Department:** [CSE(AIML)]

**College:** [Easwari Engineering College]
