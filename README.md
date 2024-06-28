## Project Overview
A simple web application built with the MERN (MongoDB, Express, React, Node.js) stack for tracking income and expenses.

## Features
* Add new transactions with description and amount.
* Separate view for income and expenses.
* Real-time balance calculation.
* User-friendly interface for easy tracking.
* Efficient data storage and retrieval using MongoDB.

## Installation
1. Clone the repository or download the source code.
```bash
git clone [repository_url]
```
2. Navigate to the project directory.
```bash
cd Expense-Tracker
```
3. Install dependencies.
```bash
npm install
cd client npm install
cd ..
```

## Production
1. Run front and backend.
```bash
npm run dev
```
2. Run backend only.
```bash
npm run server
```
3. Run frontend only.
```bash
npm run client
```
4. Build client.
```bash
cd client
npm run build
```

## Project Structure
```arduino
Expense-Tracker/
│
├── client/
│   ├── public/
│   │   ├── index.html
│   │   └── ...other public files
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── AddTransaction.js
│   │   │   ├── Balance.js
│   │   │   ├── Header.js
│   │   │   ├── IncomeExpenses.js
│   │   │   ├── Transaction.js
│   │   │   ├── TransactionList.js
│   │   │   └── ...other components
│   │   │
│   │   ├── context/
│   │   │   ├── AppReducer.js
│   │   │   ├── GlobalContext.js
│   │   │   └── GlobalProvider.js
│   │   │
│   │   ├── utils/
│   │   │   └── format.js
│   │   │
│   │   ├── App.js
│   │   ├── Index.js
│   │   └── ...other main files
│   │
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   └── ...other client-specific files
│
├── config/
│   ├── config.env
│   └── db.js
│
├── controllers/
│   └── transactions.js
│
├── models/
│   └── Transaction.js
│
├── routes/
│   └── transactions.js
│
├── server.js
├── package.json
├── package-lock.json
└── README.md
```

## Screenshots
<img src='images/sc1.png'>
<img src='images/sc2.png'>
<img src='images/sc3.png'>

## Tech Used
* Frontend: React, React Hooks, Context API
* Backend: Node.js, Express.js
* Database: MongoDB
* CSS
* API Requests: Axios

## License
[MIT](LICENSE)