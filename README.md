# Personal Finance Management System

## Introduction

Welcome to the Personal Finance Management System! This application helps you track and manage your financial transactions, including income and expenses. It provides an easy-to-use interface for adding, editing, and deleting transactions, and offers insightful analytics to help you understand your financial habits.

## Features

- **Add, Edit, Delete Transactions**: Manage your transactions effortlessly.
- **Transaction Categories**: Classify transactions into different categories.
- **View Transactions**: Display transactions in a table or analytical view.
- **Date Range Filter**: Filter transactions based on custom date ranges.
- **Transaction Type Filter**: Filter transactions by type (income or expense).
- **Analytics**: Gain insights into your financial behavior through analytics.

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **Ant Design**: UI framework for React used for components like forms, tables, and modals.
- **Axios**: HTTP client for making API requests.
- **Moment.js**: Library for date formatting and manipulation.
- **Node.js and Express**: Backend framework for handling API requests.

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB for the database

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ritik7739/personal-finance-management.git
   ```

2. Navigate to the project directory:

   ```sh
   cd personal-finance-management
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

4. Start the backend server (ensure MongoDB is running):

   ```sh
   npm run server
   ```

5. Start the frontend development server:

   ```sh
   npm start
   ```

6. Open your browser and navigate to `http://localhost:8080`.

## Usage

### Home Page

The home page provides a comprehensive view of all your transactions. You can filter transactions by date range and type, and switch between table and analytical views.

#### Filters

- **Select Frequency**: Choose between last 1 week, last 1 month, last 1 year, or custom date range.
- **Select Type**: Filter transactions by all, income, or expense.

#### Actions

- **Add New**: Click the "Add New" button to add a new transaction.
- **Edit**: Click the edit icon next to a transaction to edit it.
- **Delete**: Click the delete icon next to a transaction to delete it.

### Adding/Editing Transactions

A modal form allows you to add or edit transactions. The form includes fields for amount, type, category, date, reference, and description.

### Deleting Transactions

Click the delete icon next to a transaction to delete it. Confirm the action in the modal that appears.

## Code Structure

### Components

- **Layout**: Main layout component for the app.
- **Spinner**: Loading spinner component.
- **Analytics**: Component for displaying analytical data.

### Pages

- **HomePage**: Main page for displaying and managing transactions.

### State Management

- **useState**: Used for managing local state.
- **useEffect**: Used for fetching data and performing side effects.

### API Requests

- **axios**: Used for making HTTP requests to the backend server.

## Contributing

1. Fork the repository.
2. Create your feature branch:

   ```sh
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```sh
   git commit -m 'Add some feature'
   ```

4. Push to the branch:

   ```sh
   git push origin feature/your-feature-name
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License 

-------------------------------------------------------------------------------------------------------------------

Thank you for using the Personal Finance Management System! We hope it helps you manage your finances more effectively.
