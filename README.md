# Todo App

This is a combined Markdown file containing information about a simple CRUD Todo app built with React and Express/MongoDB.

## Features

- Add new Todo items
- View all existing Todo items
- Update existing Todo items
- Delete Todo items

## Technologies Used

- **Frontend**: React
- **Backend**: Express.js, MongoDB
- **Database**: MongoDB
- **Styling**: Bootstrap (optional)

## Setup

### Backend Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the backend server:

   ```bash
   npm start
   ```

3. The backend server will run on port 5000 by default.

### Frontend Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the frontend server:

   ```bash
   npm start
   ```

3. The frontend server will run on port 3000 by default.

### Connecting Frontend to Backend

- Ensure the backend server is running on http://localhost:5000.
- The frontend server is configured to proxy requests to the backend server automatically.

## Folder Structure

```
todo-app/
├── backend/
│   ├── server.js
│   ├── models/
│   ├── routes/
│   └── ...
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AddTodo.js
│   │   │   ├── TodoList.js
│   │   │   ├── EditTodo.js
│   │   │   └── ...
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   └── ...
└── README.md
```
