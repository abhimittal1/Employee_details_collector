# Employee Details App 🛠️

This is a **MERN stack** application with **Tailwind CSS** for managing employee details. It allows users to add and view employee information. The app features a React.js frontend, an Express.js backend, and MongoDB as the database.

---

## Features

- **Home Page:** Displays the list of employees.
- **Add Employee Page:** Allows adding new employee details.
- **MERN Stack:** Utilizes MongoDB, Express.js, React.js, and Node.js.
- **Tailwind CSS:** For a clean and responsive UI.
- **CORS Enabled:** To allow cross-origin requests.
- **Environment Variables:** Uses `.env` for configuration.

---

## Tech Stack

- **Frontend:** React.js, Tailwind CSS, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Middleware:** CORS, dotenv
- **API Routes:** RESTful APIs for employee management

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

---

#### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abhimittal1/Employee_details_collector
   cd employee-details-app
   ```

2. **Install dependencies**
   - Backend:
   ```bash
   cd backend
   npm install
   ```
   - Frontend:
   ```bash
   cd frontend
   npm install
   ```

---

### Environment Variables

Create a `.env` file in the `backend` directory with the following:
```
PORT=4000
MONGO_URI=your-mongodb-connection-string
```

---

### Running the App

1. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

2. Start the frontend server:
   ```bash
   cd frontend
   npm start
   ```

- The backend will be running at: `http://localhost:4000`
- The frontend will be running at: `http://localhost:3000`

---

## Folder Structure

### Backend
```
/backend
 ├── config          # Database configuration
 ├── controller      # Request handlers (business logic)
 ├── models          # MongoDB models
 ├── node_modules    # Dependencies
 ├── routes          # API routes
 ├── .env            # Environment variables
 ├── .gitignore      # Git ignore file
 ├── index.js        # Entry point for the backend server
 ├── package.json    # Project metadata and dependencies
 ├── package-lock.json # Dependency lock file
```

### Frontend
```
/frontend
 ├── public                # Static files (index.html)
 ├── src
 │    ├── components       # Reusable UI components
 │    ├── pages            # HomePage and CreateEmployeePage
 │    ├── App.js           # Main React component with routing
 │    ├── index.js         # React entry point
 ├── tailwind.config.js    # Tailwind CSS configuration (outside src)
 ├── postcss.config.js     # PostCSS configuration (outside src)
 ├── node_modules          # Frontend dependencies
 ├── .gitignore            # Git ignore file
 ├── package.json          # Frontend project metadata
 ├── package-lock.json     # Dependency lock file

```

---

## Future Improvements

- Implement employee data editing and deleting.
- Add authentication and authorization.
- Deploy the app using Vercel (frontend) and Render/Heroku (backend).

---

## Author

- **Abhishek Mittal**
- [Contact](mailto:abhishekmittal24gold@gmail.com)

---

✅ Happy coding!
