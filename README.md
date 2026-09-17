# Todo Application

A full-stack Todo Application developed with separate frontend and backend. The application allows users to create, view, update, complete, and delete daily tasks.

## Project Overview

This project is developed using a separate frontend and backend architecture.

The frontend provides the user interface, while the backend provides REST APIs and handles the application logic and database operations.

The application follows a client-server architecture where the frontend communicates with the backend through HTTP requests.

## Features

- Add new Todo
- View all Todos
- Update Todo
- Delete Todo
- Mark Todo as completed
- Manage daily tasks
- REST API integration
- Database integration
- Separate frontend and backend
- Responsive user interface
- Error handling
- CORS configuration

## Technologies Used

### Frontend

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Axios

### Backend

- Node.js
- Express.js
- REST API
- CORS

### Database

- MongoDB

### Development Tools

- Git
- GitHub
- VS Code
- Postman
- npm

## Project Architecture

    Todo Application
           |
           |
    +------+------+
    |             |
    |             |
 Frontend       Backend
    |             |
 React.js      Node.js
    |          Express.js
    |             |
    |         REST APIs
    |             |
    +------HTTP---+
           |
        MongoDB

## Project Structure

    todo/
    |
    +-- frontend/
    |   |
    |   +-- public/
    |   +-- src/
    |   |   +-- components/
    |   |   +-- App.jsx
    |   |   +-- main.jsx
    |   |
    |   +-- package.json
    |
    +-- backend/
    |   |
    |   +-- controllers/
    |   +-- models/
    |   +-- routes/
    |   +-- middleware/
    |   +-- app.js
    |   +-- package.json
    |
    +-- .gitignore
    +-- README.md

Note: The exact folder and file names may vary depending on the project implementation.

## Getting Started

Follow the steps below to run the project locally.

### 1. Clone the Repository

    git clone YOUR_REPOSITORY_URL

### 2. Navigate to the Project

    cd todo

## Frontend Setup

Navigate to the frontend directory:

    cd frontend

Install frontend dependencies:

    npm install

Start the frontend development server:

    npm run dev

The frontend application will start in development mode.

## Backend Setup

Open a new terminal and navigate to the backend directory:

    cd backend

Install backend dependencies:

    npm install

Start the backend server:

    node app.js

If Nodemon is configured, you can start the backend using:

    npm run dev

## Environment Variables

Create a `.env` file inside the backend directory.

Example:

    PORT=5000
    MONGODB_URI=your_mongodb_connection_string

Add other environment variables required by the application if necessary.

Do not upload the `.env` file or sensitive credentials to GitHub.

Add the following entries to `.gitignore`:

    .env
    node_modules/

## Database

The application uses MongoDB to store Todo information.

Todo data can contain information such as:

- Todo title
- Todo description
- Completion status
- Created date
- Updated date

Example Todo data:

    {
      "title": "Complete Project",
      "description": "Complete Todo Application",
      "completed": false
    }

## REST API

The backend provides REST APIs for managing Todo tasks.

### Create Todo

    POST /api/todos

Creates a new Todo.

### Get All Todos

    GET /api/todos

Returns all Todo tasks.

### Get Todo by ID

    GET /api/todos/:id

Returns a specific Todo using its ID.

### Update Todo

    PUT /api/todos/:id

Updates an existing Todo.

### Delete Todo

    DELETE /api/todos/:id

Deletes an existing Todo.

## CRUD Operations

The application implements CRUD operations.

| Operation | HTTP Method | Description |
|-----------|-------------|-------------|
| Create | POST | Create a new Todo |
| Read | GET | Retrieve Todo data |
| Update | PUT | Update an existing Todo |
| Delete | DELETE | Delete a Todo |

## Application Flow

    User
      |
      v
    Frontend
      |
      | HTTP Request
      v
    Express.js Backend
      |
      v
    Routes
      |
      v
    Controllers
      |
      v
    MongoDB
      |
      v
    Backend Response
      |
      v
    Frontend
      |
      v
    Updated User Interface

## API Testing

The backend APIs can be tested using Postman.

Testing process:

1. Start the backend server.
2. Open Postman.
3. Select the required HTTP method.
4. Enter the API endpoint.
5. Send the request.
6. Check the API response.
7. Verify the data in MongoDB.

## Useful Commands

### Frontend

Install dependencies:

    npm install

Start development server:

    npm run dev

Create production build:

    npm run build

Preview production build:

    npm run preview

### Backend

Install dependencies:

    npm install

Start backend:

    node app.js

Start backend with Nodemon:

    npm run dev

## Git Commands

Check project status:

    git status

Add all changes:

    git add .

Commit changes:

    git commit -m "Update Todo Application"

Push changes:

    git push

## Error Handling

The backend handles common errors such as:

- Invalid requests
- Missing Todo data
- Invalid Todo ID
- Database errors
- Server errors
- Resource not found

## CORS

CORS is used to allow communication between the frontend and backend when they are running on separate origins.

Example:

    const cors = require("cors");

    app.use(cors());

## Responsive Design

The frontend is designed to provide a user-friendly experience on different screen sizes, including:

- Desktop
- Laptop
- Tablet
- Mobile

## Learning Outcomes

Through this project, I gained practical experience in:

- React.js
- JavaScript ES6+
- Node.js
- Express.js
- MongoDB
- REST API development
- CRUD operations
- Axios
- API integration
- Frontend and backend separation
- Database connectivity
- CORS
- Error handling
- Git
- GitHub
- Postman
- Full-stack application development

## Future Improvements

Possible future improvements include:

- User authentication
- Login and registration
- JWT authentication
- Task due dates
- Task categories
- Search and filtering
- Task reminders
- Dark mode
- Task statistics
- Email notifications
- Cloud deployment

## Author

**Karan Awari**

B.Sc. Computer Science Graduate | MERN Stack Developer

## Skills

- HTML5
- CSS3
- JavaScript
- React.js
- Node.js
- Express.js
- MongoDB
- MySQL
- Bootstrap
- Git
- GitHub
- Postman
- AWS

## Project Highlights

- Full-stack Todo Application
- Separate frontend and backend
- React.js frontend
- Node.js backend
- Express.js REST API
- MongoDB database
- CRUD operations
- API integration
- Postman API testing
- Responsive user interface
- Git and GitHub
- Full-stack development experience
