# Todo App

This is a simple CRUD (Create, Read, Update, Delete) Todo app built using React for the frontend and Express with MongoDB for the backend.

## Features

- Add a new Todo item
- View all Todo items
- Update existing Todo items
- Delete Todo items

## Technologies Used

- **Frontend**: React
- **Backend**: Express.js, MongoDB
- **Database**: MongoDB
- **Styling**: Bootstrap

## Setup

### Backend Setup

1. Install dependencies:
   ```bash
   npm install
   Start the backend server:
   ```

bash
Copy code
npm start
The backend server will run on port 5000 by default.

Frontend Setup
Install dependencies:

bash
Copy code
npm install
Start the frontend server:

bash
Copy code
npm start
The frontend server will run on port 3000 by default.

Connecting Frontend to Backend
Ensure that the backend server is running on http://localhost:5000.
The frontend server is configured to proxy requests to the backend server automatically.
Folder Structure
css
Copy code
todo-app/
├── backend/
│ ├── server.js
│ ├── models/
│ ├── routes/
│ └── ...
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ │ ├── AddTodo.js
│ │ │ ├── TodoList.js
│ │ │ ├── EditTodo.js
│ │ │ └── ...
│ │ ├── App.js
│ │ ├── index.js
│ │ └── ...
│ └── ...
└── README.md
Contributors
