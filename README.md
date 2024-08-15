                Transaction Tracker App

                Overview
The Transaction Tracker App is a React-based application designed to manage and track financial transactions. Users can view a list of transactions, add new transactions, and search through recent transactions by description.


                Features
View Transactions: Display a list of transactions in a structured table.
Add Transactions: Add new transactions with details such as date, description, category, and amount.
Search Transactions: Filter transactions by description.

                Technologies Used
React
JavaScript
HTML/CSS
Fetch API for data handling

            Components

AccountContainer
Description: Manages the state for transactions and search term. Handles fetching 

transaction data, adding new transactions, and filtering transactions.
Location: src/AccountContainer.js

Search
Description: A search bar component to filter transactions based on their description.
Location: src/Search.js

AddTransactionForm
Description: A form component for adding new transactions, including fields for date, description, category, and amount.
Location: src/AddTransactionForm.js

TransactionsList
Description: Displays a list of transactions in a table format.
Location: src/TransactionsList.js

Transaction
Description: Renders a single row of a transaction in the transactions table.
Location: src/Transaction.js

                API Endpoints
GET /transactions: Fetches the list of transactions.
POST /transactions: Adds a new transaction.

                Usage
View Transactions: The transactions will be displayed automatically when the app loads.
Add a Transaction: Use the form provided to input transaction details and submit to add a new transaction.
Search Transactions: Use the search bar to filter transactions by description.

                Project Structure
public/: Contains static files such as index.html.
src/: Contains React components and JavaScript files.
components/: Contains React component files.
App.js: The main component of the application.
index.js: The entry point for the React application.


                License
This project is licensed under the MIT License.


