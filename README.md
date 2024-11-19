# User Management Application

This project is a **User Management Application** built with **ReactJS** for the frontend, **Redux** for state management, and **Toastify** for notifications. The application allows users to add, edit, delete, and view a list of users. The list is paginated, and the user can perform CRUD (Create, Read, Update, Delete) operations on users through modals.

## Features
- **CRUD Operations**: Add, Edit, and Delete users.
- **Pagination**: The list of users is paginated, showing a specific number of users per page.
- **Error Handling**: Comprehensive error handling using `try-catch` blocks, with error messages displayed via Toast notifications.
- **User Interface**: Simple, clean UI with modals for adding and editing users.
- **Notifications**: Success and error notifications using `react-toastify`.

## Tech Stack
- **Frontend**: ReactJS, Redux, React Toastify
- **CSS**: Custom styles using basic CSS
- **State Management**: Redux for managing the user state

## Installation

### Prerequisites
Make sure you have the following installed:
- **Node.js**: Version 14 or above.
- **npm** or **yarn**: Package manager for installing dependencies.

### Steps to Start the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/user-management-app.git
   cd user-management-app
Install Dependencies: Install the required dependencies by running:



npm install
or if you're using yarn:


yarn install
Start the Development Server: After installing the dependencies, you can start the development server:


npm start
or with yarn:


yarn start
Open in Browser: Open your browser and navigate to http://localhost:3000 to see the application running.
Important Packages
1. React:
The core library for building the user interface.


npm install react
2. Redux:
A state management library used to store and manage the state of the users list.


npm install redux react-redux
3. react-toastify:
A library used to show toast notifications for success and error messages.

bash
Copy code
npm install react-toastify
4. React Router (Optional for routing, if your app has multiple views):
This is for managing client-side routing within React components. Not used in this specific project but can be installed for future use.


npm install react-router-dom
Project Structure
The project is structured as follows:


/user-management-app
│
├── /src
│   ├── /components
│   │   ├── AddUserModal.js        # Modal for adding a new user
│   │   ├── EditModal.js          # Modal for editing an existing user
│   │   ├── Home.js               # Main component to display users and handle CRUD operations
│   │   └── UserTable.js          # Table component to display users with pagination
│   │
│   ├── /store
│   │   ├── userActions.js        # Redux actions for fetching, adding, updating, and deleting users
│   │   ├── userReducer.js        # Redux reducer to manage user state
│   │   ├── store.js              # Redux store setup
│   │   └── rootReducer.js        # Combine reducers
│   │
│   ├── App.js                    # Main entry point for React application
│   ├── index.js                  # Renders App component into the root DOM node
│   └── /assets                   # Any static assets like images, icons, etc.
│
├── package.json                  # Project dependencies and scripts
├── README.md                     # Project documentation
└── /public                       # Static files for public use
    └── index.html                # Main HTML template file
