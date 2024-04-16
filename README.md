# MERN Expense Tracker

[MERN Expense Tracker](https://expense-manager-zeta-two.vercel.app/)

This is a simple expense tracker application built using the MERN stack. It allows users to track their expenses by entering transactions and categorizing them.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Transaction Management**: Users can add new transactions, delete existing ones, and view their transaction history.
- **Category Filtering**: Transactions can be categorized for better organization, and users can filter transactions by category.
- **Dashboard**: Provides users with an overview of their expenses, including total spending, categorized spending, and trends over time.

## Technologies Used

- **MongoDB**: For database storage of user information and transactions.
- **Express.js**: To handle HTTP requests and routes.
- **React.js**: Frontend framework for building user interfaces.
- **Node.js**: Backend runtime environment.
- **Redux**: For state management in the frontend.
- **JWT**: JSON Web Tokens for secure user authentication.
- **Chart.js**: For visualization of expense data.

## Installation

1. Clone the repository:
   ```git clone https://github.com/yourusername/expense-tracker.git```
   
3. Navigate to the project directory:
  ```cd expense-tracker ```

4. Install dependencies:
   ```npm install```

5. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following environment variables:
     ```PORT=5000
        MONGODB_URI=your_mongodb_uri
        JWT_SECRET=your_jwt_secret```

6. Start the development server:
   ```npm start```
   
7. Navigate to `http://localhost:3000` in your browser to view the application.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any problems or have suggestions for improvements.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).









