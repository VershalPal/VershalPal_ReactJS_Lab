# Flatmate Expense Tracker

## Overview

The Flatmate Expense Tracker is a web application designed to simplify the process of tracking shared expenses between flatmates. By digitizing the expense-sharing process, this application helps users easily manage their bills and determine who owes what at the end of the month.

## Features

1. **JSON Server Integration**: The app uses a JSON server to store expense data for future use.
2. **Automatic ID Assignment**: Each expense entry is automatically assigned a unique ID, eliminating manual entry.
3. **User-Friendly GUI**: A graphical user interface displays data retrieved from the JSON server and allows users to input new expenses easily.
4. **Expense Summary**: The app calculates total expenses, individual contributions, and identifies who owes whom.
5. **Separate Add Item Form**: Users can access the form for adding new expenses via React Router.

## Future Developments

- Select and view expenses by month.
- Restrict date selection to the current month only.
- Implement user login functionality.
- Prevent modifications to previous month data.

## Requirements

- Node.js
- React
- JSON Server

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd flatmate-expense-tracker
   
2. Install dependencies:
   npm install
   
3. Start the JSON server:
   json-server --watch db.json

4. Run the React application:
   npm start

## Usage
- Open your browser and navigate to http://localhost:3000 to access the application.
- Use the interface to add expenses and view summaries.
