# MERN Stack Capstone Project

https://week-7-devops-deployment-assignment-xix-f5xi.onrender.com

## Getting Started

1. Accept the GitHub Classroom assignment
2. Clone the repository to your local machine
3. Follow the instructions in the `Week8-Assignment.md` file
4. Plan, develop, and deploy your capstone project

## Files Included

```
├── FinTrack-server/
│   ├── config/             # Database connection setup
│   │   └── db.js
│   ├── controllers/        # Business logic for routes
│   │   ├── authController.js
│   │   └── expenseController.js
│   ├── middleware/         # Custom middleware (e.g., authentication)
│   │   └── authMiddleware.js
│   ├── models/             # Mongoose schemas for data models
│   │   ├── User.js
│   │   └── Expense.js
│   ├── routes/             # API endpoints
│   │   ├── authRoutes.js
│   │   └── expenseRoutes.js
│   ├── .env                # Environment variables (sensitive info)
│   ├── package.json
│   └── server.js           # Main Express server file
│
└── FinTrack-client/
    ├── public/
    ├── src/
    │   ├── App.js          # Main application component, handles routing
    │   ├── AuthForm.js     # Login and Registration form component
    │   ├── Dashboard.js    # Main dashboard component, manages expense state
    │   ├── ExpenseForm.js  # Component for adding new expenses
    │   ├── ExpenseList.js  # Component for displaying expenses table
    │   └── index.js        # React app entry point
    ├── package.json
    └── README.md           # This file
```
- `Week8-Assignment.md`: Detailed assignment instructions

## Requirements

- Node.js (v18 or higher)
- MongoDB (local installation or Atlas account)
- npm or yarn
- Git and GitHub account
- Accounts on deployment platforms (Render/Vercel/Netlify/etc.)

## Resources

- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://react.dev/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [GitHub Classroom Guide](https://docs.github.com/en/education/manage-coursework-with-github-classroom) 