# Attendance Management System

A modern, full-stack Attendance Management System built with the MERN stack (MongoDB, Express, React, Node.js). This application allows for efficient tracking of student attendance, user authentication, and data export features.

## 🚀 Features

- **User Authentication**: Secure Login and Registration system using JWT.
- **Role-Based Access**: Dedicated Admin panel for managing records.
- **Attendance Tracking**: Easy-to-use form for recording daily attendance.
- **Department Filtering**: Supports multiple departments like BCA, BCom, BSc, and BBA.
- **Data Export**: Export attendance records to Excel files (.xlsx) for reporting.
- **Responsive Design**: Clean and modern UI built with React and custom CSS.
- **Real-time Updates**: Instant feedback and validation on forms.

## 🛠️ Tech Stack

**Frontend:**
- [React.js](https://reactjs.org/) (Vite)
- [React Router DOM](https://reactrouter.com/)
- [Axios](https://axios-http.com/)
- [XLSX](https://github.com/SheetJS/sheetjs) (for Excel exports)

**Backend:**
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/) (Mongoose ODM)
- [JSON Web Tokens (JWT)](https://jwt.io/)
- [BcryptJS](https://github.com/dcodeIO/bcrypt.js)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/en/download/) (v16.x or higher)
- [MongoDB](https://www.mongodb.com/try/download/community) (Local or Atlas)
- npm or yarn


## 📂 Project Structure

```text
attendance-system/
├── client/             # React frontend (Vite)
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── context/    # Auth and State management
│   │   └── ...
├── server/             # Node.js backend
│   ├── models/         # Mongoose schemas
│   ├── routes/         # API endpoints
│   ├── middleware/     # Auth and validation
│   └── server.js       # Entry point
└── package.json        # Combined scripts
```

## 📝 License

This project is licensed under the ISC License.

---
Built with ❤️ by Rehemath Ali
